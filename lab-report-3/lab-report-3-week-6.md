# Lab Report 3

## Stremalining ssh Configuration

* Create a config file in ssh and input the necessary lines
  * ![Image](1.1.png)

* Use the ssh command to log into the account now with only `ssh ieng6`
  * ![Image](1.2.png)

* Use scp to copy in a file. `scp < filename > ieng6:~/`
  * ![Image](1.3.png)

## Setup Github Access from ieng6

* Where the public key is stored on Github
  * ![Image](2.1.png)

* Where the private key is stored on my user account 
  * ![Image](2.2.png)
* Git command to commit and push a change to lab report to Github while logged into ieng6
  * ![Image](2.31.png)
* [Link for the resulting commit](https://github.com/xicoreyes513/markdown-parser-copy/commit/eb2fad18e33c4708c1b4a1672df9656bf790ead5)

## Copy whole directories with `scp -r`

* Copying entire markdown-parse directory to ieng6 
  * ![Image](3.1.png)
* Loggin in to ieng6 and compiling the tests 
  * ![Image](3.2.png)
* Combining `scp`, `;`, and `ssh`
  * ![Image](3.3.png)