# Intro to the CLI Lab - Exercise

![Hero image](./assets/hero.png)

<img src="https://i.imgur.com/YmNE2R2.png">


## Episode X: A New Terminal

A long time ago in a Unix environment far, far away... young Jedi Padawans who knew only of desktop software were seduced by the dark side of the Force to enter: 

The Terminal...

<br>

### Part I: `mkdir` & `touch` - Set the Scene

The `mkdir` and `touch` commands are foundational for managing files and directories. `mkdir` stands for "make directory," and it allows you to create new folders in your file system. On the other hand, `touch` is used for creating new files. 

Both commands provide a quick and straightforward way to set up your project's structure. 

**Practice:**

  1. At the start of this Lab you should already be in a directory called `star_wars`.

  2. Create a new directory here called `death_star`.

  3. Create the following files inside of it: `darth_vader.txt`, `princess_leia.txt`, `storm_trooper.txt`

  4. Make another directory in `star_wars` called `galaxy_far_far_away`.

  5. Inside of `galaxy_far_far_away`, make a directory named `tatooine` and create the following files in it: `luke.txt`, `ben_kenobi.txt`.

  6. Inside of `tatooine` make a directory called `millenium_falcon`, and in it create `han_solo.txt` and `chewbacca.txt` files.

<br>

### Part II: `cp` - copy

The `cp` command in Bash is used for copying files and directories. Short for "copy," this command lets you duplicate files from one location to another, straight from the command line. 

For example, `cp source.txt destination.txt` would copy the contents of `source.txt` into a new file called `destination.txt`. It's a versatile tool often used in scripts and batch operations. While it's powerful and efficient, it's crucial to use it carefully to avoid accidental overwrites of the destination file. 

> Check the manual: Run `man cp` to see the options — hit the `Q` key to get out of the manual page viewer.

**Practice:**

  1. Copy `storm_trooper.txt` from `death_star` to `tatooine`.

<br>

### Part III: `mv` - move

The `mv` command in Bash is your go-to tool for moving and renaming files and directories. Short for "move", this command allows you to take a file from one location and place it into another, all without the need for a graphical interface. But it's more versatile than just that, you'll see why soon.

To move a file from one directory to another, you could use `mv myfile.txt /new/folder/`. It's that simple.

> Check the manual: Run `man mv` to see the options —hit the `Q` key to get out of the manual page viewer.

**Practice:**

  1. Move `luke.txt` and `ben_kenobi.txt` to the `millenium_falcon`.

  2. Move `millenium_falcon` out of `tatooine` and into `galaxy_far_far_away`.

  3. Move `millenium_falcon` into `death_star`.

  4. Move `princess_leia.txt` into the `millenium_falcon`.

<br>

### Part IV: `mv` - rename

You can also use `mv` to rename files. Simply 'move' a file to a new name in the same location, and voilà, it's renamed!

Using the command `mv oldfile.txt newfile.txt` will rename `oldfile.txt` to `newfile.txt`. 

**Practice:**

  1. Rename `ben_kenobi.txt` to `obi_wan.txt`.

<br>

### Part V: `rm` - remove

The `rm` command in Bash stands for "remove" and is used to delete files and directories. To **delete a file**, you'd type `rm filename`. To **delete a directory** and all the files inside of it, you'd use `rm -r directoryname`. 

While the `rm` command is efficient for cleaning up, it comes with a ***caution***: deleted items don't go to a recycle bin— they're permanently removed. So before executing this command, make sure you want to permanently delete the target. 

**Practice:**

  1. Delete `obi_wan.txt`.

Bye!

<br>

### Part VI: All together

The `mkdir`, `touch`, `cp`, `mv`, and `rm` commands are essential tools for file and directory management in the command line. 

- `mkdir` creates directories
- `touch` creates files
- `cp` copies files or directories
- `mv` moves or renames them
- `rm` deletes them

Let's try these all together!

**Practice:**

  1. In `galaxy_far_far_away`, make a directory called `yavin_4`.

  2. Move the `millenium_falcon` out of the `death_star` and into `yavin_4`.

  3. Make a directory in `yavin_4` called `x_wing`.

  4. Move `princess_leia.txt` to `yavin_4` and `luke.txt` to `x_wing`.

  5. Move the `millenium_falcon` and `x_wing` out of `yavin_4` and into `galaxy_far_far_away`.

  6. In `death_star`, create directories for `tie_fighter_1`, `tie_fighter_2` and `tie_fighter_3`.

  7. Move `darth_vader.txt` into `tie_fighter_1`.

  8. Make a copy of `storm_trooper.txt` in both `tie_fighter_2` and `tie_fighter_3`.

  9. Move all of the `tie_fighters` out of the `death_star` and into `galaxy_far_far_away`.

<br>

### Part VII: `rm -r`: Remove directories and everything they contain

Remember, this command will not ask you if you "really want to delete." It will just delete.
Once you hit enter, its gone forever. 

Always make sure you are deleting the right thing, or you could accidentally delete the contents of your computer (it has happened).

**Practice:**

  1. Remove `tie_fighter_2` and `tie_fighter_3`.

<br>

## Part VIII: May the Force Be With You...

Let's wrap up this story properly.

**Practice:**

  1. Touch a file in `x_wing` called `the_force.txt`.

  2. Destroy the `death_star` and anyone inside of it.

  3. Return `x_wing` and the `millenium_falcon` to `yavin_4`.

<br>

## Part IX: Clean up 

1. Navigate to your **`~/code/ga/labs`** directory:

```bash
cd ~/code/ga/labs
```

1. Remove `star_wars` and all its contents. 


Like it never happened! 