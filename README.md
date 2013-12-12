# GitHub Flavored Markdown README Template #

## Overview ##
This is a style guide for GitHub Flavored Markdown READMEs. It will include syntax, cleanliness, content, and layout. Please feel free to improve upon this.

Forked with gratitude from: <https://github.com/JoePShoulak/README-Styleguide>

You may also like:
- <http://daringfireball.net/projects/markdown>
- <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>
- <https://help.github.com/articles/github-flavored-markdown>

If you have any suggestions or improvements, please let me know [@kyletcarlson](https://twitter.com/kyletcarlson).

# Title #
```# Title #```
Notice the space inside the ```#```s. Much more readable than ```#Title#```. You'll notice this isn't as large as the first title of the README, You're not allowed to have two at that level. Still use ```## ##``` later on, even though it is now the default size for ```# #```, for readability.

## Project Overview ##
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


## TODO ##
Here are the features we want to add soon. It's not a necessary section in a README, but it gives potential users an idea of where your project is going & contributors a starting point for what to help with.
- Add feature one
- Fix this bug
- Foo this
- Bar that
- Sell for $1B
- Profit, literally


## Testing ##

To run the tests:

    $ rspec spec 

Please ensure code you submit is tested & the whole suite passes before submitting a pull request.

Check out my [RSpec model testing template](https://gist.github.com/kyletcarlson/6234923) for a nice template to test in RSpec. TDD doesn't have to be hard.


## Contributing ##

1. Fork it.
2. Create a branch (`git checkout -b my_branch`)
3. Commit your changes (`git commit -am "Added sweet sweet feature."`)
4. Push to the branch (`git push origin my_branch`)
5. Open a [Pull Request][1]
6. Go have a drink & feel good for helping!

Make sure to change the pull request link to your repo instead of the generic link at the bottom of the Markdown code.


## Acknowledgements ##
Now we're an open source _community_, so let's be nice and thank anyone who helped us out, using a bulleted list of people who helped out a lot (in no particular order):

- John Skeet
- David Heinemeier Hansson
- Yukihiro Matzumoto
- Linus Torvalds
- Alan Kays

Bulleted lists are done like so: ```- StackOverflow user2062950```. Notice the space after the ```-```.



[1]: https://github.com/your-username/fetlocker/pulls

