* Classes:
  * ConcurrentExclusiveSchedulerPair - Provides task schedulers that coordinate to execute tasks while ensuring that concurrent tasks may run concurrently and exclusive tasks never do.
  * Parallel - Provides support for parallel loops and regions.
  * ParallelLoopState - Enables iterations of parallel loops to interact with other iterations. An instance of this class is provided by the Parallel class to each loop; you can not create instances in your code.
  * ParallelOptions - Stores options that configure the operation of methods on the Parallel class.
  * Task - Represents an asynchronous operation.
  * Task<TResult> - Represents an asynchronous operation that can return a value.
  * TaskAsyncEnumerableExtensions - Provides a set of static methods for configuring task-related behaviors on asynchronous enumerables and disposables.
  * TaskCompletionSource - Represents the producer side of a Task unbound to a delegate, providing access to the consumer side through the Task property.
  * TaskCompletionSource<TResult> - Represents the producer side of a Task<TResult> unbound to a delegate, providing access to the consumer side through the Task property.
  * TaskExtensions - Provides a set of static methods for Task.
  * TaskFactory - Provides support for creating and scheduling Task objects.
  * TaskFactory<TResult> - Provides support for creating and scheduling Task<TResult> objects.
  * TaskScheduler - Represents an object that handles the low-level work of queuing tasks onto threads.
  * TaskToAsyncResult - Provides methods for using Task to implement the Asynchronous Programming Model pattern based on "Begin" and "End" methods.
  * TimeProviderTaskExtensions - Provides extensions methods for Task operations with TimeProvider.
  * UnobservedTaskExceptionEventArgs - Provides data for the event that is raised when a faulted Task's exception goes unobserved.
* Exception Classes:
  * TaskCanceledException - Represents an exception used to communicate task cancellation.
  * TaskSchedulerException - Represents an exception used to communicate an invalid operation by a TaskScheduler.
* Structs:
  * ParallelLoopResult - Provides completion status on the execution of a Parallel loop.
  * ValueTask - Provides an awaitable result of an asynchronous operation.
  * ValueTask<TResult> - Provides a value type that wraps a Task<TResult> and a TResult, only one of which is used.
* Enums:
  * ConfigureAwaitOptions - Options to control behavior when awaiting.
  * TaskContinuationOptions - Specifies the behavior for a task that is created by using the ContinueWith(Action<Task>, CancellationToken, TaskContinuationOptions, TaskScheduler) or ContinueWith(Action<Task<TResult>>, TaskContinuationOptions) method.
  * TaskCreationOptions - Specifies flags that control optional behavior for the creation and execution of tasks.
  * TaskStatus - Represents the current stage in the lifecycle of a Task.
