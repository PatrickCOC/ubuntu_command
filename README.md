# ubuntu 22.0 wayland(remote desktop)
enable/disable wayland on Ubuntu 22.04 Desktop

* ```sudo nano /etc/gdm3/custom.conf```
* WaylandEnable=true -> WaylandEnable=false
* ```sudo systemctl restart gdm3```
* To login to Ubuntu 22.04 using the Wayland click on the gear button and select Ubuntu option before you login. If you have disabled the Wayland display server, you will only see the Xorg option appear, or the gear button doesn’t show up at all.
# nodejs version control

## install nvm
- ``curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash``

or

- ``wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash``

Running either of the above commands downloads a script and runs it. The script clones the nvm repository to ~/.nvm, and attempts to add the source lines from the snippet below to the correct profile file (~/.bash_profile, ~/.zshrc, ~/.profile, or ~/.bashrc).

    export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
    [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" 
    # This loads nvm

**To verify that nvm has been installed, do:**

    command -v nvm

**use different versions of node** 

    $ nvm use 16
    Now using node v16.9.1 (npm v7.21.1)
    $ node -v
    v16.9.1
    $ nvm use 14
    Now using node v14.18.0 (npm v6.14.15)
    $ node -v
    v14.18.0
    $ nvm install 12
    Now using node v12.22.6 (npm v6.14.5)
    $ node -v
    v12.22.6


# ubuntu_command
