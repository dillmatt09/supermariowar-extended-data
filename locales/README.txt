Translations of the game's text, one TOML file per language, named after its language code.
Pick the language in Options > Graphics > Language.

en.toml lists every translatable text and is the template for a new language: copy it as
<code>.toml (for example nl.toml), fill in [meta] and translate the right-hand side of each
line. "{}" stands for a number. Missing lines stay in English.

[meta]
name = the language's name in itself (shown with the smooth font)
english_name = its name in English (shown with the pixel fonts if they can't show the name)
pixel_font = false for languages the pixel fonts can't show (Russian, Japanese, ...): they need
             a TTF/OTF font in data/fonts, and are hidden from the menu when there is none
