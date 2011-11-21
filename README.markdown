## OVERVIEW
i3tree is a program I wrote to help myself adjust to version 4 of the i3 tiling window manager. It displays the containers your windows are children of and what layout those containers are using.

## INSTALLATION
i3tree requires an installation of the i3 window manager, perl, and the following two perl modules.

  * AnyEvent::I3
  * X11::Protocol

## USAGE
Just run it.

## EXAMPLES

    $  i3tree
    Workspace 1 (horizontal)
            Window foo@bar: ~
            Split (vertical)
                    Window foo@bar: ~
                    Window foo@bar: ~
    Workspace 2 (vertical)
            Window foo@bar: ~
            Window foo@bar: ~

## LIMITATIONS
You have to start i3tree from a running terminal. It would be neat if i3tree could be invoked from a keyboard shortcut and draw to a floating window.

i3tree shows containers from all workspaces. It could be useful to optionally limit this to only the current workspace.

## THANKS
Thanks to everyone who has contributed to i3.
