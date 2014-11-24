sublime-logstash-syntax-highlighter
===================================

Logstash DSL Syntax Highlighting for Sublime Text 3 (Might also work on ST2... but it wasn't tested).

Install using [Sublime Package Control](https://sublime.wbond.net/installation).
Just look for `Logstash Syntax`.

For the latest version, clone this repo and put the files from the `Syntaxes` dir in the packages/user dir in your ST config dir.

Will auto-recognize files named:

* logstash.conf
* logstash.conf.template
* logstash.conf.j2

Please let me know if you're using additional formats that should be added to the list.

See `example` dir for a logstash.conf file.

Make sure you follow [this](http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html) for development.

Also make sure you're using [AAAPackageDev](https://bitbucket.org/guillermooo/aaapackagedev) to convert JSON to tmLanguage files.

![Screenshot!](https://github.com/nir0s/sublime-logstash-syntax-highlighter/raw/master/scr.png)
