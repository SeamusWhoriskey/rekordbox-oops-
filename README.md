**rekordbox oops!: undelete deleted rekordbox files :)**

Use this at your own risk! This version works for me, and I’m pretty sure it will work for other people, but I want to get the okay from someone at Pioneer to make sure I’m not corrupting anything!

**Notes:**

Mac only, idk anything about windows sry! This will only revert ONE (1) deletion (meaning if you select 20 songs, and delete with this once, you’ll be able to recover it, but if you select 10 songs, delete, and then another 10 songs, delete, you can only recover the last 10 songs with this. If you want to recover all the songs from the deleting 10 songs twice, follow the steps in the BIG OOPS section). Note that you MUST use the keyboard shortcut to delete, it's a slight bit longer to delete, but it allows you to restore to right before you've deleted! If you delete with ⌘+del, go to the big oops section

***WARNING:***
When undoing, rekordbox will restart, so like don’t undo when you’re DJing lol

**Setup:**
There are a few steps to set this up sadly :( but it’s more customizable this way :) 

(also if anyone reading this has any clue as to how to turn this into an app or any ideas in general lmk)

0. Double click rekordbox oops Setup, and run it ONCE. Double click rekordbox Delete and rekordbox Undo, and save them. 
1. Go to System Preferences -> Security & Privacy -> Privacy -> Accessibility
   1.1. Add Automator, Script Editor and rekordbox to the Accessibility list
2. Go to System Preferences -> Keyboard -> Shortcuts -> Services
   2.1. Locate rekordbox Delete, and add the shortcut desired to delete (for some reason you can’t use command delete)
   2.2. Locate rekordbox Undo, and add the shortcut desired to undo (command Z is free)

**BIG OOPS**

This section is if you've deleted multiple times, and you realize that you want it all back!

1. Open finder
2. Hit ⌘+⇧+G, type in ~/Library/Pioneer/rekordbox
3. Find the four files beginning with datafile, copy these files into the rekordboxBackup folder on your desktop.
4. Close rekordbox, wait until it's shut down, then in the .../Pioneer/rekordbox folder 
5. Rename datafile.edb to datafile.original.edb
6. Rename datafile.backup.edb to datafile.edb
7. When you open rekordbox again, it should be restored to the most recent backup :)

