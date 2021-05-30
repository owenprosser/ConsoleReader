# ConsoleReader
An app for reading [HackerNews](https://news.ycombinator.com) from the console.

![ConsoleReader Screen Shot](http://owenprosser.com/ConsoleReader/ConsoleReader.png "ConsoleReader Screen Shot")

## To run as commmand in bash:
Make the file executable

```
$ chmod +x news
```

Creat bin dir

```
$ mkdir -p ~/bin
```
Copy the file to the new ~/bin dir

```
$ cp news ~/bin
```
Add this new dir to your PATH

```
export PATH=$PATH":$HOME/bin"
```

Add this line to .bash_profile to make it a permenant change.