# alu-shell Project

This repository contains a collection of shell scripts designed to help learn and practice various Linux commands, file permissions, user management, and scripting concepts.

## Scripts Description

| Script Name             | Description                                                                                   |
|------------------------|-----------------------------------------------------------------------------------------------|
| `0-iam_betty`          | Switches the current user to user `betty`.                                                   |
| `1-who_am_i`           | Prints the effective username of the current user.                                           |
| `2-groups`             | Prints all groups the current user belongs to.                                               |
| `3-new_owner`          | Changes the owner of the file `hello` to user `betty`.                                      |
| `4-empty`              | Creates an empty file named `hello`.                                                        |
| `5-execute`            | Adds execute permission to the owner of the file `hello`.                                   |
| `6-multiple_permissions`| Sets specific permissions (execute for owner and group, read for others) on the file `hello`. |
| `7-everybody`          | Adds execute permission to owner, group, and others on the file `hello`.                     |
| `8-James_Bond`         | Switches the current user to `jamesbond` using `su` command.                                |
| `9-John_Doe`           | Switches the current user to `johndoe`.                                                     |
| `10-mirror_permissions`| Sets the permissions of `hello` to match those of the file `olleh`.                         |
| `11-directories_permissions` | Adds execute permissions to all subdirectories of the current directory for all users.   |
| `12-directory_permissions` | Creates nested directories `welcome/`, `welcome/to/`, and `welcome/to/school/`.            |
| `13-change_group`       | Changes the group owner of the file `hello` to `school`.                                   |
| `14-change_owner_and_group` | Changes owner to `vincent` and group to `staff` for all files and directories in the current directory. |
| `15-symbolic_link_permissions` | Changes owner and group of the symbolic link `_hello` to `vincent` and `staff`.          |
| `16-if_only`            | Changes the owner of the file `hello` to `vincent` only if it is currently owned by `guillaume`. |

## Usage

Make sure to give execution permissions to the scripts before running them:

```bash
chmod +x <script_name>
./<script_name>
