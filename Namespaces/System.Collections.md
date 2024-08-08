* Classes:
  * `ArrayList` - Implements the IList interface using an array whose size is dynamically increased as required.
  * `BitArray` - Manages a compact array of bit values, which are represented as Booleans, where true indicates that the bit is on (1) and false indicates the bit is off (0).
  * `CaseInsensitiveComparer` - Compares two objects for equivalence, ignoring the case of strings.
  * `CaseInsensitiveHashCodeProvider` - Supplies a hash code for an object, using a hashing algorithm that ignores the case of strings.
  CollectionBase - Provides the abstract base class for a strongly typed collection.
  * `Comparer` - Compares two objects for equivalence, where string comparisons are case-sensitive.
  * `DictionaryBase` - Provides the abstract base class for a strongly typed collection of key/value pairs.
  * `Hashtable` - Represents a collection of key/value pairs that are organized based on the hash code of the key.
  * `Queue` - Represents a first-in, first-out collection of objects.
  * `ReadOnlyCollectionBase` - Provides the abstract base class for a strongly typed non-generic read-only collection.
  * `SortedList` - Represents a collection of key/value pairs that are sorted by the keys and are accessible by key and by index.
  * `Stack` - Represents a simple last-in-first-out (LIFO) non-generic collection of objects.
  * `StructuralComparisons` - Provides objects for performing a structural comparison of two collection objects.
* Structs:
  * `DictionaryEntry` - Defines a dictionary key/value pair that can be set or retrieved.
* Interfaces:
  * `ICollection` - Defines size, enumerators, and synchronization methods for all nongeneric collections.
  * `IComparer` - Exposes a method that compares two objects.
  * `IDictionary` - Represents a nongeneric collection of key/value pairs.
  * `IDictionaryEnumerator` - Enumerates the elements of a nongeneric dictionary.
  * `IEnumerable` - Exposes an enumerator, which supports a simple iteration over a non-generic collection.
  * `IEnumerator` - Supports a simple iteration over a non-generic collection.
  * `IEqualityComparer` - Defines methods to support the comparison of objects for equality.
  * `IHashCodeProvider` - Supplies a hash code for an object, using a custom hash function.
  * `IList` - Represents a non-generic collection of objects that can be individually accessed by index.
  * `IStructuralComparable` - Supports the structural comparison of collection objects.
  * `IStructuralEquatable` - Defines methods to support the comparison of objects for structural equality.
