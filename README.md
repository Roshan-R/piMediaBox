# piMediaBox
A raspberry pi media streaming setup for popular streaming sites.

## Setup
The chromuim browser, out of the box does have support to play DRM protected content.
Thankfully, enabling this has been easier than before thanks to [this](https://blog.vpetkov.net/2020/03/30/raspberry-pi-netflix-one-line-easy-install-along-with-hulu-amazon-prime-disney-plus-hbo-spotify-pandora-and-many-others/) wonderul blogpost.

```
sudo apt update && sudo apt upgrade
curl -fsSL https://pi.vpetkov.net -o ventz-media-pi
sh ventz-media-pi
```
once that is done, clone this repo and execute setup.sh, install and enjoy
