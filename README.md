#  MGageMorgan's monaco-port
The next version of Monaco, fixed up and pretty-fied for use on MediaWiki, thanks to yours truly.

(Undoctored Community, sorry)

![alt-text](https://github.com/MGageMorgan/monaco-port/blob/master/screenshots/latest.png?raw=true 2)

## Known Bugs/Issues
There is one open issue pertaining the Community. The login link (I believe) is still broken. This message will be removed once I fix it.

## Bugfixes for MediaWiki 1.25
I fixed some of the bugs but not all. The biggest were in the sidebar class and naturally the skin class. Deprecation is horrible. But, I fixed what I could. ALSO, UseCommunity in skin.json is now able to be used rather than monaco.php. 

## New (Original) Feature
In response to not really wanting to fix a bug but provide a nicer-looking, uncluttered solution, all your user links are out of the way. They can be found by hovering on that pretty blue button (literally) with your name on it in the top left. I've re-formatted them to look a bit more modern than the MonoBook/Vector ones are (and I don't want to hear it from those who don't like some of the more "modern" design, if you want the old stuff, you can not-so-easily re-implement it yourself).

## Sidebar Improvements!!!
I've been nice and have gone from implementing my own version of SW's Community Widget to fixing the search bar to look like theirs as well as implementing code from their extension "NewsBox" right into the skin itself. Have a look!

![alt-text](https://github.com/MGageMorgan/monaco-port/blob/master/screenshots/sidebar-new.png?raw=true 2)

## Community Widget Re-Implementation
I have implemented a ShoutWiki-style (close, but not exact) Community box. Install instructions are available when the skin is first added to MediaWiki. They will be in a sidebox widget with no title.

### Community Widget Screenshots
![alt-text](https://github.com/MGageMorgan/monaco-port/blob/master/screenshots/Screenshot%20from%202016-07-08%2021-01-22.png?raw=true 2)
![alt-text](https://github.com/MGageMorgan/monaco-port/blob/master/screenshots/Screenshot%20from%202016-07-08%2021-03-05.png?raw=true 4)`

**Running in Chromium on Ubuntu 16.04 localhost

## Installation
This section details how to install depending on what/which version of MediaWiki you plan to install Monaco to.

### MediaWiki's wfLoadSkin (MediaWiki >= 1.25.0)
I've brought Monaco up-to-speed on the latest with the new installation method. The new way to install Monaco is:

```php
wfLoadSkin( 'monaco' );
```

### For Older MediaWiki Installations (MediaWiki <= 1.24.0)
If you are running Mediawiki >= 1.25.0, the above subsection applies to you. Everyone else (MediaWiki <= 1.24.0) can install the original way:

```php
require_once("$IP/skins/monaco/monaco.php");
```
## Screenshots
Zoomed-out images of the skin itself:
![alt-text](https://github.com/MGageMorgan/monaco-port/blob/master/screenshots/shot1.png?raw=true 1)
![alt-text](https://github.com/MGageMorgan/monaco-port/blob/master/screenshots/shot2.png?raw=true 3)

