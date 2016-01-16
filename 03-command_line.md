# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](http://cli.learncodethehardway.org/book/). This is a great,
quick tutorial. Each "chapter" focuses on a command. Type the commands
you see in the _Do This_ section, and read the _You Learned This_
section. Move on to the next chapter. You should be able to go through
these in a couple of hours.


---

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do, focused on things that are new, interesting, or otherwise worth remembering.

> > cd-change wd to folder. .
. -enclosing folder 
pushd/popd - save/return to cwd
mv file /dest/ - move object
cp file newfile -r - copy/copy contents
q -quit
less - view file
| < - pipe right/left
>  >> write left to write
* - matches pattern
$ - access value of a variable 


---


---

What does `ls` do? What do `ls -a`, `ls -l`, and `ls -lh` do? What combinations of those flags are meaningful?

> > ls lists the cw directory contents. -a includes files that start with . -l includes author and modification inf -h includes file sizes, but only when used with -l

---


---

What does `xargs` do? Give an example of how to use it.

> > It combines the results of a previous command (like find) and uses them to execute the new command. Such as find '*.txt' | xargs rm  

---

