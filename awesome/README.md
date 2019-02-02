Per-user configurations: `$XDG_CONFIG_HOME/awesome/rc.lua` (usually: `~/.config/awesome/rc.lua`)

awesome uses a lua config file that arranges all binding into a table created by `gears.table.join(...)`.
In order to change the default mapping, they need to be override by one of these methods:
 - Overriding the clause under `-- {{{ Key bindings` with the modified version from `JeitgeiK_def.lua`.
 - Run lua code that searchs and switchs `j` and `k` keys automatically.
Currently, only the first solution is provided.
