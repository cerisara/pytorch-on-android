# pytorch-on-android

I tried the original recipe int the repository this one is forked from, but it failed
with an error about failing to write some SHA1 file when cloning the git repository.

So I rather tried this modified version, which seems to work:

# Version without compilation

install pytorch on android


Requirements :

Install Termux from F-Droid

Install Archlinux from https://sdrausty.github.io/TermuxArch/docs/install.html

Clone this repository

Install :

Run Termux

Run startarch

Run setuppytorch.sh

It's likely to fail during this last step, but then, you may want to rather run from this repository:

```
pip install numpy
pip install pytorch*.whl
```
