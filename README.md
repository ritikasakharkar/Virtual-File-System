# Virtual-File-System

- Almost all users use the operating system for file system management. It provides the interface for storage of and access to data and programs of the operating system for all the users of the computer system. 

- The file system consists of two parts: a collection of files for storing related data and a directory structure for organizing and providing information about all the files in the system.

- VFS allows client to access different types of concrete file systems in a uniform way. We are making files in which we will be using VIRTUAL FILE SYSTEM. The functionalities of our virtual file management system includes listing file, creating new file, searching for a file, deleting file and search for a keyword in a file.

-- SIMPLE  ARCHITECTURE --

- File systems provide easy access to the storage by storing, locating, and retrieving data easily. A file system has two different design problems. 

- The first problem is how the file system will look for the user. This errand includes defining a file its characteristics, the operations permitted on a file, and the directory structure for sorting out directory. 

- The second issue is making algorithms and data structures to outline logical file system onto the physical secondary-storage devices.

- The file system itself is made of many different layers. Each layer uses the features of lower layer to create new features for higher layers.

- The basic file system is needed only to send generic commands to the device driver to read and write physical blocks on the disk. The file-organization module has data about the files and their logical blocks and also the physical blocks. 

- By knowing the type of file allocation used and the address of the file, the file-organization module can translate logical block addresses to physical block addresses for the basic file system to transfer.
 
- Finally, the logical file system manages metadata information. Metadata includes all of the filesystem structure except the actual data (or contents of the files). The logical file system manages the directory structure to provide the file-organization module with the information the latter needs, given a symbolic file name.

-- TO RUN THE CODE --

  -> g++ file.cpp -o l.out

  -> ./l.out
