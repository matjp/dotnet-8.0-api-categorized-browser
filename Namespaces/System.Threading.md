* Classes:
  * AsyncLocal<T> - Represents ambient data that is local to a given asynchronous control flow, such as an asynchronous method.
  * AutoResetEvent - Represents a thread synchronization event that, when signaled, releases one single waiting thread and then resets automatically. This class cannot be inherited.
  * Barrier - Enables multiple tasks to cooperatively work on an algorithm in parallel through multiple phases.
  * CancellationTokenSource - Signals to a CancellationToken that it should be canceled.
  * CompressedStack - Provides methods for setting and capturing the compressed stack on the current thread. This class cannot be inherited.
  * CountdownEvent - Represents a synchronization primitive that is signaled when its count reaches zero.
  * EventWaitHandle - Represents a thread synchronization event.
  * EventWaitHandleAcl - Provides a Windows-specific extension method for creating EventWaitHandle objects with specific access control list (ACL) security.
  * ExecutionContext - Manages the execution context for the current thread. This class cannot be inherited.
  * HostExecutionContext - Encapsulates and propagates the host execution context across threads.
  * HostExecutionContextManager - Provides the functionality that allows a common language runtime host to participate in the flow, or migration, of the execution context.
  * Interlocked - Provides atomic operations for variables that are shared by multiple threads.
  * LazyInitializer - Provides lazy initialization routines.
  * ManualResetEvent - Represents a thread synchronization event that, when signaled, must be reset manually. This class cannot be inherited.
  * ManualResetEventSlim - Represents a thread synchronization event that, when signaled, must be reset manually. This class is a lightweight alternative to ManualResetEvent.
  * Monitor - Provides a mechanism that synchronizes access to objects.
  * Mutex - A synchronization primitive that can also be used for interprocess synchronization.
  * MutexAcl - Provides a Windows-specific extension method for creating Mutex objects with specific access control list (ACL) security.
  * Overlapped - Provides a managed representation of a Win32 OVERLAPPED structure, including methods to transfer information from an Overlapped instance to a NativeOverlapped structure.
  * PeriodicTimer - Provides a periodic timer that enables waiting asynchronously for timer ticks.
  * PreAllocatedOverlapped - Represents pre-allocated state for native overlapped I/O operations.
  * ReaderWriterLock - Defines a lock that supports single writers and multiple readers.
  * ReaderWriterLockSlim - Represents a lock that is used to manage access to a resource, allowing multiple threads for reading or exclusive access for writing.
  * RegisteredWaitHandle - Represents a handle that has been registered when calling RegisterWaitForSingleObject(WaitHandle, WaitOrTimerCallback, Object, UInt32, Boolean). This class cannot be inherited.
  * Semaphore - Limits the number of threads that can access a resource or pool of resources concurrently.
  * SemaphoreAcl - Provides a Windows-specific extension method for creating Semaphore objects with specific access control list (ACL) security.
  * SemaphoreSlim - Represents a lightweight alternative to Semaphore that limits the number of threads that can access a resource or pool of resources concurrently.
  * SynchronizationContext - Provides the basic functionality for propagating a synchronization context in various synchronization models.
  * Thread - Creates and controls a thread, sets its priority, and gets its status.
  * ThreadExceptionEventArgs - Provides data for the ThreadException event.
  * ThreadingAclExtensions - Provides Windows-specific extension methods for managing the access control list (ACL) security descriptors for EventWaitHandle, Mutex, and Semaphore.
  * ThreadLocal<T> - Provides thread-local storage of data.
  * ThreadPool - Provides a pool of threads that can be used to execute tasks, post work items, process asynchronous I/O, wait on behalf of other threads, and process timers.
  * ThreadPoolBoundHandle - Represents an I/O handle that is bound to the system thread pool and enables low-level components to receive notifications for asynchronous I/O operations.
  * Timeout - Contains constants that specify infinite time-out intervals. This class cannot be inherited.
  * Timer - Provides a mechanism for executing a method on a thread pool thread at specified intervals. This class cannot be inherited.
  * Volatile - Contains methods for performing volatile memory operations.
  * WaitHandle - Encapsulates operating system-specific objects that wait for exclusive access to shared resources.
  * WaitHandleExtensions - Provides convenience methods to for working with a safe handle for a wait handle.
