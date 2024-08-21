### System Namespace

<details>
<summary>ADO.NET</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/framework/data/adonet/ado-net-overview)

* Namespaces
  * [`System.Data`](https://learn.microsoft.com/en-us/dotnet/api/system.data?view=net-8.0) - Provides access to classes that represent the ADO.NET architecture. ADO.NET lets you build components that efficiently manage data from multiple data sources.
  * [`System.Data.Common`](https://learn.microsoft.com/en-us/dotnet/api/system.data.common?view=net-8.0) - Contains classes shared by .NET data providers.
  * [`System.Data.Odbc`](https://learn.microsoft.com/en-us/dotnet/api/system.data.odbc?view=net-8.0) - The System.Data.Odbc namespace is the .NET Framework Data Provider for ODBC.
  * [`System.Data.OleDb`](https://learn.microsoft.com/en-us/dotnet/api/system.data.oledb?view=net-8.0) - The System.Data.OleDb namespace is the.NET Framework Data Provider for OLE DB.
  * [`System.Data.OracleClient`](https://learn.microsoft.com/en-us/dotnet/api/system.data.oracleclient?view=net-8.0) - The System.Data.OracleClient namespace is the .NET Framework Data Provider for Oracle.
  * [`System.Data.SqlClient`](https://learn.microsoft.com/en-us/dotnet/api/system.data.sqlclient?view=net-8.0) - The System.Data.SqlClient namespace is the .NET Data Provider for SQL Server.
  * [`System.Data.SqlTypes`](https://learn.microsoft.com/en-us/dotnet/api/system.data.sqltypes?view=net-8.0) - Provides classes for native data types in SQL Server. These classes provide a safer, faster alternative to the data types provided by the .NET Framework common language runtime (CLR). Using the classes in this namespace helps prevent type conversion errors caused by loss of precision. Because other data types are converted to and from SqlTypes behind the scenes, explicitly creating and using objects within this namespace also yields faster code.

</details>

<details>
<summary>Attributes</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/csharp/advanced-topics/reflection-and-attributes/)

* Classes
  * `Attribute` - Represents the base class for custom attributes.
  * `AttributeUsageAttribute` - Specifies the usage of another attribute class. This class cannot be inherited.
  * `CLSCompliantAttribute` - Indicates whether a program element is compliant with the Common Language Specification (CLS). This class cannot be inherited.
  * `ContextStaticAttribute` - Indicates that the value of a static field is unique for a particular context.
  * `NonSerializedAttribute` - Indicates that a field of a serializable class should not be serialized. This class cannot be inherited.
  * `ObsoleteAttribute` - Marks the program elements that are no longer in use. This class cannot be inherited.
  * `ParamArrayAttribute` - Indicates that a method will allow a variable number of arguments in its invocation. This class cannot be inherited.
  * `SerializableAttribute` - Indicates that a class can be serialized using binary or XML serialization. This class cannot be inherited.
* Enums
  * `AttributeTargets` - Specifies the application elements on which it is valid to apply an attribute.

</details>

<details>
<summary>Collections</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/collections/)

* Classes
  * `Array` - Provides methods for creating, manipulating, searching, and sorting arrays, thereby serving as the base class for all arrays in the common language runtime.
  * `Buffer` - Manipulates arrays of primitive types.
* Exception Classes
  * `ArrayTypeMismatchException` - The exception that is thrown when an attempt is made to store an element of the wrong type within an array.
  * `IndexOutOfRangeException` - The exception that is thrown when an attempt is made to access an element of an array or collection with an index that is outside its bounds.
  * `RankException` - The exception that is thrown when an array with the wrong number of dimensions is passed to a method.
* Namespaces
  * [`System.Collections`](https://learn.microsoft.com/en-us/dotnet/api/system.collections?view=net-8.0) - Contains interfaces and classes that define various collections of objects, such as lists, queues, bit arrays, hash tables and dictionaries.
  * [`System.Collections.Concurrent`](https://learn.microsoft.com/en-us/dotnet/api/system.collections.concurrent?view=net-8.0) - Provides several thread-safe collection classes that should be used in place of the corresponding types in the `System.Collections` and *`System.Collections.Generic` namespaces whenever multiple threads are accessing the collection concurrently. However, access to elements of a collection object through extension methods or through explicit interface implementations are not guaranteed to be thread-safe and may need to be synchronized by the caller.
  * [`System.Collections.Frozen`](https://learn.microsoft.com/en-us/dotnet/api/system.collections.frozen?view=net-8.0)
  * [`System.Collections.Generic`](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic?view=net-8.0) - Contains interfaces and classes that define generic collections, which allow users to create strongly typed collections that provide better type safety and performance than non-generic strongly typed collections.
  * [`System.Collections.Immutable`](https://learn.microsoft.com/en-us/dotnet/api/system.collections.immutable?view=net-8.0) - Contains interfaces and classes that define immutable collections.
  * [`System.Collections.ObjectModel`](https://learn.microsoft.com/en-us/dotnet/api/system.collections.objectmodel?view=net-8.0) - Contains classes that can be used as collections in the object model of a reusable library. Use these classes when properties or methods return collections.
  * [`System.Collections.Specialized`](https://learn.microsoft.com/en-us/dotnet/api/system.collections.specialized?view=net-8.0) - Contains specialized and strongly-typed collections; for example, a linked list dictionary, a bit vector, and collections that contain only strings.
* Structs
  * `ArraySegment<T>.Enumerator` - Provides an enumerator for the elements of an `ArraySegment<T>`.
  * `ArraySegment<T>` - Delimits a section of a one-dimensional array.
  * `Range` - Represents a range that has start and end indexes.

</details>

<details>
<summary>Configuration</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/core/extensions/configuration)

* Namespaces
  * [`System.Configuration`](https://learn.microsoft.com/en-us/dotnet/api/system.configuration?view=net-8.0) - Contains the types that provide the programming model for handling configuration data.
  * [`System.Configuration.Assemblies`](https://learn.microsoft.com/en-us/dotnet/api/system.configuration.assembly?view=net-8.0) - Contains classes that are used to configure an assembly.
  * [`System.Configuration.Internal`](https://learn.microsoft.com/en-us/dotnet/api/system.configuration.internal?view=net-8.0) - Contains configuration types that are intended for internal use only.
  * [`System.Configuration.Provider`](https://learn.microsoft.com/en-us/dotnet/api/system.configuration.provider?view=net-8.0) - Contains the base classes shared by both server and client applications to support a pluggable model to easily add or remove functionality.

</details>

<details>
<summary>Console</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/building-console-apps)

* Classes
  * `Console` - Represents the standard input, output, and error streams for console applications. This class cannot be inherited.
  * `ConsoleCancelEventArgs` - Provides data for the CancelKeyPress event. This class cannot be inherited.
* Delegates
  `ConsoleCancelEventHandler` - Represents the method that will handle the CancelKeyPress event of a Console.
* Enums
  * `ConsoleColor` - Specifies constants that define foreground and background colors for the console.
  * `ConsoleKey` - Specifies the standard keys on a console.
  * `ConsoleModifiers` - Represents the SHIFT, ALT, and CTRL modifier keys on a keyboard.
  * `ConsoleSpecialKey` - Specifies combinations of modifier and console keys that can interrupt the current process.
* Structs
  * `ConsoleKeyInfo` - Describes the console key that was pressed, including the character represented by the console key and the state of the SHIFT, ALT, and CTRL modifier keys.

</details>

<details>
<summary>Delegates</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/delegates-lambdas)

* Classes
  * `Delegate` - Represents a delegate, which is a data structure that refers to a static method or to a class instance and an instance method of that class.
  * `MulticastDelegate` - Represents a multicast delegate; that is, a delegate that can have more than one element in its invocation list.
* Delegates
  * `Action` - Encapsulates a method that has no parameters and does not return a value.
  * `Action<T>` - Encapsulates a method that has a single parameter and does not return a value.
  * `Action<T1,T2>` - Encapsulates a method that has two parameters and does not return a value.
  * `Action<T1,T2,T3>` - Encapsulates a method that has three parameters and does not return a value.
  * `Action<T1,T2,T3,T4>` - Encapsulates a method that has four parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5>` - Encapsulates a method that has five parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6>` - Encapsulates a method that has six parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7>` - Encapsulates a method that has seven parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8>` - Encapsulates a method that has eight parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9>` - Encapsulates a method that has nine parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10>` - Encapsulates a method that has 10 parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11>` - Encapsulates a method that has 11 parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12>` - Encapsulates a method that has 12 parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13>` - Encapsulates a method that has 13 parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13,T14>` - Encapsulates a method that has 14 parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13,T14,T15>` - Encapsulates a method that has 15 parameters and does not return a value.
  * `Action<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13,T14,T15,T16>` - Encapsulates a method that has 16 parameters and does not return a value.
  * `Func<TResult>` - Encapsulates a method that has no parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T,TResult>` - Encapsulates a method that has one parameter and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,TResult>` - Encapsulates a method that has two parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,TResult>` - Encapsulates a method that has three parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,TResult>` - Encapsulates a method that has four parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,TResult>` - Encapsulates a method that has five parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,TResult>` - Encapsulates a method that has six parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,TResult>` - Encapsulates a method that has seven parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,TResult>` - Encapsulates a method that has eight parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,TResult>` - Encapsulates a method that has nine parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,TResult>` - Encapsulates a method that has 10 parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,TResult>` - Encapsulates a method that has 11 parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,TResult>` - Encapsulates a method that has 12 parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13,TResult>` - Encapsulates a method that has 13 parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13,T14,TResult>` - Encapsulates a method that has 14 parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13,T14,T15,TResult>` - Encapsulates a method that has 15 parameters and returns a value of the type specified by the TResult parameter.
  * `Func<T1,T2,T3,T4,T5,T6,T7,T8,T9,T10,T11,T12,T13,T14,T15,T16,TResult>` - Encapsulates a method that has 16 parameters and returns a value of the type specified by the TResult parameter.
* Exception Classes
  * `MulticastNotSupportedException` - The exception that is thrown when there is an attempt to combine two delegates based on the Delegate type instead of the MulticastDelegate type. This class cannot be inherited.

</details>

<details>
<summary>Diagnostics</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/core/diagnostics/)

* Classes
  * `FakeLoggerServiceProviderExtensions` - Extensions for configuring fake logging, used in unit tests.
  * `FakeRedactionServiceProviderExtensions` - Extensions that allow registering a fake redactor in the application.
* Namespaces
  * [`System.Diagnostics`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics?view=net-8.0) - Provides classes that allow you to interact with system processes, event logs, and performance counters.
  * [`System.Diagnostics.CodeAnalysis`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.codeanalysis?view=net-8.0) - Contains classes for interaction with code analysis tools. These tools are used to analyze code for conformance to coding conventions such as naming or security rules.
  * [`System.Diagnostics.Contracts`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.contracts?view=net-8.0) - Contains static classes for representing program contracts such as preconditions, postconditions, and invariants.
  * [`System.Diagnostics.Eventing.Reader`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.eventing.reader?view=net-8.0) - Using the System.Diagnostics.Eventing.Reader namespace, you can develop applications that read and manage event logs. An event in an event log contains information, a warning, or an error that has been published by a specific application, service, or operating system component. These events are read by applications that monitor a computer's health and applications that take action when specific events occur. For more information, see Technology Summary for Reading and Managing Event Logs and Event Log Scenarios.
  * [`System.Diagnostics.Metrics`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.metrics?view=net-8.0) - Metrics are numerical measurements reported over time, most often used to monitor the health of an application and generate alerts. For example, a web service might track how many requests it receives each second, how many milliseconds it took to respond, and how many of the responses sent an error back to the user. These metrics can be reported to a monitoring system at frequent, regular intervals. The System.Diagnostics.Metrics namespace can be used to add metrics to an application. The APIs work on all platforms supported by .NET and are designed to integrate well with OpenTelemetry's growing ecosystem of tools. They also integrate with .NET SDK tools, such as dotnet-counters. A listener API is available for developers that want to create custom tooling or adapters to other systems.
  * [`System.Diagnostics.PerformanceData`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.performancedata?view=net-8.0) - Use the classes in this namespace to provide counter data. The counters are used to expose performance metrics to consumers such as the Performance Monitor. The namespace does not contain classes for consuming the counter data. For a complete description of the performance counters architecture, see Performance Counters.
  * [`System.Diagnostics.SymbolStore`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.symbolstore?view=net-8.0) - Provides classes that allow you to read and write debug symbol information, such as source line to Microsoft intermediate language (MSIL) maps. Compilers that target .NET can store the debug symbol information into programmer's database (PDB) files. Debuggers and code profiler tools can read the debug symbol information at run time.
  * [`System.Diagnostics.Tracing`](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.tracing?view=net-8.0) - Provides types and members that enable you to create strongly typed events to be captured by event tracing for Windows (ETW).

</details>

<details>
<summary>Environment</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.environment?view=net-8.0)

* Classes
  * `Environment` - Provides information about, and means to manipulate, the current environment and platform. This class cannot be inherited.
  * `OperatingSystem` - Represents information about an operating system, such as the version and platform identifier. This class cannot be inherited.
* Enums
  * `Environment.SpecialFolder` - Specifies enumerated constants used to retrieve directory paths to system special folders.
  * `Environment.SpecialFolderOption` - Specifies options to use for getting the path to a special folder.
  * `EnvironmentVariableTarget` - Specifies the location where an environment variable is stored or retrieved in a set or get operation.
  * `PlatformID` - Identifies the operating system, or platform, supported by an assembly.
* Exception Classes
  * `PlatformNotSupportedException` - The exception that is thrown when a feature does not run on a particular platform.
  * `UnauthorizedAccessException` - The exception that is thrown when the operating system denies access because of an I/O error or a specific type of security error.

</details>

<details>
<summary>Events</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/events/)

* Classes
  * `EventArgs` - Represents the base class for classes that contain event data, and provides a value to use for events that do not include event data.
* Delegates
  * `EventHandler` - Represents the method that will handle an event that has no event data.
  * `EventHandler<TEventArgs>` - Represents the method that will handle an event when the event provides data.

</details>

<details>
<summary>Exceptions</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/exceptions/)

* Classes
  * `ArgumentException` - The exception that is thrown when one of the arguments provided to a method is not valid.
  * `ArgumentNullException` - The exception that is thrown when a null reference (Nothing in Visual Basic) is passed to a method that does not accept it as a valid argument.
  * `ArgumentOutOfRangeException` - The exception that is thrown when the value of an argument is outside the allowable range of values as defined by the    invoked method.
  * `Exception` - Represents errors that occur during application execution.
  * `FieldAccessException` - The exception that is thrown when there is an invalid attempt to access a private or protected field inside a class.
  * `InvalidOperationException` - The exception that is thrown when a method call is invalid for the object's current state.
  * `MemberAccessException` - The exception that is thrown when an attempt to access a class member fails.
  * `MethodAccessException` - The exception that is thrown when there is an invalid attempt to access a method, such as accessing a private method from partially trusted code.
  * `MissingFieldException` - The exception that is thrown when there is an attempt to dynamically access a field that does not exist. If a field in a class library has been removed or renamed, recompile any assemblies that reference that library.
  * `MissingMemberException` - The exception that is thrown when there is an attempt to dynamically access a class member that does not exist or that is not declared as public. If a member in a class library has been removed or renamed, recompile any assemblies that reference that library.
  * `MissingMethodException` - The exception that is thrown when there is an attempt to dynamically access a method that does not exist.
  * `NotImplementedException` - The exception that is thrown when a requested method or operation is not implemented.
  * `NotSupportedException` - The exception that is thrown when an invoked method is not supported, or when there is an attempt to read, seek, or write to a stream that does not support the invoked functionality.
  * `NullReferenceException` - The exception that is thrown when there is an attempt to dereference a null object reference.
  * `ObjectDisposedException` - The exception that is thrown when an operation is performed on a disposed object.
  * `OverflowException` - The exception that is thrown when an arithmetic, casting, or conversion operation in a checked context results in an overflow.
  * `TimeoutException` - The exception that is thrown when the time allotted for a process or operation has expired.
  * `TypeAccessException` - The exception that is thrown when a method attempts to use a type that it does not have access to.
  * `TypeInitializationException` - The exception that is thrown as a wrapper around the exception thrown by the class initializer. This class cannot be inherited.
  * `TypeLoadException` - The exception that is thrown when type-loading failures occur.
  * `TypeUnloadedException` - The exception that is thrown when there is an attempt to access an unloaded class.
  * `UnhandledExceptionEventArgs` - Provides data for the event that is raised when there is an exception that is not handled in any application domain.
* Delegates
  * `UnhandledExceptionEventHandler` - Represents the method that will handle the event raised by an exception that is not handled by the application domain.

</details>

<details>
<summary>Formatting</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/base-types/formatting-types)

* Classes
  * `FormattableString` - Represents a composite format string, along with the arguments to be formatted.
* Enums
  * `Base64FormattingOptions` - Specifies whether relevant ToBase64CharArray and ToBase64String methods insert line breaks in their output.
* Exception Classes
  * `FormatException` - The exception that is thrown when the format of an argument is invalid, or when a composite format string is not well formed.
* Interfaces
  * `ICustomFormatter` - Defines a method that supports custom formatting of the value of an object.
  * `IFormatProvider` - Provides a mechanism for retrieving an object to control formatting.
  * `IFormattable` - Provides functionality to format the value of an object into a string representation.
  * `ISpanFormattable` - Provides functionality to format the string representation of an object into a span.
  * `IUtf8SpanFormattable` - Provides functionality to format the string representation of an object into a span as UTF-8.
* Namespaces
  * [`System.Formats.Asn1`](https://learn.microsoft.com/en-us/dotnet/api/system.formats.asn1?view=net-8.0) - Contains types used in reading and writing Abstract Syntax Notation One (ASN.1) data structures.`
  * [`System.Formats.Cbor`](https://learn.microsoft.com/en-us/dotnet/api/system.formats.cbor?view=net-8.0) - Contains types used in reading and writing data in the Concise Binary Object Representation (CBOR) format.`
  * [`System.Formats.Nrbf`](https://learn.microsoft.com/en-us/dotnet/api/system.formats.nrbf?view=net-8.0)
  * [`System.Formats.Tar`](https://learn.microsoft.com/en-us/dotnet/api/system.formats.tar?view=net-8.0) - Contains types used in reading and writing data in the Tape Archive (TAR) file archiving format.

</details>

<details>
<summary>Globalization and Localization</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/core/extensions/globalization-and-localization)

* Classes
  * `TimeProvider` - Provides an abstraction for time.
  * `TimeZone` - Represents a time zone.
  * `TimeZoneInfo` - Represents any time zone in the world.
  * `TimeZoneInfo.AdjustmentRule` - Provides information about a time zone adjustment, such as the transition to and from daylight saving time.
* Enums
  * `DateTimeKind` - Specifies whether a DateTime object represents a local time, a Coordinated Universal Time (UTC), or is not specified as either local time or UTC.
  * `DayOfWeek` - Specifies the day of the week.
* Exception Classes
  * `InvalidTimeZoneException` - The exception that is thrown when time zone information is invalid.
  * `TimeZoneNotFoundException` - The exception that is thrown when a time zone cannot be found.
* Namespaces
  * [`System.Globalization`](https://learn.microsoft.com/en-us/dotnet/api/system.globalization?view=net-8.0) - Contains classes that define culture-related information, including language, country/region, calendars in use, format patterns for dates, currency, and numbers, and sort order for strings. These classes are useful for writing globalized (internationalized) applications. Classes such as StringInfo and TextInfo provide advanced globalization functionalities, including surrogate support and text element processing.
  * [`System.Resources`](https://learn.microsoft.com/en-us/dotnet/api/system.resources?view=net-8.0) - Provides classes and interfaces that allow developers to create, store, and manage various culture-specific resources used in an application. One of the most important classes of the System.Resources namespace is the ResourceManager class.
  * [`System.Resources.Extensions`](https://learn.microsoft.com/en-us/dotnet/api/system.resources.extensions?view=net-8.0) - Provides classes that can read and write resources in a format that supports non-primitive objects.
* Structs
  * `DateOnly` - Represents dates with values ranging from January 1, 0001 Anno Domini (Common Era) through December 31, 9999 A.D. (C.E.) in the Gregorian calendar.
  * `DateTime` - Represents an instant in time, typically expressed as a date and time of day.
  * `DateTimeOffset` - Represents a point in time, typically expressed as a date and time of day, relative to Coordinated Universal Time (UTC).
  * `TimeOnly` - Represents a time of day, as would be read from a clock, within the range 000000 to 235959.9999999.
  * `TimeSpan` - Represents a time interval.
  * `TimeZoneInfo.TransitionTime` - Provides information about a specific time change, such as the change from daylight saving time to standard time or vice versa, in a particular time zone.

</details>

<details>
<summary>I/O</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/io/)
  
* Namespaces
  * [`System.IO`](https://learn.microsoft.com/en-us/dotnet/api/system.io?view=net-8.0) - Contains types that allow reading and writing to files and data streams, and types that provide basic file and directory support.
  * [`System.IO.Compression`](https://learn.microsoft.com/en-us/dotnet/api/system.io.compression?view=net-8.0) - Contains classes that provide basic compression and decompression services for streams.
  * [`System.IO.Enumeration`](https://learn.microsoft.com/en-us/dotnet/api/system.io.enumeration?view=net-8.0) - Provides classes, structs, and delegates to search and enumerate file system elements.
  * [`System.IO.Hashing`](https://learn.microsoft.com/en-us/dotnet/api/system.io.hashing?view=net-8.0) - Contains types used in computing non-cryptographic hash values.
  * [`System.IO.IsolatedStorage`](https://learn.microsoft.com/en-us/dotnet/api/system.ioisolatedstorage?view=net-8.0) - Contains types that allow the creation and use of isolated stores. With these stores, you can read and write data that less trusted code cannot access and prevent the exposure of sensitive information that can be saved elsewhere on the file system. Data is stored in compartments that are isolated by the current user and by the assembly in which the code exists. Additionally, data can be isolated by domain. Roaming profiles can be used in conjunction with isolated storage so isolated stores will travel with the user's profile. The IsolatedStorageScope enumeration indicates different types of isolation. For more information about when to use isolated storage, see Isolated Storage.
  * [`System.IO.MemoryMappedFiles`](https://learn.microsoft.com/en-us/dotnet/api/system.io.memorymappedfiles?view=net-8.0) - Provides classes for using a memory-mapped file, which maps the contents of a file to an application's logical address space.
  * [`System.IO.Packaging`](https://learn.microsoft.com/en-us/dotnet/api/system.io.packaging?view=net-8.0) - Provides classes that support storage of multiple data objects in a single container.
  * [`System.IO.Pipelines`](https://learn.microsoft.com/en-us/dotnet/api/system.io.pipelines?view=net-8.0) - Provides types for performing complex, high performance input-output (IO) operations.
  * [`System.IO.Pipes`](https://learn.microsoft.com/en-us/dotnet/api/system.io.pipes?view=net-8.0) - Contains types that provide a means for interprocess communication through anonymous and/or named pipes.
  * [`System.IO.Ports`](https://learn.microsoft.com/en-us/dotnet/api/system.io.ports?view=net-8.0) - Contains classes for controlling serial ports. The most important class, SerialPort, provides a framework for synchronous and event-driven I/O, access to pin and break states, and access to serial driver properties. It can be used to wrap Stream objects, allowing the serial port to be accessed by classes that use streams.

</details>

<details>
<summary>LINQ</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/linq/)

* Namespaces
  * [`System.Dynamic`](https://learn.microsoft.com/en-us/dotnet/api/system.dynamic?view=net-8.0) - Provides classes and interfaces that support Dynamic Language Runtime.
  * [`System.Linq`](https://learn.microsoft.com/en-us/dotnet/api/system.linq?view=net-8.0) - Provides classes and interfaces that support queries that use Language-Integrated Query (LINQ).
  * [`System.Linq.Expressions`](https://learn.microsoft.com/en-us/dotnet/api/system.linq.expressions?view=net-8.0) - Contains classes, interfaces and enumerations that enable language-level code expressions to be represented as objects in the form of expression trees.

</details>

<details>
<summary>Memory</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/automatic-memory-management)

* Classes
  * `BinaryData` - A lightweight abstraction for a payload of bytes that supports converting between string, stream, JSON, and bytes.
  * `GC` - Controls the system garbage collector, a service that automatically reclaims unused memory.
  * `MemoryExtensions` - Provides extension methods for the memory-related and span-related types, such as `Memory<T>`, `ReadOnlyMemory<T>`, `Span<T>`, and `ReadOnlySpan<T>`.
* Enums
  * `GCCollectionMode` - Specifies the behavior for a forced garbage collection.
  * `GCKind` - Specifies the kind of a garbage collection.
  * `GCNotificationStatus` - Provides information about the current registration for notification of the next full garbage collection.
* Exception Classes
  * `AccessViolationException` - The exception that is thrown when there is an attempt to read or write protected memory.
  * `DataMisalignedException` - The exception that is thrown when a unit of data is read from or written to an address that is not a multiple of the data size. This class cannot be inherited.
  * `InsufficientExecutionStackException` - The exception that is thrown when there is insufficient execution stack available to allow most methods to execute.
  * `InsufficientMemoryException` - The exception that is thrown when a check for sufficient available memory fails. This class cannot be inherited.
  * `OutOfMemoryException` - The exception that is thrown when there is not enough memory to continue the execution of a program.
  * `StackOverflowException` - The exception that is thrown when the execution stack exceeds the stack size. This class cannot be inherited.
* Interfaces
  * `IDisposable` - Provides a mechanism for releasing unmanaged resources.
* Namespaces
  * [`System.Buffers`](https://learn.microsoft.com/en-us/dotnet/api/system.buffers?view=net-8.0) - Contains types used in creating and managing memory buffers, such as those represented by `Span<T>` and `Memory<T>`.
  * [`System.Buffers.Binary`](https://learn.microsoft.com/en-us/dotnet/api/system.buffers.binary?view=net-8.0) - Provides static methods for reading and writing the binary representations of primitive types from and to spans of bytes, respectively.
  * [`System.Buffers.Text`](https://learn.microsoft.com/en-us/dotnet/api/system.buffers.text?view=net-8.0) - This namespace contains types that can be used to parse and format common data types to and from UTF-8 text representations.
* Structs
  * `GCGenerationInfo` - Represents the size and the fragmenation of a generation on entry and on exit of the GC reported in GCMemoryInfo.
  * `GCMemoryInfo` - Provides a set of APIs that can be used to retrieve garbage collection information.
  * `Memory<T>` - Represents a contiguous region of memory.
  * `MemoryExtensions.TryWriteInterpolatedStringHandler` - Provides a handler used by the language compiler to format interpolated strings into character spans.
  * `ReadOnlyMemory<T>` - Represents a contiguous region of memory, similar to `ReadOnlySpan<T>`. Unlike `ReadOnlySpan<T>`, it is not a byref-like type.
  * `ReadOnlySpan<T>.Enumerator` - Provides an enumerator for the elements of a `ReadOnlySpan<T>`.
  * `ReadOnlySpan<T>` - Provides a type-safe and memory-safe read-only representation of a contiguous region of arbitrary memory.
  * `SequencePosition` - Represents a position in a non-contiguous set of memory. Properties of this type should not be interpreted by anything but the type that created it.
  * `Span<T>.Enumerator` - Provides an enumerator for the elements of a `Span<T>`.
  * `Span<T>` - Provides a type-safe and memory-safe representation of a contiguous region of arbitrary memory.

</details>

<details>
<summary>Net</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.net?view=net-8.0)

* Namespaces
  * [`System.Net`](https://learn.microsoft.com/en-us/dotnet/api/system.net?view=net-8.0) - Provides a simple programming interface for many of the protocols used on networks today. Classes in the System.Net namespace can be used to develop Windows Store apps or desktop apps. When used in a Windows Store app, classes in the System.Net namespace are affected by network isolation feature, part of the application security model used by the Windows Developer Preview. The appropriate network capabilities must be enabled in the app manifest for a Windows Store app for the system to allow network access by a Windows Store app. For more information, see the Network Isolation for Windows Store Apps.
  * [`System.Net.Cache`](https://learn.microsoft.com/en-us/dotnet/api/system.net.cache?view=net-8.0) - Defines the types and enumerations used to define cache policies for resources obtained using the WebRequest and HttpWebRequest classes.
  * [`System.Net.Http`](https://learn.microsoft.com/en-us/dotnet/api/system.net.http?view=net-8.0) - Provides a programming interface for modern HTTP applications.
  * [`System.Net.Http.Headers`](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.headers?view=net-8.0) - Provides support for collections of HTTP headers used by the System.Net.Http namespace.
  * [`System.Net.Http.Json`](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.json?view=net-8.0) - Provides extension methods for HttpClient and HttpContent that perform automatic serialization and deserialization using System.Text.Json.
  * [`System.Net.Http.Metrics`](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.metrics?view=net-8.0) - Provides additional APIs for advanced metrics use-cases.
  * [`System.Net.Mail`](https://learn.microsoft.com/en-us/dotnet/api/system.net.mail?view=net-8.0) - Contains classes used to send electronic mail to a Simple Mail Transfer Protocol (SMTP) server for delivery.
  * [`System.Net.Mime`](https://learn.microsoft.com/en-us/dotnet/api/system.net.mime?view=net-8.0) - Contains types that are used to represent Multipurpose Internet Mail Exchange (MIME) headers. These types are used with the types in the System.Net.Mail namespace to specify Content-Type, Content-Disposition, and Content-transfer-Encoding headers when using the SmtpClient class to send email.
  * [`System.Net.NetworkInformation`](https://learn.microsoft.com/en-us/dotnet/api/system.net.networkinformation?view=net-8.0) - Provides access to network traffic data, network address information, and notification of address changes for the local computer. The namespace also contains classes that implement the Ping utility. You can use Ping and related classes to check whether a computer is reachable across the network.
  * [`System.Net.PeerToPeer`](https://learn.microsoft.com/en-us/dotnet/api/system.net.peertopeer?view=net-8.0) - Provides access to peer networking functionality.
  * [`System.Net.PeerToPeer.Collaboration`](https://learn.microsoft.com/en-us/dotnet/api/system.net.peertopeer.collaboration?view=net-8.0) - Enhances System.Net.PeerToPeer networking functionality and provides capabilities for serverless managed collaboration sessions.
  * [`System.Net.Quic`](https://learn.microsoft.com/en-us/dotnet/api/system.net.quic?view=net-8.0) - Contains types that implement the QUIC protocol specified by RFC 9000.
  * [`System.Net.Security`](https://learn.microsoft.com/en-us/dotnet/api/system.net.security?view=net-8.0) - Provides network streams for secure communications between hosts.
  * [`System.Net.ServerSentEvents`](https://learn.microsoft.com/en-us/dotnet/api/system.net.serversentevents?view=net-8.0)
  * [`System.Net.Sockets`](https://learn.microsoft.com/en-us/dotnet/api/system.net.sockets?view=net-8.0) - Provides a managed implementation of the Windows Sockets (Winsock) interface for developers who need to tightly control access to the network.
  * [`System.Net.WebSockets`](https://learn.microsoft.com/en-us/dotnet/api/system.net.websockets?view=net-8.0) - Provides a managed implementation of the WebSocket interface for developers.

</details>

<details>
<summary>Numerics</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/numerics)

* Classes
  * `Math` - Provides constants and static methods for trigonometric, logarithmic, and other common mathematical functions.
  * `MathF` - Provides constants and static methods for trigonometric, logarithmic, and other common mathematical functions.
  * `Random` - Represents a pseudo-random number generator, which is an algorithm that produces a sequence of numbers that meet certain statistical requirements for randomness.
* Enums
  * `MidpointRounding` - Specifies the strategy that mathematical rounding methods should use to round a number.
* Exception Classes
  * `ArithmeticException` - The exception that is thrown for errors in an arithmetic, casting, or conversion operation.
  * `DivideByZeroException` - The exception that is thrown when there is an attempt to divide an integral or Decimal value by zero.
  * `NotFiniteNumberException` - The exception that is thrown when a floating-point value is positive infinity, negative infinity, or Not-a-Number (NaN).
* Namespaces
  * [`System.Numerics`](https://learn.microsoft.com/en-us/dotnet/api/system.numerics?view=net-8.0) - Contains numeric types that complement the numeric primitives, such as Byte, Double, and Int32, that are defined by .NET.
  * [`System.Numerics.Tensors`](https://learn.microsoft.com/en-us/dotnet/api/system.numerics.tensors?view=net-8.0)
* Structs
  * `Decimal` - Represents a decimal floating-point number.
  * `Double` - Represents a double-precision floating-point number.
  * `Half` - Represents a half-precision floating-point number.
  * `Int128` - Represents a 128-bit signed integer.
  * `Int16` - Represents a 16-bit signed integer.
  * `Int32` - Represents a 32-bit signed integer.
  * `Int64` - Represents a 64-bit signed integer.
  * `Single` - Represents a single-precision floating-point number.
  * `UInt128` - Represents a 128-bit unsigned integer.
  * `UInt16` - Represents a 16-bit unsigned integer.
  * `UInt32` - Represents a 32-bit unsigned integer.
  * `UInt64` - Represents a 64-bit unsigned integer.

</details>

<details>
<summary>Observer Pattern</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/events/observer-design-pattern)

* Interfaces
  * `IObservable<T>` - Defines a provider for push-based notification.
  * `IObserver<T>` - Provides a mechanism for receiving push-based notifications.

</details>

<details>
<summary>Parsing</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/base-types/parsing-strings)

* Interfaces
  * `IParsable<TSelf>` - Defines a mechanism for parsing a string to a value.
  * `ISpanParsable<TSelf>` - Defines a mechanism for parsing a span of characters to a value.
  * `IUtf8SpanParsable<TSelf>` - Defines a mechanism for parsing a span of UTF-8 characters to a value.

</details>

<details>
<summary>Progress</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.progress-1?view=net-8.0)

* Classes
  * `Progress<T>` - Provides an `IProgress<T>` that invokes callbacks for each reported progress value.
* Interfaces
  * `IProgress<T>` - Defines a provider for progress updates.

</details>

<details>
<summary>Reflection</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/fundamentals/reflection/reflection)

* Classes
  * `Type` - Represents type declarations class types, interface types, array types, value types, enumeration types, type parameters, generic type definitions, and open or closed constructed generic types.
* Namespaces
  * [`System.Reflection`](https://learn.microsoft.com/en-us/dotnet/api/system.reflection?view=net-8.0) - Contains types that retrieve information about assemblies, modules, members, parameters, and other entities in managed code by examining their metadata. These types also can be used to manipulate instances of loaded types, for example to hook up events or to invoke methods. To dynamically create types, use the System.Reflection.Emit namespace.
  * [`System.Reflection.Context`](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.context?view=net-8.0) - Contains classes that enable customized reflection contexts.
  * [`System.Reflection.Emit`](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.emit?view=net-8.0) - Contains classes that allow a compiler or tool to emit metadata and Microsoft intermediate language (MSIL) and optionally generate a PE file on disk. The primary clients of these classes are script engines and compilers.
  * [`System.Reflection.Metadata](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.metadata?view=net-8.0)` - Provides low-level functionality for reading assembly metadata according to ECMA-335. This namespace is designed to be used by compilers and other tools that need to read assembly metadata.
  * [`System.Reflection.Metadata.Ecma335`](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.metadata.ecma335?view=net-8.0) - Provides low-level functionality for writing assembly metadata according to ECMA-335.
  * [`System.Reflection.PortableExecutable`](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.portableexecutable?view=net-8.0) - Provides classes related to reading or writing Portable Executable (PE) files.

</details>

<details>
<summary>Runtime</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/runtime-libraries-overview)

* Attributes
  * `LoaderOptimizationAttribute` - Used to set the default loader optimization policy for the main method of an executable application.
* Classes
  * `AppContext` - Provides members for setting and retrieving data about an application's context.
  * `AppDomain` - Represents an application domain, which is an isolated environment where applications execute. This class cannot be inherited.
  * `AppDomainSetup` - Represents assembly binding information that can be added to an instance of AppDomain.
  * `ApplicationId` - Contains information used to uniquely identify a manifest-based application. This class cannot be inherited.
  * `ApplicationIdentity` - Provides the ability to uniquely identify a manifest-activated application. This class cannot be inherited.
  * `AssemblyLoadEventArgs` - Provides data for the AssemblyLoad event.
  * `ResolveEventArgs` - Provides data for loader resolution events, such as the TypeResolve, ResourceResolve, ReflectionOnlyAssemblyResolve, and AssemblyResolve events.
  * `Version` - Represents the version number of an assembly, operating system, or the common language runtime. This class cannot be inherited.
* Delegates
  * `AssemblyLoadEventHandler` - Represents the method that handles the AssemblyLoad event of an AppDomain.
  * `ResolveEventHandler` - Represents a method that handles the TypeResolve, ResourceResolve, or AssemblyResolve event of an AppDomain.
* Enums
  * `LoaderOptimization` - An enumeration used with the LoaderOptimizationAttribute class to specify loader optimizations for an executable.
* Exception Classes
  * `AggregateException` - Represents one or more errors that occur during application execution.
  * `AppDomainUnloadedException` - The exception that is thrown when an attempt is made to access an unloaded application domain.
  * `ApplicationException` - Serves as the base class for application-defined exceptions.
  * `BadImageFormatException` - The exception that is thrown when the file image of a dynamic link library (DLL) or an executable program is invalid.
  * `CannotUnloadAppDomainException` - The exception that is thrown when an attempt to unload an application domain fails.
  * `ContextMarshalException` - The exception that is thrown when an attempt to marshal an object across a context boundary fails.
  * `DllNotFoundException` - The exception that is thrown when a DLL specified in a DLL import cannot be found.
  * `EntryPointNotFoundException` - The exception that is thrown when an attempt to load a class fails due to the absence of an entry method.
  * `Exception` - Represents errors that occur during application execution.
  * `ExecutionEngineException` - The exception that is thrown when there is an internal error in the execution engine of the common language runtime. This class cannot be inherited.
  * `InvalidProgramException` - The exception that is thrown when a program contains invalid Microsoft intermediate language (MSIL) or metadata. Generally this indicates a bug in the compiler that generated the program. This exception is also thrown when internal runtime implementation limits have been exceeded by the program.
* Namespaces
  * [`System.Runtime`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime?view=net-8.0) - Contains advanced types that support diverse namespaces such as the System, Runtime, and the Security namespaces.
  * [`System.Runtime.Caching`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.caching?view=net-8.0) - Contains types that let you implement caching in .NET applications.
  * [`System.Runtime.Caching.Hosting`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.caching.hosting?view=net-8.0) - Contains types that support .NET Framework hosting environments that use the caching features in ASP.NET.
  * [`System.Runtime.CompilerServices`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.compilerservices?view=net-8.0) - Provides functionality for compiler writers who use managed code to specify attributes in metadata that affect the run-time behavior of the common language runtime.
  * [`System.Runtime.ConstrainedExecution`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.constrainedexecution?view=net-8.0) - Defines a set of types that enumerate and define a contract for reliability between the author of some code, and the developers who take a dependency on that code. The types in the System.Runtime.ConstrainedExecution namespace are intended for use in constrained execution regions (CERs).
  * [`System.Runtime.Diagnostics`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.diagnostics?view=net-8.0)
  * [`System.Runtime.ExceptionServices`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.exceptionservices?view=net-8.0) - Provides classes for advanced exception handling.
  * [`System.Runtime.InteropServices`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.interopservices?view=net-8.0) - Provides a wide variety of members that support COM interop and platform invoke services. If you are unfamiliar with these services, see Interoperating with Unmanaged Code.
  * [`System.Runtime.InteropServices.ComTypes`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.interopservices.comtypes?view=net-8.0) - Contains managed types that correspond to types used by COM interop.
  * [`System.Runtime.InteropServices.JavaScript`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.interopservices.javascript?view=net-8.0) - Contains JSImportAttribute and JSExportAttribute, which can be used to interop with JavaScript when running in the browser or other WASM architectures.
  * [`System.Runtime.InteropServices.Marshalling`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.interopservices.marshalling?view=net-8.0) - Contains support types for source-generated interop, such as MarshalUsingAttribute.
  * [`System.Runtime.InteropServices.ObjectiveC`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.interopservices.objectivec?view=net-8.0) - Contains classes that support interoperation between managed code and the Objective-C Runtime.
  * [`System.Runtime.Intrinsics`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.intrinsics?view=net-8.0) - Contains types used to create and convey register states in various sizes and formats for use with instruction-set extensions. For the instructions to manipulate these registers, see System.Runtime.Intrinsics.X86 and System.Runtime.Intrinsics.Arm.
  * [`System.Runtime.Intrinsics.Arm`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.intrinsics.arm?view=net-8.0) - Exposes select instruction-set extensions for ARM systems. These instruction sets are expressed as separate classes for each extension. Support for any extension within the current environment can be determined by querying the IsSupported property on the respective type.
  * [`System.Runtime.Intrinsics.Wasm`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.intrinsics.wasm?view=net-8.0)
  * [`System.Runtime.Intrinsics.X86`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.intrinsics.x86?view=net-8.0) - Exposes select instruction-set extensions for x86 and x64 systems. These instruction sets are expressed as separate classes for each extension. Support for any extension within the current environment can be determined by querying the IsSupported property on the respective type.
  * [`System.Runtime.Loader`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.loader?view=net-8.0) - Provides interfaces and classes to allow developers the opportunity to influence runtime loading behavior.
  * [`System.Runtime.Remoting`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.remoting?view=net-8.0) - Provides classes and interfaces that allow developers to create and configure distributed applications. Some of the more important classes of the System.Runtime.Remoting namespace are the RemotingConfiguration class, the RemotingServices class, and the ObjRef class.
  * [`System.Runtime.Serialization`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.serialization?view=net-8.0) - Contains classes that can be used for serializing and deserializing objects. Serialization is the process of converting an object or a graph of objects into a linear sequence of bytes for either storage or transmission to another location. Deserialization is the process of taking in stored information and recreating objects from it.
  * [`System.Runtime.Serialization.DataContracts`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.serialization.datacontracts?view=net-8.0)
  * [`System.Runtime.Serialization.Json`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.serialization.json?view=net-8.0) - Provides classes related to Json serialization.
  * [`System.Runtime.Versioning`](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.versioning?view=net-8.0) - Contains advanced types that support versioning in side by side implementations of .NET.
* Structs
  * `ArgIterator` - Represents a variable-length argument list; that is, the parameters of a function that takes a variable number of arguments.
  * `ModuleHandle` - Represents a runtime handle for a module.
  * `RuntimeArgumentHandle` - References a variable-length argument list.
  * `RuntimeFieldHandle` - Represents a field using an internal metadata token.
  * `RuntimeMethodHandle` - RuntimeMethodHandle is a handle to the internal metadata representation of a method.
  * `RuntimeTypeHandle` - Represents a type using an internal metadata token.

</details>

<details>
<summary>Security</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/security/key-security-concepts)

* Namespaces
  * [`System.Security`](https://learn.microsoft.com/en-us/dotnet/api/system.security?view=net-8.0) - Provides the underlying structure of the common language runtime security system, including base classes for permissions.
  * [`System.Security.AccessControl`](https://learn.microsoft.com/en-us/dotnet/api/system.security?view=net-8.0) - Provides programming elements that control access to and audit security-related actions on securable objects.
  * [`System.Security.Authentication`](https://learn.microsoft.com/en-us/dotnet/api/system.security.authentication?view=net-8.0) - Provides a set of enumerations that describe the security of a connection. These enumerations include CipherAlgorithmType, ExchangeAlgorithmType, HashAlgorithmType, and SslProtocols.
  * [`System.Security.Authentication.ExtendedProtection`](https://learn.microsoft.com/en-us/dotnet/api/system.security.authentication.extendedprotection?view=net-8.0) - Provides support for authentication using extended protection for applications.
  * [`System.Security.Claims`](https://learn.microsoft.com/en-us/dotnet/api/system.security.claims?view=net-8.0) - Contains classes that implement claims-based identity in .NET, including classes that represent claims, claims-based identities, and claims-based principals.
  * [`System.Security.Cryptography`](https://learn.microsoft.com/en-us/dotnet/api/system.security.cryptography?view=net-8.0) - Provides cryptographic services, including secure encoding and decoding of data, as well as many other operations, such as hashing, random number generation, and message authentication. For more information, see Cryptographic Services.
  * [`System.Security.Cryptography.Cose`](https://learn.microsoft.com/en-us/dotnet/api/system.security.cryptography.cose?view=net-8.0) - Contains types used in creating and processing CBOR Object Signing and Encryption (COSE) messages.
  * [`System.Security.Cryptography.Pkcs`](https://learn.microsoft.com/en-us/dotnet/api/system.security.cryptography.pkcs?view=net-8.0) - Provides programming elements for Public Key Cryptography Standards (PKCS), including methods for signing data, exchanging keys, requesting certificates, public key encryption and decryption, and other security functions.
  * [`System.Security.Cryptography.X509Certificates`](https://learn.microsoft.com/en-us/dotnet/api/system.security.cryptography.x509certificates?view=net-8.0) - Contains the common language runtime implementation of the Authenticode X.509 v.3 certificate. This certificate is signed with a private key that uniquely and positively identifies the holder of the certificate.
  * [`System.Security.Cryptography.Xml`](https://learn.microsoft.com/en-us/dotnet/api/system.security.cryptography.xml?view=net-8.0) - Contains classes to support the creation and validation of XML digital signatures. The classes in this namespace implement the World Wide Web Consortium Recommendation, XML-Signature Syntax and Processing.
  * [`System.Security.Permissions`](https://learn.microsoft.com/en-us/dotnet/api/system.security.permissions?view=net-8.0) - Defines classes that control access to operations and resources based on policy.
  * [`System.Security.Policy`](https://learn.microsoft.com/en-us/dotnet/api/system.security.policy?view=net-8.0) - Contains code groups, membership conditions, and evidence. These three types of classes are used to create the rules applied by the common language runtime security policy system. Evidence classes are the input to security policy and membership conditions are the switches; together these create policy statements and determine the granted permission set. Policy levels and code groups are the structure of the policy hierarchy. Code groups are the encapsulation of a rule and are arranged hierarchically in a policy level.
  * [`System.Security.Principal`](https://learn.microsoft.com/en-us/dotnet/api/system.security.principal?view=net-8.0) - Defines a principal object that represents the security context under which code is running. For more information, see Role-Based Security.

</details>

<details>
<summary>Text</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/base-types/character-encoding)

* Classes
  * `CharEnumerator` - Supports iterating over a String object and reading its individual characters. This class cannot be inherited.
  * `StringNormalizationExtensions` - Provides extension methods to work with string normalization.
* Enums
  * `StringSplitOptions` - Specifies options for applicable Split method overloads, such as whether to omit empty substrings from the returned array or trim whitespace from substrings.
* Namespaces
  * [`System.Text`](https://learn.microsoft.com/en-us/dotnet/api/system.text?view=net-8.0) - Contains classes that represent ASCII and Unicode character encodings; abstract base classes for converting blocks of characters to and from    blocks of bytes; and a helper class that manipulates and formats String objects without creating intermediate instances of String.
  * [`System.Text.Encodings.Web`](https://learn.microsoft.com/en-us/dotnet/api/system.text.encodings.web?view=net-8.0) - Contains a base class that represent a web encoder; subclasses that represent HTML, JavaScript, and Url character encoding; and a class that represents a filter for allowing only certain characters, character ranges, or code points to be encoded.
  * [`System.Text.Json`](https://learn.microsoft.com/en-us/dotnet/api/system.text.json?view=net-8.0) - Provides high-performance, low-allocating, and standards-compliant capabilities to process JavaScript Object Notation (JSON), which includes serializing objects to JSON text and deserializing JSON text to objects, with UTF-8 support built-in. It also provides types to read and write JSON text encoded as UTF-8, and to create an in-memory document object model (DOM) for random access of the JSON elements within a structured view of the data.
  * [`System.Text.Json.Nodes`](https://learn.microsoft.com/en-us/dotnet/api/system.text.json.nodes?view=net-8.0) - Provides types for handling an in-memory writeable document object model (DOM) for random access of the JSON elements within a structured view of the data.
  * [`System.Text.Json.Schema`](https://learn.microsoft.com/en-us/dotnet/api/system.text.json.schema?view=net-8.0)
  * [`System.Text.Json.Serialization`](https://learn.microsoft.com/en-us/dotnet/api/system.text.json.serialization?view=net-8.0) - Contains classes that are used to customize and extend serialization and deserialization of objects into JSON formatted documents or streams, either via an attribute model or via type converters.
  * [`System.Text.Json.Serialization.Metadata`](https://learn.microsoft.com/en-us/dotnet/api/system.text.json.serialization.metadata?view=net-8.0)
  * [`System.Text.RegularExpressions`](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions?view=net-8.0) - Provides regular expression functionality that may be used from any platform or language that runs within .NET. In addition to the types contained in this namespace, the RegexStringValidator class enables you to determine whether a particular string conforms to a regular expression pattern.
  * [`System.Text.Unicode`](https://learn.microsoft.com/en-us/dotnet/api/system.text.unicode?view=net-8.0) - Contains types that let you retrieve and work with named Unicode ranges.

</details>

<details>
<summary>Threading</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/threading/managed-threading-basics)

* Attributes
  * `MTAThreadAttribute` - Indicates that the COM threading model for an application is multithreaded apartment (MTA).
  * `STAThreadAttribute` - Indicates that the COM threading model for an application is single-threaded apartment (STA).
  * `ThreadStaticAttribute` - Indicates that the value of a static field is unique for each thread.
* Classes
  * `LocalDataStoreSlot` - Encapsulates a memory slot to store local data. This class cannot be inherited.
* Delegates
  * `AsyncCallback` - References a method to be called when a corresponding asynchronous operation completes.
* Exception Classes
  * `DuplicateWaitObjectException` - The exception that is thrown when an object appears more than once in an array of synchronization objects.
  * `OperationCanceledException` - The exception that is thrown in a thread upon cancellation of an operation that the thread was executing.
* Interfaces
  * `IAsyncDisposable` - Provides a mechanism for releasing unmanaged resources asynchronously.
  * `IAsyncResult` - Represents the status of an asynchronous operation.
* Namespaces
  * [`System.Threading`](https://learn.microsoft.com/en-us/dotnet/api/system.threading?view=net-8.0) - Provides classes and interfaces that enable multithreaded programming. In addition to classes for synchronizing thread activities and access to data (Mutex, Monitor, Interlocked, AutoResetEvent, and so on), this namespace includes a ThreadPool class that allows you to use a pool of system-supplied threads, and a Timer class that executes callback methods on thread pool threads.
  * [`System.Threading.Channels`](https://learn.microsoft.com/en-us/dotnet/api/system.threading.channels?view=net-8.0) - Provides a set of synchronization data structures for passing data between producers and consumers asynchronously.
  * [`System.Threading.Tasks`](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks?view=net-8.0) - Provides types that simplify the work of writing concurrent and asynchronous code. The main types are Task which represents an asynchronous operation that can be waited on and cancelled, and `Task<TResult>`, which is a task that can return a value. The TaskFactory class provides static methods for creating and starting tasks, and the TaskScheduler class provides the default thread scheduling infrastructure.
  * [`System.Threading.Tasks.Dataflow`](https://learn.microsoft.com/en-us/dotnet/api/system.threading.dataflow?view=net-8.0) - Provides an actor-based programming model that supports in-process message passing for coarse-grained dataflow and pipelining tasks.
  * [`System.Threading.Tasks.Sources`](https://learn.microsoft.com/en-us/dotnet/api/system.threading.sources?view=net-8.0) - Provides types for creating `ValueTask` and `ValueTask<TResult>` optimized to minimize allocations. The IValueTaskSource and `IValueTaskSource<TResult>` interfaces can be implemented on objects used to provide the backing implementations for `ValueTask` and `ValueTask<TResult>`, and `ManualResetValueTaskSourceCore<TResult>` can be used to implement the core logic necessary to support the task lifecycle. These are advanced types and need only be used in specialized situations where performance is paramount.

</details>

<details>
<summary>Timer</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/threading/timers)

* Classes
  * `ElapsedEventArgs` - Provides data for the Elapsed event.
  * `Timer` - Generates an event after a set interval, with an option to generate recurring events.
  * `TimersDescriptionAttribute` - Sets the description that visual designers can display when referencing an event, extender, or property.
* Delegates
  * `ElapsedEventHandler` - Represents the method that will handle the Elapsed event of a Timer.
* Namespaces
  * [`System.Timers`](https://learn.microsoft.com/en-us/dotnet/api/system.timers?view=net-8.0) - Provides the Timer component, which allows you to raise an event on a specified interval.

</details>

<details>
<summary>Transactions</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/framework/data/transactions/transaction-fundamentals)

* Namespaces
  * [`System.Transactions`](https://learn.microsoft.com/en-us/dotnet/api/system.transactions?view=net-8.0) - Contains classes that allow you to write your own transactional application and resource manager. Specifically, you can create and participate in a transaction (local or distributed) with one or multiple participants.

</details>

<details>
<summary>Tuples</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/value-tuples#tuples-vs-systemtuple)

* Classes
  * `Tuple` - Provides static methods for creating tuple objects.
  * `Tuple<T1>` - Represents a 1-tuple, or singleton.
  * `Tuple<T1,T2>` - Represents a 2-tuple, or pair.
  * `Tuple<T1,T2,T3>` - Represents a 3-tuple, or triple.
  * `Tuple<T1,T2,T3,T4>` - Represents a 4-tuple, or quadruple.
  * `Tuple<T1,T2,T3,T4,T5>` - Represents a 5-tuple, or quintuple.
  * `Tuple<T1,T2,T3,T4,T5,T6>` - Represents a 6-tuple, or sextuple.
  * `Tuple<T1,T2,T3,T4,T5,T6,T7>` - Represents a 7-tuple, or septuple.
  * `Tuple<T1,T2,T3,T4,T5,T6,T7,TRest>` - Represents an n-tuple, where n is 8 or greater.
  * `TupleExtensions` - Provides extension methods for tuples to interoperate with language support for tuples in C#.
* Structs
  * `ValueTuple` - Provides static methods for creating value tuples.
  * `ValueTuple<T1>` - Represents a value tuple with a single component.
  * `ValueTuple<T1,T2>` - Represents a value tuple with 2 components.
  * `ValueTuple<T1,T2,T3>` - Represents a value tuple with 3 components.
  * `ValueTuple<T1,T2,T3,T4>` - Represents a value tuple with 4 components.
  * `ValueTuple<T1,T2,T3,T4,T5>` - Represents a value tuple with 5 components.
  * `ValueTuple<T1,T2,T3,T4,T5,T6>` - Represents a value tuple with 6 components.
  * `ValueTuple<T1,T2,T3,T4,T5,T6,T7>` - Represents a value tuple with 7 components.
  * `ValueTuple<T1,T2,T3,T4,T5,T6,T7,TRest>` - Represents an n-value tuple, where n is 8 or greater.

</details>

<details>
<summary>Types</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/base-types/common-type-system)

* Attributes
  * `FlagsAttribute` - Indicates that an enumeration can be treated as a bit field; that is, a set of flags.
* Classes
  * `Activator` - Contains methods to create types of objects locally or remotely, or obtain references to existing remote objects. This class cannot be inherited.
  * `ContextBoundObject` - Defines the base class for all context-bound classes.
  * `DBNull` - Represents a nonexistent value. This class cannot be inherited.
  * `Enum` - Provides the base class for enumerations.
  * `Lazy<T>` - Provides support for lazy initialization.
  * `Lazy<T,TMetadata>` - Provides a lazy indirect reference to an object and its associated metadata for use by the Managed Extensibility Framework.
  * `MarshalByRefObject` - Enables access to objects across application domain boundaries in applications that support remoting.
  * `Nullable` - Supports a value type that can be assigned null. This class cannot be inherited.
  * `Object` - Supports all classes in the .NET class hierarchy and provides low-level services to derived classes. This is the ultimate base class of all .NET classes; it is the root of the type hierarchy.
  * `String` - Represents text as a sequence of UTF-16 code units.
  * `ValueType` - Provides the base class for value types.
  * `WeakReference` - Represents a weak reference, which references an object while still allowing that object to be reclaimed by garbage collection.
  * `WeakReference<T>` - Represents a typed weak reference, which references an object while still allowing that object to be reclaimed by garbage collection.
* Enums
  * `TypeCode` - Specifies the type of an object.
* Interfaces
  * `ICloneable` - Supports cloning, which creates a new instance of a class with the same value as an existing instance.
* Structs
  * `Boolean` - Represents a Boolean (true or false) value.
  * `Byte` - Represents an 8-bit unsigned integer.
  * `Char` - Represents a character as a UTF-16 code unit.
  * `Guid` - Represents a globally unique identifier (GUID).
  * `HashCode` - Combines the hash code for multiple values into a single hash code.
  * `Index` - Represents a type that can be used to index a collection either from the beginning or the end.
  * `IntPtr` - Represents a signed integer where the bit-width is the same as a pointer.
  * `Nullable<T>` - Represents a value type that can be assigned null.
  * `SByte` - Represents an 8-bit signed integer.
  * `TypedReference` - Describes objects that contain both a managed pointer to a location and a runtime representation of the type that may be stored at that location.
  * `UIntPtr` - Represents an unsigned integer where the bit-width is the same as a pointer.
  * `Void` - Specifies a return value type for a method that does not return a value.

</details>

<details>
<summary>Type Comparison</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.icomparable?view=net-8.0)

* Classes
  * `StringComparer` - Represents a string comparison operation that uses specific case and culture-based or ordinal comparison rules.
* Delegates
  * `Comparison<T>` - Represents the method that compares two objects of the same type.
  * `Predicate<T>` - Represents the method that defines a set of criteria and determines whether the specified object meets those criteria.
* Enums
  * `StringComparison` - Specifies the culture, case, and sort rules to be used by certain overloads of the Compare(String, String) and Equals(Object) methods.
* Interfaces
  * `IComparable` - Defines a generalized type-specific comparison method that a value type or class implements to order or sort its instances.
  * `IComparable<T>` - Defines a generalized comparison method that a value type or class implements to create a type-specific comparison method for ordering or sorting its instances.
  * `IEquatable<T>` - Defines a generalized method that a value type or class implements to create a type-specific method for determining equality of instances.

</details>

<details>
<summary>Type Conversion</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/base-types/type-conversion)

* Classes
  * `BitConverter` - Converts base data types to an array of bytes, and an array of bytes to base data types.
  * `Convert` - Converts a base data type to another base data type.
* Delegates
  * `Converter<TInput,TOutput>` - Represents a method that converts an object from one type to another type.
* Exception Classes
  * `InvalidCastException` - The exception that is thrown for invalid casting or explicit conversion.
* Interfaces
  * `IConvertible` - Defines methods that convert the value of the implementing reference or value type to a common language runtime type that has an equivalent value.

</details>

<details>
<summary>Uri</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/fundamentals/runtime-libraries/system-uri)

* Classes
  * `FileStyleUriParser` - A customizable parser based on the File scheme.
  * `FtpStyleUriParser` - A customizable parser based on the File Transfer Protocol (FTP) scheme.
  * `GenericUriParser` - A customizable parser for a hierarchical URI.
  * `GopherStyleUriParser` - A customizable parser based on the Gopher scheme.
  * `HttpStyleUriParser` - A customizable parser based on the HTTP scheme.
  * `LdapStyleUriParser` - A customizable parser based on the Lightweight Directory Access Protocol (LDAP) scheme.
  * `NetPipeStyleUriParser` - A parser based on the NetPipe scheme for the "Indigo" system.
  * `NetTcpStyleUriParser` - A parser based on the NetTcp scheme for the "Indigo" system.
  * `NewsStyleUriParser` - A customizable parser based on the news scheme using the Network News Transfer Protocol (NNTP).
  * `Uri` - Provides an object representation of a uniform resource identifier (URI) and easy access to the parts of the URI.
  * `UriBuilder` - Provides a custom constructor for uniform resource identifiers (URIs) and modifies URIs for the Uri class.
  * `UriParser` - Parses a new URI scheme. This is an abstract class.
  * `UriTypeConverter` - Converts a String type to a Uri type, and vice versa.
* Enums
  * `GenericUriParserOptions` - Specifies options for a UriParser.
  * `UriComponents` - Specifies the parts of a Uri.
  * `UriFormat` - Controls how URI information is escaped.
  * `UriHostNameType` - Defines host name types for the CheckHostName(String) method.
  * `UriIdnScope` - Provides the possible values for the configuration setting of the IdnElement in the System.Configuration namespace.
  * `UriKind` - Defines the different kinds of URIs.
  * `UriPartial` - Defines the parts of a URI for the GetLeftPart(UriPartial) method.
* Exception Classes
  * `UriFormatException` - The exception that is thrown when an invalid Uniform Resource Identifier (URI) is detected.
* Structs
  * `UriCreationOptions` - Provides options that control how a Uri is created and behaves.

</details>

<details>
<summary>XAML</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.xaml?view=windowsdesktop-8.0)

* Namespaces
  * [`System.Xaml`](https://learn.microsoft.com/en-us/dotnet/api/system.xaml?view=net-8.0) - Provides classes related to XAML.
  * [`System.Xaml.Permissions`](https://learn.microsoft.com/en-us/dotnet/api/system.xaml?view=net-8.0) - Contains types that specify permissions for certain XAML loading scenarios, such as loading under partial trust or loading internal types.

</details>

<details>
<summary>XML</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/standard/data/xml/)

* Namespaces
  * [`System.Xml`](https://learn.microsoft.com/en-us/dotnet/api/system.xml?view=net-8.0) - Provides standards-based support for processing XML.
  * [`System.Xml.Linq`](https://learn.microsoft.com/en-us/dotnet/api/system.xml.linq?view=net-8.0) - Contains the classes for LINQ to XML. LINQ to XML is an in-memory XML programming interface that enables you to modify XML documents efficiently and easily.
  * [`System.Xml.Resolvers`](https://learn.microsoft.com/en-us/dotnet/api/system.xml.resolvers?view=net-8.0) - Provides support for prepopulating the cache with DTDs or XML streams.
  * [`System.Xml.Schema`](https://learn.microsoft.com/en-us/dotnet/api/system.xml.schema?view=net-8.0) - Contains the XML classes that provide standards-based support for XML schema definition language (XSD) schemas.
  * [`System.Xml.Serialization`](https://learn.microsoft.com/en-us/dotnet/api/system.xml.serialization?view=net-8.0) - Contains classes that are used to serialize objects into XML format documents or streams.
  * [`System.Xml.XPath`](https://learn.microsoft.com/en-us/dotnet/api/system.xml.xpath?view=net-8.0) - Contains the classes that define a cursor model for navigating and editing XML information items as instances of the XQuery 1.0 and XPath 2.0 Data Model.
  * [`System.Xml.Xsl`](https://learn.microsoft.com/en-us/dotnet/api/system.xml.xsl?view=net-8.0) - Provides support for Extensible Stylesheet Transformation (XSLT) transforms. It supports the W3C XSL Transformations (XSLT) Version 1.0 Recommendation.

</details>

### Deprecated

<details>
<summary>CodeDOM</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/dynamic-source-code-generation-and-compilation)

* Namespaces
  * [`System.CodeDom`](https://learn.microsoft.com/en-us/dotnet/api/system.codedom?view=net-8.0) - Contains classes that can be used to represent the elements and structure of a source code document. The classes in this namespace can be used to model the structure of a source code document that can be output as source code in a supported language using the functionality provided by the System.CodeDom.Compiler namespace.
  * [`System.CodeDom.Compiler`](https://learn.microsoft.com/en-us/dotnet/api/system.codedom.compiler?view=net-8.0) - Contains types for managing the generation and compilation of source code in supported programming languages. Code generators can each produce source code in a particular programming language based on the structure of Code Document Object Model (CodeDOM) source code models consisting of elements provided by the System.CodeDom namespace.

</details>

<details>
<summary>Component Model and Composition</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/framework/mef/)

* Interfaces
  * `IServiceProvider` - Defines a mechanism for retrieving a service object; that is, an object that provides custom support to other objects.
* Namespaces
  * [`System.ComponentModel`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel?view=net-8.0) - Provides classes that are used to implement the run-time and design-time behavior of components and controls. This namespace includes the base classes and interfaces for implementing attributes and type converters, binding to data sources, and licensing components.
  * [`System.ComponentModel.Composition`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.composition?view=net-8.0) - This namespace provides classes that constitute the core of the Managed Extensibility Framework, or MEF.
  * [`System.ComponentModel.Composition.Hosting`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.composition.hosting?view=net-8.0) - Provides Managed Extensibility Framework (MEF) types that are useful to developers of extensible applications, or hosts.
  * [`System.ComponentModel.Composition.Primitives`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.composition.primitives?view=net-8.0) - This namespace provides the primitive types underlying the MEF programming model.
  * [`System.ComponentModel.Composition.ReflectionModel`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.composition.reflectionmodel?view=net-8.0) - Provides Managed Extensibility Framework (MEF) types for developers who use a reflection-based programming model.
  * [`System.ComponentModel.Composition.Registration`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.composition.registration?view=net-8.0) - Contains types that enable rule-based configuration of Managed Extensibility Framework (MEF) parts.
  * [`System.ComponentModel.DataAnnotations`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.dataannotations?view=net-8.0) - Provides attribute classes that are used to define metadata for ASP.NET MVC and ASP.NET data controls.
  * [`System.ComponentModel.DataAnnotations.Schema`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.dataannotations.schema?view=net-8.0) - Provides support for attribute classes that are used to define metadata for ASP.NET MVC and ASP.NET data controls.
  * [`System.ComponentModel.Design`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.design?view=net-8.0) - Contains classes that developers can use to build custom design-time behavior for components and user interfaces for configuring components at design time. The design time environment provides systems that enable developers to arrange components and configure their properties. Some components may require specific design-time only behavior to function properly in a design time environment. It may also be valuable to provide custom user interfaces which assist developers in configuring components or the values of complex data types. The classes and interfaces defined within this namespace can be used to build design-time behavior for components, access design-time services, and implement customized design-time configuration interfaces.
  * [`System.ComponentModel.Design.Serialization`](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.design.serialization?view=net-8.0) - Provides types that support customization and control of serialization at design time.
  * [`System.Composition`](https://learn.microsoft.com/en-us/dotnet/api/system.composition?view=net-8.0) - Contains classes for creating and specifying export attributes, retrieving exports from a composition, configuring import attributes, and for specifying how parts interact during composition.
  * [`System.Composition.Convention`](https://learn.microsoft.com/en-us/dotnet/api/system.composition?view=net-8.0) - Contains classes that represent convention builders for constructing rules used to configure CLR objects as MEF parts.
  * [`System.Composition.Hosting`](https://learn.microsoft.com/en-us/dotnet/api/system.composition?view=net-8.0) - Contains classes for building and configuring a composition container and for reporting exceptions from a failed composition.
  * [`System.Composition.Hosting.Core`](https://learn.microsoft.com/en-us/dotnet/api/system.composition?view=net-8.0) - Contains classes that represent core functionality of the composition engine, including composition operations, contracts, part dependencies, export descriptions, and the lifetime context of a shared part that governs how it can be disposed.

</details>

<details>
<summary>Web</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.web?view=net-8.0)

* Namespaces
  * [`System.Web`](https://learn.microsoft.com/en-us/dotnet/api/system.web?view=net-8.0) - For .NET Core and .NET 5+, this namespace contains the HttpUtility class. For .NET Framework, this namespace contains classes and interfaces that enable browser-server communication. These classes include the HttpRequest class, which provides extensive information about the current HTTP request; the HttpResponse class, which manages HTTP output to the client; and the HttpServerUtility class, which provides access to server-side utilities and processes. System.Web also includes classes for cookie manipulation, file transfer, exception information, and output cache control in .NET Framework.

</details>

### Windows Only

<details>
<summary>Active Directory</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.directoryservices?view=net-8.0)

* Namespaces
  * [`System.DirectoryServices`](https://learn.microsoft.com/en-us/dotnet/api/system.directoryservices?view=net-8.0) - Provides easy access to Active Directory Domain Services from managed code. The namespace contains two component classes, DirectoryEntry and DirectorySearcher, which use the Active Directory Services Interfaces (ADSI) technology. ADSI is the set of interfaces that Microsoft provides as a flexible tool for working with a variety of network providers. ADSI gives the administrator the ability to locate and manage resources on a network with relative ease, regardless of the size of the network.
  * [`System.DirectoryServices.AccountManagement`](https://learn.microsoft.com/en-us/dotnet/api/system.directoryservices.accountmanagement?view=net-8.0) - Provides uniform access and manipulation of user, computer, and group security principals across the multiple principal stores Active Directory Domain Services (AD DS), Active Directory Lightweight Directory Services (AD LDS), and Machine SAM (MSAM). System.DirectoryServices.AccountManagement manages directory objects independent of the System.DirectoryServices namespace.
  * [`System.DirectoryServices.ActiveDirectory`](https://learn.microsoft.com/en-us/dotnet/api/system.directoryservices.activedirectory?view=net-8.0) - Provides a high level abstraction object model that builds around Microsoft Active Directory services tasks. The Active Directory service concepts such as forest, domain, site, subnet, partition, and schema are part of the object model.
  * [`System.DirectoryServices.Protocols`](https://learn.microsoft.com/en-us/dotnet/api/system.directoryservices.protocols?view=net-8.0) - Provides the methods defined in the Lightweight Directory Access Protocol (LDAP) version 3 (V3) and Directory Services Markup Language (DSML) version 2.0 (V2) standards.

</details>

<details>
<summary>Drawing (GDI+)</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.graphics?view=net-8.0)

* Namespaces
  * [`System.Drawing`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing?view=net-8.0) - Provides access to GDI+ basic graphics functionality. The System.Drawing.Drawing2D, System.Drawing.Imaging, and System.Drawing.Text namespaces provide more advanced functionality. For limitations, see the Remarks section.
  * [`System.Drawing.Configuration`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.configuration?view=net-8.0) - Contains a class that supports configuration for classes in the System.Drawing namespace.
  * [`System.Drawing.Design`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.design?view=net-8.0) - Contains classes that extend design-time user interface (UI) logic and drawing.
  * [`System.Drawing.Drawing2D`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.drawing2d?view=net-8.0) - Provides advanced two-dimensional and vector graphics functionality.
  * [`System.Drawing.Imaging`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.imaging?view=net-8.0) - Provides advanced GDI+ imaging functionality. Basic graphics functionality is provided by the System.Drawing namespace.
  * [`System.Drawing.Interop`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.interop?view=net-8.0)
  * [`System.Drawing.Printing`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.printing?view=net-8.0) - Provides print-related services for Windows Forms applications.
  * [`System.Drawing.Text`](https://learn.microsoft.com/en-us/dotnet/api/system.drawing.text?view=net-8.0) - Provides advanced GDI+ typography functionality.

</details>

<details>
<summary>Identity Model</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.identitymodel.tokens.securitytoken?view=net-8.0)

* Namespaces
  * [`System.IdentityModel`](https://learn.microsoft.com/en-us/dotnet/api/system.identitymodel?view=net-8.0) - Contains classes that are used to build security token services (STS). These include the SecurityTokenService and Scope classes, as well as exception several utility classes that provide the ability to perform cookie transforms.
  * [`System.IdentityModel.Claims`](https://learn.microsoft.com/en-us/dotnet/api/system.identitymodel.claims?view=net-8.0) - Contains classes that implement the Windows Communication Foundation (WCF) claims-based identity authorization model. This model includes the Claim class and the ClaimSet class. Beginning with .NET Framework 4.5 and the integration of Windows Identity Foundation (WIF) into the .NET Framework, the WCF claims-based identity model has been superseded by WIF. WIF provides a claims-based identity object model that can be used to provide authentication and authorization across several Microsoft product stacks, including the CLR, WCF, and ASP.NET. The WIF classes that represent claims, claim types, and identities and principals that are based on claims are contained in the System.Security.Claims namespace. Beginning with .NET 4.5, these classes should be used instead of those in the System.IdentityModel.Claims namespace.
  * [`System.IdentityModel.Policy`](https://learn.microsoft.com/en-us/dotnet/api/system.identitymodel.policy?view=net-8.0) - Contains classes that are used to implement authorization policy when using the WCF claims-based identity model. Beginning with .NET Framework 4.5 and the integration of Windows Identity Foundation (WIF) into the .NET Framework, the WCF claims-based identity model has been superseded by WIF. WIF provides a claims-based identity object model that can be used to provide authentication and authorization across several Microsoft product stacks, including the CLR, WCF, and ASP.NET. In WIF, authorization policy is implemented by extending the ClaimsAuthorizationManager class. Beginning with .NET 4.5, authorization policy should be implemented by using WIF instead of the classes in the System.IdentityModel.Claims namespace.
  * [`System.IdentityModel.Selectors`](https://learn.microsoft.com/en-us/dotnet/api/system.identitymodel.selectors?view=net-8.0) - Contains classes that implement authentication in the Windows Communication Foundation (WCF) claims-based identity model. Beginning with .NET Framework 4.5 and the integration of Windows Identity Foundation (WIF) into the .NET Framework, the WCF claims-based identity model has been superseded by WIF. WIF provides a claims-based identity object model that can be used to provide authentication and authorization across several Microsoft product stacks, including the CLR, WCF, and ASP.NET. The WIF classes that represent security tokens and that are used to process security tokens are contained in the System.IdentityModel.Tokens namespace; for example, SecurityToken and SecurityTokenHandler. Beginning with .NET 4.5, the classes in the System.IdentityModel.Tokens namespace should be used instead of those in the System.IdentityModel.Selectors namespace.
  * [`System.IdentityModel.Tokens`](https://learn.microsoft.com/en-us/dotnet/api/system.identitymodel.tokens?view=net-8.0) - Contains base classes such as SecurityToken, SecurityTokenHandler, and SecurityKeyIdentifierClause, as well as classes that derive from these classes and represent several of the token types, artifacts, and handlers for which the Windows Identity Foundation (WIF) has built in support. This includes classes that contain support for SAML v1.1 and v2.0 tokens, such as SamlSecurityToken, SamlSecurityTokenHandler, Saml2SecurityToken, and Saml2SecurityTokenHandler.

</details>

<details>
<summary>Media</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.media?view=net-8.0)

* Namespaces
  * [`System.Media`](https://learn.microsoft.com/en-us/dotnet/api/system.media?view=net-8.0) - Contains classes for playing sound files and accessing sounds provided by the system.

</details>

<details>
<summary>Service Process</summary>

* Namespaces
  * [`System.ServiceProcess`](https://learn.microsoft.com/en-us/dotnet/api/system.serviceprocess?view=net-8.0) - Provides classes that allow you to implement, install, and control Windows service applications. Services are long-running    executables that run without a user interface. Implementing a service involves inheriting from the ServiceBase class and defining specific behavior to process when start, stop, pause, and continue commands are passed in, as well as custom behavior and actions to take when the system shuts down.

</details>

<details>
<summary>Speech</summary>

* Namespaces
  * [`System.Speech.AudioFormat`](https://learn.microsoft.com/en-us/dotnet/api/system.speech.audioformat?view=net-8.0) - Contains a single class, SpeechAudioFormatInfo, that contains information about the format of the audio that is being input to the speech recognition engine, or being output from the speech synthesis engine.
  * [`System.Speech.Recognition`](https://learn.microsoft.com/en-us/dotnet/api/system.speech.recognition?view=net-8.0) - Contains Windows Desktop Speech technology types for implementing speech recognition.
  * [`System.Speech.Recognition.SrgsGrammar`](https://learn.microsoft.com/en-us/dotnet/api/system.speech.recognition.srgsgrammar?view=net-8.0) - With the members of the System.Speech.Recognition.SrgsGrammar namespace, you can programmatically create grammars that comply with the W3C Speech Recognition Grammar Specification Version 1.0 (SRGS).
  * [`System.Speech.Synthesis`](https://learn.microsoft.com/en-us/dotnet/api/system.speech.synthesis?view=net-8.0) - Contains classes for initializing and configuring a speech synthesis engine, for creating prompts, for generating speech, for responding to events, and for modifying voice characteristics.
  * [`System.Speech.Synthesis.TtsEngine`](https://learn.microsoft.com/en-us/dotnet/api/system.speech.synthesis.ttsengine?view=net-8.0) - Supports the creation of Speech Synthesis Markup Language (SSML) based custom engines for rendering text to speech (TTS).

</details>

<details>
<summary>WCF Service Model</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/framework/wcf/whats-wcf)

* Namespaces
  * [`System.ServiceModel`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel?view=net-8.0) - Provides classes related to the service model.
  * [`System.ServiceModel.Channels`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel.channels?view=net-8.0) - Provides classes related to service model channels.
  * [`System.ServiceModel.Description`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel.description?view=net-8.0) - Provides classes related to the service model description.
  * [`System.ServiceModel.Dispatcher`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel.dispatcher?view=net-8.0) - Provides classes related to dispatching the service model.
  * [`System.ServiceModel.Federation`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel.federation?view=net-8.0)
  * [`System.ServiceModel.Security`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel.security?view=net-8.0) - Contains general security-related types.
  * [`System.ServiceModel.Security.Tokens`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel.tokens?view=net-8.0) - Deals with security tokens and certificates.
  * [`System.ServiceModel.Syndication`](https://learn.microsoft.com/en-us/dotnet/api/system.servicemodel.syndication?view=net-8.0) - Provides classes related to service model syndication.

</details>

<details>
<summary>Windows Management Instrumentation</summary>

* Namespaces
  * [`System.Management`](https://learn.microsoft.com/en-us/dotnet/api/system.management?view=net-8.0) - Provides access to a rich set of management information and management events about the system, devices, and applications instrumented to the Windows Management Instrumentation (WMI) infrastructure. Applications and services can query for interesting management information (such as how much free space is left on the disk, what is the current CPU utilization, which database a certain application is connected to, and much more), using classes derived from ManagementObjectSearcher and ManagementQuery, or subscribe to a variety of management events using the ManagementEventWatcher class. The accessible data can be from both managed and unmanaged components in the distributed environment.

</details>

<details>
<summary>Windows Presentation Foundation</summary>

* [Overview](https://learn.microsoft.com/en-us/dotnet/api/system.windows?view=windowsdesktop-8.0)

* Namespaces
  * [`System.Windows`](https://learn.microsoft.com/en-us/dotnet/api/system.windows?view=net-8.0) - Provides classes related to Windows Presentation Foundation.
  * [`System.Windows.Input`](https://learn.microsoft.com/en-us/dotnet/api/system.windows.input?view=net-8.0) - Most of the types in this namespace support the Windows Presentation Foundation (WPF) input system. This includes device abstraction classes for mouse, keyboard, and stylus devices, a common input manager class, support for commanding and custom commands, and various utility classes. However, some of the types are applicable beyond WPF.
  * [`System.Windows.Markup`](https://learn.microsoft.com/en-us/dotnet/api/system.windows.markup?view=net-8.0) - Provides types to support XAML. Some of these types are located in WPF assemblies and are specific to WPF scenarios that involve XAML. Other types in this namespace provide support for .NET XAML Services in general, and don't require referencing WPF assemblies.

</details>

