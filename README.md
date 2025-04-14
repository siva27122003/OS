####  **OS – Listing Files and Directories**

| **Command** | **Purpose** |
|-------------|-------------|
| ls | List files and directories in the current location |
| cd | Change the directory |
| pwd | Show current directory (print working directory) |
| mkdir | Create a new directory |
| rmdir | Remove an empty directory |
| rm | Remove files or directories |
| cp | Copy files or directories |
| mv | Move or rename files or directories |
| touch | Create a new empty file |
| cat | View content of a file |
| find | Search files and directories |
| tree | Show directory structure in tree format |

---

####  **Usage Examples**

**1. Listing all files and directories**
```bash
ls
ls -l           # Detailed listing
ls -a           # Includes hidden files
```

**2. cd – Change directory**
```bash
cd folder_name/ 
cd ..           # Go one level up
cd /home/user   # Go to a specific path
```

**3. mkdir – Create a new directory**
```bash
mkdir new_folder
mkdir -p dir1/dir2  # Create nested directories
```

**4. rmdir – Remove an empty directory**
```bash
rmdir empty_folder
```

**5. rm – Remove files or directories**
```bash
rm file.txt
rm -i file.txt         # Ask before deleting
rm -r folder_name/     # Delete a folder recursively
```

**6. cp – Copy files or directories**
```bash
cp file.txt /destination/
cp -r folder/ /destination/  # Copy folders recursively
```

**7. mv – Move or rename files/directories**
```bash
mv file.txt /destination/       # Move file
mv oldname.txt newname.txt      # Rename file
```

**8. touch – Create a new empty file**
```bash
touch file.txt
```

**9. cat – View content of a file**
```bash
cat file.txt
```

**10. find – Search for files/directories**
```bash
find . -name "file.txt"
find /home -type d -name "folder_name"
```

---

###  **Some Docker Commands**

| **Command** | **Purpose** |
|-------------|-------------|
| docker images | List all available Docker images |
| docker run -it <image_name> | Run a container in interactive mode |
| docker ps | List all running containers |
| docker ps -a | List all containers (including stopped ones) |
| docker exec -it <container_id> bash | Access the running container’s shell |
| docker stop <container_id> | Stop a running container |
| docker start <container_id> | Start a previously stopped container |
| docker rm <container_id> | Remove a container |
| docker rmi <image_id> | Remove an image from the system |
| docker commit <container_id> <image_name> | Save a container's state as a new image |
| docker logs <container_id> | View the logs/output of a container |
| docker pull <image_name> | Download an image from Docker Hub |

---
