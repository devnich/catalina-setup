- <a href="#security" id="toc-security"><span class="toc-section-number">1</span> Security</a>
  - <a href="#login" id="toc-login"><span class="toc-section-number">1.1</span> Login</a>
  - <a href="#firewall" id="toc-firewall"><span class="toc-section-number">1.2</span> Firewall</a>
  - <a href="#ssh" id="toc-ssh"><span class="toc-section-number">1.3</span> SSH</a>
  - <a href="#dns" id="toc-dns"><span class="toc-section-number">1.4</span> DNS</a>
  - <a href="#give-some-programs-permission-to-access-the-entire-directory-structure" id="toc-give-some-programs-permission-to-access-the-entire-directory-structure"><span class="toc-section-number">1.5</span> Give some programs permission to access the entire directory structure</a>
- <a href="#ergonomics" id="toc-ergonomics"><span class="toc-section-number">2</span> Ergonomics</a>
  - <a href="#fonts" id="toc-fonts"><span class="toc-section-number">2.1</span> Fonts</a>
  - <a href="#minimize-input-lag" id="toc-minimize-input-lag"><span class="toc-section-number">2.2</span> Minimize input lag</a>
  - <a href="#make-keyboard-settings-as-fast-as-possible-via-command-line." id="toc-make-keyboard-settings-as-fast-as-possible-via-command-line."><span class="toc-section-number">2.3</span> Make keyboard settings as fast as possible via command line.</a>
- <a href="#desktop-applications" id="toc-desktop-applications"><span class="toc-section-number">3</span> Desktop applications</a>
  - <a href="#safari" id="toc-safari"><span class="toc-section-number">3.1</span> Safari</a>
  - <a href="#force-office-to-save-locally" id="toc-force-office-to-save-locally"><span class="toc-section-number">3.2</span> Force Office to save locally</a>
- <a href="#time-machine-settings" id="toc-time-machine-settings"><span class="toc-section-number">4</span> Time Machine settings</a>
  - <a href="#exclude-some-directories-from-time-machine" id="toc-exclude-some-directories-from-time-machine"><span class="toc-section-number">4.1</span> Exclude some directories from Time Machine</a>
  - <a href="#delete-time-machine-backups" id="toc-delete-time-machine-backups"><span class="toc-section-number">4.2</span> Delete Time Machine backups</a>
- <a href="#install-xcode-command-line-tools-git-and-clang" id="toc-install-xcode-command-line-tools-git-and-clang"><span class="toc-section-number">5</span> Install XCode Command Line Tools (git and clang)</a>
  - <a href="#update-xcode-command-line-tools" id="toc-update-xcode-command-line-tools"><span class="toc-section-number">5.1</span> Update XCode Command Line Tools</a>
- <a href="#install-the-nix-package-manager" id="toc-install-the-nix-package-manager"><span class="toc-section-number">6</span> Install the Nix Package Manager</a>
- <a href="#using-the-nix-package-manager" id="toc-using-the-nix-package-manager"><span class="toc-section-number">7</span> Using the Nix Package Manager</a>
  - <a href="#orientation" id="toc-orientation"><span class="toc-section-number">7.1</span> Orientation</a>
  - <a href="#documentation" id="toc-documentation"><span class="toc-section-number">7.2</span> Documentation</a>
  - <a href="#update-list-of-available-packages" id="toc-update-list-of-available-packages"><span class="toc-section-number">7.3</span> Update list of available packages</a>
  - <a href="#show-installed-packages" id="toc-show-installed-packages"><span class="toc-section-number">7.4</span> Show installed packages</a>
  - <a href="#search-for-packages" id="toc-search-for-packages"><span class="toc-section-number">7.5</span> Search for packages</a>
  - <a href="#install-packages" id="toc-install-packages"><span class="toc-section-number">7.6</span> Install packages</a>
  - <a href="#upgrade-packages" id="toc-upgrade-packages"><span class="toc-section-number">7.7</span> Upgrade packages</a>
  - <a href="#force-an-update-of-the-package-manager" id="toc-force-an-update-of-the-package-manager"><span class="toc-section-number">7.8</span> Force an update of the package manager</a>
  - <a href="#remove-older-software-versions-from-local-cache" id="toc-remove-older-software-versions-from-local-cache"><span class="toc-section-number">7.9</span> Remove older software versions from local cache</a>
