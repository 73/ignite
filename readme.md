# IGNITE (the fox)

> You are running a beautiful GNOME Desktop.
> You click on a hyperlink within your notepad and a notification pops up, telling you that the link you wanted open, is now opened ... somewhere.
> You click on the notification and suddenly you move an unknown amount of workspaces without any clou how to get back to the place you just worked at.

If this drives you mad, *ignite (the fox)* is for you.
It is a workaround, which opens a Firefox windows on the current workspace, if there is none.
If a Firefox window exists on the current workspace, it will be activated and clicked links will open new tabs in that window.


## REQUIREMENTS
Ignite is tested on Debian Stable (Bookworm).
It needs [Windows Calls](https://github.com/ickyicky/window-calls) and `jq` installed.


## INSTALL
It may work for other distributions and desktop environments, but that is not tested.

1. Put the `ignite` script into your `$PATH`.
   `/$HOME/.local/bin` or  `$HOME/bin` seem like sane choices.
2. Copy the launcher `cp ignite.desktop ~/.local/share/applications`.
3. Set it to be your default browser: `xdg-settings set default-web-browser ignite.desktop`
4. Sanity


Did you know there is a [GNOME Theme for Firefox](https://github.com/rafaelmardojai/firefox-gnome-theme)?

