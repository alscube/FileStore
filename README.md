# FileStore

A defined record read/write library with BTree indexing.

FileStore is a cross platform SDK for Windows, Linux, and macOS.


# FileStore SDK

This is a complete SDK that can be used to build a simple record storage file.
FileStore provides all the I/O mechanisms to Open, Read, Write, and Detete files/records.
FileStore keeps track of records deleted and reuses storage space.

A fully working example is provided showing how to use the SDK classes.

The Docs directory contains a PDF file (FileStore.pdf) that provides a walkthrough as
well as class level documentation (Class_Documentation.html).


# Coding Language / Requirements

This is a C++ library built using the Qt SDK 6.x. You will need a copy 
of the Qt SDK 6.x to link with. 

Qt can be downloaded from https://www.qt.io

FileStore SDK only uses Qt's core libraries. 


# Sample Project

In the Sample folder you will find a Qt project file, FileStoreSample.pro.  You can 
create a Visual Studio project or Xcode project from it if needed.

For Windows copy the FileStore DLL to the debug/release directory where the EXE was created.

Be aware that the FileStore library throws exceptions.  When developing always use the 
Debug or Release version that matches your build type.  If the FileStore library does not 
match your build type exceptions will not be handled correctly.


# Licensing

This SDK is provided free to all users.  It is licensed under the LGPLv3 license.

See the FileStore LICENSE file.

