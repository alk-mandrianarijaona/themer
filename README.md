# `themer`

Your theme's unique URL:

https://themer.dev/?colors.dark.shade0=%23343637&colors.dark.shade1=%23495A64&colors.dark.shade2=%23556873&colors.dark.shade3=%238fabbd&colors.dark.shade4=%23899BA6&colors.dark.shade5=%23A7B8C2&colors.dark.shade6=%23cae2f2&colors.dark.shade7=%23f2f2f2&colors.dark.accent0=%23e66565&colors.dark.accent1=%23F2C38F&colors.dark.accent2=%23fffa70&colors.dark.accent3=%2392dd69&colors.dark.accent4=%237FC1CA&colors.dark.accent5=%2383AFE5&colors.dark.accent6=%23ff944d&colors.dark.accent7=%23ff8ab3&activeColorSet=dark&calculateIntermediaryShades.dark=false&calculateIntermediaryShades.light=true

If you find `themer` useful, here are some ways to support the project:

* Star [`themer` on GitHub](https://github.com/mjswensen/themer)
* Follow [@themerdev](https://twitter.com/themerdev) on Twitter
* [Send a tip through the Brave Browser](https://brave.com/the537), either on [the repository page](https://github.com/mjswensen/themer) or [the Web UI](https://themer.dev)
* Pay what you want when downloading your theme from [themer.dev](https://themer.dev)

# Installation instructions

## Chrome

1. Launch Chrome and go to `chrome://extensions`.
2. Check the "Developer mode" checkbox at the top.
3. Click the "Load unpacked extension..." button and choose the desired theme directory (`Chrome/Themer Dark`).

(To reset or remove the theme, visit `chrome://settings` and click "Reset to Default" in the "Appearance" section.)

## iTerm

1. Launch iTerm
2. Press `command`-`I` to open the iTerm preferences
3. Choose Colors > Color Presets... > Import... and choose the generated theme file (`iTerm/themer-iterm-dark.itermcolors`)

## Slack sidebar

Copy the contents of `Slack sidebar/themer-slack-dark.txt` and paste into the custom theme input in Slack's preferences.

## Vim

Copy or symlink `Vim/ThemerVim.vim` to `~/.vim/colors/`.

Then set the colorscheme in `.vimrc`:

    " The background option must be set before running this command.
    colo ThemerVim

## VS Code

Copy (or symlink) the generated package directory into the VS Code extensions directory:

    cp -R 'VS Code/theme-themer-vscode' ~/.vscode/extensions/

Then reload or restart VS Code. The generated theme package should be in the list of installed extensions, and "Themer Dark" will be available in the list of themes.