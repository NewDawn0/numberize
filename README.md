# numberize
a tool for bash to display numbers in scientific and easier to read ways

## Installation
```
git clone
cd numberize
sudo cp numberize /usr/local/bin
```

## Usage
- As a pipe
  - Normal</br>
  `cat .zshrc | wc -c | numberize`
  - Scientific</br>
  `cat .zshrc | wc -c | numberize -s`
- As input
  - normal</br>
  `numberize $(cat .zshrc | wc -c)`
  - Scientific</br>
  `numberize -s $(cat .zshrc | wc -c)`
