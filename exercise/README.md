# Intro to the CLI Lab - Exercise

![Hero image](./assets/hero.png)

## Episode X: A New Terminal

A long time ago, in a Unix environment far, far away... young Jedi Padawans who knew only of desktop software were seduced by the dark side of the Force to enter: 

The Terminal

## Part I: `mkdir` and `touch` - set the scene

The `mkdir` and `touch` commands are foundational for managing files and directories. `mkdir` stands for ***make directory***. `mkdir` allows you to create new directories in your file system. On the other hand, `touch` is used for creating new files. 

Both commands provide a quick and straightforward way to set up your project's structure. 

**Practice:**

1. At the start of this lab, you should already be in a directory called `star_wars`.

2. Create a new directory here called `death_star`.

3. Create the following files inside of it: `darth_vader.txt`, `princess_leia.txt`, and `storm_trooper.txt`.

4. Make another directory in `star_wars` called `galaxy_far_far_away`.

5. Inside the `galaxy_far_far_away` directory, make a new directory named `tatooine` and create the following files inside it: `luke.txt` and `ben_kenobi.txt`.

6. Inside the `tatooine` directory, make a directory called `millenium_falcon`, and inside it, create `han_solo.txt` and `chewbacca.txt` files.

## Part II: `cp` - copy

The `cp` command is used for copying files and directories. Short for ***copy***, this command lets you duplicate files from one location to another. 

For example, `cp source.txt destination.txt` would copy the contents of `source.txt` into a new file called `destination.txt`. It's a versatile tool often used in scripts and batch operations. While `cp` is powerful and efficient, it's crucial to use it carefully to avoid accidental overwrites of the destination file. 

> 💡 Check the manual: Run `man cp` to see the options — hit the `Q` key to get out of the manual page viewer.

**Practice:**

1. Copy `storm_trooper.txt` from the `death_star` directory to the `tatooine` directory.

## Part III: `mv` - move

The `mv` command is your go-to tool for moving and renaming files and directories. Short for ***move***, this command allows you to take a file from one location and place it into another. But it's more versatile than that; you'll see why soon.

You could use `mv myfile.txt /new/folder/` to move a file from one directory to another.

> 💡 Check the manual: Run `man mv` to see the options —hit the `Q` key to get out of the manual page viewer.

**Practice:**

1. Move `luke.txt` and `ben_kenobi.txt` to the `millenium_falcon` directory.

2. Move the `millenium_falcon` directory out of the `tatooine` directory and into the `galaxy_far_far_away` directory.

3. Move the `millenium_falcon` directory into the `death_star` directory.

4. Move `princess_leia.txt` into the `millenium_falcon` directory.

## Part IV: `mv` - rename

You can also use `mv` to rename files. This is accomplished by moving the file from one name to another within the same directory.

Using the command `mv oldfile.txt newfile.txt` will rename `oldfile.txt` to `newfile.txt`. 

**Practice:**

1. Rename `ben_kenobi.txt` to `obi_wan.txt`.

## Part V: `rm` - remove

The `rm` command stands for ***remove*** and deletes files and directories. To delete a ***file***, you'd type `rm filename`. To delete a ***directory and all the files inside of it***, you'd use `rm -r directoryname`. 

While the `rm` command is efficient for cleaning up, it comes with a ***caution***: deleted items don't go to a recycle bin— they're permanently removed. So before executing this command, make sure you want to delete the target permanently. 

**Practice:**

  1. Delete `obi_wan.txt`.

## Part VI: All together

The `mkdir`, `touch`, `cp`, `mv`, and `rm` commands are essential tools for file and directory management in the command line. 

- `mkdir` creates directories
- `touch` creates files
- `cp` copies files or directories
- `mv` moves or renames them
- `rm` deletes them

Let's try these all together!

**Practice:**

1. In the `galaxy_far_far_away` directory, make a directory called `yavin_4`.

2. Move the `millenium_falcon` directory out of the `death_star` directory and into the `yavin_4` directory.

3. Make a directory in the `yavin_4` directory called `x_wing`.

4. Move `princess_leia.txt` to the `yavin_4` directory and `luke.txt` to the `x_wing` directory.

5. Move the `millenium_falcon` directory and the `x_wing` directory out of the `yavin_4` directory and into the `galaxy_far_far_away` directory.

6. In the `death_star` directory, create directories for `tie_fighter_1`, `tie_fighter_2`, and `tie_fighter_3`.

7. Move `darth_vader.txt` into the `tie_fighter_1` directory.

8. Make a copy of `storm_trooper.txt` into both the `tie_fighter_2` and `tie_fighter_3` directories.

9. Move all of the `tie_fighters` directories out of the `death_star` directory and into `galaxy_far_far_away` directory.

## Part VII: `rm -r`: Remove directories and everything they contain

Remember, this command will not ask you if you really want to delete the directory and its files. It will just delete.

Once you hit `Enter`, its gone forever. 

Always make sure you are deleting the right thing, or you could accidentally delete things you don't intend to delete.

**Practice:**

1. Remove the `tie_fighter_2` and `tie_fighter_3` directories.

## Part VIII: May the Force be with you

Let's wrap up this story properly.

**Practice:**

1. Touch a file in the `x_wing` directory called `the_force.txt`.

2. Destroy the `death_star` directory and anyone inside of it.

3. Return the `x_wing` and `millenium_falcon` directory to the `yavin_4` directory.

## Part IX: Clean up 

1. Navigate to your **`~/code/ga/labs`** directory:

   ```bash
   cd ~/code/ga/labs
   ```

2. Remove the `star_wars` directory and all its contents. 

Like it never happened!