- <a href="#install-packages-with-nix-package-manager" id="toc-install-packages-with-nix-package-manager"><span class="toc-section-number">8</span> Install packages with Nix package manager</a>
  - <a href="#install-packages-1" id="toc-install-packages-1"><span class="toc-section-number">8.1</span> Install packages</a>
  - <a href="#instructions-for-specific-packages" id="toc-instructions-for-specific-packages"><span class="toc-section-number">8.2</span> Instructions for specific packages</a>
- <a href="#shell-configuration" id="toc-shell-configuration"><span class="toc-section-number">9</span> Shell configuration</a>
- <a href="#install-mamba" id="toc-install-mamba"><span class="toc-section-number">10</span> Install Mamba</a>
  - <a href="#install-micromamba" id="toc-install-micromamba"><span class="toc-section-number">10.1</span> Install micromamba</a>
- <a href="#python-anaconda-distribution" id="toc-python-anaconda-distribution"><span class="toc-section-number">11</span> Python Anaconda distribution</a>
  - <a href="#install-for-single-user" id="toc-install-for-single-user"><span class="toc-section-number">11.1</span> Install for single user</a>
  - <a href="#using-conda-environments" id="toc-using-conda-environments"><span class="toc-section-number">11.2</span> Using Conda environments</a>
  - <a href="#installing-packages" id="toc-installing-packages"><span class="toc-section-number">11.3</span> Installing packages</a>
  - <a href="#update-python-conda-and-python-packages" id="toc-update-python-conda-and-python-packages"><span class="toc-section-number">11.4</span> Update Python, Conda, and Python packages</a>
  - <a href="#install-git-drivers-for-jupyter-notebooks" id="toc-install-git-drivers-for-jupyter-notebooks"><span class="toc-section-number">11.5</span> Install Git drivers for Jupyter Notebooks</a>
  - <a href="#install-python-anaconda-distribution-for-multi-user-not-recommended" id="toc-install-python-anaconda-distribution-for-multi-user-not-recommended"><span class="toc-section-number">11.6</span> Install Python Anaconda distribution for multi-user (NOT RECOMMENDED)</a>
- <a href="#install-r" id="toc-install-r"><span class="toc-section-number">12</span> Install R</a>
- <a href="#install-julia" id="toc-install-julia"><span class="toc-section-number">13</span> Install Julia</a>
- <a href="#optional-assorted-research-and-developer-tools" id="toc-optional-assorted-research-and-developer-tools"><span class="toc-section-number">14</span> (Optional) Assorted research and developer tools</a>
  - <a href="#build-bookdown-book-e.g.-advanced-r" id="toc-build-bookdown-book-e.g.-advanced-r"><span class="toc-section-number">14.1</span> Build Bookdown book (e.g., "Advanced R")</a>
  - <a href="#install-clan" id="toc-install-clan"><span class="toc-section-number">14.2</span> Install CLAN</a>
  - <a href="#compile-and-serve-uc-love-data-week-website-locally-with-jekyll" id="toc-compile-and-serve-uc-love-data-week-website-locally-with-jekyll"><span class="toc-section-number">14.3</span> Compile and serve UC Love Data Week website locally with Jekyll</a>

# Security

## Login

1.  Remove password quality restrictions

    ``` bash
    pwpolicy -clearaccountpolicies
    ```

2.  Disable Global Protect VPN autostart <https://www.robertsetiadi.com/disabling-globalprotect-vpn-auto-run-during-mac-start-up/>

