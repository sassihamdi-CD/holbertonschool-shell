# Shell Permissions Novice

This repository contains a collection of shell scripts that cover various concepts related to permissions in Linux. These scripts serve as a practical guide to understanding and manipulating file permissions, ownership, and executing commands with root privileges.

## Learning Objectives

By the end of this project, you will be able to:

- Explain the purpose and usage of commands such as `chmod`, `sudo`, `su`, `chown`, `chgrp`, `id`, `groups`, `whoami`, `adduser`, and `useradd`.
- Understand Linux file permissions and how to represent them as a single digit for owner, group, and other users.
- Change permissions, ownership, and group of a file.
- Comprehend why a normal user cannot change ownership of a file.
- Run commands with root privileges.
- Change user ID or become a superuser.

## Getting Started

To get started with this project, follow the steps below:

1. Clone this repository: [holbertonschool-shell](https://github.com/sassihamdi-CD/holbertonschool-shell).
2. Navigate to the `permissions` directory.

## Scripts Overview

The following scripts are included in this repository:

- `0-iam_betty`: Switches the current user to the user `betty`.
- `1-who_am_i`: Prints the effective username of the current user.
- `2-groups`: Prints all the groups the current user is part of.
- `3-new_owner`: Changes the owner of the file `hello` to the user `betty`.
- `4-empty`: Creates an empty file called `hello`.
- `5-execute`: Adds execute permission to the owner of the file `hello`.
- `6-multiple_permissions`: Adds execute permission to the owner and group owner, and read permission to other users, to the file `hello`.
- `7-everybody`: Adds execution permission to the owner, the group owner, and other users, to the file `hello`.

