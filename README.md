# rscope

A tool to fast-preview videos, pdfs, images, and txt/code files in iterm2.

## Technologies used - 
- bash

## 3rd party tools used - 
- [fzf](https://github.com/junegunn/fzf)
- md5sum
- [pdftoppm](https://man.archlinux.org/man/pdftoppm.1.en#:~:text=Pdftoppm%20converts%20Portable%20Document%20Format,%2C%20PPM%2Droot%2Dnumber.)
- [chafa](https://github.com/hpjansson/chafa)
- [ffmpeg](https://github.com/FFmpeg/FFmpeg)

## Installation

Install all the above mentioned libraries using Homebrew to run this.

## Run Locally

- Clone the project

```bash
  git clone https://github.com/rohinish404/rscope.git
```

- Go to you zshrc file, add the project directory to the path and source the file.
  
```bash
  vi ~/.zshrc
  #make changes
  source ~/.zshrc
```
- Type rscope in iterm2 to get something like in the demo below.
    

## Demo
https://github.com/user-attachments/assets/333b7369-5cab-4cb0-a35c-113cbc458fef

## Notes - 
- I have only used this in iterm2 and terminal (mac) so not sure about other terminals. Iterm2 it works best. Terminal, the navigation works but for some reason the previews are blurry.
- It's slow and buggy. Sometimes if you move fast, it breaks but i'd implemented sort of caching which will save all the previews in a dir. So second time when you open it, it doesnt break and is faster than earlier.
- I'll be further improving this whenever i get time to make it more faster.

## Thanks for trying out. Do star⭐️ the repo if you found this useful
