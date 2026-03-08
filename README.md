# dotfiles-wofi

Wofi launcher configuration.
Blurred, black, minimal.

---

## Stack

- **Launcher** : Wofi
- **Font** : Maple Mono NF

---

## Dependencies

```bash
sudo pacman -S wofi
yay -S maplemono-otf
```

---

## Install

```bash
git clone git@github.com:Hugo-Fabresse/dotfiles-wofi.git ~/dotfiles/wofi
ln -s ~/dotfiles/wofi ~/.config/wofi
```

The blur effect requires the following in `hyprland.conf` :

```ini
layerrule = blur, wofi
layerrule = ignorezero, wofi
```

---

## Content

```
wofi/
├── config
└── style.css
```
