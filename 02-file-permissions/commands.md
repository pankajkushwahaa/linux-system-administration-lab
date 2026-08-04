## View File Permissions

### Objective

Display the permissions and ownership of files and directories.

### Command

```bash
ls -l
```

### Explanation

Lists files in long format, showing permissions, owner, group, size, and modification date.

### Verification

Check the permission string, for example:

```text
-rw-r--r--
```


## Change File Permissions (Numeric)

### Command

```bash
chmod 755 test.sh
```

### Explanation

Sets:

- Owner → Read, Write, Execute
- Group → Read, Execute
- Others → Read, Execute

### Verification

```bash
ls -l test.sh
```


## Change File Permissions (Symbolic)

### Command

```bash
chmod u+x test.sh
```

### Explanation

Adds execute permission for the file owner.

### Verification

```bash
ls -l test.sh
```


## Change File Owner

### Command

```bash
sudo chown user1 file.txt
```

### Explanation

Changes the ownership of the file to user1.

### Verification

```bash
ls -l file.txt
```


## Change Group Ownership

### Command

```bash
sudo chgrp developers file.txt
```

### Explanation

Changes the group owner of the file.

### Verification

```bash
ls -l file.txt
```


## Change Owner and Group

### Command

```bash
sudo chown user1:developers file.txt
```

### Explanation

Changes both the file owner and group in a single command.

### Verification

```bash
ls -l file.txt
```


## Display Default Permissions

### Command

```bash
umask
```

### Explanation

Displays the default permission mask applied to newly created files and directories.