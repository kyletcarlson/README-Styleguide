# GitHub Flavored Markdown README Style Guide #

## Overview ##
This is a style guide for GitHub Flavored Markdown READMEs. It will include syntax, cleanliness, content, and layout. Please feel free to improve upon this.

## Details ##
I have recently realized that there is no uniform style guide for GFM READMEs and I decided to ask about it on StackOverflow. They said, "Well, how about you make it, and we'll help." So here I am making it. 

---

Let's start with content and layout.

I have used the same layout I am going to suggest in this same README. So let's see what we've got...

Start with a title, at a header level of 1

# Title #
```# Title #```
Notice the space inside the ```#```s. Much more readable than ```#Title#```. You'll notice this isn't as large as the first title of the README, You'r enot allowed to have two at that level. Still use ```## ##``` later on, even though it is now the default, for readability.

## Overview ##
Next should come an overview of your application. It should be short and not in great detail, simply stating what it's trying to do, and a basic idea of how it's doing it. This should be at header level 2.
Notice the two ```#``` in to define it as a second level header. ```## Overview ##```

## Details ##
This is where you get into the nitty-gritty of how your application works. What algorithms you're using, whose repos you forked, what libraries you're including, etc.

## Installation ##
Here is where you would put instructions on how to install your application. If it's a bash file, we might put something like
```bash
$ curl http://github.com/user/repo > /usr/bin
```

This should be simple and straight forward. Notice the ```$``` in front of system commands.

## Usage ##
Usage comes next, which should contain instructions for using your application. For example, if my application were unix's ```mkdir``` command, I would put something like this:
```bash
$ ls
  stuff         fun_stuff
  school_stuff  pictures
$ mkdir movies
$ ls
  stuff         fun_stuff  movies
  school_stuff  pictures
```

Notice again the ```$``` for when we're putting input to the command line, and the indentations (2 space, soft tabs) for the output of the function.

## Acknowledgements ##
Now we're an open source _community_, so let's be nice and thank anyone who helped us out, using a bulleted list of people who helped out a lot (in no particular order)
- StackOverflow user2062950
Bulleted lists are done like so: ```- StackOverflow user2062950```. Notice the space after the ```-```.

## Formatting

