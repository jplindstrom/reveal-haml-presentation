reveal-haml-presentation
========================

Template for creating reveal.js presentations with Haml markup.

## Installation

* Install Ruby
* Install Haml
    sudo gem install haml
    sudo gem install redcarpet
    # possibly others


* Clone the project

    git clone git@github.com:jplindstrom/reveal-haml-presentation.git
    cd reveal-haml-presentation/

## Write Presentation

* Start the auto-builder

    ./watch.pl --run=./haml-file.pl *.haml

* Edit index.haml (or copy to another name), open the .html file in a browser.
    * The watcher will rebuild the .html files on change

* Write a kick-ass presentation!



