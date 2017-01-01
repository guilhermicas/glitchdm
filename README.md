*Note: this theme is forked from [pedropenna/musfealle](https://github.com/pedropenna/musfealle)*  
*Credit goes to him for the simplified login process*

# GlitchDM

##### A LightDM Webkit Greeter Theme with unknown purpose.  Extremely rare.

![Demo](img/glitch-demo.gif?raw=true)

This greeter theme was built based on the Antergos Greeter Theme (https://github.com/Antergos/lightdm-webkit-theme-antergos)


## Installation

1. Install [lightdm-webkit2-greeter](https://github.com/Antergos/lightdm-webkit2-greeter) using the package provided in their repo
2. Set lightdm-webkit2-greeter to be the default greeter.  The preferred way is to create a file inside `/etc/lightdm/lightdm.conf.d`.  This file can have any name you want, but something like `50-lightdm-webkit2-greeter.conf` is not a bad choice.  The contents of the file should be :
```
[Seat:*]
greeter-session=lightdm-webkit2-greeter
```
3. Clone this theme
4. Copy the contents of this theme into `/usr/share/lightdm-webkit/themes`
5. Edit the file `/etc/lightdm/lightdm-webkit2-greeter.conf` and set the
"webkit-theme" property to "glitchdm".
6. Restart!


## Keyboard Shortcuts

- Alt + R: Restart
- Alt + D: Shutdown
- Alt + H: Hibernate
- Alt + P: Suspend
- Alt + S or Alt + C: Cycle through the session options
- Tab: Move focus between username and password fields
- Enter: Log In

*gif images are under [Creative Commons License](https://gitlab.com/mixedCase/sddm-lain-wired-theme/raw/master/LICENSE) and are sourced from [Andrés Rodríguez's repository](https://gitlab.com/mixedCase/sddm-lain-wired-theme/tree/master)*
