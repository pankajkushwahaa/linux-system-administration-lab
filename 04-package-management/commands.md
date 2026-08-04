## Update Package Repository

### Ubuntu

```bash
sudo apt update
```

### CentOS

```bash
sudo dnf check-update
```

### Explanation

Downloads the latest package information from configured repositories.

### Verification

No package installation is performed.


## Upgrade Installed Packages

### Ubuntu

```bash
sudo apt upgrade
```

### CentOS

```bash
sudo dnf upgrade
```

### Explanation

Updates installed software packages to newer versions.


## Install Package

### Ubuntu

```bash
sudo apt install tree
```

### CentOS

```bash
sudo dnf install tree
```

### Explanation

Installs the Tree package.

### Verification

```bash
tree --version
```


## Remove Package

### Ubuntu

```bash
sudo apt remove tree
```

### CentOS

```bash
sudo dnf remove tree
```


## Search Package

### Ubuntu

```bash
apt search nginx
```

### CentOS

```bash
dnf search nginx
```


## Display Package Information

### Ubuntu

```bash
apt show nginx
```

### CentOS

```bash
dnf info nginx
```


## List Installed Packages

### Ubuntu

```bash
apt list --installed
```

### CentOS

```bash
dnf list installed
```


## Remove Unused Packages

### Ubuntu

```bash
sudo apt autoremove
```

### Explanation

Removes packages that were installed as dependencies but are no longer required.


## Clean Package Cache

### Ubuntu

```bash
sudo apt clean
```

### CentOS

```bash
sudo dnf clean all
```


