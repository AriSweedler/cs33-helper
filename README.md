# CS 33 helper

## Why should you read this document

It will help you succeed in CS 33.

CS 33 teaches you a ton of cool stuff. It's a great class, it's challenging,
rewarding, and in my opinion, worth every second. It's a theory-based class, and
subscribes to the theory that the best way to learn stuff is by doing - which is
a philosophy I totally agree in.

However, there's a huge problem with that. It's an intro class, and proficiency
with these practical tools isn't a prerequisite. So, I want to help you out.

* Instead of struggling with logging into the SEASnet servers, I want you to
  struggle with the tricky bitwise data lab.
* Instead of struggling with editing a text file via a command-line editor, I
  want you to struggle with `segfaulting` cuz you fucked up something with
  pointers (again) (haha) (oof...).
* Instead of struggling with what gdb syntax, I want you to struggle with the
  theory of gdb.
* Instead of being blocked by some inane error preventing you from doing useful
  work, I want you to struggle with the theory of what code to optimize an why.

**I want to remove blockers, so you can learn the pure beauty of Computer Science
without being distracted by those annoying things we call "computers".**

> Computer science is not about machines, in the same way that astronomy is not
> about telescopes
*Michael R. Fellows*

This document is advice, 3 basic tutorials, and a collection of manuals. I want
it to be a useful resource on how to set up and operate a telescope for CS 33,
so you can enjoy the big beautiful universe out there.

## How will this help you succeed in CS 33

I will remove blockers by acquainting you with the 3 systems that you need to
know about in order to succeed in this class.

### How will I remove blockers?
You can't just walk up and *do* whatever task you want to do. You need to:
1. learn how each tool is *supposed* to be used
2. learn how to *actually* use said tool

If you just dive in and start using any one of these tools, it'll work fine.
You'll learn, and you'll be able to succeed in CS 33. But if you take the time
to understand *why* bash differentiates between single quotes and double quotes,
*why* gdb keeps printing stuff like `$1 =` or `$2 =`, then you'll succeed AND
enjoy it.


That means that we have to learn about `shell`, `debuggers`, and `text editors`
before we learn about `bash`, `gdb`, and `vim`.


