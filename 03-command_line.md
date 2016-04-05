# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](http://cli.learncodethehardway.org/book/). This is a great,
quick tutorial. Each "chapter" focuses on a command. Type the commands
you see in the _Do This_ section, and read the _You Learned This_
section. Move on to the next chapter. You should be able to go through
these in a couple of hours.

---

###Q1.  Cheat Sheet of Commands  

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do, focused on things that are new, interesting, or otherwise worth remembering.

> >
pwd - current folder
ls - list files
touch - create file
cat - stream file content
find - to search for a file
grep - to search for text
mkdir - create folder
sort - to sort contents of a file
> - to redirect content to a specific file
I - to run commands in order

---

###Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`
`ls -l`
`ls -lh`
`ls -lah`
`ls -t`  
`ls -Glp`

> >
`ls` - list files
`ls -a`  include directories with name beginning with a dot
`ls -l`  long form include details
`ls -lh` long form with unit suffixes
`ls -lah` long form, including directories with name beginning with a dot and use unit suffixes
`ls -t` list files sorted by time
`ls -Glp` list files, colorized output, in long form with folders identified by /

###Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > - m - comma separated list, R - display subdirectories

---

###Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > can use it to take input from the command line run a command on a result set. Eg: find . -name “textfile*.txt” | xargs cat > “consolidatedfile.txt” would include contents of all text files found in the search in the consolidated file.txt.
