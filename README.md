![GA logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)

#  Homework 1: Terminal & Loops

Duration: 3 hrs approx. <br>
Creator: Thom Page <br>
Modified by: Kristyn Bryan and Reuben Ayres <br>
Topics: Terminal <br>

---

# Section 1: Terminal Practice

## Episode X: A New Terminal

A long time ago in a Unix environment far, far away, young Jedi padawans who
knew only of desktop software were seduced by the dark side of the Force to
enter… The Terminal.

Follow the instructions below using all the console commands introduced in
Fundamentals, class, or that you find on your own.

## Setup

* Open the **Terminal app**

* Make a directory in today's folder called `homework`.  Create a new directory in that `homework` directory called `homework_part_1` and enter it.

* Create a file called `commands.txt`.

* Paste the answer to each numbered question (i.e. the command(s) that accomplished the task) in `commands.txt` once you get it to work.


## Part I: Set the Scene

1. Create a directory called `death_star`, and make the following files inside of it: `darth_vader.txt`, `princess_leia.txt`, `storm_trooper.txt`

2. In `galaxy_far_far_away`, make a directory named `tatooine` and create the following files in it: `luke.txt`, `ben_kenobi.txt`.

3. Inside of `tatooine` make a directory called `millenium_falcon`, and in it create: `han_solo.txt`, `chewbaca.txt`

<br>

## Part II: `mv` - rename

* You can rename a file using the `mv` command. 

4. Rename `ben_kenobi.txt` to `obi_wan.txt`.

<br>

## Part II: `cp` - copy

* You can copy a file from one location to another using the `cp` command. (`man cp` for more info)

- Directories can be sibling (parrell to each other) or can be parents (the folder that contains the folder you are in)

5. Copy `storm_trooper.txt` from `death_star` to `tatooine`.

<br>

## Part IV: `mv` - move

* You can use the `mv` command to move files from one location to another. `mv` can be used for renaming, moving, or both.  Run `man mv` to see the options—remember hit the `Q` key to get out of the manual page viewer.

6. Move `luke.txt` and `obi_wan.txt` to the `millenium_falcon`.

7. Move `millenium_falcon` out of `tatooine` and into `galaxy_far_far_away`.

8. Move `millenium_falcon` into `death_star`.

9. Move `princess_leia.txt` into the `millenium_falcon`.

<br>


## Part V: `rm` - remove

### ***BE CAREFUL WITH `rm`!!! THERE IS NO "TRASH" IN THE UNIX CLI. WHEN YOU DELETE SOMETHING IT IS GONE FOREVER!!!***

You can use `rm` to delete a file.


10. Delete `obi_wan.txt`.

<br>

## Part VI: all together

11. In `galaxy_far_far_away`, make a directory called `yavin_4`.

12. Move the `millenium_falcon` out of the `death_star` and into `yavin_4`.

13. Make a directory in `yavin_4` called `x_wing`.

14. Move `princess_leia.txt` to `yavin_4` and `luke.txt` to `x_wing`.

15. Move the `millenium_falcon` and `x_wing` out of `yavin_4` and into `galaxy_far_far_away`.

16. In `death_star`, create directories for `tie_fighter_1`, `tie_fighter_2` and `tie_fighter_3`.

17. Move `darth_vader.txt` into `tie_fighter_1`.

18. Make a copy of `storm_trooper.txt` in both `tie_fighter_2` and `tie_fighter_3`.

19. Move all of the `tie_fighters` out of the `death_star` and into `galaxy_far_far_away`.

<br>

## Part VII: `rm -r`: remove directories and everything they contain

***BE CAREFUL WITH `rm`!!! THERE IS NO TRASH CAN IN THE UNIX CLI. WHEN YOU DELETE SOMETHING IT IS GONE FOREVER***

Before you hit enter, make sure are deleting the right thing, or you could accidentally delete the contents of your computer (it has happened).

This command will not typically ask you if you "really want to delete." It will just delete.


20. Remove `tie_fighter_2` and `tie_fighter_3`.


## Part VIII:

21. Touch a file in `x_wing` called `the_force.txt`.

22. Destroy the `death_star` and anyone inside of it.

23. Return `x_wing` and the `millenium_falcon` to `yavin_4`.


### Celebrate. You've reached the end of section 1 :)

<br>
<hr>

# :red_circle: Commit and push your updated code:

"Add" your changes (prepare them to be "committed"):
```bash
$ git add -A
```

"Commit" your changes—any time you make a commit, you can always restore the files in the repo to that point:
```bash
$ git commit -m "Completed homework assignment"
```

"Push" your commits to github:
```bash
$ git push origin master
```

---

# Homework submission

Once you've got your homework all done and pushed to github, do a pull request to get it submitted. If you're not sure how to do this, reach out to your instructor for help
