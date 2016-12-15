Debian & Ubuntu Installation instructions
=========================================

First we need to install Ruby:

$ sudo apt-get install ruby-full

Next, we need to install Jekyll:

$ sudo apt-get install jekyll

Next we need to create a directory, and clone the git repository there:

$ mkdir websites
$ cd websites
$ git clone https://github.com/RossGammon/the-gammons.net.git

To build the site locally and run a test server:

$ cd the-gammons.net
$ jekyll serve --watch

With the "--watch" option, you can update files and hit "refresh" in
your browser to immediately see the changes.

To check all links and images, and html syntax, you can use html-proofer
locally. This is already set up on Travis CI, and the test will run for
every push to the git repository on Github. But you can also do it
locally. To install it:

$ gem install html-proofer
# Note, I hope to package this for Debian eventually.

To test, first build the site and then run html-proofer on the "_site"
directory:

$ jekyll build
$ htmlproofer ./_site
