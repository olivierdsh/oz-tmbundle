# Sublime Text package/TextMate Bundle for the Oz programming language

Sublime Text package/TextMate Bundle to help developing with [Oz](http://www.mozart-oz.org/).

## TextMate Install(OSX)

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/eregon/oz-tmbundle.git Oz.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Sublime Text Install

### Linux

    cd ~/.config/sublime-text-2/Packages
    git clone git@github.com:olivierdsh/oz-tmbundle.git Oz.tmbundle

### OSX

    cd ~/Library/Application Support/Sublime Text 2/Packages
    git clone git@github.com:olivierdsh/oz-tmbundle.git Oz.tmbundle

You may need to restart Sublime Text for the changes to take effect

## Features

* Basic Grammar of the language
* Indentation
* Some Snippets (fun, if, if/else, local … in … end)
* Compile and execute scripts and output as html or text (⌘R, ⌘⇧R)
* Run functors from Sublime Text (Ctrl+b)

## Author

Benoit Daloze
