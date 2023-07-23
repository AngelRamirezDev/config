Creado el 22 de julio del 2022

# Config

```shell
mkdir ~/gitLocal
```

## Git

```shell
    git config --global user.name "Angel Ramirez"
    git config --global user.email miguelangel8877@outlook.com
    git config --global core.editor "code --wait"
    git config --global -e
```

### salto de linea

#### linux

```shell
    git config --global core.autocrlf input
```

#### windows

```shell
    git config --global core.autocrlf true
```

## oh my bash

```shell
bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"
```

### Cambiar tema

- robbyrussell
- rr

```shell
code ~/.bashrc
```

# Arch

## Problemas con paquetes

```shell
pacman -Sy archlinux-keyring
```

luego, forzar actualización

```shell
pacman -Syyu
```

## VSCode

```shell
yay -S visual-studio-code-bin
```

## Pamac

```shell
yay -S pamac-all
```

## Programas

Activar AUR y Flatpak

- microsoft-edge-stable-bin (AUR)
- visual-studio-code-bin (AUR)
