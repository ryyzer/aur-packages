# aur-packages

A collection of **PKGBUILDS** I maintain for the [Arch User Repository](https://aur.archlinux.org), currently including:
 - [odin2-synthesizer](https://aur.archlinux.org/packages/odin2-synthesizer)
 - odin2-synthesizer-bin (WIP - Currently non-functional due to certificate issues at source)

### INSTALLATION:
**Manually, from Github:**
 - `git clone https://github.com/ryyzer/aur-packages`
 - `cd aur-packages/{package_name}`
 - `makepkg -sri`

**Manually, from AUR:**
 - `git clone https://aur.archlinux.org/{package_name}`
 - `cd {package_name}`
 - `makepkg -sri`

**Using YAY (or other AUR-helper):**
 - `yay -S {package_name}`
