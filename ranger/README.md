Systemwide configuration: `/etc/ranger/rc.conf`
Per-user configuration: `~/.config/ranger/rc.conf`

`JeitgeiK.conf` contains the commands to redo the mapping in the style seen in the default `rc.conf` file.

JeitgeiK can be installed by appending the content of `JeitgeiK.conf` to `rc.conf`, or copying the file to `~/.config/ranger` and adding the following line to the end of `rc.conf`:
```
source %confdir/JeitgeiK.conf
```
The path can be changed to anyway other path if `JeitgeiK.conf` is anywhere else.
