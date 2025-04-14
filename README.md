# OS

##  Listing Files and Directories
 
command                                     Purpose                                                 
1. ls                        List files and directories in the current location                         
2. cd                        Change the directory                                                    
3. pwd                       Show current directory(print working directory)
4. mkdir                     Create a new directory
5. rmdir                     remove the empty directory
6. rm                        remove the files or directory
7. cp                        copy the files or directory
8. mv                        move or rename files or directory
9. touch                     To Create a new empty file
10. cat                      cat	View content of a file
11. find                     find	Search files and directories
12. tree                     Show directory structure in tree format

### Usage examples

**1.listing all files and directories**
ls
ls -l           # Detailed listing
ls -a           # Includes hidden files

**2.cd – Change directory**
cd folder_name/ 
cd ..           # Go one level up
cd /home/user   # Go to a specific path

**3.mkdir – Create a new directory**
mkdir new_folder
mkdir -p dir1/dir2  # Create nested directories

**4.rmdir – Remove an empty directory**
rmdir empty_folder

**5.rm – Remove files or directories**
rm file.txt
rm -i file.txt       # Ask before deleting
rm -r folder_name/   # Delete a folder recursively
**6.cp – Copy files or directories**
cp file.txt /destination/
cp -r folder/ /destination/  # Copy folders recursively

**7.mv – Move or rename files/directories**
mv file.txt /destination/      # Move file
mv oldname.txt newname.txt     # Rename file

**8.touch – Create a new empty file**
touch file.txt

**9.cat – View content of a file**
cat file.txt

**10.find – Search for files/directories**
find . -name "file.txt"
find /home -type d -name "folder_name"

### SOME DOCKER COMMANDS 
COMMANDS                                            PURPOSE
1.docker images	                           List all available Docker images on your system
2.docker run -it <image_name>            	 Run a container in interactive mode from the specified image
3.docker ps	                               List all running containers
4.docker ps -a	                           List all containers (including stopped ones)
5.docker exec -it <container_id>           bash	Access the running container’s shell
6.docker stop <container_id>	             Stop a running container
7.docker start <container_id>	             Start a previously stopped container
8.docker rm <container_id>	               Remove a container
9.docker rmi <image_id>	                   Remove an image from the system
10.docker commit <container_id> <image_name>	Save a container's current state as a new image
11.docker logs <container_id>	View the logs/output of a container
12.docker pull <image_name>	               Download an image from Docker Hub


