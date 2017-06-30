# **beman** | **be**ginner **man** pages

**beman** stands for beginner man pages, and is a project to simplify linux man pages. beman lists a short description and the most common use cases of a linux command, which is pretty much everything that a linux newbie needs to get started.

The man pages provide exhaustive documentation about a linux shell command. As we all know this can be a little intimidating for the newbie. beman just provides them with the stuff to get them started so that they can try things out and eventually get to read real man pages (Isn't that noble?). That's it.

#### Usage

```bash
$ beman command-name
```

(Just like the man command you dread). 

Here's an example :

```shell
$ beman ls
ls - lists the files and folders in a directory.
FORMAT 
ls {OPTIONS}...{DIR}...
EXAMPLES  
ls 
lists the contents of the present working directory. 
ls -a  
list the contents of the present working directory. Including the hidden files. 
ls -l  
list the contents along with their permissions, ownership nad some more details.
ls /path/to/directory/ 
list the contents of the specified directory. The options -a and -l works as expected.
```

It's not like anyone is gonna need help using '**ls**'. Try this with '**sed**' or '**grep**' or something like that.