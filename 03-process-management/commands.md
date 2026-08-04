## View Running Processes

### Objective

Display currently running processes.

### Command

```bash
ps
```

### Explanation

Shows processes running in the current shell.

### Verification

Observe the process ID (PID), terminal, execution time, and command.


## View All Processes

### Command

```bash
ps -ef
```

### Explanation

Lists all running processes in full format.

### Verification

Check PID, PPID, user, start time, and command.


## Monitor Processes

### Command

```bash
top
```

### Explanation

Displays real-time CPU, memory, and process usage.

### Exit

Press `q`.


## Interactive Process Viewer

### Command

```bash
htop
```

### Explanation

Interactive version of `top`.

### Installation

Ubuntu

```bash
sudo apt install htop
```

CentOS

```bash
sudo dnf install htop
```


## Kill Process

### Command

```bash
kill PID
```

### Explanation

Terminates the specified process.

### Verification

Run:

```bash
ps -ef
```


## Force Kill

### Command

```bash
kill -9 PID
```

### Explanation

Immediately terminates a process that does not respond to normal termination.


## Kill by Process Name

### Command

```bash
pkill firefox
```

### Explanation

Terminates processes matching the given name.


## Run in Background

### Command

```bash
sleep 300 &
```

### Explanation

Starts a background process.


## Display Jobs

### Command

```bash
jobs
```

### Explanation

Displays jobs started from the current shell.


## Foreground Job

### Command

```bash
fg %1
```

### Explanation

Brings Job 1 back to the foreground.


## Suspend Running Process

Press:

```text
Ctrl + Z
```

Moves the running process into the background (stopped state).


## Resume Job

### Command

```bash
bg %1
```

### Explanation

Resumes the stopped job in the background.


## Process Tree

### Command

```bash
pstree
```

### Explanation

Displays parent-child relationships of running processes.


