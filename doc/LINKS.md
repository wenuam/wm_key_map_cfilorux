# wm_key_layout_cfilorux

Source : https://github.com/wenuam/wm_key_layout_cfilorux/

## Documentation

Some useful links :

### Unicode

* https://www.compart.com/en/unicode/ / https://www.compart.com/en/unicode/block/U+0300
* https://symbl.cc/en/unicode/ / https://symbl.cc/en/unicode/table/#combining-diacritical-marks

### Diacritics

* https://en.citizendium.org/wiki/Diacritic
* https://en.wikipedia.org/wiki/Diacritic
* https://fr.wikipedia.org/wiki/Diacritiques_de_l%27alphabet_latin
* https://bepo.fr/wiki/Touches_mortes
* https://kbdlayout.info/features/deadkeys
<br>

* https://microsoft.public.win32.programmer.international.narkive.com/1dA5t1Cc/how-to-combine-dead-keys
* http://archives.miloush.net/michkap/archive/2011/04/16/10154700.html

### Special symbols

* https://mycodetips.com/tipstricks/special-characters-and-symbols-in-programming-languages-3624.html
* https://stackoverflow.com/questions/3421532/frequency-of-symbols-in-programming-languages
* http://www.knosof.co.uk/cbook/

### Language codes

* https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes

### Making your own layout

* https://support.wasdkeyboards.com/hc/en-us/articles/115009403848-Intro-to-Custom-Layouts
* https://www.tuxedocomputers.com/en/Infos/Help-Support/Frequently-asked-questions/Keyboards-Layouts_1.tuxedo
* https://www.tuxedocomputers.com/en/Infos/Help-Support/Instructions/Keyboard-laser-etching-and-logo-printing-service.tuxedo
* https://inkscape-manuals.readthedocs.io/

## Mapping

The keyboard mapping is the assignation of letters to certains keys. It could be done in several ways :

1- In the keyboard firmware (they are sending standardized scan codes, extended codes for media keys)
2- In the keyboard key mapper (if they can host such a mapping reconfiguration)
3- Low-level key input remapping on the computer side, before the Operating System gets it
4- Language selection at the Operating System level (ie. [Windows] key + [Space] bar)

Depending on the case, it requires the keyboard mapping configuration files in the right format.

Keyboard mapping utilities depends on the operating system in use :

### Cross

* https://keyman.com/ (by SIL, free and open source)
* https://github.com/kmonad/kmonad
* https://github.com/thantthet/keymagic / https://github.com/minnkyaw/keymagic

### Linux

For Linux it is quite complex, several tools with different syntax :

* https://github.com/rvaiya/keyd
* https://github.com/samvel1024/kbct
<br>

* https://wiki.archlinux.org/title/X_keyboard_extension
* https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions
* https://medium.com/@damko/a-simple-humble-but-comprehensive-guide-to-xkb-for-linux-6f1ad5e13450
* https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/include/uapi/linux/input-event-codes.h

### Windows

* [Microsoft Keyboard Layout Creator] (by Michael Kaplan) / https://msklc-guide.github.io/
* https://github.com/topics/msklc
* https://github.com/alexriss/keyboard-layout-converter
<br>

* https://github.com/cajhin/capsicain
* https://github.com/oskar-anderson/Multikeys
* https://github.com/giladreich/QuickCut

[Microsoft Keyboard Layout Creator]: https://www.microsoft.com/en-us/download/details.aspx?id=102134

### Testing

You can also use tools to test the relevance of a mapping :

* http://patorjk.com/keyboard-layout-analyzer/
* https://keyboardsimulator.xyz/

## Keycaps

The layout is already implemented for different keyboards :

* CORSAIR [Vengeance K95 RGB] (Limited Edition)
* TUXEDO [Sirius 16 - Gen1]
* TUXEDO [Stellaris 16 - Gen5 - AMD]

