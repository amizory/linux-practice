# Linux

* [Base command](#command)
* [Administration](#administration)
* [Boot Linux](#boot)
* [](#)
* [](#)
* [](#)
* [](#)
* [](#)
* [](#)
* [](#)
* [](#)

## Start

### <a id="command">Base command</a>

```sh
cd          -> transfer
ls          -> watch direction
mkdir       -> make direction 
rm          -> remove
cp          -> copy
mv          -> move with delete
cat         -> output content file
echo        -> output text
man/info    -> information about command
pwd         -> path
history     -> history command
```

### <a id="administration">Administration</a>

```sh
1 - su root / su -
2 - apt-get install sudo -y 
3 - usermod -aG sudo <NAME>
4 - visudo or /etc/sudoers
```

### <a id="boot">Boot Linux</a>

```sh
1 - BIOS
2 - Bootloader
3 - Kernel
4 - Init
5 - Systemd
6 - System services
7 - Login
```

### <a id="uid-gid">User-Group</a>

```sh
useradd/groupadd -> new user/group 
usermod/groupmod -> features user/group
userdel/groupdel -> remove user/group

Example: 

/etc/passwd ---> amizory:x:1000:1000:,,,:/home/amizory:/bin/bash

                    NAME-PASS-UID-GID-FULL_NAME-HOMEDIR-SHELL

/etc/group
/etc/shadow ---> password

useradd [flags] ->
                    -m -> homedir
                    -G -> group
                    -s -> shell
                    -p -> pass
                    -d -> PATH
                    -g -> group
usermod [flags] ->
                    -d -> change dir PATH PATH
                    -l -> rename NEWNAME OLDNAME

```