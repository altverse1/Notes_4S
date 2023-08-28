## Q. List and explain any 3 services provided by OS to user and 3 services provided by OS to the system

**Services Provided to Users:**

1. **User Interface (UI):** The operating system provides various types of user interfaces such as Command Line Interface (CLI), Graphical User Interface (GUI), and even touch screen interfaces. CLI allows users to interact with the system by entering commands, while GUI provides a user-friendly desktop environment with icons and actions controlled via mouse, keyboard, and monitor. Touch screen interfaces enable users to interact using gestures, virtual keyboards, and voice commands.
    
2. **Program Execution:** The OS is responsible for loading programs into memory, executing them, and terminating them. It ensures that programs run efficiently by managing memory allocation and processor time. In case of abnormal execution, the OS can report errors to users, helping them understand and resolve issues.
    
3. **I/O Operations:** The operating system manages Input/Output (I/O) operations, which involve interactions with files and devices. It provides services to read from and write to files, manage file attributes, and control devices like printers, scanners, and network interfaces. This service ensures efficient data exchange between programs and the external world.

4. **File System Manipulation**:
    - **File Reading/Writing:** The OS provides APIs for programs to read from and write to files, allowing data storage and retrieval.
    - **Directory Operations:** It supports creating, deleting, and managing directories to organize and structure files.
    - **File Search:** Allows programs and users to search for specific files based on criteria like name, date, or content.
    - **File Information:** The OS offers functions to retrieve metadata about files, such as size, permissions, and creation date.

5. **Communications:**
    - **Inter-Process Communication (IPC):** The OS enables processes to exchange information and synchronize their actions through shared memory or message passing.
    - **Networking:** Facilitates communication between devices over networks, including internet connectivity, data sharing, and remote access.

6. **Error Detection and Handling:**
    - **Error Detection:** The OS continuously monitors system operations for errors, such as hardware failures or software bugs.
    - **Error Correction:** When errors are detected, the OS takes corrective measures to ensure stable operation and prevent data corruption or system crashes.
    - **Debugging Facilities:** Provides tools for developers to diagnose and debug issues in their programs, enhancing the overall software development experience.
    

**Services Provided to the System(for efficiency and integrity):**

1. **Resource Allocation:** The OS allocates system resources like CPU time, memory space, and I/O devices to multiple tasks running concurrently. It ensures fair and efficient sharing of resources among different processes, preventing resource conflicts and ensuring optimal system performance.
    
2. **Logging and Monitoring:** The OS maintains logs that track resource usage by different users and processes. This information helps administrators monitor system activity, detect unusual patterns, and identify potential performance bottlenecks or security breaches. Logging is crucial for system analysis and troubleshooting.
    
3. **Protection and Security:** The OS enforces protection mechanisms to control access to system resources. Protection ensures that unauthorized users or processes cannot interfere with the execution of legitimate programs or access sensitive data. Security measures, such as user authentication and permission-based access control, defend the system from unauthorized access and attacks from external sources.
    

These services collectively contribute to creating a controlled and efficient environment for both users and the system to interact within an operating system


## Q. Explain various types of system calls provided by the operating system

**Process Control System Calls:**

1. **Create Process:** This system call is used to create a new process. The operating system allocates necessary resources for the process, sets up its execution environment, and initializes its data structures.
    
2. **Terminate Process:** This system call is used to end the execution of a process. The operating system releases the allocated resources, deallocates memory, and removes the process from the system.
    
3. **Load Program:** This system call loads a program into memory for execution. It involves reading the program from storage into memory and preparing it for execution.
    
4. **Execute Program:** This system call is used to start the execution of a program that is already in memory. The operating system transfers control to the program's entry point.
    
5. **Wait for Time or Event:** This system call makes a process wait for a specified amount of time or for a particular event to occur. It is often used for synchronization between processes.
    

**File Management System Calls:**

1. **Create File:** This system call is used to create a new file. The operating system allocates space for the file and sets up data structures to manage it.
    
2. **Delete File:** This system call deletes an existing file from the file system. It releases the space occupied by the file and removes its entry from the directory.
    
3. **Open File:** This system call is used to open an existing file for reading, writing, or both. The operating system returns a file descriptor that the process uses to access the file.
    
4. **Read File:** This system call reads data from an open file into a buffer in memory. It provides the process with access to the contents of the file.
    
5. **Write File:** This system call writes data from a buffer in memory to an open file. It allows the process to modify the contents of the file.
    

**Device Management System Calls:**

1. **Request Device:** This system call is used to request access to a particular I/O device, such as a printer or network interface.
    
2. **Release Device:** This system call releases the access to an I/O device that was previously acquired.
    
3. **Read Device:** This system call reads data from an I/O device into a buffer in memory. It enables the process to receive data from input devices.
    
4. **Write Device:** This system call writes data from a buffer in memory to an I/O device. It allows the process to send data to output devices.
    
5. **Get Device Attributes:** This system call retrieves information about a specific I/O device, such as its status or configuration.
    

**Protection System Calls:**

1. **Get Permissions:** This system call retrieves the permissions associated with a file or resource. It allows a process to determine what operations are allowed on the resource.
    
2. **Set Permissions:** This system call is used to change the permissions associated with a file or resource. It enables authorized processes to modify access rights.
    
3. **Allow Access:** This system call grants a process permission to access a protected resource. It is used to establish controlled access to sensitive data.
    
4. **Deny Access:** This system call revokes a process's permission to access a resource. It helps prevent unauthorized access and maintain security.
    

These system calls provide a bridge between user programs and the underlying operating system, allowing users to interact with the OS's services and resources in a controlled and efficient manner.