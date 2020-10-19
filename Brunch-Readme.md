To install, update and run the brunch toolkit FIRST:
- Open a crosh shell (ctrl + alt + t) and type shell at the prompt
- type: bash ~/Downloads/brunch-toolkit-v1.0.4b.sh (or or the filename of whichever version you'd downloaded)
- (Note that this feature does not work on versions earlier than 1.0.4b of the brunch-toolkit)
- Install the toolkit from the toolkit menu. This isn't a requirement, but it is suggested!
- run the toolkit again and select Shell Options, or run with the new option: brunch-toolkit --shell
- (you can also use: brunch-toolkit -s)
- Install shell tools from the toolkit menu. By default it includes a few useful commands

Now that the toolkit is installed and prepared, you can do the following to intall the extention:
- Unzip the file and move the directory inside somewhere safe so that it doesnt get deleted
- Go to: chrome://extensions/
- In the top right corner, toggle Developer Mode on
- Select "Load Unpacked" from the toolbar near the top
- Select the directory you unzipped earlier (Not the zip file)

Now any time the crosh shell is pulled up with Ctrl + Alt + t, it will automatically enter the shell and supply a toolbar with useful commands. the toolbar can be customized with the toolbox from the main menu after it's been installed once with --shell (or -s)
If the extentions folder is removed, the extention will crash. Simply remove it from the extentions page to restore the original Crosh shell.