* Exception Classes:
  * AbandonedMutexException - The exception that is thrown when one thread acquires a Mutex object that another thread has abandoned by exiting without releasing it.
  * BarrierPostPhaseException - The exception that is thrown when the post-phase action of a Barrier fails.
  * LockRecursionException - The exception that is thrown when recursive entry into a lock is not compatible with the recursion policy for the lock.
  * SemaphoreFullException - The exception that is thrown when the Release method is called on a semaphore whose count is already at the maximum.
  * SynchronizationLockException - The exception that is thrown when a method requires the caller to own the lock on a given Monitor, and the method is invoked by a caller that does not own that lock.
  * ThreadAbortException - The exception that is thrown when a call is made to the Abort(Object) method. This class cannot be inherited.
  * ThreadInterruptedException - The exception that is thrown when a Thread is interrupted while it is in a waiting state.
  * ThreadStartException - The exception that is thrown when a failure occurs in a managed thread after the underlying operating system thread has been started, but before the thread is ready to execute user code.
  * ThreadStateException - The exception that is thrown when a Thread is in an invalid ThreadState for the method call.
  * WaitHandleCannotBeOpenedException - The exception that is thrown when an attempt is made to open a system mutex, semaphore, or event wait handle that does not exist.
* Structs:
  * AsyncFlowControl - Provides the functionality to restore the migration, or flow, of the execution context between threads.
  * AsyncLocalValueChangedArgs<T> - The class that provides data change information to AsyncLocal<T> instances that register for change notifications.
  * CancellationToken - Propagates notification that operations should be canceled.
  * CancellationTokenRegistration - Represents a callback delegate that has been registered with a CancellationToken.
  * LockCookie - Defines the lock that implements single-writer/multiple-reader semantics. This is a value type.
  * NativeOverlapped - Provides an explicit layout that is visible from unmanaged code and that will have the same layout as the Win32 OVERLAPPED structure with additional reserved fields at the end.
  * SpinLock - Provides a mutual exclusion lock primitive where a thread trying to acquire the lock waits in a loop repeatedly checking until the lock becomes available.
  * SpinWait - Provides support for spin-based waiting.
* Interfaces:
  * IThreadPoolWorkItem - Represents a work item that can be executed by the ThreadPool.
  * ITimer - Represents a timer that can have its due time and period changed.
* Enums:
  * ApartmentState - Specifies the apartment state of a Thread.
  * EventResetMode - Indicates whether an EventWaitHandle is reset automatically or manually after receiving a signal.
  * LazyThreadSafetyMode - Specifies how a Lazy<T> instance synchronizes access among multiple threads.
  * LockRecursionPolicy - Specifies whether a lock can be entered multiple times by the same thread.
  * ThreadPriority - Specifies the scheduling priority of a Thread.
  * ThreadState - Specifies the execution states of a Thread.
* Delegates:
  * ContextCallback - Represents a method to be called within a new context.
  * IOCompletionCallback - Receives the error code, number of bytes, and overlapped value type when an I/O operation completes on the thread pool.
  * ParameterizedThreadStart - Represents the method that executes on a Thread.
  * SendOrPostCallback - Represents a method to be called when a message is to be dispatched to a synchronization context.
  * ThreadExceptionEventHandler - Represents the method that will handle the ThreadException event of an Application.
  * ThreadStart - Represents the method that executes on a Thread.
  * TimerCallback - Represents the method that handles calls from a Timer.
  * WaitCallback - Represents a callback method to be executed by a thread pool thread.
  * WaitOrTimerCallback - Represents a method to be called when a WaitHandle is signaled or times out.
