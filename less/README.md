User's configuration settings: `~/.lesskey`
User's configuration: `~/.less`

Less uses 2 files for maintaining the binding configurations; a human readable .lesskey file and a binary .less key which is the one actually used by less.
In order to apply the changes, copy the file to `~` and run `lesskey` to generate the binary file.
The file can also be appended to an existing `.lesskey` file, or used from a different path by using
```
lesskey -- <.lesskey path>
```
