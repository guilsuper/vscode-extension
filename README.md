# IntelliSense for CSS class names

A Visual Studio Code extension that provides CSS class name completion for the HTML `class` attribute based on the CSS class definitions that can be found in your workspace or in external files referenced through the `link` element.

![](https://i.imgur.com/5crMfTj.gif)

## Features
* Gives you autocompletion for CSS class definitions that can be found in your workspace (defined in CSS files or the in types listed in the Supported Language Modes section)
* Supports external stylesheets referenced through `link` elements in HTML files
* Command to manually re-cache the class definitions used in the autocompletion

## Supported Language Modes
* HTML
* Razor
* PHP
* JavaScript
* JavaScript React (.jsx)
* TypeScript React (.tsx)
* Vue (.vue) [requires [octref.vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)]
* Twig
* Markdown (.md)
* Embedded Ruby (.html.erb) [requires [rebornix.Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)]
* Handlebars
* EJS (.ejs)

## Contributions
You can request new features and/or contribute to the extension development on its [repository on GitHub](https://github.com/Zignd/HTML-CSS-Class-Completion/issues). Look for an issue you're interested in working on, comment on it to let me know you're working on it and submit your pull request! :D

## What's new in version 1.11.0 (Out 14, 2017)
* Fix error that occurs when you try to get completion and the extension is loading.
* Add limitations to the concurrency in resource-intensive operations.
* Add progress indicator, useful for large projects.
* The `node_modules` will not be ignored. With those changes, it seems that there's no need to ignore it.

Check out the [change log](https://github.com/zignd/HTML-CSS-Class-Completion/blob/master/CHANGELOG.md) for the current and previous updates.

## Usage
If there are HTML files on your workspace the extension automatically starts and look for CSS class definitions. In case new CSS classes are definined or new CSS files are added to the workspace and you also want auto completion for them simply hit the lightning icon you will find on the status bar and execute the command pressing `Ctrl+Shift+P` and then typing "Cache CSS class definitions".

![](https://i.imgur.com/O7NjEUW.gif)
![](https://i.imgur.com/uyiXqMb.gif)
