 ### Linux ###

```
git clone https://github.com/tank-trax/DAFx19-Gamelanizer.git
cd DAFx19-Gamelanizer
git checkout linux
git submodule update --init --recursive
cd Plug-in
```

* Open Gamelanizer_Linux.jucer in Projucer
* Save

```
cd Builds/LinuxMakefile/
make CONFIG=Release
```
