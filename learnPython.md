THINGS I WISH I KNEW WHEN I STARTED
===================================
- python 2.7 vs 3
    - I'm sure you've already seen this and if you haven't figured it out, 
    it's kind of a pain in the ass sometimes.
    - There be two versions of python that are currently supported, 2.x and 3.x.
    - 2.x has been around for a long time and is widely supported, 3.x has not
    and is not.
    - 3.x is the future and everyone, whether the like it or, not is moving
    there. It is just taking a really long time, but that was expected.
    - The reason for this is, in the beginning Python didn't so some things
    the way they should have...so they kept supporting them for backwards
    compatibility, but eventually realized it wasn't worth it so they changed
    the language and removed the crappy stuff and fixed it with 3.x.  They knew
    what they were doing and that it would take a long time for all the libraries
    to update to 3.x.  It was not a mistake, this was very much on purpose.
    - I learned on 2.7 which is the latest version that isn't 3.x.  It has
    almost all of the features of 3.x, but it's not 3.x...it's a little different.
    - The differences do not matter to you for the most part. They are all minor
    and really only matter to guys way smarter than us or guys who have been
    doing it a lot longer than us.
    - I wish I'd have started learning 3.x and then just changed stuff to be
    compatible with 2.x on an as needed basis.  Now I have to break my habits
    so that I can make sure my stuff is 3.x friendly.
    - A lot of libraries and tools (the bigger they are the more likely they
    aren't up to date yet), aren't on 3.x (but they will be eventually) so you
    may need to know 2.7 also...but it's minor stuff.  I think you'll be able
    to find help on the differences pretty easily.
    - Take what you will from that.
- pypi.python.org
    - This is the app store for python, it makes it easy to install packages
    for python. Anytime you see a new module or package you need or want to
    try.  It's probably here.
- pip
    - This is the apt-get for python, it makes it easy to install packages
    from pypi.
    - sudo apt-get install python-pip
    - Then you can just do
        - pip install package-name
- virtualenv & virtualenvwrapper
    - This makes it so you can install whatever packages you need and
    their specific versions for whatever project you're working on without
    worry about breaking all your other packages for other projects. Everyone
    uses it from beginners to the big guys on their production machines.
    - I've never used virtualenvwrapper cause I didn't know about it
    for a long time, but I hear it's great, it looks great...but it breaks
    my work flow since I started without it.  I'd like to start using it though.
- pep8
    - python.org/dev/peps/pep-0008/
    - Python style guide.  You'll see this mentioned everywhere so just be
    aware of it.  Everyone who isn't a jackass uses this as at least a guidline
    on how their code should be written.
    - There is probably a plug in in whatever text editor you're using to
    automatically highlight your non-compliance.  I use 'flake8' which combines
    pep8 (style checker) with pyFlakes (syntax/error checker) and I dig them.
- pep20 (zen)
    - python.org/dev/peps/pep-0020/
    - commonly known as the Zen of Python.
    - available in the interpreter by typing 'import this'
    - This, in whole or in part, is constantly referenced by people. It might not
    mean a lot to you now, but it will eventually...
- ipython
    - This is a drop-in replacement for the normal python interpreter, it is
    better and nicer.  Hard to explain why, but it is.  No need to use it
    just yet, but you'll see it mentioned a lot of places.
- reddit
    - /r/learnpython
    - /r/python
    - ##learnpython on freenode
    - They always seem pretty helpful here.  You can find me on irc quite a bit.
- projecteuler.net/
    - problems to solve for practice
- doc strings, tests, and comments
    - just write the damn things when you start
    - everyone said "practice doing it now so you don't suck at it later"
    - I didn't.
    - I suck at it now
- git
    - it's used everywhere and will make your life much easier.
    - even keeping your dumb, silly, bad projects in it is good, it makes it much
    easier to share stuff to ask for help and it also frees you to make more
    mistakes and to experiment more since you can commit as often as you want
    - git is a complex tool, but you only need to know little bit
        - when I grep my history these are 90% of my last 2000 commands
            - config, init, clone, status, add, rm, commit, push, pull, merge,
            .gitignore, branch, checkout
            - and 90% of that is just
                - git init or git clone, git add README, git commit -m "add readme",
                git push remoteName
    - github is also just great to go look at other peoples code and read it
    - git-scm.com/book
        - this is the most thorough way to learn git.
    - try.github.io
        - free and you'll learn the basics


RESOURCES
=============

- learnpythonthehardway.org/
    - This is where I started.  It is good, highly recommended by everyone,
    including me.  Starts pretty basic and doesn't get too complex, however,
    it doesn't get too in depth on some concepts either.
- codecademy.com/
    - I did this second, but it might be better first.  This doesn't teach you
    much, if any, higher level stuff at all, almost entirely sytax, but it's
    solid at syntax and you can get through it pretty quickly. This is mostly
    just fun, like all of their stuff is.
- edx
    - MIT 6.00 I just started this and it seems like it would be a pretty good
    intro, however, it's an intro to CS and not to python.  Python is just the
    language they've chosen to use for the class.
    - Harvard CS50 supposed to be good too and I'm probably gonna watch it after
    MIT 6.00.
- Various videos
    - pyvideo.org/speaker/138/raymond-hettinger
        - This guy is great.  He's a core dev for python, a lot of this language
        happened because of this guy.  He's a lot of fun.
        - pyvideo.org/video/1669/keynote-3
            - This video is about what makes Python awesome (his words, not
            mine). It does get into a lot of what sets Python apart from other
            languages and things you might want to think about.
