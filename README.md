# Mastering Bash



Learning Path to Learn Bash | With Gun



# Table of Contents





----



Last touched on 12 July 2023



# Shell

Shell is command interpreter for the linux operating system, shell provides interactive user interface between user and kernel.



## Zsh

Zsh is a shell designed for interactive use and powerful scripting language



## Hello World!

To create shell script we will use vi editor :

```
$ vi hello.sh
```

Save the following into a file called hello.sh :

```bash
#!/bin/zsh
echo "Hello, World!" 
```

If we try to execute the script we will get error :

```
$ ./hello.sh
zsh: permission denied: ./hello.sh
```

To fix this execute this command :

```bash
$ chmod +x hello.sh
```

Execute

```
$ ./hello.sh
hello world, gun gun febrianza!
```





## Resources

- [Bash Stream Handbook](https://github.com/miguelmota/bash-streams-handbook) by Miguel Mota
