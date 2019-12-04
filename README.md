# Essential-Linux-Android-Commands

## Transfer Folder/Files from one Host to other Host

Here we use _**scp**_ command to transfer files across hosts. See [man page for scp](http://man7.org/linux/man-pages/man1/scp.1.html) for more details

### scp command to copy a file

```bash

$ scp user1@host1IPAddr:absolutePath1/fileName user2@host2IPAddr:absolutePath2

```

### scp command to copy all files in a folder

```bash

$ scp user1@host1IPAddr:absolutePath1/* user2@host2IPAddr:absolutePath2

```

### scp command to copy folder

```bash

$ scp -r user1@host1IPAddr:absolutePath1 user2@host2IPAddr:absolutePath2

```
