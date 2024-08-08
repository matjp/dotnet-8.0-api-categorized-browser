* Classes:
  * `CollectionExtensions` - Provides extension methods for generic collections.
  * `Comparer<T>` - Provides a base class for implementations of the `IComparer<T>` generic interface.
  * `Dictionary<TKey,TValue>.KeyCollection` - Represents the collection of keys in a `Dictionary<TKey,TValue>`. This class cannot be inherited.
  * `Dictionary<TKey,TValue>.ValueCollection` - Represents the collection of values in a `Dictionary<TKey,TValue>`. This class cannot be inherited.
  * `Dictionary<TKey,TValue>` - Represents a collection of keys and values.
  * `EqualityComparer<T>` - Provides a base class for implementations of the `IEqualityComparer<T>` generic interface.
  * `HashSet<T>` - Represents a set of values.
  * `KeyedByTypeCollection<TItem>` - Provides a collection whose items are types that serve as keys.
  * `KeyValuePair` - Creates instances of the `KeyValuePair<TKey,TValue>` struct.
  * `LinkedList<T>` - Represents a doubly linked list.
  * `LinkedListNode<T>` - Represents a node in a `LinkedList<T>`. This class cannot be inherited.
  * `List<T>` - Represents a strongly typed list of objects that can be accessed by index. Provides methods to search, sort, and manipulate lists.
  * `PriorityQueue<TElement,TPriority>.UnorderedItemsCollection` - Enumerates the contents of a `PriorityQueue<TElement,TPriority>`, without any ordering guarantees.
  * `PriorityQueue<TElement,TPriority>` - Represents a collection of items that have a value and a priority. On dequeue, the item with the lowest priority value is removed.
  * `Queue<T>` - Represents a first-in, first-out collection of objects.
  * `ReferenceEqualityComparer` - An `IEqualityComparer<T>` that uses reference equality (ReferenceEquals(Object, Object)) instead of value equality (Equals(Object)) when comparing two object instances.
  * `SortedDictionary<TKey,TValue>.KeyCollection` - Represents the collection of keys in a `SortedDictionary<TKey,TValue>`. This class cannot be inherited.
  * `SortedDictionary<TKey,TValue>.ValueCollection` - Represents the collection of values in a `SortedDictionary<TKey,TValue>`. This class cannot be inherited.
  * `SortedDictionary<TKey,TValue>` - Represents a collection of key/value pairs that are sorted on the key.
  * `SortedList<TKey,TValue>` - Represents a collection of key/value pairs that are sorted by key based on the associated `IComparer<T>` implementation.
  * `SortedSet<T>` - Represents a collection of objects that is maintained in sorted order.
  * `Stack<T>` - Represents a variable size last-in-first-out (LIFO) collection of instances of the same specified type.
  * `SynchronizedCollection<T>` - Provides a thread-safe collection that contains objects of a type specified by the generic parameter as elements.
  * `SynchronizedKeyedCollection<K,T>` - Provides a thread-safe collection that contains objects of a type specified by a generic parameter and that are grouped by keys.
  * `SynchronizedReadOnlyCollection<T>` - Provides a thread-safe, read-only collection that contains objects of a type specified by the generic parameter as elements.
* Exception Classes:
  * `KeyNotFoundException` - The exception that is thrown when the key specified for accessing an element in a collection does not match any key in the collection.
* Structs:
  * `Dictionary<TKey,TValue>.Enumerator` - Enumerates the elements of a `Dictionary<TKey,TValue>`.
  * `Dictionary<TKey,TValue>.KeyCollection.Enumerator` - Enumerates the elements of a `Dictionary<TKey,TValue>.KeyCollection`.
  * `Dictionary<TKey,TValue>.ValueCollection.Enumerator` - Enumerates the elements of a `Dictionary<TKey,TValue>.ValueCollection`.
  * `HashSet<T>.Enumerator` - Enumerates the elements of a `HashSet<T>` object.
  * `KeyValuePair<TKey,TValue>` - Defines a key/value pair that can be set or retrieved.
  * `LinkedList<T>.Enumerator` - Enumerates the elements of a `LinkedList<T>`.
  * `List<T>.Enumerator` - Enumerates the elements of a `List<T>`.
  * `PriorityQueue<TElement,TPriority>.UnorderedItemsCollection.Enumerator` - Enumerates the element and priority pairs of a `PriorityQueue<TElement,TPriority>`, without any ordering guarantees.
  * `Queue<T>.Enumerator` - Enumerates the elements of a `Queue<T>`.
  * `SortedDictionary<TKey,TValue>.Enumerator` - Enumerates the elements of a `SortedDictionary<TKey,TValue>`.
  * `SortedDictionary<TKey,TValue>.KeyCollection.Enumerator` - Enumerates the elements of a `SortedDictionary<TKey,TValue>.KeyCollection`.
  * `SortedDictionary<TKey,TValue>.ValueCollection.Enumerator` - Enumerates the elements of a `SortedDictionary<TKey,TValue>.ValueCollection`.
  * `SortedSet<T>.Enumerator` - Enumerates the elements of a `SortedSet<T>` object.
  * `Stack<T>.Enumerator` - Enumerates the elements of a `Stack<T>`.
* Interfaces:
  * `IAsyncEnumerable<T>` - Exposes an enumerator that provides asynchronous iteration over values of a specified type.
  * `IAsyncEnumerator<T>` - Supports a simple asynchronous iteration over a generic collection.
  * `ICollection<T>` - Defines methods to manipulate generic collections.
  * `IComparer<T>` - Defines a method that a type implements to compare two objects.
  * `IDictionary<TKey,TValue>` - Represents a generic collection of key/value pairs.
  * `IEnumerable<T>` - Exposes the enumerator, which supports a simple iteration over a collection of a specified type.
  * `IEnumerator<T>` - Supports a simple iteration over a generic collection.
  * `IEqualityComparer<T>` - Defines methods to support the comparison of objects for equality.
  * `IList<T>` - Represents a collection of objects that can be individually accessed by index.
  * `IReadOnlyCollection<T>` - Represents a strongly-typed, read-only collection of elements.
  * `IReadOnlyDictionary<TKey,TValue>` - Represents a generic read-only collection of key/value pairs.
  * `IReadOnlyList<T>` - Represents a read-only collection of elements that can be accessed by index.
  * `IReadOnlySet<T>` - Provides a readonly abstraction of a set.
  * `ISet<T>` - Provides the base interface for the abstraction of sets.
