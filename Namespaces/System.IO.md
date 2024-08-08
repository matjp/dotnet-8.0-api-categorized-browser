* Classes:
  * BinaryReader - Reads primitive data types as binary values in a specific encoding.
  * BinaryWriter - Writes primitive types in binary to a stream and supports writing strings in a specific encoding.
  * BufferedStream - Adds a buffering layer to read and write operations on another stream. This class cannot be inherited.
  * Directory - Exposes static methods for creating, moving, and enumerating through directories and subdirectories. This class cannot be inherited.
  * DirectoryInfo - Exposes instance methods for creating, moving, and enumerating through directories and subdirectories. This class cannot be inherited.
  * DriveInfo - Provides access to information on a drive.
  * EnumerationOptions - Provides file and directory enumeration options.
  * ErrorEventArgs - Provides data for the Error event.
  * File - Provides static methods for the creation, copying, deletion, moving, and opening of a single file, and aids in the creation of FileStream objects.
  * FileInfo - Provides properties and instance methods for the creation, copying, deletion, moving, and opening of files, and aids in the creation of FileStream objects. This class cannot be inherited.
  * FileStream - Provides a Stream for a file, supporting both synchronous and asynchronous read and write operations.
  * FileStreamOptions - Defines a variety of configuration options for FileStream.
  * FileSystemAclExtensions - Provides Windows-specific static extension methods for manipulating Access Control List (ACL) security attributes for files and directories.
  * FileSystemEventArgs - Provides data for the directory events: Changed, Created, Deleted.
  * FileSystemInfo - Provides the base class for both FileInfo and DirectoryInfo objects.
  * FileSystemWatcher - Listens to the file system change notifications and raises events when a directory, or file in a directory, changes.
  * MemoryStream - Creates a stream whose backing store is memory.
  * Path - Performs operations on String instances that contain file or directory path information. These operations are performed in a cross-platform manner.
  * RandomAccess - Provides offset-based APIs for reading and writing files in a thread-safe manner.
  * RenamedEventArgs - Provides data for the Renamed event.
  * Stream - Provides a generic view of a sequence of bytes. This is an abstract class.
  * StreamReader - Implements a TextReader that reads characters from a byte stream in a particular encoding.
  * StreamWriter -Implements a TextWriter for writing characters to a stream in a particular encoding.
  * StringReader - Implements a TextReader that reads from a string.
  * StringWriter - Implements a TextWriter for writing information to a string. The information is stored in an underlying StringBuilder.
  * TextReader - Represents a reader that can read a sequential series of characters.
  * TextWriter - Represents a writer that can write a sequential series of characters. This class is abstract.
  * UnmanagedMemoryAccessor - Provides random access to unmanaged blocks of memory from managed code.
  * UnmanagedMemoryStream - Provides access to unmanaged blocks of memory from managed code.
* Exception Classes:
  * DirectoryNotFoundException - The exception that is thrown when part of a file or directory cannot be found.
  * DriveNotFoundException - The exception that is thrown when trying to access a drive or share that is not available.
  * EndOfStreamException - The exception that is thrown when reading is attempted past the end of a stream.
  * FileFormatException - The exception that is thrown when an input file or a data stream that is supposed to conform to a certain file format specification is malformed.
  * FileLoadException - The exception that is thrown when a managed assembly is found but cannot be loaded.
  * FileNotFoundException - The exception that is thrown when an attempt to access a file that does not exist on disk fails.
  * InternalBufferOverflowException - The exception thrown when the internal buffer overflows.
  * InvalidDataException - The exception that is thrown when a data stream is in an invalid format.
  * IOException - The exception that is thrown when an I/O error occurs.
  * PathTooLongException - The exception that is thrown when a path or fully qualified file name is longer than the system-defined maximum length.
  * PipeException - Thrown when an error occurs within a named pipe.
* Structs:
  * DriveType - Defines constants for drive types, including CDRom, Fixed, Network, NoRootDirectory, Ram, Removable, and Unknown.
  * FileAccess - Defines constants for read, write, or read/write access to a file.
  * FileAttributes - Provides attributes for files and directories.
  * FileMode - Specifies how the operating system should open a file.
  * FileOptions - Represents advanced options for creating a FileStream object.
  * FileShare - Contains constants for controlling the kind of access other operations can have to the same file.
  * HandleInheritability - Specifies whether the underlying handle is inheritable by child processes.
  * MatchCasing - Specifies the type of character casing to match.
  * MatchType - Specifies the type of wildcard matching to use.
  * NotifyFilters - Specifies changes to watch for in a file or folder.
  * SearchOption - Specifies whether to search the current directory, or the current directory and all subdirectories.
  * SeekOrigin - Specifies the position in a stream to use for seeking.
  * UnixFileMode - Represents the Unix filesystem permissions. This enumeration supports a bitwise combination of its member values.
  * WatcherChangeTypes - Changes that might occur to a file or directory.
* Delegates:
  * ErrorEventHandler - Represents the method that will handle the Error event of a FileSystemWatcher object.
  * FileSystemEventHandler - Represents the method that will handle the Changed, Created, or Deleted event of a FileSystemWatcher class.
  * RenamedEventHandler - Represents the method that will handle the Renamed event of a FileSystemWatcher class.
