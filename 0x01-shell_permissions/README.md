## Hello world
#### Change current user to `betty`
```bash
$ su betty
```

#### how to know the current user
```bash
$ whoami
# betty
```

#### list the groups that the current user belongs to
```bash
$ groups
# adm dialout cdrom floppy audio video plugdev users
```

#### Change the owner of the file `hello` to `betty`
```bash
$ chown betty ./hello
```

#### Create a file `hello`
```bash
$ touch hello
```