[Vengeance K95 RGB]: https://www.corsair.com/us/en/p/keyboards/ch-9000060-na/vengeance-k95-rgb-limited-edition-fully-mechanical-gaming-keyboard-cherry-mx-red-ch-9000060-na
[Sirius 16 - Gen1]: https://www.tuxedocomputers.com/en/TUXEDO-Sirius-16-Gen1.tuxedo
[Stellaris 16 - Gen5 - AMD]: https://www.tuxedocomputers.com/en/TUXEDO-Stellaris-16-Gen5-AMD.tuxedo

Max Keyboard layouts (6.5 bottom row for the Corsair K95 keyboard) :

* http://blog.maxkeyboard.com/dwkb/keycap-profile-size-information/
* http://www.maxkeyboard.com/download.html
<br>

* https://cherryxtrfy.com/custom-keyboard-builder
* https://www.wasdkeyboards.com/products/keycaps/keycap-set.html
* https://www.wasdkeyboards.com/105-key-iso-custom-cherry-mx-keycap-set.html
* https://www.maxkeyboard.com/iso-layout-custom-backlight-cherry-mx-keycap-set-top-print.html
* https://www.maxkeyboard.com/black-clear-translucent-18-g-keys-pack-for-corsair-k95-blank-front-top-printed.html
<br>

* https://geekhack.org/index.php?topic=96010.0
<br>

* https://lucidar.me/en/keyboards/where-can-we-buy-french-keycaps/

## Fonts

Some fonts were used to create to keycaps :

### Google fonts

* https://github.com/google/fonts (Exo 2 by Natanael GAMA)
* https://github.com/google/material-design-icons / https://fonts.google.com/icons
* https://github.com/ionic-team/ionicons / https://ionic.io/ionicons

### Symbols

* https://www.tuxedocomputers.com/en/Key-combinations-and-special-keys.tuxedo

### Specific fonts

* https://kinsta.com/blog/best-programming-fonts/
* https://collab.its.virginia.edu/wiki/toolbox/Unicode%20Diacritic%20Fonts.html

### Free fonts

* https://www.cufonfonts.com/
* https://www.fontspace.com/
* https://www.1001fonts.com/

## Archives

Here are the previous attempts that led to this version :

* http://www.keyboard-layout-editor.com/#/gists/a64eae70f4f459e1325f92014f825195
* http://www.keyboard-layout-editor.com/#/gists/c2ca5f0f7dc0f5527d60b11fadf26018
* http://www.keyboard-layout-editor.com/#/gists/8ff177453d8869cd82990cd966ee7c62

First public mention :

* https://deskthority.net/viewtopic.php?t=17889

## Troubleshot

### Microsoft Keyboard Layout Creator

* https://ilgthegeek.wordpress.com/2010/05/31/editing-windows-custom-keyboard-layouts/
* https://www.googlecloudcommunity.com/gc/Workspace-Q-A/Insert-Non-breaking-Space/m-p/508394
* https://archives.miloush.net/michkap/archive/2008/08/15/8869343.html
* http://archives.miloush.net/michkap/archive/2011/04/16/10154700.html

### Tuxedo

In case something might break :

* https://www.tuxedocomputers.com/en/Infos/Help-Support/Help-for-my-device/TUXEDO-Polaris-series/TUXEDO-Polaris-15/Special-keys-assignment.tuxedo
* https://www.tuxedocomputers.com/en/Infos/Help-Support/Instructions/Updating-EFI-BIOS-EC.tuxedo
* https://github.com/tuxedocomputers/tuxedo-keyboard

Other sources of tweaks :

* https://encarsia.github.io/en/posts/tuxedo-keyboard-tweaks/
* https://forum.manjaro.org/t/built-in-keyboard-issues-on-tuxedo-computer/40209
* https://www.reddit.com/r/tuxedocomputers/comments/ktaqa2/pulse_14_completely_wrong_fn_keys_with_tuxedo_os/
* https://www.reddit.com/r/tuxedocomputers/comments/kn0vuo/pulse_15_fn_keys_layout/
