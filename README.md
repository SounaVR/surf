# Souna's Arch Tools 🐧🛠️
Welcome ! Here's one of the tools I use on my Arch installation, and it's obviously subject to evolution and improvement.

The main goal of this kind of repo is to keep "backups" in case I break anything.

Also it'll be very useful for my **future custom arch install interactive script** 🔥.

### Oh ? Interested by using it ? Nothing special but.. Why not.

Just clone the repo by typing the following lines in a terminal

```bash
git clone https://github.com/SounaVR/surf.git
cd surf
sudo pacman -S webkit2gtk gcr
sudo make clean install
```

Use `surf [url]` to open the browser. (I use [dmenu](https://github.com/SounaVR/dmenu.git) to open it)

(<kbd>CTRL+G</kbd>) to browse.

Can be [patch](https://surf.suckless.org/patches/).


### Edit the configuration
The `config.def.h` can be edit to suit your needs.
Don't forget to delete the `config.h` before compiling again.