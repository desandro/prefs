# Prefs

_Personal preferences._ I use this list when I get a new computer.

## Applications

+ DragonDrop
+ [GitX-dev](https://rowanj.github.io/gitx/)
+ [Grand Perspective](http://grandperspectiv.sourceforge.net/)
+ [iTerm2](https://www.iterm2.com/)
+ [Quicksilver](http://qsapp.com/)
+ [TextMate 2](http://macromates.com/)

## System Preferences

**Keyboard**

+ **Keyboard > Modifier Keys >** Caps Lock Key: ^ Control
+ **Keyboard > Shortcuts > Keyboard >** Full Keyboard Access: All controls
+ **Keyboard > Text >** Disable Correct spelling automatically and Capitalize words automatically
+ **Keyboard > Shortcuts > Mission Control** Change _Move left a space_ to `Ctrl + Cmd + Left`, and likewise for right. Resolves conflict with moving by word in Textmate

**Accessibility > Zoom >** Disable _Smooth images_

Disabling pasting with style (via [mmdei on metafilter](http://ask.metafilter.com/187733/OSX-How-to-copy-plaintext-always-everywhere-without-exception#2702700))

+ Go to **Keyboard > Keyboard Shortcuts > App Shortcuts >**
+ Click **+** below right listbox
+ Select **All Applications** for 'Application' input box
+ Type **Paste and Match Style** into the 'Menu Title' input box
+ In the 'Keyboard Shortcut' input box, pretend that you are about to paste something by typing command-v. There should now be the cloverleaf command sign followed by a -v in this box.

### Sharing

Rename machine to something short, yet awe-inspring.

## Windex

Install [Windex](https://github.com/desandro/windex) and viewing `~/projects` as `localhost`.

Add no extension redirects for `.html`

```
RewriteEngine on
RewriteCond %{REQUEST_FILENAME} !-d
RewriteCond %{REQUEST_FILENAME}\.html -f
RewriteRule ^(.*)$ $1.html
```

## Dotfiles

Install [dotfiles](https://github.com/desandro/dotfiles)

## Node

+ Install [nvm](https://github.com/creationix/nvm)
+ Create `~/.nvmrc` with latest stable version

## TextMate

Install my **Sunset DD** theme

**TextMate > Preferences > Bundles >** Enable:

+ Markdown (GitHub)
+ Mustache

Install

+ [savetheclocktower/javascript.tmbundle](https://github.com/savetheclocktower/javascript.tmbundle/tree/overhaul). See [javascript.tmbundle issue #63](https://github.com/textmate/javascript.tmbundle/pull/63). Disable/remove default JavaScript bundle before installing this one.
+ [javascript-eslint.tmbundle](https://github.com/natesilva/javascript-eslint.tmbundle). Add location of `which node` to **Preferences > Variables**. In JavaScript ESLint bundle editor, disable _Save & Validate_. Change key commands for _Validate with ESLint_ and _Automatically Fix Problems_ to `Cmd + K` and `Shift + Cmd + K`.

Disable un-used bundles

Remove Baskerville serif font family in Markdown. Go to **Bundles > Edit Bundles... > Themes > Settings**. Remove `fontName` setting.

Enable _Remove trailing whitespace_ key command. Go to **Bundles > Edit Bundles.. > Text > Converting / Striping > Remove Trailing Spaces in Document / Selection**. Set Key Equivalent

## Everything else

+ **Safari > Preferences > Advanced** Enable _Show Develop menu in menu bar_
+ Install [ievms](https://github.com/xdissent/ievms) for IE & Edge in virtual machines
