---
title: ios FileManager
date: 2021-04-30 15:59:16
tags:
---

[File System Programming Guide][1]

- Resource files:
  - Nib filesTLS certificate is being provisioned.p
  - Image files
  - Sound files
  - String files
  - Localized resources
- Text Files
  - Plain text file
  - UTF-8 formatted file
  - Utf-16 formatted file
- Structured data files
  - XML file
  - Property list file
  - Preference file
- Archive files
  - Binary files created using a keyed archiver objecct
- File packages
  - Custom document formats
- Bundles
  - Apps
  - Plug-ins
  - Frameworks
- Code files 
  - Binary code resources
  - Dynamic shared libraries  


NSURL VS NSString

    The preferred way to specify the location of a file or directory is to use the NSURL class. Although the NSString class has many methods related to path creation, URLs offer a more robust way to locate files and directories. For apps that also work with network resources, URLs also mean that you can use one type of object to manage items located on a local file system or on a network server.

There kind of path
  - Path-based URL:file://localhost/Users/steve/Documents/MyFiles.txt
  - File reference URL:file:///.file/id=referenceId
  - String-based path:/Users/steve/Documents/MyFiles.txt


![](/images/Avatar.png)

[1]:https://developer.apple.com/library/archive/documentation/FileManagement/Conceptual/FileSystemProgrammingGuide/AccessingFilesandDirectories/AccessingFilesandDirectories.html#//apple_ref/doc/uid/TP40010672-CH3-SW1
