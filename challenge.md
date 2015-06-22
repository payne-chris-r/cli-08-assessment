![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Carry out all of the following tasks using _only the command line_! As is usually the case, you're welcome to use any resource you can find (except another student, of course) to reach your answer.

<hr>

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `quiz` inside the root directory of this repository (`cli-08-assessment`).

2. Create a new file inside `quiz` called `rhyme.txt`.

3. Open `rhyme.txt` using Sublime (via the terminal) and add the following text:

 "The rain in Spain falls mainly in the plain."

Once you've done this, save the file and quit.

4. Make a directory inside `quiz` called `temp`. Inside it, create a new blank file called `temp.md`.

5. Navigate back up to `quiz`, and delete the `temp` directory (with `temp.md` inside of it).
Use `ls` to show the contents of `quiz` - was `temp` deleted?

## Absolute and Relative Paths

Open up this file in your text editor, and write your answers below (where indicated).

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

<!-- Answer Starts Here -->

Abosolute, because / is shorthand for the root directory, and we're given a set of folders that follow.'

<!-- Answer Ends Here -->

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

<!-- Answer Starts Here -->

Absolute. If you're referencing something on the internet you'll want to use an absolute directory because it doesn't live within your project. The only issue with this is if they decide to move the file (font in this case) you're screwed.'

<!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

<!-- Answer Starts Here -->
Relative. In order to keep the path up to date in the event we move the file, we'd want to use a relative path.'
<!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