3.  Manually kill and restart Global Protect VPN (via <https://joshcurry.co.uk/posts/how-to-quit-globalprotect-mac/>)

    ``` bash
    launchctl unload /Library/LaunchAgents/com.paloaltonetworks.gp.pangp*
    launchctl load /Library/LaunchAgents/com.paloaltonetworks.gp.pangp*
    ```

## Firewall

Enable and activate stealth mode

## SSH

1.  If you have a `.ssh` directory in your old machine's home directory, copy the contents of that directory to your new machine using Magic Wormhole (this will require a Linux package manager; see Nix section below)

2.  Otherwise, create a new `.ssh` directory and generate a public/private key pair. On MacOS or Linux, open the Terminal application; on Windows 10, open the Powershell application. Then:

    ``` bash
    cd ~/
    mkdir .ssh
    ssh-keygen -t ed25519 -C "<your email address>"
    ```

    1.  You will be prompted to enter a file name for the keys. Press Return to accept the default.
    2.  You we be prompted to enter a passphrase. Type a passphrase and press Return (the Terminal will not display your password while you are typing).

3.  Set permissions for .ssh directory and keys.

    ``` bash
    cd ~/
    chmod 700 .ssh/                 # .ssh directory
    cd .ssh/
    chmod 600 *                     # private keys and other files
    chmod 644 *.pub                 # public keys
    ```

4.  If you have more than one key pair, create a configuration file (`.ssh/config`) that lists the resolution order for the keys. The `ssh` command will try the keys in order until one succeeds. The contents of `config` should follow this template:

    ``` bash
    IdentityFile ~/.ssh/<key_file_1>
    IdentityFile ~/.ssh/<key_file_2>
    # et cetera
    ```

### Windows 10/11:

The best approach on Windows is probably to use the Github Credential Manager: <https://github.com/GitCredentialManager> . It's difficult to find clear guidance on how to set file permissions for .ssh/ and its contents.

## DNS

Configure in System Preferences → Network → WiFi → Advanced → DNS

### DNS Servers

``` bash
9.9.9.9
2620:fe::fe
2620:fe::9
8.8.8.8
```

### Search Domains

``` bash
duckduckgo.com
google.com
```

## Give some programs permission to access the entire directory structure

Configure in System Preferences → Privacy & Security

1.  Accessibility tab
    1.  Terminal
    2.  Emacs
2.  Full Disk Access tab
    1.  Terminal
    2.  Emacs
3.  Developer Tools tab The "Developer Tools" tab will appear when you run the command to enable developer mode for the terminal (step 1 below)
    1.  Terminal

        ``` bash
        # Enable Developer Tools tab and add Terminal to it
        sudo spctl developer-mode enable-terminal
        ```

    2.  Emacs

    3.  Coreutils version of ls (once installed)

    4.  ispell (once installed)

    5.  movemail (once installed)

    6.  nix (once installed)

# Ergonomics

## Fonts

Download and install DejaVu fonts

## Minimize input lag

1.  Settings → Keyboard: Key Repeat = Fast

2.  Settings → Keyboard: Delay Until Repeat = Short

3.  Settings → General: Disable iCloud handoff

4.  Disable Bluetooth (or unplug all USB devices, depending on input source)

5.  Disable accents pop-up menu

    ``` bash
    defaults write -g ApplePressAndHoldEnabled -bool false
    ```

## Make keyboard settings as fast as possible via command line.

via <https://news.ycombinator.com/item?id=39528809> Each integer on the scale == 15 ms

``` bash
# "Set a blazingly fast keyboard repeat rate, "
# Default fastest value = 2 (30 ms)
defaults write NSGlobalDomain KeyRepeat -int 1
# "Set a shorter Delay until key repeat"
# Default shortest value = 15 (225 ms)
defaults write NSGlobalDomain InitialKeyRepeat -int 10
# disable accents on key hold
defaults write -g ApplePressAndHoldEnabled -bool false
```

Reboot after setting the values. Don't ever change repeat rate in Preferences dialog, it resets it to the

# Desktop applications

## Safari

1.  Display URL on mouseover View menu → Show status bar
2.  Install extensions
    1.  1Password
    2.  AdGuard
    3.  Box Tools
    4.  Pinboard Tools
    5.  Zotero Connector

## Force Office to save locally

1.  Stay signed out of office
2.  Tweak privacy settings: <https://docs.microsoft.com/en-us/deployoffice/privacy/mac-privacy-preferences>

# Time Machine settings

## Exclude some directories from Time Machine

1.  Nix disk partition
2.  \~/Library/CloudStorage
3.  \~/Google Drive mirrored directory name

## Delete Time Machine backups

1.  List backups

    ``` bash
    tmutil listbackups
    ```

2.  Delete selected backup

    ``` bash
    # Delete /Volumes/LaCie/Backups.backupdb/Hermes/2023-03-13-101503
    sudo tmutil delete -d /Volumes/LaCie -t 2023-03-13-101503
    ```

3.  References

    - <https://derflounder.wordpress.com/2022/07/01/removing-unwanted-time-machine-backups-from-apfs-formatted-time-machine-backup-drives-on-macos-monterey/>

    - <https://appleinsider.com/articles/21/06/26/how-to-delete-time-machine-local-snapshots-in-macos>

# Install XCode Command Line Tools (git and clang)

You can install Git on your Mac using one of the following methods (we list more than one method because sometimes your permission settings will prevent one of the methods from working. Start at the top of the list and work your way down).

1.  Method 1: Install from the terminal

    ``` bash
    xcode-select --install

    # Follow on-screen prompts to install
    ```

2.  Method 2: Install from the terminal

    ``` bash
    clang --version

    # Follow on-screen prompts to install
    ```

3.  Method 3: Manually download the latest version of "Command Line Tools for XCode" from <https://developer.apple.com/download/more/>

## Update XCode Command Line Tools

This shouldn't be necessary most of the time; the normal MacOS update process should also offer updates to the command line tools when they are available.

1.  Search for software updates

    ``` bash
    softwareupdate --list
    ```

2.  Install using full name

    ``` bash
    softwareupdate -i "Command Line Tools (macOS High Sierra version 10.13) for Xcode-10.1"
    ```

# Install the Nix Package Manager

Following <https://www.philipp.haussleiter.de/2020/04/fixing-nix-setup-on-macos-catalina/>

1.  Verify that your file system is APFS

    ``` bash
    diskutil list | grep APFS
    ```

2.  Create a new APFS disk volume called "nix" using Disk Utility

3.  Create a mount point by adding the volume name to /etc/synthetic.conf:

    ``` example
    nix
    ```

4.  Reboot. This will create the "/nix" mount point.

5.  Get the disk volume partition for the /nix mount point.

    ``` bash
    diskutil list | grep APFS | grep nix
    ```

6.  Use the volume partition number to find its UUID

    ``` bash
    diskutil info /dev/disk1s6 | grep UUID
    ```

7.  Create and edit /etc/fstab, preferably using vifs (note that vifs uses vi keybindings). Be sure to use **your** UUID, not the UUID in the example.

    ``` bash
    sudo vifs
    ```

    ``` example
    UUID=78012913-F18F-4CB5-9CF0-CFFBB609692C /nix apfs rw
    ```

8.  Reboot.

9.  Create a `.profile` file in your home directory if it doesn't already exist.

10. Download the nix installation script from <https://nixos.org/nix/install> as "install.sh", then execute:

    ``` bash
    sh install.sh
    ```

11. Copy contents of `.profile` to `.zshrc` (or rename `.profile` to `.zshrc` if it doesn't already exist)

# Using the Nix Package Manager

## Orientation

NixOS implements reproducible builds using profiles (current) or flakes (experimental). These approaches don't work when using Nix as the package manager for a third-party system. Instead, we have to do imperative package management using the `nix-env` family of commands.

## Documentation

Major Nix commands have separate documentation for each higher-order flag; e.g., `nix-env` has separate man pages for `nix-env --query`, `nix-env --install`, etc.

1.  To get a list of the higher-order flags, run:

    ``` bash
    nix-env --help
    ```

2.  To get the man page for a specific flag, run:

    ``` bash
    # man page for `nix-env --query`
    man nix-env-query
    ```

## Update list of available packages

``` bash
nix-channel --update
```

## Show installed packages

This works for imperatively installed packages (installed with \`nix-env -i\`), but not for profiles or flakes.

``` bash
# Show brief listing
nix-env -q

# Show complete installation profile
nix-env -q --json --meta
```

## Search for packages

1.  Show available packages matching the symbolic name. This will output the attribute path (`--attr-path` \| `-P`), which you can use to disambiguate between multiple versions of the package.

    ``` bash
    nix-env -qasP coreutils
    ```

    ``` example
    -PS  nixpkgs.coreutils           coreutils-9.4
    --S  nixpkgs.coreutils-prefixed  coreutils-9.4
    ```

2.  Show available packages matching the attribute path. This is much faster.

    ``` bash
    nix-env -qasA nixpkgs.coreutils
    ```

    ``` example
    -PS  coreutils-9.4
    ```

3.  Show available packages matching a regular expression.

    ``` bash
    nix-env -qasP '.*LaTeXML.*'
    ```

    ``` example
    --S  nixpkgs.perl536Packages.LaTeXML  perl5.36.3-LaTeXML-0.8.7
    IPS  nixpkgs.perl538Packages.LaTeXML  perl5.38.2-LaTeXML-0.8.7
    ```

    1.  Show the package description

        ``` bash
        nix-env -qasA nixpkgs.coreutils --description
        ```

        ``` example
        -PS  coreutils-9.4  The GNU Core Utilities
        ```

4.  Show the package location

    ``` bash
    nix-env -qasA nixpkgs.coreutils --drv-path
    ```

    ``` example
    -PS  coreutils-9.4  /nix/store/xaia11jsmshb2scm9v6g5fh103i8hlvb-coreutils-9.4.drv
    ```

## Install packages

1.  Install package by symbolic name

    ``` bash
    nix-env -i emacs-26.3
    ```

2.  Install package by attribute path

    ``` bash
    nix-env -iA nixpkgs.coreutils
    nix-env -iA nixpkgs.perl538Packages.LaTeXML
    ```

3.  Remove package

    ``` bash
    nix-env -e <package>
    ```

## Upgrade packages

1.  Show which packages will be upgraded

    ``` bash
    nix-env -u --dry-run
    ```

2.  Run the upgrade

    ``` bash
    nix-env -u
    ```

3.  Delete and recreate symbolic links for apps (i.e. Emacs; see installation instructions for more details)

4.  Restore Full-Disk Access privileges for updated apps

5.  Run mandb to recreate man page database

    ``` bash
    sudo mandb -c
    ```

## Force an update of the package manager

This usually isn't required.

``` bash
nix upgrade-nix
```

## Remove older software versions from local cache

1.  Show list of installed generations

    ``` bash
    nix-env --list-generations
    ```

2.  Remove previous generations by ordinal distance (option 1)

    ``` bash
    # Remove all but last 3 generations
    nix-env --delete-generations +3
    nix-collect-garbage
    ```

3.  Remove previous generations by age (option 2)

    ``` bash
    # Optionally, delete and collect garbage in one pass
    nix-collect-garbage --delete-older-than 60d
    ```

# Install packages with Nix package manager

## Install packages

1.  adoptopenjdk-hotspot-bin
2.  age
3.  darcs (required for Emacs interaction with /usr/share/zsh/\<version\>/functions)
4.  fish (required for Derek's Emacs configuration)
5.  htop
6.  ispell (required for Emacs)
7.  magic-wormhole
8.  nano
9.  nodejs
10. pandoc
11. poppler-utils (required for Emacs)
12. ripgrep (required for Emacs)
13. ruby 3.14
14. stow (required for managing dot files)
15. tree
16. wget

## Instructions for specific packages

1.  Emacs

    1.  Get the complete version information of all the package variants. Installing by the symbolic name may not get you the latest version.

        ``` bash
        nix-env -qasP emacs
        nix-env -i emacs-29.1
        ```

    2.  Create symbolic link from application location to Applications folder

        ``` bash
        sudo su
        cd /Applications/
        ln -s /nix/var/nix/profiles/per-user/gilgamesh/profile/Applications/Emacs.app Emacs.app
        ```

    3.  If upgrading from a previous version

        1.  Set `desktop-save-mode` to `0`:
            - In the `lisp/init-local.el` file
            - In current session via EShell
        2.  Rename `custom.el` to `custom.el.bak`
        3.  Delete session files:
            - `.session`
            - `history`
            - `recentf`
            - `.emacs.desktop`
            - `.emacs.desktop.lock`
        4.  Restart Emacs (you will probably have to do this multiple times to get all of the libraries to compile)
        5.  Once Emacs is fully updated and starts without error, reset `desktop-save-mode` to `1`

2.  coreutils (required for Emacs) These instructions use the **un-prefixed** version of coreutils, thereby overwriting BSD utilities such as `ls` with the Linux coreutils for the normal user. The root user is unaffected and will continue to use the BSD versions

    1.  Get complete version information for all of the package variants. We are looking for the un-prefixed version of the GNU/Linux utilities (e.g., the `ls` command will be installed as `ls`, not `gls`).

        ``` bash
        nix-env -qasP coreutils
        ```

    2.  Install un-prefixed version

        ``` bash
        nix-env -iA nixpkgs.coreutils
        ```

3.  imagemagick

    ``` bash
    nix-env -i ghostscript
    nix-env -iA nixpkgs.imagemagick7
    ```

4.  man-db (caches man pages for faster loading in Emacs)

    1.  Install man-db

        ``` bash
        nix-env -i man-db
        ```

    2.  Create /var/cache/man directory and set owner to logged in user

        ``` bash
        cd /var/
        sudo mkdir cache/man
        sudo chown -R <user>:<group> cache/
        ```

    3.  Create database

        ``` bash
        sudo mandb

        # If the database becomes corrupt, recreate it:
        sudo mandb -c
        ```

5.  LaTeXML

    ``` bash
    nix-env -qasP '.*LaTeXML.*'
    nix-env -qaA nixpkgs.perl538Packages.LaTeXML

    nix-env -iA nixpkgs.perl538Packages.LaTeXML
    ```

# Shell configuration

Clone the dot file repository <https://github.com/devnich/dotfiles> into your home directory and follow the installation instructions in the README. Note that some files (e.g., `.zshenv`, `.nix-channel`) may conflict with files you have already created during the setup process. If this happens, you should merge the contents of each "live" file into its respective repository version before running the `stow` command.

# Install Mamba

Davis Data Lab review: At UC Davis, most of the DataLab, several professors, and also the HPC admins use and recommend (Micro)mamba. We're also making Micromamba the preferred tool for installing userland software on servers in one of our upcoming workshops. Mamba has 147 contributors on GitHub to Conda's 424 and both have around 5.5k stars, so I'm not particularly worried about development unexpectedly stopping. Micromamba (but not Mamba) gets rid of the need for a base environment, which makes it harder for newbies to break. And as one sample point, I've been using it locally and on HPC servers for at least a year now without any problems.

<https://mamba.readthedocs.io/en/latest/>

## Install micromamba

cf. <https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html>

1.  Download and extract the latest release. For consistency with Anaconda, we are installing in the user's `opt/` directory.

    ``` bash
    cd ~/opt

    # Download for macOS Intel (x86_64)
    curl -LOJ https://micro.mamba.pm/api/micromamba/osx-64/latest
    # Alternatively, download for macOS Silicon/M1 (ARM64)
    curl -LOJ https://micro.mamba.pm/api/micromamba/osx-arm64/latest

    # Extract the micromamba binary
    tar -xf <filename>.tar.bz2 bin/micromamba
    ```

2.  Modify `.zshrc` to enable `micromamba` commands

    ``` bash
    ./bin/micromamba shell init -s zsh -p ~/micromamba
    ```

3.  Restart terminal

# Python Anaconda distribution

## Install for single user

Install Python 3 version. After installation, `which python` should report that Python is installed in `/Users/<your user name>/opt/anaconda3/bin/python`. If it reports the system Python location, copy the relevant lines from `.bash_profile` to `.zshrc`.

## Using Conda environments

1.  Deactivate Anaconda to use system Python or utilities

    ``` bash
    # Deactivate Anaconda install
    conda deactivate
    which python                    # outputs /usr/bin/python

    # Reactivate
    conda activate
    which python                    # outputs /Users/<user_name>/opt/anaconda3/bin/python
    ```

2.  Create a virtual environment

    1.  Option 1: Create an environment with selected libraries

        ``` bash
        conda create -n <env name> google-api-python-client pandas
        ```

    2.  Option 2: Create an environment cloned from a preexisting environment

        ``` bash
        conda create -n <env name> --clone base
        ```

    3.  Option 3: Create an environment following a YAML spec

        ``` bash
        conda env create -f <env file name>.yml
        ```

3.  Show environment

    ``` bash
    conda env list
    ```

4.  Switch to environment

    ``` bash
    conda activate <env name>
    ```

5.  Export current environment to YAML

    ``` bash
    conda env export > <env file name>.yml
    ```

6.  Install additional software with `pip` **Always do this last.** Conda cannot correctly install or update an environment that has been touched by `pip`.

    ``` bash
    pip install search_sampler
    ```

7.  Remove environment

    ``` bash
    conda env remove -n <env name>
    ```

8.  References

    1.  <https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html>
    2.  <https://docs.python.org/3/tutorial/modules.html>

## Installing packages

1.  Find new packages

    ``` bash
    conda search [-i/v] <package-name>
    ```

2.  Install new packages

    ``` bash
    conda install <package-name>
    ```

## Update Python, Conda, and Python packages

1.  Check for updates

    ``` bash
    conda update --all --dry-run
    ```

2.  Update conda package manager (may also update other packages)

    ``` bash
    # conda update -n base conda
    conda update -n base -c defaults conda
    ```

3.  Update default (base) environment

    ``` bash
    conda update --all
    ```

## Install Git drivers for Jupyter Notebooks

Install nbdime diff and merge tools in a Conda environment. You must use this environment for development and for Git actions.

1.  Create a new Conda environment. For testing purposes, do this first; for non-believers, do this at the end.

    ``` bash
    conda create -n <env name> --clone base
    conda activate <env name>
    ```

2.  Install nbdime

    ``` bash
    conda install nbdime
    ```

3.  Option 1: Enable nbdime for user account This will add a `~/.config/git/attributes` file and update the user's `.gitconfig` file (on MacOS and Linux)

    ``` bash
    nbdime config-git --enable
    ```

4.  Option 2. Enable nbdime for specific project This will add a `.gitattributes` file to the project and update the project's `.git/config` file.

    ``` bash
    nbdime config-git --enable --global
    ```

### References

1.  <https://nbdime.readthedocs.io/en/latest/installing.html>
2.  <https://nbdime.readthedocs.io/en/latest/vcs.html>

## Install Python Anaconda distribution for multi-user (NOT RECOMMENDED)

1.  If installing Anaconda on a lab machine, choose the multi-user installation
2.  In a multi-user installation, you cannot start Jupyter Lab from the Anaconda Navigator launcher. There are two work-arounds:
    1.  Launch the Anaconda Powershell prompt and run

        ``` bash
        python -m jupyterlab
        ```

    2.  Launch Jupyter Notebook. Edit the notebook URL, replacing \`\`\`tree\`\`\` with \`\`\`lab\`\`\`, and reload.

# Install R

1.  Install R from CRAN: <https://cran.r-project.org>

2.  Install RStudio IDE: <https://posit.co/products/open-source/rstudio/>

3.  Install XQuartz: <https://www.xquartz.org>

4.  Use R language manager to install useful libraries

    ``` r
    install.packages("tidyverse")

    # Required for building Hadley's Advanced R book
    install.packages(c("rmarkdown", "bookdown", "downlit", "lobstr", "sloop", "tinytex"))
    install.packages("devtools")
    devtools::install_github("hadley/emo")

    # Optional utilities
    install.packages("renv")
    install.packages("lintr")
    ```

5.  If installing TinyTeX (Bookdown dependency for generating PDFs), change owner of "/usr/local/bin"

    ``` bash
    sudo chown -R `whoami`:admin /usr/local/bin
    ```

6.  Install Jupyter kernel for R

    1.  Check whether R as a Jupyter kernel

        ``` bash
        jupyter kernelspec list
        ```

    2.  If R kernel not listed, install it

        ``` r
        install.packages('IRkernel')
        IRkernel::installspec()
        ```

7.  Update R packages. Do this after you update R.

    ``` r
    update.packages(ask = FALSE)
    ```

# Install Julia

1.  Install binary: <https://julialang.org/downloads/>

2.  Add Julia kernel to Jupyter Lab

    ``` r
    using Pkg
    Pkg.add("IJulia")
    ```

3.  Make Julia available in path

    ``` bash
    # Remove original /usr/local/bin/julia symlink if it exists
    ln -s /Applications/Julia-1.8.app/Contents/Resources/julia/bin/julia /usr/local/bin/julia
    ```

4.  Remove old kernel version from Jupyter Lab

    ``` bash
    jupyter kernelspec list
    jupyter kernelspec uninstall <kernel-name>
    ```

# (Optional) Assorted research and developer tools

## Build Bookdown book (e.g., "Advanced R")

c.f. <https://bookdown.org/yihui/bookdown/build-the-book.html>

1.  Test for dependencies via repeated failure

    ``` r
    bookdown::render_book()
    ```

2.  Build the PDF

    ``` r
    bookdown::render_book('index.Rmd', 'bookdown::pdf_book')
    ```

## Install CLAN

1.  Give full disk access to Terminal
    1.  Go to System Preferences → Security & Privacy → Full Disk Access
    2.  Check Terminal (or add with + if it doesn't already appear in the list of programs)
2.  Install XCode Command Line Tools
    1.  Open Terminal
    2.  Type "clang –version"
    3.  Follow prompts for installation
    4.  Report mysterious errors so we can learn together
3.  Download Unix CLAN
4.  Move folder to desired install location (I used \~/Code/unix-clan)
5.  Edit installation files in unix-clan/src according to the instructions found in unix-clan/src/0README.TXT
    1.  In unix-clan/src/makefile, uncomment all lines under "for Apple Unix AND FreeBSD \>= 3.2"
    2.  In unix-clan/src/common.h, update the "DEPDIR" variable: \#define DEPDIR "\<absolute-path-to\>/unix-clan/lib" (e.g. "/Users/gilgamesh/Code/unix-clan/lib")
6.  Compile
    1.  Open Terminal and cd into unix-clan/src
    2.  type "make"
7.  Add unix-clan/unix/bin directory to PATH
    1.  Create the \~/.zshrc file if it doesn't already exist
    2.  Add the following line to .zshrc: export PATH="\<absolute-path-to\>/unix-clan/unix/bin:\$PATH"
    3.  Quit and restart Terminal
8.  Test
    1.  cd into unix-clan/examples
    2.  Type "freq sample.cha"

## Compile and serve UC Love Data Week website locally with Jekyll

Documentation: <https://jekyllrb.com>

### Install

1.  Install Jekyll and dependencies

    ``` bash
    gem install bundler
    gem install jekyll
    gem install jekyll-sitemap
    gem install jekyll-seo-tag
    ```

2.  Update .bashrc and/or .zshrc

    ``` bash
    # Add Ruby Gems to path
    if which ruby >/dev/null && which gem >/dev/null; then
        PATH="$(ruby -r rubygems -e 'puts Gem.user_dir')/bin:$PATH"
    fi
    ```

3.  Serve web page from site directory

    ``` bash
    jekyll serve
    ```

### Project structure

1.  pages are composed of layouts and includes
2.  data from spreadsheet goes in data
3.  liquid is part of jekyll build process in github
4.  liquid statements can iterate through YAML files as if they are complex data structures
5.  content and dates pulled from workshops.yml
