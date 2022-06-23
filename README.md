
# FileStore

A defined record read/write library with indexing.

# FileStore SDK

This is a complete SDK that can be used to build a simple record storage file.
FileStore provides all the I/O mechanisms to Open files, Read, Write, and Detete records.
FileStore keeps track of records deleted and reuses storage space.

FileStore also provides a BTree indexing.

A fully working example is provided showing how to use the SDK classes.

The Docs directory contains a PDF file (FileStore.pdf) that provides a walkthrough as
well as class level documentation (Class_Documentation.html).

# Coding Language / Requirements

This is a C++ library built using the Qt SDK 6.x.
You will need a copy of the Qt SDK 6.x library files to link with FileStore SDK.

# Sample Project

In the Sample folder you will find a Qt project file, FileStoreSample.pro.  You can 
create a Visual Studio project or Xcode project from it if needed.
If you use QtCreator set the "Build Directory" in the build setting to:
<your_folder>/FileStore/build

# Licensing

This SDK is provided free to all users.
It is licensed under the LGPLv3 license.
