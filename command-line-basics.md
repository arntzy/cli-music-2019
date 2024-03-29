# Command Line Basics

This is a very introductory introduction to the command line. Those interested in learning more should see: 
[Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial)


----

List contents of current directory

```
ls 
```

Show name of current directory and full path

```
pwd
```

Change directory

```
cd DIRECTORYNAME
```

Go up one

```
cd ..
```

Go to your home directory

```
cd
```

Make a new directory

```
mkdir DIRECTORYNAME
```

Open a file using the default application (mac only)

```
open FILENAME
```

Open the current directory in the Finder (mac only)
(the ```.``` means "here")

```
open .
```

Print the contents of a file to the screen

```
cat FILENAME
```

Print the contents of a file to the screen, with pagination

```
more FILENAME
```

Search for a something in a text file

```
grep "search term" FILENAME
```

Create an alias for an annoying or long command

```
alias ll='ls -lahG'
```

Pipe the output of one command into another

```
ll | grep '*.mp3'
```

Redirect output to overwrite a file

```
echo "this is a command line tutorial" > cli.txt
```

Redirect output appending to an existing file
```
echo "yet ANOTHER command line tutorial" >> cli.txt
```
