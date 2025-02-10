# Shell Permissions

Hey there! 👋 This is my collection of bash scripts that I created while learning about shell permissions in Linux.

## What's Inside?

Here's a breakdown of each script and what it does:

* `0-iam_betty` - Switches the current user to the user `betty`
* `1-who_am_i` - Prints the effective username of the current user
* `2-groups` - Prints all the groups the current user is part of
* `3-new_owner` - Changes the owner of the file `hello` to the user `betty`
* `4-empty` - Creates an empty file called `hello`
* `5-execute` - Adds execute permission to the owner of the file `hello`
* `6-multiple_permissions` - Adds execute permission to owner and group owner, and read permission to others for `hello`
* `7-everybody` - Adds execution permission to owner, group owner and others for `hello`
* `8-James_Bond` - Sets permissions for `hello` to no permission for owner/group and all permissions for others (007)
* `9-John_Doe` - Sets mode of `hello` to -rwxr-x-wx (753)
* `10-mirror_permissions` - Mirrors the permissions of file `olleh` onto `hello`
* `11-directories_permissions` - Adds execute permission to all subdirectories for all users
* `12-directory_permissions` - Creates a directory `my_dir` with permissions 751
* `13-change_group` - Changes the group owner of `hello` to `school`
* `14-change_owner_and_group` - Changes owner to `vincent` and group owner to `staff` for all files and directories
* `15-symbolic_link_permissions` - Changes the owner and group owner of symbolic link `_hello` to `vincent` and `staff`
* `16-if_only` - Changes the owner of `hello` to `vincent` only if it's owned by `guillaume`