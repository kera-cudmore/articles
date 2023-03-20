# VSCode Fonts & Ligatures

![VSCode Fonts & Ligatures Banner Image](https://user-images.githubusercontent.com/92253071/223649697-850db066-b5ed-417a-81e3-ae3ce9db5282.png)

You may already know that you can change the theme in VSCode, but did you know you can also change the fonts and add ligatures!

There are a number of fonts out there aimed at programmers, some look pretty cool and others claim to prevent eye strain while reading all those lines of code, so how do you change the font in VSCode? And what is a ligature?

## How to Change Your Font

1. Download and unzip your font.
2. Find the ttf file and install the fonts from here. On a mac you can just open the font with the font book and install from here. On windows, right click the file and choose install.
3. In VSCode, go to settings and search for font family.
4. From here you can choose where you would like to use your new font. There are a number of options that include the editor, the terminal, your markdown preview and more.  Note that a number of the other choices, such as the  terminal, use the editor font as their default font if no font is chosen.
5. Want to change the font size? Search in settings for font size and you can select a default font size to be used in your editor.

## What is a Ligature?

A ligature is a glyph that combines a sequence of characters into a new form that makes it more pleasant to the eye (remember, we're all about reducing eye strain).

Some fonts allow the use of ligatures, and they're pretty simple to enable - allowing you to create fat arrows and triple equals just like all the cool coders on Youtube 😂

![Example of Fira Code Ligatures](https://repository-images.githubusercontent.com/26500787/bf313080-6b02-11ea-9cd5-c3dca880736d)

### How to Enable Ligatures

1. In the command palette, search for your settings.json file.
2. Find the editor.fontLigatures key and change the value to true.
3. Save the file and you should be able to now use the ligatures. If they don't display, perform a refresh.

## Some Fonts to Try

All these fonts include ligatures. Some may have additional features, like italics or script versions of the font.

### Free Fonts

* [Cascadia Code](https://github.com/microsoft/cascadia-code)
* [Fira Code](https://github.com/tonsky/FiraCode)
* [Fixedsys Excelsior](https://github.com/kika/fixedsys)
* [Hasklig](https://github.com/i-tu/Hasklig)
* [Iosevka](https://typeof.net/Iosevka/)
* [Jetbrains Mono](https://github.com/JetBrains/JetBrainsMono)
* [Monoid](https://larsenwork.com/monoid/)
* [Victor Mono](https://rubjo.github.io/victor-mono/)

### Paid Fonts

* [Dank Mono](https://philpl.gumroad.com/l/dank-mono#:~:text=Phil%20Pluckthun,italic%20variant%20and%20bold%20style.)
* [Mona Lisa](https://www.monolisa.dev/)
* [Pragmata Pro](https://fsd.it/shop/fonts/pragmatapro/)


## Bonus: VSCode Profiles

Did you know that VSCode also has profiles? 

Profiles are a way to set up a custom workspace that can be easily switched as well as imported or exported - so for example you could have a profile that uses a specific theme and font for working with python, and then have another profile set up for PHP, or a profile for work and another for your personal projects.

You can find more information on profiles here: [VSCode Profiles](https://code.visualstudio.com/docs/editor/profiles)

Do you use custom fonts and ligatures in your IDE, or customised profiles? Share your favourite settings in the comments 😊