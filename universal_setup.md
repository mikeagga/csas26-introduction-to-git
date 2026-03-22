Please complete this setup before the workshop. If you encounter issues, arrive
10 minutes early or reach out to [mikeag916@gmail.com].

Before the workshop date the following should be true:

- You can sign into a GitHub account and optionally set up SSH.
- You can open Git Bash (Windows) or terminal (other).
- Git is installed and version shows.

This document provides a brief tutorial for all the objectives mentioned above.

# Create GitHub Account
First, in your browser, please either create or sign into your GitHub account.

[GitHub sign up](https://github.com/signup)

It may also be beneficial to set up an SSH connection. You can follow the
official guide here:
(https://docs.github.com/en/authentication/connecting-to-github-with-ssh).
Although it is not required, it is good practice.

# Install Git on Your Computer

Next, you should have Git installed on your computer.

Regarding Git and its installation, you may fall into one of the groups below.
Please follow whichever path suits you:

## macOS

### Git is Installed

Open your terminal and run this command: `git --version`.

If a version is listed, then congratulations! You have Git installed on your
Mac. According to the official Git website, the latest version of Git is 2.53.0.
If you have an earlier version installed, you should still be able to follow
along, although it would be beneficial to update it.

You are all set up now!

### Git is NOT Installed (Install Git on macOS)

There are a few ways to install Git on your Mac, but the easiest is to use
Homebrew, a package manager that allows you to easily install other
applications.

Visit [brew.sh](https://brew.sh) in your browser. You will find the following
command:

``` 
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Copy and paste this command into your terminal.

**Tip:** Open the terminal by pressing Command + Space to launch Spotlight, then
search for "Terminal."

Once Homebrew has finished installing, run this command:

```
brew install git
```

Once installation is complete, verify Git is installed:

```
git --version
```

If a version appears, congratulations! You have successfully installed Git on
your Mac.

## Windows

### Git is Installed

Open your Start menu and search for "Git Bash."

If the application is installed, then congratulations! You have Git installed on
your Windows device. According to the official Git website, the latest version
of Git is 2.53.0. If you have an earlier version installed, you should still be
able to follow along, although it would be beneficial to update it.

You can check your Git version by opening Git Bash or Command Prompt and
running:


```
git --version
```

### Git is NOT Installed (Install Git on Windows)

The simplest way to install Git on Windows is to use the official Git installer.

Visit the official Git website: https://git-scm.com/install/windows

Download the "Standalone Installer." If you're on a 64-bit system, choose "Git
for Windows/x64 Setup."

After the download finishes, find the file and follow the installation
instructions.

Now search for "Git Bash" in your Start menu. If it appears, you have
successfully installed Git on your Windows device.

## Linux

Many Linux distributions have Git installed by default. To check, open your
terminal and run:

```
git --version
```

According to the official Git website, the latest version of Git is 2.53.0. If
you have an earlier version installed, you should still be able to follow along,
although updating it would be beneficial.

If the command is not found, your distribution may prompt you to install Git. If
it does, follow the installation instructions. Otherwise, use your default
package manager. If you're on Ubuntu, Mint, or Debian, run:

```
sudo apt install git
```

If you're on a different distribution and unsure which package manager to use,
search for instructions online. Although, the instructions should be similar.

## Other Operating Systems

Most users will fall into one of these categories. However, if you're on a
different operating system, I recommend searching online or consulting an AI
assistant for Git installation instructions specific to your system.
