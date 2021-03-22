# Configuring a Mac

## Dotfiles
macOS is a Unix-based and uses a Unix-terminal. In a Unix-like enviroment files that start with a `.` are automatically hidden. (Commonly referred to as dotfiles) To make them visible in Finder, simply toggle the visibility setting by pressing <kbd>Command ⌘</kbd> + <kbd>Shift ⇧</kbd> + <kbd>.</kbd> on your keyboard.

## Software
### IDE
* [Xcode](https://developer.apple.com/xcode/) (Install from [App Store](https://apps.apple.com/us/app/xcode/id497799835?mt=12))
* [Eclipse](https://www.eclipse.org/eclipseide/)
* [Microsoft Visual Studio](https://code.visualstudio.com/)

Xcode is very intertwined into programming on a mac and won't be avoidable in some cases. It's also an 11.6GB download, so if you're limited on space you may not want to install it at all. It can take a while to download so if you have the space, it might be worth getting it out of the way.

The **Xcode Command Line Tools** are the most likely reason you will need Xcode if you aren't using it as an IDE. Running this command in terminal should install those features without actually downloading Xcode.

```bash
xcode-select --install
```

### Optional
* [Homebrew](https://brew.sh/)
* [iTerm2](https://iterm2.com/)
* [Git](http://git-scm.com/download/mac)
* [GitHub Desktop](https:///mac.github.com/) (GUI App) 
* [Sublime Text](https://www.sublimetext.com/)
* [Atom](https://atom.io/)
* [Docker](https://www.docker.com/)


## Smart Quotes
Apple devices use “smart quotes” (or curly quotes) and “smart dashes” by default. They are generally considered easier for reading purposes, but for developers writing code, smart quotes can cause a few problems. There are two options to avoid encountering these problems. You can exclusively use text editors or IDE's that do not convert your quotes, or you can disable them system-wide.

### Disable Smart Quotes System-Wide
#### macOS
* Go to **System Preferences** > **Keyboard** > **Text**
* Then unchecking “*Use smart quotes and dashes*.”

#### iOS
* Go to **Settings** > **General** > **Keyboard**
* Then toggle off “*Smart Punctuation*.”
