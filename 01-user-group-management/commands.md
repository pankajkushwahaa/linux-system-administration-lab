# User and Group Management Commands



## Display current user

```bash
whoami
```

Purpose:
Displays the current logged-in user.

---

## Display user ID

```bash
id
```

Purpose:
Displays UID, GID and group information.

---

## Create a new user

```bash
sudo adduser user1
```

Purpose:
Creates a new Linux user.

---

## Set password

```bash
sudo passwd user1
```

Purpose:
Sets or changes the user's password.

---

## Create a group

```bash
sudo groupadd developers
```

Purpose:
Creates a new Linux group.

---

## Add user to group

```bash
sudo usermod -aG developers user1
```

Purpose:
Adds a user to a secondary group.

---

## Show user's groups

```bash
groups user1
```

Purpose:
Displays all groups assigned to the user.

---

## Delete user

```bash
sudo userdel user1
```

Purpose:
Deletes a Linux user.

---

## Delete group

```bash
sudo groupdel developers
```

Purpose:
Deletes a Linux group.