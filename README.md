# Copy token
This simple program copy github token from local file to clipboard. It gives you more fast using Git CLI

### Dependencies
- **xclip** available in package managers, such as _apt_, _pacman_

### Installation
#### First way
1. git clone https://github.com/AlGaRitm2020/copy_token
2. cd copy_token
3. mv copy_token /usr/bin/cptoken
4. sudo chmod +x /usr/bin/cptoken

#### Second way
Add _*alias cptoken="cat ~/PATH/TO/YOUR/TOKEN/token | xclip -sel clip"*_ to your shell config. If you are using bash, this file is ~/.bashrc

### How to use
Run in terminal command cptoken and your token will be copied to clipboard

