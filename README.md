# ConsoleReader
An app for reading [HackerNews](https://news.ycombinator.com) from the console. Stories can be reading in console using Vim or opened in the default browser. Stories can be sorted by New, Best and Top.

![ConsoleReader Screen Shot](/image/ConsoleReader.png?raw=true "ConsoleReader Screen Shot")


* Install Packages from requirements

```
$ pip3 install -r requirements.txt
```

The text from news items is opened in Vim; I would reccomend adding these two lines to your ~/.vimrc to make long form text more readable.

```
set number
set linebreak
```

## To run as commmand in bash:
* Make the file executable

```
$ chmod +x news
```

* Creat bin dir

```
$ mkdir -p ~/bin
```
* Copy the file to the new ~/bin dir

```
$ cp news ~/bin
```
 *Add this new dir to your PATH

```
export PATH=$PATH":$HOME/bin"
```

* Add this line to .bash_profile to make it a permenant change.