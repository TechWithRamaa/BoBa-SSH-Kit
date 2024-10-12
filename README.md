# BoBo-SSH-Kit
- **BoBo-SSH-Kit** is a comprehensive solution that offers both SSH client and server implementations, designed to help users securely connect to and manage remote systems.
- With an emphasis on security and ease of use, BoBo-SSH-Kit allows users to establish encrypted connections, remotely manage server instances, and transfer files securely over the SSH protocol.

# Core Utilities 
- **BoBoSSH** is a lightweight and reliable client for initiating secure connections to remote servers, enabling users to execute commands and transfer files
- **BoBoServer** is a low-latent ssh-server implemented using epoll for efficient I/O event handling and threadpool for execution of tasks by worker threads
- **BoBo-SSH-Server** is a ssh-server based on traditional fork model for handling clients in a separate child process for isolation & robust shell experience

# Repository links 
- You can checkout [BoBoSSH](https://github.com/TechWithRamaa/BobaSSH)
- You can checkout [BoBoServer](https://github.com/TechWithRamaa/Boba-Server)
- You can checkout [BoBo-SSH-Server](https://github.com/TechWithRamaa/Boba-SSH-Server)
  
### Key Features
- **Remote Access**: Execute commands and manage your remote server instances securely over SSH
- **File Transfers**: Transfer files between the local machine and remote server using SCP or SFTP
- **Tunneling & Port Forwarding**: Securely tunnel traffic between systems through encrypted connections
- **Authentication**: Supports password-based or public/private key pair authentication for secure user access

### Tech Stack
- **C++**: Core logic for handling socket programming, client-server interactions, and command execution
- **POSIX APIs**: Used for handling process creation (fork()), networking (sockets), and signals
- **Linux**: The server runs on Linux-based systems leveraging its networking and process management features

### Contributions
* Contributions are welcome! If you have an idea for a new feature implementation or improvements to existing projects, feel free to fork the repository and submit a pull request

### License
* This project is licensed under the MIT License - see the LICENSE file for details

### Acknowledgments
* Started this mini project while learning Socket Progamming as part of a course
* Check out the course here: [Advanced C++ with Networking Course](https://register.educosys.com/new-courses)
* Special shout-out to **Educosys**[🔗](https://www.educosys.com/) for meticulously curating this course and skillfully teaching concepts from the ground up

