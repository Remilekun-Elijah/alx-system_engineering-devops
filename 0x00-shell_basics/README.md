# Shell Basics

#### How to see your absolute path of your current directory.
```bash
 $ pwd
 /home/remilekun/Documents/github/alx/alx-system_engineering-devops
```

#### how to make a shell file executable.
```bash
 $ chmod u+x ./shell_file
```

#### how to list all files in a directory.
```bash
 $ ls
 ```

 #### how to navigate to current users home directory.
```bash
 $ cd ~
 $ pwd
 /home/remilekun
```

#### Display current directory contents in a long format
 ```bash
 $ ls -l
 ```

 #### Display current directory contents in a long format, including hidden files
```bash
ls -l -a
```

 #### Display current directory contents. 
 - Long format
 - with user and group IDs displayed numerically and hidden files (starting with .)
```bash
ls -l -a -n
```

#### Create a script that creates a directory named my_first_directory in the /tmp/ directory.

> The task is to create a script that creates a directory named my_first_directory in the /tmp/ directory.
```bash
mkdir /tmp/my_first_directory
```

#### Move the file betty from /tmp/ to /tmp/my_first_directory.
```bash
mv /tmp/betty /tmp/my_first_directory/betty
```