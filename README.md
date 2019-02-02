# Jeitgeik: switching J and K
JeitgeiK(pronounced similarly to zeitgeist) is an attempt to standardize a new key-mapping based on the widely used "vim-like", where the key `j` is understood as "previous" or "up" and the key `k` is understood as "next" or "down".
In the traditional sense, `j` will be understood as "previous line" in vim.
Other common uses are "previous tab" (Vimperator, browsers), "previous window" (window managers) and "window above the current one"(VIM windows)

## Expectations
JeitgeiK is constructed for ease of use and readability. It is an attempt to change one aspect of the mapping and as such has a limited scope.
 - Actionable code (source code/scripts/configuration files) is kept small and self-contained. The code might be a code fragment, and there might be some meta-config helpers (such as makefiles/patches/etc.) but the code is beileved to be the entirety of the needed change, if possible.
 - Through either comments or a README file, the changes are explained.
 - There are no changes beyond the scope of switching the meanings of `j` and `k` in programs where `j` and `k` binding are understood as "next" and "previous"
 - An effort is made to cover all existing meanings of `j` and `k` for a given program
Changing someone's existing habits is not one of this project's goals.

## Rationale
JeitgeiK exists to change a standard and make the use of this change easy. The rationale holds both the reasons this change is good as well as why this project is necessary.
 - There is no known inherit value to treating `j` as "next" rather than "previous"
 - As time goes on, there are more people who are not yet using the already existing standard, which means there are more people who won't find this change jarring and might find it useful.
 - `h` and `l` are "left" and "right", respectively and in accordance to their physical QWERTY positions. This creates a dissonace when `j` and `k` key are treated as "next" and "previous".
 - Since most programming languages and programs using "vim-like" keybinding are based on left to right alphabets/languages, and since `j` comes "before" `k`, it is more intuative to use `j` as "previous".
 - Most of the affected programs are client sided, and the changes will only affect those who wish to use them.
 - Programs using "vim-like" key binding often also support rebinding of keys, so it is often the case that the change is very easy.
 - Programs supporting rebinding of keys use vastly different ways to rebind keys, so "switching" to JeitgeiK is a different process for each program.
 - Different programs interpet "back" and "next" differently, for different uses, so it's helpful to have them documented.

