# Hacktober Fest - Basic Command Line Interface for a File System

You may program a simple command line interface for a File System.
The program should read in pre defined commands and perform the appropriate operations. 

**Points will be given for completing every feature. Bonus Points will be granted for optimizations as well as efficiency.**

We have deliberately retained some details so that there is room for improvisation and interpretation. A contributor has the option to implement any subset of the features mentioned below.


Use of suitable Data Structure and Algorithm should be ensured to maintain file structure. Appropriate logic and libraries should also be used for Multi Processing.

**Seperate branches are available for different choices of programming languages for implementation. You may create a new branch for your choice of language if it isn't already present**

### Implement these features of an OS :

1. **File System**
    1. File Structure and Storage (+10 points)
        1. The file system should support folders (collection of files) and files
            
            ```objectivec
            create folder Folder1
            created folder Folder1...
            
            create file newFile.txt
            created file newFile.txt...
            ```
            
        2. these files should be stored permanently on the device
    2. Features executable as Commands
        1. Navigation between directories (+10 points)
            
            ```objectivec
            cd Folder1
            changed directory to root\Folder1...
            ```
            
        2. List all files and folders in current directory (+10 points)
            
            ```objectivec
            ls Folder1
            no files inside Folder1...
            
            ls root
            - newFile.txt
            ```
            
        3. File creation (+10 points)
            
            ```objectivec
            cd Folder1
            create file demoFile.txt
            ```
            
        4. Read File (+10 points)
            
            ```objectivec
            read file demoFile.txt
            // display files contents
            ```
            
        5. File editing (+10 points)
            
            ```objectivec
            edit file demoFile.txt
            opening demoFile.txt for editing...
            // display files content and allow editing in the terminal itself
            
            // have a command for quiting edit mode - Ctrl+C for example - when editing is complete
            would you like to save changes (y/n)? y
            changes saved...
            ```
            
        6. File deletion (+10 points)
            
            ```objectivec
            delete file demoFile.txt
            are you sure (y/n)? y
            delted file demoFile.txt...
            
            ```
            
        
    3. Extra features
        1. Searching for a file or folder on the entire system (+10 points)
            
            ```objectivec
            find file demoFile.txt
            file does not exist...
            
            find folder Folder1
            path: root\Folder1
            ```
            
        2. Caching ( most recently accessed files / most frequently accessed files) (+10 points)
            
            ```objectivec
            cache
             - root\Folder1\demoFile.txt
             - root\newFile.txt
            ```
            
        3. File editing features:
            1. String search (direct matching or fuzzy matching) (+10 points)
                
                ```objectivec
                find "sample string" in root\newFile.txt
                0 instances of "sample string" found...
                ```
                
            2. Find and replace (+10 points)
                
                ```objectivec
                // let contents of file newFile.txt be - Hello world!
                
                find-replace "world" with "everyone" in root\newFile.txt
                1 instance of "world" replaced with "everyone"...
                
                // updated contents of file newFile.txt be - Hello everyone!
                ```
                
            3. File concatenation (+10 points)
                
                ```objectivec
                create file anotherFile.txt
                created file anotherFile.txt...
                
                combine file newFile.txt file anotherFile.txt
                combined newFile.txt and anotherFile.txt...
                
                // combined contents are stored in the file mentioned first - here newFile.txt
                // command may accept more than 2 files
                ```
                
            4. Command completion (+10 points)
                
                ```objectivec
                cr
                // show create on pressing Tab
                
                f
                /* show
                 - find
                 - find-replace
                on pressing Tab */
                ```
                
    
2. **Multi Processing**
    1. Create and handle multiple processes simultaneously using a single command (+15 points)
        
        ```objectivec
        // use || - to execute commands sequentially
        // use && - to execute commands parallely
        
        create file File1.txt || create file File2.txt
        created file File1.txt...
        created file File2.txt...
        
        create file File3.txt && create file File4.txt
        created file File3.txt and created file File4.txt...
        
        // handle executing more than 1 commands at once by using multiple threads
        ```
        
    2. Handle file accessing using semaphores (+15 points)
        
        ```objectivec
        edit file File1.txt && read file File1.txt
        
        // manage data integrity when multiple processes access the same file
        ```
