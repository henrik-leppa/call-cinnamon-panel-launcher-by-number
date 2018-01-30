Call Cinnamon Panel Launcher By Number 1.0.0
============================================

Call a panel launcher by number in the Cinnamon desktop environment.

Panel launcher numbering starts at 1.


Setting Up Shortcuts
--------------------

You can set up shorcuts that use this to open panel items using the
"Super key"/"Windows key", like this:
1. Copy the script to `/home/username/bin/`.
   - (Create the bin directory if it does not exist.)
2. Make the script executable.
3. Open Keyboard settings.
4. Add custom shortcuts that follow this format:
   - Name:
     - Call Cinnamon Panel Launcher By Number 1
   - Command:
     - `call-cinnamon-panel-launcher-by-number 1`
   - Keyboard binding:
     - Super+1
   - (Use Super+0 for the 10th item.)


Command-line Usage
------------------

```
call-cinnamon-panel-launcher-by-number <launcher_number>
```
or:
```
call-cinnamon-panel-launcher-by-number [--help|--version|-H|-h|-?|-V|-v]
```

### Options

- `--help, -H, -h, -?`:
  - Print the usage message.
- `--version, -V, -v`:
  - Print version and copyright information.
- `<launcher_number>`:
  - Number of the launcher you want to start. Must be a positive integer.
