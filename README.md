# Quick Settings Tweaks [<img src=".github/images/quick-settings-tweaker.png" width="200px" align="right" alt="QuickSettings-Tweaker SkeletonUI">](https://extensions.gnome.org/extension/5446/quick-settings-tweaker/)

<div align="center">

### Let's tweak Gnome Quick Settings!

[<img src="https://raw.githubusercontent.com/andyholmes/gnome-shell-extensions-badge/master/get-it-on-ego.svg?sanitize=true" alt="Get it on GNOME Extensions" height="100" align="middle">](https://extensions.gnome.org/extension/5446/quick-settings-tweaker/)
<br>
<br>
Quick Settings Tweaker is a Gnome 46+ extension which allows you to customize the new Quick Settings Panel to your liking!

</div>
<br>
<br>

## Features

| <p align="center">With this extension, you can...</p> | How it will appear |
|:-------------------------------|:--------------------:|
| <p align="center">**Add the Media Controls Widget**</p><p align="center">Control your music and videos directly from the Quick Settings, instead of the Date Menu.<br><br>For a cooler look, you can also get colors from the cover image and create a gradient.</p> | <img src=".github/images/media-control.png" width="600px" alt="Media controls widget screenshot"> |
| <p align="center">**Add the Volume Mixer Widget**</p><p align="center">Adjust application volumes, without opening extra application.<br><br>Place the menu button next to the output slider for a compact and natural layout.</p> | <img src=".github/images/volume-mixer.png" width="600px" alt="Volume mixer widget screenshot"> |
| <p align="center">**Add the Notifications Widget**</p><p align="center">You can check what has been sent to your mailbox or messenger, without missing!</p> | <img src=".github/images/notifications.png" width="600px" alt="Notifications widget screenshot"> |
| <p align="center">**Layout customize**</p><p align="center">Hide, re-order, re-color your panel and Quick Settings layout<br><br>Make it simple and keep organized!</p> | <img src=".github/images/layout.png" width="600px" alt="Notifications widget screenshot"> |
| <p align="center">**Overlay menu layout**</p><p align="center">Your Quick Settings panel is too big?<br><br>Try overlay layout! you can customize background and animation style too.</p> | <img src=".github/images/overlay.png" width="600px" alt="Notifications widget screenshot"> |

## Sponsor

You can promote and support development by [github sponsor!](https://github.com/sponsors/qwreey) You can help keep this project maintained

Here is my sponsors, thank for your support!

[![sponsors](https://readme-contribs.as93.net/sponsors/qwreey?shape=square&margin=16&perRow=15&title=Qwreey's%20Sponsors&textColor=f5acff&backgroundColor=0e001a&fontFamily=cursive&fontSize=14&limit=90&footerText=none&outerBorderRadius=24)](https://github.com/sponsors/qwreey)

## Stars

[![Star History Chart](https://api.star-history.com/svg?repos=qwreey/quick-settings-tweaks&type=Date)](https://star-history.com/#qwreey/quick-settings-tweaks&Date)

## Development

### Building

> Prerequirements: You need to install nodejs, bash, and gnome-shell for compiling extension from source

You can create development build by executing `TARGET=dev ./install.sh create-release`. make sure run `npm i` first to ensure all build dependencies installed

Or, you can get nightly preview build from [github releases tab](https://github.com/qwreey/quick-settings-tweaks/releases). Build extension from `dev` branch is not encouraged, because the `dev` branch has unchecked bleeding-edge features not guaranteed to work. github-preview build is tested by developer and much stable than building `dev` branch.

### Contribution and Issues

Keep in mind that there may be one or a few developers, but there may be many issues and users. I think you know how to behave with manners without even having to say it.

Please check github [project board page](https://github.com/users/qwreey/projects/2) for issue priority and progress.

#### Raise an issue

If you want to raise an issue, First, **you must search your issue first.** duplicated issue will be closed, and disturb developer's time.

Second, **you must attach a related log files, gnome version and extension version informations.** if you don't provide information much about your issue, it is hard to solve your issue. and to be clear, Please use `[migration]`, `[feature]`, `[bug]` prefix for issue title, It is very useful for searching and organizing issues

And last, **you must use well-formed english** You can use a translator or AI to write it, so avoid wasting time by having the developer translate and take notes. This takes up a surprising amount of the developer's time, making analysis very difficult, especially if the logs are mixed in English and other languages.

#### PR and code contribution

If you want to contribute, **you must pull `dev` branch, Not master branch.** master branch is release branch, because AUR and some user distributions use master branch as build source. **If you create pull-request to master branch, it will be closed.** you should re-open PR to dev branch.

### Testing

![gnome-docker devlopment screenshot](.github/images/dev-preview.png)

You can test extension with command `./install.sh dev`. You will need tigervnc client and docker in host. Tested in arch linux but it should working on any systemd based platform

You can re-build extension by log out and close vnc window or send SIGINT to exit dev docker.
