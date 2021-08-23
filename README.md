# Saya

## About
A dark color scheme (originally based on Oblivion and Tango) for gtksourceview and gedit.

![saya screenshot](https://github.com/circumjacence/saya/raw/master/images/screenshot-2021-08-22--660w.png "Saya Screenshot")

## GEdit Installation

To install this color scheme in gedit 3.x, do the following:
- Download [saya.xml](https://raw.github.com/circumjacence/saya/master/saya.xml "Download saya.xml")
- Open gedit
- Go to Edit > Preferences > Font & Colors
- Click the small "+" button to add a new color scheme
- Select saya.xml
  - *This will copy saya.xml to*:  ~/.local/share/gedit/styles/saya.xml
- Select Saya as your chosen color scheme


## Terminator Profile Installation

To add a Saya themed profile to Terminator:

1. Open: ~/.config/terminator/config
2. Find the end of the [[default]] profile: 

```
[profiles]
  [[default]]
    ... PROFILE SETTINGS HERE ...
```

3. Immediately after the end of the [[default]] profile add the following:

```
  [[Saya]]
    background_color = "#110f0f"
    cursor_color = "#aaaaaa"
    foreground_color = "#fffafa"
    palette = "#110f0f:#cc0000:#83c244:#fcaf3e:#729fcf:#b673af:#fce94f:#eeeeec:#110f0f:#a40000:#4e9a06:#ce5c00:#204a87:#5c3566:#c4a000:#babdb6"
```

4. Open Terminator and go to: Preferences > Profiles > Colors and select Saya from the profile list.

