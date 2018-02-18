# `git-self-blame`

`git-self-blame` is a simple `git` plugin that lets you take the blame for code
you didn't write.

## Motivation

Ever wonder, **_Who wrote this garbage code?_** Sure, you could find out with `git blame`,
but even if it wasn't you:

* Maybe you approved that garbage in code review.
* Maybe you could've mentored the author on writing less-garbagey code.
* Maybe you helped foster a culture of shipping garbage.
* Maybe you put pressure on deadlines that lead to the garbaginess.
* ~~Maybe~~ you've written things **much, much worse**.

Take some responsibility instead with `git self-blame`.

> "You can put the blame on me."
> —Akon, on his motto as a Linux kernel maintainer

![It works, I swear.](https://user-images.githubusercontent.com/1114569/36355517-754d5ff0-14b2-11e8-9ca1-7a51150bca37.gif)

## Features

* Doesn't change your `git` history or configuration or anything else. This is a real tool, not some joke to mess up your whole repo.
* Definitely works in Bash and Zsh. Probably works in most other shells?
* Accepts any arguments that `git blame` accepts.
* Can be safely run in parallel with other `git` commands (including
  other `git self-blame` commands).
* It blames you for everything, what more do you want?

## Installation

```bash
git clone https://github.com/JacobEvelyn/git-self-blame.git
cd git-self-blame
export PATH=$PATH:$(pwd)

# If you want to actually use this more than once, add this
# to your PATH in a more permanent place, like your
# `~/.bashrc` or `~/.zshrc` files.
```

## How does it work?

There's a handy walkthrough
[in the source](https://github.com/JacobEvelyn/git-self-blame/blob/master/git-self-blame)!

## Who are you?

I'm Jacob. I do a lot of [humor writing](https://medium.com/@jacobevelyn) and
[tech writing](https://medium.freecodecamp.org/@jacobevelyn) and
[code writing](https://github.com/JacobEvelyn), and you can blame me for all
of it.
