* Classes:
  * Enumerable - Provides a set of static (Shared in Visual Basic) methods for querying objects that implement IEnumerable<T>.
  * EnumerableExecutor - Represents an expression tree and provides functionality to execute the expression tree after rewriting it.
  * EnumerableExecutor<T> - Represents an expression tree and provides functionality to execute the expression tree after rewriting it.
  * EnumerableQuery - Represents an IEnumerable as an EnumerableQuery data source.
  * EnumerableQuery<T> - Represents an IEnumerable<T> collection as an IQueryable<T> data source.
  * ImmutableArrayExtensions - LINQ extension method overrides that offer greater efficiency for ImmutableArray<T> than the standard LINQ methods. NuGet package: System.Collections.Immutable (about immutable collections and how to install)
  * Lookup<TKey,TElement> - Represents a collection of keys each mapped to one or more values.
  * OrderedParallelQuery<TSource> - Represents a sorted, parallel sequence.
  * ParallelEnumerable - Provides a set of methods for querying objects that implement ParallelQuery{TSource}. This is the parallel equivalent of Enumerable.
  * ParallelQuery - Represents a parallel sequence.
  * ParallelQuery<TSource> - Represents a parallel sequence.
  * Queryable - Provides a set of static (Shared in Visual Basic) methods for querying data structures that implement IQueryable<T>.
* Interfaces:
  * IGrouping<TKey,TElement> - Represents a collection of objects that have a common key.
  * ILookup<TKey,TElement> - Defines an indexer, size property, and Boolean search method for data structures that map keys to IEnumerable<T> sequences of values.
  * IOrderedEnumerable<TElement> - Represents a sorted sequence.
  * IOrderedQueryable - Represents the result of a sorting operation.
  * IOrderedQueryable<T> - Represents the result of a sorting operation.
  * IQueryable - Provides functionality to evaluate queries against a specific data source wherein the type of the data is not specified.
  * IQueryable<T> - Provides functionality to evaluate queries against a specific data source wherein the type of the data is known.
  * IQueryProvider - Defines methods to create and execute queries that are described by an IQueryable object.
* Enums:
  * ParallelExecutionMode - The query execution mode is a hint that specifies how the system should handle performance trade-offs when parallelizing queries.
  * ParallelMergeOptions - Specifies the preferred type of output merge to use in a query. In other words, it indicates how PLINQ should merge the results from the various partitions back into a single result sequence. This is a hint only, and may not be respected by the system when parallelizing all queries.
