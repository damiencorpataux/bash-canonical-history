bash-canonical-history
======================

A centralized .bash_history management system so that you will never crave for a bash history line again

### Problem...
Have you ever been in such situations:
* you need a long command that lies in the history of another user / host / screen
* you crash your box with all your precious commands in it

### Solution !
A .bash_history file that is
* Centralized (using a git repo)
* Hook-processable (cleaning, ordering, filtering, regexing definitely)
* Handy (history should reload seamlessly of eye-blinkingly)
* Modulable (per-host history could be kept using git branches)
