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
            
            ![ex1](https://user-images.githubusercontent.com/54301942/135761038-ed7300e0-bedc-4b8b-8041-9697eb2532e4.png)
            
        2. these files should be stored permanently on the device
    2. Features executable as Commands
        1. Navigation between directories (+10 points)
            
            ![ex2](https://user-images.githubusercontent.com/54301942/135761089-4dfeec7b-0508-4b45-bf82-3e0f57d843c9.png)
            
        2. List all files and folders in current directory (+10 points)
            
            ![ex3](https://user-images.githubusercontent.com/54301942/135761101-8f682f3b-faf8-4037-831a-4d1b656fdfe6.png)
            
        3. File creation (+10 points)
            
            ![ex4](https://user-images.githubusercontent.com/54301942/135761133-575fefe7-49ab-467b-93c2-ee6d07170f08.png)
            
        4. Read File (+10 points)
            
            ![ex5](https://user-images.githubusercontent.com/54301942/135761155-3f9265b1-7e01-4282-8fdb-7db153d962fc.png)
            
        5. File editing (+10 points)
            
            ![ex6](https://user-images.githubusercontent.com/54301942/135761157-60800310-8715-458e-833d-3efdb4ffd82e.png)
            
        6. File deletion (+10 points)
            
            ![ex7](https://user-images.githubusercontent.com/54301942/135761162-b1018255-aba1-4f87-a312-b89404f62f90.png)
            
        
    3. Extra features
        1. Searching for a file or folder on the entire system (+10 points)
            
            ![ex8](https://user-images.githubusercontent.com/54301942/135761183-a66d2a66-1f85-4226-bc70-c7bb9aa6bcd6.png)
            
        2. Caching ( most recently accessed files / most frequently accessed files) (+10 points)
            
            ![ex9](https://user-images.githubusercontent.com/54301942/135761202-2c42e60f-b704-4e02-b545-4d41542048d7.png)
            
        3. File editing features:
            1. String search (direct matching or fuzzy matching) (+10 points)
                
                ![ex10](https://user-images.githubusercontent.com/54301942/135761378-d54a39d3-2534-4e3c-b9e5-4babcfa00ccf.png)
                
            2. Find and replace (+10 points)
                
                ![ex11](https://user-images.githubusercontent.com/54301942/135761382-b5092dfb-1080-4e9a-a3f8-c67712b631fe.png)
                
            3. File concatenation (+10 points)
                
                ![ex12](https://user-images.githubusercontent.com/54301942/135761392-2a2f94d1-9097-4892-932d-93eccc4fe20e.png)
                
            4. Command completion (+10 points)
                
                ![ex13](https://user-images.githubusercontent.com/54301942/135761401-89d0f2de-c467-4eb3-a7f1-fcfd4f43b897.png)
                
    
2. **Multi Processing**
    1. Create and handle multiple processes simultaneously using a single command (+15 points)
        
        ![ex14](https://user-images.githubusercontent.com/54301942/135761404-6cc81458-6c96-449d-bab7-a2c969f55601.png)
        
    2. Handle file accessing using semaphores (+15 points)
        
        ![ex15](https://user-images.githubusercontent.com/54301942/135761412-847c95a5-107f-4a53-9fb3-92e848477908.png)
