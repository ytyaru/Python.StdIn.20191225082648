[ja](./ReadMe.md)

# Python stdin

Stdin reading in Python.

# Requirement

* <time datetime="2019-12-25T08:26:41+0900">2019-12-25</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspbian](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2019-09-26 <small>[setup](http://ytyaru.hatenablog.com/entry/2019/12/25/222222)</small>
* bash 5.0.3(1)-release
* Python 2.7.16
* Python 3.7.3

```sh
$ uname -a
Linux raspberrypi 4.19.75-v7l+ #1270 SMP Tue Sep 24 18:51:41 BST 2019 armv7l GNU/Linux
```

# Usage

```bash
git clone https://github.com/ytyaru/Python.StdIn.20191225082648
cd Python.StdIn.20191225082648
./run.sh
```

There is stdin.

```bash
echo -e "A\n\tA11\n\t\tA111\nB" | ./a.py
```

Without stdin.

```bash
./a.py
```

Key|Result
---|------
<kbd><kbd>Ctrl</kbd>+<kbd>D</kbd></kbd>|Normal end
<kbd><kbd>Ctrl</kbd>+<kbd>D</kbd></kbd>|Exception occurs 
<kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd></kbd>|Forced termination

# Author

ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# License

This software is CC0 licensed.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.en)

