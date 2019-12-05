# Essential-Linux-Commands

### Transfer Folder/Files from one Host to other Host

Here we use _**scp**_ command to transfer files across hosts. See [man page for scp](http://man7.org/linux/man-pages/man1/scp.1.html) for more details

#### scp command to copy a file

```bash

$ scp user1@host1IPAddr:absolutePath1/fileName user2@host2IPAddr:absolutePath2

```

#### scp command to copy all files in a folder

```bash

$ scp user1@host1IPAddr:absolutePath1/* user2@host2IPAddr:absolutePath2

```

#### scp command to copy folder

```bash

$ scp -r user1@host1IPAddr:absolutePath1 user2@host2IPAddr:absolutePath2

```

### Finding locations of a file 

Here we use _**find**_ command to find the location/path where a file exists. See [man page for find](http://man7.org/linux/man-pages/man1/find.1.html) for more details

#### find command to find a file from root folder 

```bash

$ find -name fileName /

```

#### find command to find a file from current folder 

```bash

$ find -name fileName .

```

### Finding which executable current environment referring to

Here we use ***which*** command to find the location of the executable used in current environment. ***which*** command looks for **PATH** variable to find the location of the executable used in current environment. See [man page for which](https://linux.die.net/man/1/which) for more details

```bash

$ which python

```

### Finding location of executable

Here we use ***whereis*** command to find the locations of the executable used. ***where*** command looks for ***common Linux locations***, **PATH**, **MANPATH** variable to find the locations of the executable. See [man page for whereis](http://man7.org/linux/man-pages/man1/whereis.1.html) for more details

```bash

$ whereis python

```
