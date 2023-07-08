# Worlds Without Number for Obsidian

An Obsidian Vault for Resources for Worlds without Number.

> Note: Due to restrictions and allowance by Sine Nomine publishing, we intend this vault to act as a quickstart, and briefly describes much of this vault in the rewritten text of the Free version of WWN. See our [[License]] and [this reddit post](https://www.reddit.com/r/SWN/comments/xk5auc/a_trademark_question/) for more details.
> 
> We encourage you to grab at least the [free version of the book](https://www.drivethrurpg.com/product/348809/Worlds-Without-Number-Free-Edition), and support the author by [purchasing the full version](https://www.drivethrurpg.com/product/348791/Worlds-Without-Number?cPath=5875_38601).


## Filesystem Conventions

To maximise the filesystem compatibility, this vault uses the following naming conventions:

**Kebab Case**: `this-is-a-file.md`

Kebab casing replaces the `%20` space character, and makes it easier to navigate files in a command line or terminal.

**WWN Extensions**: `this-is-a-file-wwn.md`

Many files in this compendium share the same names for abilities and sections as found in other compendiums. As such, we're adding the suffix `-wwn` to each file, and relying on aliases and title metadata to hide the `-wwn`.

**Absolute Links**: `vault-root/this/is/a/file.md`

Absolute links work to catch edge cases that the WWN Extensions naming convention would not catch, or where WWN-Extension is not practical.

### Renaming Files

It is understood that what ***YOU*** need for your vault is different than what is needed for a sharable vault. As such, here is how to fix the filenames back to "standard" form.

Please note, if you use folder notes, temporarily disable that plugin until the renaming is done.

> :Danger: DO NOT RENAME FILES OUTSIDE OF OBSIDIAN.

1. Install the community plugin [Obsidian Bulk Rename](https://github.com/OlegLustenko/obsidian-bulk-rename).
2. Enable the plugin
3. Inside the plugin settings options, decide if you are going to **Remove the -wwn**, **Remove the -**, or both. 
	1. Start with **Remove the -WWN**.
	2. Search by: Folder
	3. Choose which folder you want to do all the renaming of the child notes in. We recommend starting with a small folder like Equipment first to ensure the results look right on your setup.
	4. In the existing field, type `-wwn`
	5. In the replace field, leave empty
	6. Below the list of file, select preview to ensure the renamed files end up looking like `file-name.md`, then select replace.
	7. Let Obsidian Rename the files. Links should update appropriately. 
4. Exit settings and ensure the files look good. Repeat as necessary until all desire files no longer have `-wwn` in the name.
5. Now that you have confirmed `-wwn` has been removed, go back into the bulk rename settings and get ready to remove all `-` and replace with a space.
	1. Search by: Folder
	2. Choose which folder you want to do all the renaming of the child notes in. As before, we recommend starting with a small folder like Equipment first to ensure the results look right on your setup.
	3. In the existing field, type `-`
	4. in the replace field, make one space with the spacebar ` `. The field will appear empty.
	5. Below the list of file, select preview to ensure the renamed files end up looking like `file name.md`, then select replace.
	6. Let Obsidian Rename the files. Links should update appropriately. 
6. Exit settings and ensure the files look good. Repeat as necessary until all desire files no longer have `-` in the name.
7. You are now done with the rename.

### Renaming Links

1. Complete the renaming steps above, if desired.
2. Ensure in your settings the link preferences of choice are set.
3. Rename `wwn` to `wwn2`. Let Obsidian take the time it needs to update all links.
4. When Obsidian is done, rename `wwn2` back to `wwn`. 

All your links in the child notes should now be your link choice. 
