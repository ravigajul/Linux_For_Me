# Linux_For_Me
Echo $SHELL  result /bin/bash

# 1. Print to screen
Echo Hi

# 2. List files & Directories
Ls
# 3. Change Directory
CD Test

# 4. Present Working Directory
PWD
# Directory
## 1. create a new directory
Mkdir test

## 2. Run multiple Commands
Cd new_directory; mkdir www; pwd

## 3. Create a directory tree
Mkdir -p /tmp/asia/india/hyderabad

## 4. Remove a directory and all of subdirectories too
Rm -r tmp

## 5. Copy directory and all of its content
Cp -r   my_dir1 /tmp/my_dir1

# 6. Commands - Files
## 1. Create a new file(no contents)
touch test.txt
## 2. Add contents to file
cat > test.txt
This is a sample text in test.txt tile
CTRL+D to exit out of edit mode
## 3. View contents of file
cat test.txt
## 4. Copy file
cp path/sourfile.txt path/targetfile.txt
## 5. Move(Rename) File
mv path/oldname.txt path/newname.txt
If the file is moved in the same directory its like renaming.
