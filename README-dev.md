*ubuntu (or other GNU/Linux)
============================

Setup
-----

1. Install packages:

    ```
    sudo apt-get install ruby-full build-essential zlib1g-dev
    sudo apt install ruby-bundler
    ```

1. Add this to .bashrc config:

    ```
    export GEM_HOME="$HOME/gems"
    export PATH="$HOME/gems/bin:$PATH"
    ```

1. Install jekyll:    
    ```
    gem install jekyll
    ```

1. From repo:

    ```
    bundle install
    ```
    
Serve locally
-------------

* Run this command from the repository:
```
./serve_locally.sh
```
* Open http://127.0.0.1:4000/ in your browser.

Windows
=======
Setup
-----
Follow the instructions here: https://jekyllrb.com/docs/installation/windows/

Serve locally
-------------
* Double-click on **serve_locally.bat**
* Open http://127.0.0.1:4000/ in your browser.

Markdown editors
================
* https://wereturtle.github.io/ghostwriter/ (for Windows)
* https://github.com/ondratu/formiko (available in *ubuntu repositories)
