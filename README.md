# Unshittify Discord

A CSS Discord theme that keeps the modern design while fixing most of its mistakes.

- [Installation](#installation)
- [Use to Create Other Themes](#use-to-create-other-themes)
- [Features](#features)
- [Known Issues](#known-issues)
- [License](#license)

---

## Installation

### Option 1: Online Themes (Auto Update)

Add the following line to your "Online Themes" imports:

```css
@import url("https://nak.kiwi/unshittify-discord/UnShittifySource.theme.css");
```

And the following for rounded icons:

```css
@import url("https://nak.kiwi/unshittify-discord/RoundIconsSource.theme.css");
```

### Option 2: Download Importer (Auto Update)

Download [UnShittify.theme.css](UnShittify.theme.css) or [UnShittifyRounded.theme.css](UnShittifyRounded.theme.css) and add it to your themes folder.

You can also find it on ~~[BetterDiscord](https://betterdiscord.app/theme/TODO)~~ (Waiting for verification)

### Option 3: Download Source (No Automatic Updates)

Download the raw CSS files:

- [UnShittifySource.theme.css](UnShittifySource.theme.css)
- [RoundIconsSource.theme.css](RoundIconsSource.theme.css)

And place them in your themes folder.

---

## Use to Create Other Themes

Simply add this CSS at the top of your file:

```css
@import url("https://nak.kiwi/unshittify-discord/UnShittifySource.theme.css");
```

Optionally, you can also include rounded icons:

```css
@import url("https://nak.kiwi/unshittify-discord/RoundIconsSource.theme.css");
```

---

## Features

- Removed top bar and left it floating. A drag icon was added so the window can still be moved.

  ![Floating top bar](https://github.com/user-attachments/assets/f4c1a894-f3a5-4aab-979f-4332281d2d0c)

- Adapted profile container to fit neatly under the rest of the users.

  ![Profile container fix](https://github.com/user-attachments/assets/b2e3b66d-2309-4e1a-88f4-f27d1cd4824f)

- Aligned chat input field.

  ![Aligned chat input](https://github.com/user-attachments/assets/0ba33866-efe2-4a15-adf4-50206a51a26c)

- Optional round server and folder icons.

  ![Rounded icons](https://github.com/user-attachments/assets/4e9a29c4-dd55-4dbd-9cbf-8620338908b0)

---

## Known Issues

- The drag icon may fail to register events at some window sizes.

---

## Contributing

As long as you run the code through Prettier and use tabs instead of spaces, you're good to go. 😄

---

## License

See [LICENSE.md](LICENSE.md)
