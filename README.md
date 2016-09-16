# pmxkcd
pmxkcd (Poor Man's XKCD) is a desktop XKCD webcomic viewer and downloader for Linux.


### Features :

  - View-Download current XKCD webcomic.
  - View-Download random XKCD webcomic.


### Dependencies :

  - YAD - YAD (yet another dialog) is a tool to create graphical dialogs from shell scripts. [YAD] is available in repositories of some Linux distributions. You can use following links to get YAD if it is not shipped by your distribution,

    http://www.ubuntuupdates.org/package_metas?exact_match=1&q=yad

    http://pkgs.org/download/yad


### Installation :

Download [pmxkcd-master] zip,
Extract its contents to a folder,
Open that folder in Terminal,
Give 'install-pmxkcd' the 'execute' permission,
```sh
chmod 755 install-pmxkcd
```

Run 'install-pmxkcd' script,
```sh
sudo ./install-pmxkcd
```
Or if you prefer 'su' over 'sudo',
```sh
su -c ./install-pmxkcd
```


### Removal :

Get [pmxkcd-master] zip,
Extract its contents to a folder,
Open that folder in Terminal,
Give 'remove-pmxkcd' the 'execute' permission,
```sh
chmod 755 remove-pmxkcd
```

Run 'remove-pmxkcd' script,
```sh
sudo ./remove-pmxkcd
```
Or if you prefer 'su' over 'sudo'
```sh
su -c ./remove-pmxkcd
```


### Usage :

After installation you will find 'pmxkcd' entry in your applications menu. You can also run it via Terminal by typing 'pmxkcd' and hitting Enter. After launching 'pmxkcd', to view current XKCD webcomic click on 'Current' button and to view a random XKCD webcomic click on 'Random' button. XKCD webcomics will be saved in user's '~/Pictures/xkcd' directory.


### Screenshot :

![alt text](https://github.com/hakerdefo/pmxkcd/blob/master/pmxkcd.png "pmxkcd")


### License :


[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">pmxkcd</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/pmxkcd)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.


[YAD]:https://sourceforge.net/projects/yad-dialog/
[pmxkcd-master]:https://github.com/hakerdefo/pmxkcd/archive/master.zip
