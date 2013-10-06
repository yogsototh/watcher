# Watcher

This is a simple script with watch for file modification and execute a
command when this occurs.

Examples:

    watch ./gen fic1 fic2 dir1

This will watch for changes on `fic1`, `fic2` and any file in the tree `dir1`.
If `dir1/foo` changes, `./gen dir1/foo` is executed.
