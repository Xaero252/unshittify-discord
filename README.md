# UnShittify Discord
By [@nak.kiwi](https://instagram.com/nak.kiwi) (You can call me Nakki, feel free visit wy cozy website at nak.kiwi) :3

A personal project to fix the design mistakes and disalignments in the Discord app.
If it's unreadable, it's by design, I didn't want you to steal my secret sauce.

**Disclaimer:** This is a discord unoficcial theme, it is not affiliated with Discord in any way.
If you are discord and wish for this to be taken down, please message me at hello@nak.kiwi

- [Installation](#installation)
- [Use to Create Other Themes](#use-to-create-other-themes)
- [Features](#features)
- [Known Issues](#known-issues)
- [License](#license)

![image](https://github.com/user-attachments/assets/f47c80f4-8a5f-468d-9c43-3c41c501dd79)

---

## Installation (Vencord/BetterDiscord/Browser)

### Option 1: Download Importer (Auto Update)

Download [UnShittify.theme.css](UnShittify.theme.css) or [UnShittifyRounded.theme.css](UnShittifyRounded.theme.css) and add it to your themes folder.

You can also find it on ~~[BetterDiscord](https://betterdiscord.app/theme/TODO)~~ (Waiting for verification)

> You won't need both themes for rounded icons.

### Option 2: Online Themes (Auto Update)

Add the following line to your "Online Themes" imports:

```css
@import url("https://mairiosipla.github.io/unshittify-discord/UnShittifySource.theme.css");
```

And the following for rounded icons:

```css
@import url("https://mairiosipla.github.io/unshittify-discord/RoundIconsSource.theme.css");
```

> [!NOTE]  
> You'll need both themes for rounded icons.

### Option 3 (For Bowsers using UserCSS extensions)

Check out [https://userstyles.world/style/21817](https://userstyles.world/style/21817)

### Option 4: Download Source (No Automatic Updates)

Download the raw CSS files:

- [UnShittifySource.theme.css](https://mairiosipla.github.io/unshittify-discord/UnShittifySource.theme.css)
- [RoundIconsSource.theme.css](https://mairiosipla.github.io/unshittify-discord/RoundIconsSource.theme.css)

And place them in your themes folder.

> [!NOTE]  
> You'll need both themes for rounded icons.

---

## Use to Create Other Themes

Simply add this CSS at the top of your file:

```css
@import url("https://mairiosipla.github.io/unshittify-discord/UnShittifySource.theme.css");
```

Optionally, you can also include rounded icons:

```css
@import url("https://mairiosipla.github.io/unshittify-discord/RoundIconsSource.theme.css");
```
> [!NOTE]  
> You'll need both themes for rounded icons.

---

## Features

- Removed top bar and left it floating. The window can still be moved by nearing the mouse to the top of the window.

  ![image](https://github.com/user-attachments/assets/56cdf602-d1b7-48d6-9684-807799b73af4)


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
Just open a pull request.

---

## License

See [LICENSE.md](LICENSE.md)
