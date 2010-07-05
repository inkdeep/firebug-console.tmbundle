# Textmate bundle for Firebug Console

## Features

Snippets for inserting console API commands into JavaScript code.

Documentation of the console API commands. Original content here: http://getfirebug.com/wiki/index.php/Console_API

Documentation of console.table() command. Original article here: http://www.softwareishard.com/blog/firebug/tabular-logs-in-firebug/

## Installation

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/inkdeep/firebug-console.tmbundle.git "Firebug Console.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'
    

To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/inkdeep/firebug-console.tmbundle/tarball/master
    tar zxf inkdeep-firebug-console.tmbundle*.tar.gz
    rm inkdeep-firebug-console.tmbundle*.tar.gz
    mv inkdeep-firebug-console.tmbundle* "Firebug Console.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'