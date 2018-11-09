# How to install

Update the bundle submodule:

```
git submodule update --init --recursive
```

Save your old vim config:
```
cp ~/.vimrc ~/.vimrc_bak
```

Create a link:
```
ln -fs $(pwd)/vimrc ~/.vimrc
```

Install all plugins:
```
vim +:PluginInstall +:qall
```
