# Microsoft-Font-For-Linux

## Sebelum install msfont, pastikan multiverse sudah terinstall

  - sudo apt update
  - sudo add-apt-repository multiverse
  - sudo apt update
  - sudo apt install ttf-mscorefonts-installer

## Setelah selesai melakukan install msfont, lakukan update font cache

  - sudo fc-cache -f -v
  - sudo apt update

## Jika tidak sengaja melakuan reject license agreement bisa langsung reinstall dengan cara berikut

  - sudo apt install –reinstall ttf-mscorefonts-installer
  - sudo apt update

## Reff

https://itsfoss.com/install-microsoft-fonts-ubuntu/
