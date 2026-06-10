# Lab 03 - Linux File Permissions

## Objective

Practice viewing, modifying, and understanding Linux file permissions and ownership.

## Environment

- Host Operating System: Windows
- Virtualization Platform: Oracle VirtualBox
- Guest Operating System: Red Hat Enterprise Linux

## Tasks Completed

- Viewed file permissions
- Created test files
- Modified file permissions using chmod
- Examined file ownership
- Changed file ownership using chown
- Verified permission changes

## Commands Practiced

```bash
touch
ls -l
chmod
chown
```

## Skills Demonstrated

- File Permission Management
- Ownership Management
- Linux Security Fundamentals
- Command-Line Administration

## Reflection

This lab provided hands-on experience working with Linux file permissions and ownership. Understanding how permissions are assigned and modified is a critical skill for Linux administration and system security.

## Screenshots

### Viewing Initial Permissions

The screenshot below demonstrates viewing file permissions using the `ls -l` command.

![Permissions Before](../permissions-before.png)

### Modifying Permissions with chmod

The screenshot below demonstrates changing file permissions using:

```bash
chmod 755 testfile0
```

and verifying the results with:

```bash
ls -l testfile0
```

![Permissions After](../permissions-after.png)

### Changing Ownership with chown

The screenshot below demonstrates changing file ownership using:

```bash
chown labuser0 testfile0
```

and verifying ownership changes with:

```bash
ls -l testfile0
```

![Ownership Change](../ownership-change.png) 
