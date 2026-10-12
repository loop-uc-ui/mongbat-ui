# mongbat-ui

A replacement interface for the Ultima Online Enhanced Client. It changes how
the game's windows look and work. It does not change the game itself, and you
can switch back to the default interface at any time.

## Beta

This is a beta release. Some things may be missing or may not work. The
default interface stays available from the **Custom UI** list on the login
screen, so you can switch back whenever you want. If you find a problem,
please report it on the
[issues page](https://github.com/loop-uc-ui/mongbat-ui/issues).

## What you get

- Hotbars, macros and an actions list.
- A paperdoll, a character sheet and saved equipment sets.
- Bags that show their contents as a grid or as a list, and an organizer.
- A map with your own waypoints and a search.
- Health bars, a party bar, a buff bar and a target window.
- Skills, spells, chat, shops and trading, in the same style.

## Install

You need the Ultima Online Enhanced Client. The Classic Client cannot load a
custom interface.

1. On the [releases page](https://github.com/loop-uc-ui/mongbat-ui/releases),
   open the newest release and download its zip file. The file is named
   after the release tag, for example `mongbat-ui-v1.0.0-beta.1.zip`.
2. Open the folder where the game is installed. On Windows it is usually
   `C:\Program Files (x86)\Electronic Arts\Ultima Online Enhanced`.
3. In that folder, open `UserInterface`. If there is no folder with that
   name, create it.
4. Unzip the download into `UserInterface`. You now have a folder named
   `UserInterface\mongbat-ui`. If the game is installed under
   `Program Files`, Windows may ask for administrator permission to copy the
   files.
5. Start the game. On the login screen, click **Custom UI**.
6. Under **Use Custom UI**, choose `mongbat-ui`, then click **Okay**.

## Update

Delete the folder `UserInterface\mongbat-ui`, then follow the install steps
with the newest release. Deleting the old folder first removes files that the
new release no longer uses.

## Remove

On the login screen, click **Custom UI** and choose **Default**. Then delete
the folder `UserInterface\mongbat-ui`.

## Problems

Report a problem on the
[issues page](https://github.com/loop-uc-ui/mongbat-ui/issues). Say:

- which release you installed,
- what you did, what you expected and what happened,
- a screenshot, if the problem can be seen.

The client writes a file named `logs/lua.log` in its install folder. Attach
that file to the issue as a file, by dragging it in. Do not paste it, because
it is UTF-16 text. Copy the file before you start the client again, because
the client rewrites it at every start. The line in it that holds `build=`
names the build.

## This repository

This repository holds the releases of mongbat-ui and its issues. The source
code is kept in another repository, which is not public.

## License

The UI in each release is under the [MIT License](LICENSE).
[NOTICE.md](NOTICE.md) says what the license does not cover: the icons, the
Inter font and material from the game client. No game files are included
here. To use this UI, you need your own installed copy of the client.

Ultima Online is a trademark of Electronic Arts Inc. This project is not
affiliated with, or endorsed by, Electronic Arts Inc. or Broadsword Online
Games.