### Why learn about the system when we can learn about the tool?
`bash`, `gdb`, and `vim` are all professional tools. What does that mean? It
means that they're like Photoshop. Like Unity. Like a referee's uniform. Like a
table saw. Like a fire hydrant. Anyone can look at them, and probably even
immediately "use" them. But it's not advisable. And you won't make
[this](https://i.somethingawful.com/inserts/articlepics/photoshop/12-29-06-anime/3toes.jpg "Photoshop")
or [this](https://akirassasin.itch.io/ashes-to-ashes?ac=jXdAbFQF "Unity") or
[this](https://thumbs.dreamstime.com/z/wooden-table-white-background-isolated-61386284.jpg
"table saw") without being trained, first.

### How

### What
Familiarity with 3 systems will remove blockers
1. How to navigate a computer by using a command-line interface instead of a
   mouse. [Why this is useful](#shell)
   * You'll learn about [`bash`](#bash), specifically.
2. How to use a program that gives you visibility into an executing program.
   [Why is this useful?](#debugger)
   * You'll learn about [`gdb`](#gdb), specifically.
3. A way to edit source code starting from a command-line [Why is this
   useful?](#command-line-text-editor)
   * You'll learn about [`vim`](#vim), specifically.

### Shell
TODO why is shell important
### Debugger
TODO why is debugger important
### Command Line text editor
TODO why is command line text editor important

## What
### bash
### gdb
### vim



that're helpful to know before taking CS 33 that
are unfortunately not taught in any class.

the point of CS 33 is not to learn shell and gdb, yet basic knowledge
of each of those is necessary in order to succeed.

This document is intended to serve as a manual (not a reference) in order to
help you get past the frazzling parts with minimum `frazz`.

* You can always count on Americans to do the right thing - after they've tried
  everything else.

## What
* shell
* gdb
* vim

# ##############################################################################
You must use at least 3 very complex tools, but teaching them properly would be
way out of scope

TODO - put Winston Churchill quotes in this bitch
* If you're going through hell, keep going.
* Keep calm and carry on.
* Success is not final, failure is not fatal: it is the courage to continue that
  counts.
* You will never reach your destination if you stop and throw stones at every
  dog that barks.
* Diplomacy is the art of telling people to go to hell in such a way that they
  ask for directions.
* Success consists of going from failure to failure without loss of enthusiasm.
* A pessimist sees the difficulty in every opportunity; an optimist sees the
  opportunity in every difficulty.
* It is better to do something than to do nothing while waiting to do
  everything.
* One ought never to turn one's back on a threatened danger and try to run away
  from it. If you do that, you will double the danger. But if you meet it
  promptly and without flinching, you will reduce the danger by half. Never run
  away from anything. Never!
* All the great things are simple, and many can be expressed in a single word:
  freedom, justice, honor, duty, mercy, hope.
* If two people agree on everything, one of them is unnecessary.
* He who fails to plan is planning to fail.
* The main vice of capitalism is the uneven distribution of prosperity. The main
  vice of socialism is the even distribution of misery.


# ################################ Rough draft #################################
In-depth vim manual: http://vimdoc.sourceforge.net/htmldoc/usr_toc.html

This one actually comes *with* vim, if you type in `:help usr_01.txt`. It's the
official manual, and it covers what you need to know in what I think is a pretty
cohesive order. Every other manual will leave you with more knowledge gaps than
this one will - however, knowledge gaps aren't that huge of a deal, and this one
is a lil long.  Lighter manual: (45 minute read)
https://danielmiessler.com/study/vim/

This one gives arguably the same amount of knowledge per minute - but that's
because it teaches all the easiest stuff first. To learn more from here, you'll
need to read the user manual anyway. But this is for sure good enough to get
everything done that you need.  As with every computer system, vim can feel
quite black-boxy at times. There are ways to expose internal vim states to the
outside world. To me, there's nothing better to do to learn a complex system
than to have a constant visual reminder of what's going on. Once you've spent
about 10 minutes reading one of the manuals, you'll know exactly what
information you find yourself constantly wishing you had (What mode am I in,
what command am I in the middle of typing, what line number am I on, etc.). When
you're at that point, talk to me and I'll tell you some ~magic words~ (if you
don't know them already) that give you what you want.

The reason this information is disabled by default is twofold. 1) historically,
vim didn't have to power to display such info easily and 2) no one likes being
barraged with an overwhelming amount of information, it makes learning slower.
It's better to start with a blank slate and deliberately enable things one by
one GDB reference: https://ftp.gnu.org/old-gnu/Manuals/gdb/html_mono/gdb.html

I'm nowhere near as good at gdb as I am at vim, and I also don't find it as fun
or exciting. That being said, it's pretty powerful and badass in the hands of
someone that knows what they're doing. Effectively learning GDB requires
satisfying many more prerequisites (basics of how source gets compiled, basics
of how computers execute programs - 1/3rd of CS 33) than vim does (basic shell
commands - 15 minutes).

So don't be discouraged if you don't know what the heck gdb is doing upon first
look. I had no fking clue what was happening in gdb when I first learned about
it. You'll probably have to log into the SEASnet servers, so that you can
execute commands on their machines.

(This makes distributing liscenced software easier for the school. Also, it
makes grading easier, as everyone has the same ~shell environment~, meaning that
there won't be any student unknowingly using "gdb v7.4" and running into weird
bugs when they should be running "gdb v8.1")

It's called a shell because you're not actually interacting with the core of the
computer. You're simply typing in pseudo-English, and a program that's a
wrapper-to-the-core is intercepting and interpreting these commands, then doing
whatever you asked it to do. This is useful, because you can swap out the core
(say, upgrade your operating system, or even move to a whole new computer) and
your pseudo-English still works. You're not interacting with the fragile,
error-prone, low-level parts of a machine, but a hard, robust, and portable
wrapper around it. You can probably see why the analogy "shell" works pretty
well here.

Here's a 5 minute read that'll give you most of what you will care about in CS
33:
