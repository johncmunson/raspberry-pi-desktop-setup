1. (Need instructions here for booting from SSD)
2. Install fish
    ```
    // INSTALL
    $ sudo apt install fish
    // MAKE FISH THE DEFAULT LOGIN SHELL AND INTERACTIVE SHELL
    $ chsh # enter password, then enter /usr/bin/fish
    $ chsh -s /usr/bin/fish
    // MAKE CONFIG
    touch ~/.config/fish/config.fish
    // REBOOT
    $ sudo reboot
    ```
3. Install VSCode - might already be installed in newer OS's
    ```
    $ sudo apt update
    $ sudo apt install code
    ```
4. Install vim
    ```
    $ sudo apt install vim
    ```
5. Install or update git
    ```
    $ sudo apt install git
    ```
6. Install n (the node version manager)
    ```
    $ curl -L https://git.io/n-install | bash
    Add the following line to `.config/fish/config.fish`...
    $ set -x N_PREFIX "$HOME/n"; set -x PATH "$N_PREFIX/bin" $PATH
    ```

- setup github
- create document for raspberry pi tips and tricks, and common commands
    - scrot for taking screenshots
    - https://askubuntu.com/questions/43264/how-to-open-a-pdf-file-from-terminal
    