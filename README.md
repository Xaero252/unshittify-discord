# Unshittify Discord
A css discord theme to keep the modern design, while fixing mosto of its mistakes.

- ![Installation](#Installation)
- ![Use to create other themes](#Use-to-create-other-themes)
- ![Features](#Features)
- ![Known issues](#Known-issues)
- ![License](#License)

# Installation
## Option 1: Online themes (Auto update)
Add the following line to your 'online themes' imports.
```css
"https://nak.kiwi/unshittify-discord/UnShittifySource.theme.css");
```
And the following for rounded icons:
```css
"https://nak.kiwi/unshittify-discord/RoundIconsSource.theme.css");
```
## Option 2: Download importer (Auto update)
Download ![UnShittify.theme.css](UnShittify.theme.css) or ![UnShittifyRounded.theme.css](UnShittifyRounded.theme.css) and add it to your themes folder.
You can also find it on ~~https://betterdiscord.app/theme/TODO~~ (Waiting for verification)
## Option 3: Download source (No automatic updates)
![UnShittifySource.theme.css](UnShittifySource.theme.css) and/or ![RoundIconsSource.theme.css](RoundIconsSource.theme.css) css into your themes folder



# Use to create other themes
Simply add this css at the top of yor file:
```css
@import url("https://nak.kiwi/unshittify-discord/UnShittifySource.theme.css");
```
And add rounded icons

# Features
- Removed top bar and left it floating. Added drag icon, as the spot from which the window can be dragged.

![image](https://github.com/user-attachments/assets/f4c1a894-f3a5-4aab-979f-4332281d2d0c)

- Adapted profile container to fit under the rest of the users.

![image](https://github.com/user-attachments/assets/b2e3b66d-2309-4e1a-88f4-f27d1cd4824f)

- Aligned chat input.

![image](https://github.com/user-attachments/assets/0ba33866-efe2-4a15-adf4-50206a51a26c)


- Optional round server and folder icons.

![image](https://github.com/user-attachments/assets/4e9a29c4-dd55-4dbd-9cbf-8620338908b0)


# Known issues
- Drag icon fails to register events at some window sizes.

# Contributing
As long as you run the code trough prettier and use tabs and not spaces you'r fine. :D

# License
See ![LICENSE.md](LICENSE.md)


