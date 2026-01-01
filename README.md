# Assignment_1_DevOps

## 1. Creating and Renaming Files/Directories
### Commands Used
```bash
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt
```
### Explanation
mkdir creates a new directory.
cd changes the current directory.
touch creates an empty file.
mv renames the file.

### Screenshot
<img width="1913" height="1079" alt="01_create_and_rename" src="https://github.com/user-attachments/assets/7f1fccf6-edf2-4a0f-be41-0438ef293a9b" />

## 2. Viewing File Contents & Searching for Patterns
### Commands Used
```bash
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
cat /etc/passwd | grep root -n
```
### Explanation
cat displays the complete content of a file.
head shows the first 5 lines of the file.
tail shows the last 5 lines of the file.
grep searches for specific text inside a file.

### Screenshot
<img width="1919" height="1079" alt="02_viewing_and_searching_content" src="https://github.com/user-attachments/assets/ec1510fc-0400-4bcf-84b7-007a05b557b4" />

## 3. Zipping and Unzipping Files
### Commands Used
```bash
sudo apt update
sudo apt install zip -y
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir
```
### Explanation
zip compresses files and directories.
-r means recursive (includes all files inside the directory).
unzip extracts the compressed files.

### Screenshot
<img width="1919" height="1079" alt="03_zip_and_unzip" src="https://github.com/user-attachments/assets/6b5582e1-c68c-4369-b59c-bb7041ff0b98" />

## 4. Downloading Files
### Command Used
```bash
wget https://dummyjson.com/products?limit=10&skip=10&select=title,price
```
### Explanation
wget downloads files from the internet using a URL.

### Screenshot
<img width="1919" height="1077" alt="04_wget_file" src="https://github.com/user-attachments/assets/15adf705-396b-483e-a556-1d10156c2cab" />

## 5. Changing File Permissions
### Commands Used
```bash
touch secure.txt
chmod 444 secure.txt
ls -ls secure.txt
```
### Explanation
chmod 444 makes the file read-only for everyone.
ls -l displays file permissions.

### Screenshot
<img width="1919" height="1079" alt="05_Permissions" src="https://github.com/user-attachments/assets/9e5206e6-e008-48cf-8e86-6e5836ad444c" />

## 6. Working with Environment Variables
### Commands Used
```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```
### Explanation
export creates an environment variable.
echo prints the value of the variable.

### Screenshot
<img width="1918" height="1075" alt="06_Set_and_Get_ENV" src="https://github.com/user-attachments/assets/00a90520-8986-42c2-8d84-20c8c8b99240" />

