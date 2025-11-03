# BrowshTest
**This is for anyone looking to use Browsh, which is an interactive browser that can be used in the terminal!**

**In order for Browsh to be able to run, use the following commands:**
# Install Firefox manually (headless-compatible)
`wget https://download.mozilla.org/?product=firefox-latest&os=linux64&lang=en-US -O firefox.tar.bz2`

`tar xjf firefox.tar.bz2`

`sudo mv firefox /opt/firefox`

`sudo ln -sf /opt/firefox/firefox /usr/local/bin/firefox`

# Verify the installation
firefox --headless --version

* Then run `sudo docker run --rm -it browsh/browsh`

**Congratulations! Browsh should be up and running!**

**NOTE: If you want a list of the keybinds, look below:**
* Note that OSX users need to use the `⌘/Command` key instead of `CTRL`.
* `F1` Opens the documentation
* `ARROW KEYS`, `PGUP`, `PGDN` Scrolling
* `CTRL+q` Exit app
* `CTRL+l` Focus the URL bar
* `BACKSPACE` Go back in history
* `CTRL+r` Reload page
* `CTRL+t` New tab
* `CTRL+w` Close tab
* `CTRL+\` Cycle to next tab
![Screenshot of Browsh UI.](https://github.com/Lstriker1268/browshtest/assets/50205749/f2af651c-efc7-4966-8751-2ae268452868)

