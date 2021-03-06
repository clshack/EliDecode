# EliDecode
EliDecode is a tool to decode obfuscated shellcodes using the [unicorn-engine](https://unicorn-engine.org) for the emulation and the [capstone-engine](https://capstone-engine.org) to print the asm code.
Please note I should post news on my [website](https://developpsoft.github.io).

# Architectures
EliDecode support 6 architectures, and I will add new ones as soon as possible :smile:.
Here is the updated list:
 - x86 (16, 32 and 64 bits)
 - arm (thumb, 32 and 64 bits)
 - mips (3, 32, 32r6 and 64 __little and big endian__)

# Installing
Just install python 2 (I may upgrade it to python 3 later...) and use install.py :smile:.
For example:
```sh
sudo apt install python python-dev python-setuptools git
git clone https://github.com/DeveloppSoft/EliDecode
cd EliDecode
sudo ./install.py --unicorn --capstone
./decoder.py --help
```

# Contributing
You can contribute in many ways like reporting bugs, adding new features, donating...

# Credits
EliDecode is a fork of [unicorn-decoder](https://github.com/mothran/unicorn-decoder).
=======
THE tool to decode obfuscated shellcodes using the unicorn engine by [DeveloppSoft](https://developpsoft.github.io), original repo [here](https://github.com/DeveloppSoft/EliDecode).
It currently support 6 architectures and more are coming (see the TODO list) !!


# Install
```
git clone https://github.com/unicorn-engine/unicorn
cd unicorn
sudo ./make.sh install
cd bindings/python
sudo make install

cd ../..

git clone https://github.com/aquynh/capstone
cd capstone
sudo ./make.sh install
cd bindings/python
make install

cd ../..

git clone https://github.com/DeveloppSoft/EliDecode
cd EliDecode/Eli.Decode
python decoder.py --help
```


# Usage
## Coming soon...


# Contributing
You can contribute to EliDecode by:
## Donating
If you like my work, please considermaking a donation (button coming soon).
## Coding
Please do pull requests to improve EliDecode by adding to features.
## Reporting
If you have problems with EliDecode please open an issue.
## Ideas
If you know how to improve EliDecode but don't know how to do it, don't hesistate to open an issue!
## Sharing and promoting
You can share EliDecode if you want (under the terms of the license), for example by speaking about it on your website or making videos.
## Everything else...
There is many unquoted ways to contribute...


# TODO
- [x] x86_16
- [x] x86_32
- [x] x86_64
- [x] arm_thumb
- [x] arm32
- [x] arm64
- [x] mips_3
- [x] mips_32
- [x] mips_32r6
- [x] mips_64
- [ ] build as a python module
- [ ] add nice colors
- [ ] add more testcases


# Credits
This code is based on unicorn-decoder. Finally, I want to thanks everybody which gave me time there.


# Contributors
- DeveloppSoft: project's owner (https://github.com/DeveloppSoft).
- Nguyen Anh Quynh: fixed markdown, made the capstone and unicorn engines (https://github.com/aquynh).
