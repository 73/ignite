# IGNITE (the fox)

*Ignite (the fox)* is a script for gnome-shell that will open a new Firefox window if there is no Firefox window on the current workspace.
If there is a Firefox window on the current desktop, it will be activated and clicked links will open new tabs in this instance.
I use workspaces a lot.
When I click a link form an email I sometimes jump to another workspace, because this is where the last active Firefox instance has its window.
This is *so annoying*.
*Ignite (the fox)* is the fix.

There is a simple test for you where you need *ignite* of not:
1. Open your mail client with an email that contains a link you can click
2. Open a Firefox window
3. Switch the workspace and open another Firefox window
4. Switch back to the prior workspace *without* activating the Firefox window and click the link

If you feel anger and confusion now, you need *ignite*.


## INSTALL
This procedure aims at Ubuntu 18.10.
It may work for other distributions and desktop environments, but that is not tested.

1. Install requirements: `sudo apt install wmctrl`
2. Put the ignite script into your `$PATH` [^1]. `/$HOME/.local/bin` or  `$HOME/bin` sound like a good ideas.
3. `cp ignite.desktop ~/.local/share/applications`.
4. Set it to be your default browser: `xdg-settings set default-web-browser ignite.desktop`
5. Sanity


[^1]: https://wiki.archlinux.org/index.php/environment_variables
