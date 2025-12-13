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

Website editing
===============
Create new pages
----------------
Create a new .html or .md file under **_pages**, with the following minimal YAML header:
```
---
---
```

If the YAML header is empty, it will appear under:
- **_pages/FILENAME**, if the file was named **FILENAME.md** or **FILENAME.html**
- **_pages/SUBDIR/FILENAME**, if the file was named **FILENAME.md** or **FILENAME.html** and placed in **SUBDIR**

Edit menu
---------
_data/navigation.yml

Add sidebar menu
----------------

TODO
====
* https://stackoverflow.com/questions/17207458/how-to-add-google-analytics-tracking-id-to-github-pages
* Fix warning: 
    The github-pages gem can't satisfy your Gemfile's dependencies. If you want to use a different Jekyll version or need additional dependencies, consider building Jekyll site with GitHub Actions: https://jekyllrb.com/docs/continuous-integration/github-actions/
* Update published arxiv papers (cf news page).
* Doc for PCs without admin rights.
* Fix any errors/warning in logs.
* image slideshows and other fancy features?
