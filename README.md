## Usage

Boot from the Artix Runit live ISO, then run:

```bash
git clone https://github.com/Dessemy/dotfiles && cd dotfiles && sudo bash setup
```

### Main keybindings (Super = MODKEY)

| Combo | What it does |
|---|---|
| `Super + Enter` | foot |
| `Super + Q` | qutebrowser |
| `Super + P` | hyprpicker |
| `Super + Shift + V` | Toggle VPN |
| `Super + S` / `Super + Ctrl + S` | Screenshot full / area |
| `Super + Tab` | Launcher |
| `Super + Y` | yazi |
| `Super + R` | rmpc |
| `Super + G` | gotop |
| `Super + B` | bluetui |
| `Super + W` | wiremix |
| `Super + I` | impala |
| `Super + J` / `Super + K` | Move focus to next/previous window |
| `Super + H` / `Super + L` | Shrink/grow the master area |
| `Super + Shift + I` / `Super + Shift + P` | Add/remove master windows |
| `Super + Space` | Switch layout |
| `Super + Shift + Space` | Toggle floating on the active window |
| `Super + E` | Toggle fullscreen |
| `Super + A` | Toggle gaps |
| `Super + Shift + B` | Toggle bar |
| `Super + Enter` (on focused window) | Zoom window to master |
| `Super + Ctrl + C` | Close active window |
| `Super + 1..9` | Switch to tag 1–9 |
| `Super + Shift + 1..9` | Send active window to that tag |
| `Super + 0` | Show all tags |
| `Super + ,` / `Super + .` | Move focus to left/right monitor |
| `Super + Shift + Q` | Quit dwl |

## VPN

The installer already sets up everything you need to toggle VPN. The only thing you have to add yourself is your own WireGuard config.

### setup

```bash
sudo cp ~/Downloads/ProtonVPN-*.conf /etc/wireguard/protonvpn.conf
sudo chmod 600 /etc/wireguard/protonvpn.conf
```
