# File and stream I/O (input/output) 
-	It is the process of transferring data to or from a storage medium.

-	The System.IO namespaces in.NET contain types that enable synchronous and asynchronous reading and writing on data streams and files.

-	Types that conduct file compression and decompression, as well as types that enable communication via pipes and serial ports, are all found in these namespaces.

-	A File is a sorted and named collection of bytes that has persistent storage.


## Files and directories

-	You can deal with files and directories using the types in the System.IO namespace.

Some file and directory classes:
-	DirectoryInfo: creates, moves, and enumerates over directories and subdirectories using instance methods.

-	Path: offers cross-platform methods and attributes for processing directory strings.

-	File: creates, copies, deletes, moves, and opens files, as well as assisting in the creation of a FileStream object.

-	FileInfo: aids in the creation of a FileStream object by providing instance methods for creating, copying, deleting, moving, and opening files.

-	Directory: contains static methods for creating, moving, and enumerating over directories and subdirectories

## Steams
-	Reading and writing bytes is supported by the abstract base class Stream.

-	The Stream class is inherited by all classes that represent streams.

-	A common view of data sources and repositories are provided by the stream class and its derived classes.

-	the stream class and its derived classes isolate the programmer from the operating system’s and the underlying devices’ details.

Streams are made up of three basic operations:

-	Reading: moving data from a stream to a data structure, such as a bytes’ array

-	Writing:  moving data from a data source to a stream

-	Seeking: searching for and changing the current place in a stream

## Classes and methods are used to write text to a file:

-	StreamWriter: includes ways for writing to a file synchronously or asynchronously.

-	File: it has methods for writing text to a file that are static.

-	Path: it is for strings that include information about file or directory paths.


Examples on classes that are used to read and write data:
-	System.IO.BinaryWriter
-	System.IO.BinaryReader

