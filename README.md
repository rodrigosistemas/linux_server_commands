```markdown
# Linux Commands

## File and Directory Management

### List Available Commands
```bash
ls /usr/bin
```

<img src="https://drive.google.com/uc?export=view&id=1UYNlKR7vR-AZNHo5c-TRAMd7alg412Gp" alt="Tux Penguin" width="250"/>

### Count Number of Commands
```bash
ls /usr/bin | wc -l
```

### echo
Print to screen
```bash
echo
```

### pwd
Print the current directory
```bash
pwd
```

### ls
List files or existing directories
```bash
ls
```
- List all files, including hidden ones
  ```bash
  ls -a
  ```
- List in long format
  ```bash
  ls -l
  ```

### cd
Change directory
```bash
cd
```

### cp
Copy a directory
```bash
cp
```

### mv
Move or rename a directory or folder
```bash
mv
```

### mkdir
Create a directory
```bash
mkdir
```

### rmdir
Remove a directory
```bash
rmdir
```

### rm
Remove a file
```bash
rm
```

### touch
Create a file
```bash
touch
```

### less
Provide more information about the file
```bash
less
```

### cat
Concatenate (create, merge, and print files to the screen)
```bash
cat
```

### tail
Show the last 10 lines of a file
```bash
tail
```

### head
Show the first 10 lines of a file
```bash
head
```

### which
Ask for the path of a directory's binary
```bash
which
```

### alias
View the entire list of aliases
```bash
alias
```

## System Information

### hostname
System host name
```bash
hostname
```

### whoami
Current user of the system
```bash
whoami
```

### grep
Search for the given word inside a file
```bash
grep
```

### du
Check the space of a file inside a directory
```bash
du
```
- In Bytes, Kilobytes, Megabytes
  ```bash
  du -h
  ```
  
### Default Login Shell
```bash
grep username /etc/passwd
```

## Package Management

### List installed packages with apt
```bash
apt list --installed
```

### Search for programs in repositories
```bash
sudo apt-cache search <package>
```

### List installed programs using dpkg
```bash
dpkg-query -l
```
```bash
dpkg -l
```

### Show information about a package
```bash
sudo apt-cache show <package>
```

### apt-get remove
Remove installed programs
```bash
apt-get remove <package>
```

### sudo apt-get purge
Remove all data of the programs
```bash
sudo apt-get purge <package>
```

### sudo apt-get autoremove
Clean up some program logs
```bash
sudo apt-get autoremove
```

### dpkg
Tool for installing, copying, deleting, and manipulating packages
```bash
dpkg
```

### wget
Useful for obtaining content from the web, compatible with HTTPS, HTTP, and FTP protocols
```bash
wget <url>
```

## Environment Variables

### Verify the PATH directory to execute a file
```bash
echo $PATH
```

### Show the shell language
```bash
echo $LANG
```

### Print environment variables used in the session
```bash
env
```

## System Updates and Administrator Permissions

### sudo apt-get update
Check for updates
```bash
sudo apt-get update
```

### sudo apt-get upgrade
Update all programs to their latest versions and install system updates easily
```bash
sudo apt-get upgrade
```

### sudo su
Activate administrator mode
```bash
sudo su
```

### Change user password
```bash
passwd
```

### Changing permissions (numbers)
```bash
chmod 777 file
```
```bash
chmod 755 file
```
```bash
chmod 644 file
```
```bash
chmod 000 file
```

### Changing permissions (letters)
```bash
chmod u+x file
```
```bash
chmod g-w file
```
```bash
chmod o+r file
```

### exit
Exit administrator mode
```bash
exit
```

### Create a backup
```bash
sudo apt install timeshift
```
```bash
sudo timeshift --create --comments ""
```
```bash
sudo timeshift --restore
```
```bash
timeshift --list
```
```bash
sudo timeshift --restore --snapshot ID
```
```bash
sudo timeshift --delete --snapshot ID
```

### Reboot
```bash
reboot
```
```bash
init 6
```

## File Compression and Decompression

### Compress files
```bash
tar -cvf archive.tar.gz /directory
```
- **-c**: Create a new archive
- **-v**: Show what is being archived
- **-f**: Specify the filename of the tar archive

### Decompress files
```bash
tar -xvf archive.tar.gz /directory
```
- **-x**: Extract the tar archive
- **-v**: Show what is being extracted
- **-f**: Specify the filename of the tar archive

### List the content of a tar archive
```bash
tar -tf archive.tar.gz
```

## Miscellaneous Commands

### apt moo
Show a hidden message
```bash
apt moo
```

### neofetch
Display system information
```bash
neofetch
```

### cmatrix
Show a matrix animation in the terminal
```bash
cmatrix
```

### sensors
Show the temperature of the processor and GPU
```bash
sensors
```

### htop
Show system processes in an interactive interface
```bash
htop
```

### figlet
Create ASCII art text
```bash
figlet
```
