📄 Linux Commands Assignment (Template without Screenshots)
Task 1: Creating and Renaming Files

Commands:

mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt


Explanation:
Created a directory test_dir, made an empty file, and renamed it.

Task 2: Viewing File Contents

Commands:

cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd


Explanation:

cat shows full content of /etc/passwd.

head -n 5 shows the first 5 lines.

tail -n 5 shows the last 5 lines.

Task 3: Searching for Patterns

Command:

grep "root" /etc/passwd


Explanation:
grep searches and shows all lines containing the word root.

Task 4: Zipping and Unzipping

Commands:

cd ..
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -d unzipped_dir


Explanation:

zip -r compresses the directory.

unzip -d extracts into unzipped_dir.

Task 5: Downloading Files

Command:

wget https://www.learningcontainer.com/wp-content/uploads/2020/04/sample-text-file.txt


Explanation:
Downloaded a sample text file using wget.

Task 6: Changing Permissions

Commands:

touch secure.txt
chmod 444 secure.txt
ls -l secure.txt


Explanation:
Created secure.txt and changed its permissions to read-only for all users.

Task 7: Working with Environment Variables

Commands:

export MY_VAR="Hello, Linux!"
echo $MY_VAR


Explanation:
Created a new environment variable MY_VAR and displayed its value.# linux-commands
