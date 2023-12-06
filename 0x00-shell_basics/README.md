0x00. Shell, basics
================

-   By Julien Barbier, co-founder & CEO

About `Bash` projects

Unless stated, all your projects will be auto-corrected with Ubuntu 20.04 LTS.

Concepts
---------

*For this project, we expect you to look at this concept:*

-	[Struggling with the sandbox? Try this: Using Docker & WSL on your local host](https://intranet.alxswe.com/concepts/100039 "Struggling with the sandbox? Try this: Using Docker & WSL on your local host")

![image](https://github.com/oualidchouay/alx-system_engineering-devops/assets/135179972/128aa440-73ec-4e66-a14f-f6b756aa9ada)

Resources
---------

**Read or watch:**

-	[What Is “The Shell”?](https://intranet.alxswe.com/rltoken/vwO91sqNBgRL03BLu-ueiA "What Is “The Shell”?")
-	[Navigation](https://intranet.alxswe.com/rltoken/iblidp7yp6i-QpT8rDXHaA "Navigation")
-	[Looking Around](https://intranet.alxswe.com/rltoken/xEKUCnQsMH0esQ6fJU5vLA "Looking Around")
-	[A Guided Tour](https://intranet.alxswe.com/rltoken/HUhQ73fFR1GOC5nb4r-mDw "A Guided Tour")
-	[Manipulating Files](https://intranet.alxswe.com/rltoken/olv-1tj4d1LA57Z0PrLNvw "Manipulating Files")
-	[Working With Commands](https://intranet.alxswe.com/rltoken/zUtux3Pm0BkvtwXzbTtkmA "Working With Commands")
-	[Reading Man pages](https://intranet.alxswe.com/rltoken/rddGdsqLf8_kRzp12RaD4A "Reading Man pages")
-	[Keyboard shortcuts for Bash](https://intranet.alxswe.com/rltoken/AGxMxuS5IeW8VmEvJyhwvw "Keyboard shortcuts for Bash")
-	[LTS](https://wiki.ubuntu.com/LTS "LTS")
-	[Shebang](https://intranet.alxswe.com/rltoken/cE8ZA3kgEaFhB-IDNv31bQ "Shebang")

**man or help:**

-	cd
-	ls
-	pwd
-	less
-	file
-	ln
-	cp
-	mv
-	rm
-	mkdir
-	type
-	which
-	help
-	man

Requirements
------------

### General

-	Allowed editors: `vi`, `vim`, `emacs`
-	All your scripts will be tested on Ubuntu 20.04 LTS
-	All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
-	All your files should end with a new line ([why?](http://unix.stackexchange.com/questions/18743/whats-the-point-in-adding-a-new-line-to-the-end-of-a-file/18789 "why?"))
-	The first line of all your files should be exactly `#!/bin/bash`
-	A `README.md` file at the root of the repo, containing a description of the repository
-	A `README.md` file, at the root of the folder of this project, describing what each script is doing
-	You are not allowed to use backticks, `&&`, `||` or `;`
-	All your scripts must be executable. To make your file executable, use the `chmod` command: `chmod u+x file`. Later, we’ll learn more about how to utilize this command.

More Info
----------

*Example of line count and first line*

```

julien@ubuntu:/tmp$ wc -l 12-file_type
2 12-file_type
julien@ubuntu:/tmp$ head -n 1 12-file_type
#!/bin/bash
julien@ubuntu:/tmp$

```

In order to test your scripts, you will need to use this command: `chmod u+x file`. We will see later what does `chmod` mean and do, but you can have a look at `man chmod` if you are curious.

*Example*

```

julien@ubuntu:/tmp$ ls
12-file_type
lll
julien@ubuntu:/tmp$ ls -la lll
-rw-rw-r-- 1 julien julien 15 Sep 19 21:05 lll
julien@ubuntu:/tmp$ cat lll
#!/bin/bash
ls
julien@ubuntu:/tmp$ ls -l lll
-rw-rw-r-- 1 julien julien 15 Sep 19 21:05 lll
julien@ubuntu:/tmp$ chmod u+x lll # you do not have to understand this yet
julien@ubuntu:/tmp$ ls -l lll
-rwxrw-r-- 1 julien julien 15 Sep 19 21:05 lll
julien@ubuntu:/tmp$ ./lll
12-file_type
lll
julien@ubuntu:/tmp$

```

Tasks
-----

### 0\. Where am I?

mandatory
