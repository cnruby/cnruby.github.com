---
layout: page
title:  "How to access a git repository using SSH?"
tagline: "</br>Ubuntu 20.04"
date:   2020-11-29 15:24:35 +0200
tags: [GitHub, git, SSH, Ubuntu]
categories: ubuntu
---



## 1. install git and xclip
```bash
sudo apt-get update
sudo apt-get install git
sudo apt-get install xclip
```

## 2. Generating a new SSH key and adding it to the ssh-agent
```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

## 3. Copy the SSH key to your clipboard
```bash
xclip -selection clipboard < ~/.ssh/id_ed25519.pub
```

## 4. Adding a new SSH key to your GitHub account
```bash
login your GitHub >> your profile >> Settings >>
SSH and GPG keys >> New SSH key >> add a descriptive label for the new key >>
Paste your key into the "Key" field(Ctrl+C) >> Add SSH key
```

## references
- https://askubuntu.com/questions/527551/how-to-access-a-git-repository-using-ssh
- https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh