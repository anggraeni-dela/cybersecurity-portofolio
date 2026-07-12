# Linux File Permissions

## Objective

Learn how to view and modify file permissions in Linux using `ls -l` and `chmod`.

---

## Theory

Linux uses permissions to control who can read, write, or execute a file.

Permission symbols:

- `r` = Read
- `w` = Write
- `x` = Execute

Example:

```text
-rwxr-xr-x
```

This means:

- Owner: Read, Write, Execute
- Group: Read, Execute
- Others: Read, Execute

---

## Commands

### View file permissions

```bash
ls -l
```

### Add execute permission

```bash
chmod +x script.sh
```

### Set permission using numeric mode

```bash
chmod 755 script.sh
```

---

## Practice

Commands executed:

```bash
mkdir PermissionLab
cd PermissionLab
touch script.sh
ls -l
chmod +x script.sh
ls -l
chmod 755 script.sh
ls -l
```

---

## Result

Successfully viewed and modified file permissions using `chmod`.

---

## Screenshot

![Linux File Permissions](file-permissions.png)

---

## Conclusion

Understanding Linux file permissions is important because it controls access to files and helps secure the operating system.