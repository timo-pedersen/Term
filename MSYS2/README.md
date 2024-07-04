- Install MSYS2
  - Run `pacman -Syuu` ad nauseum, restarting term until done
- Set up winterm (see below).
- Set up /home/{uid}/.bashrc (color ls, la &c)

# Winterm
JS: (note %USERPROFILE% and -use-full-path)
```js
,
            {
                "commandline": "C:/msys64/msys2_shell.cmd -defterm -here -no-start -use-full-path -ucrt64",
                "guid": "{17da3cac-b318-431e-8a3e-7fcdefe6d114}",
                "hidden": false,
                "icon": "C:/msys64/ucrt64.ico",
                "name": "UCRT64 / MSYS2",
                "startingDirectory": "%USERPROFILE%"
            }
```
