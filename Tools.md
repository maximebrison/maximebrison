# Machines

## Main computer

> Used for development, CAD, writing, video/photo editing, order my Collect&Go and the occasionnal "I haven't played this game in a long time, let's spend a whole week-end on it !".

### Specs

| Part | Model                                     |
| ---- | ----------------------------------------- |
| CPU  | AMD Ryzen 9 3900 (12C/24T @ 3.10GHz)      |
| GPU  | Gigabyte RTX 4060                         |
| RAM  | Corsair Vengeance 16Go DDR4 RAM (3200MHz) |
| OS   | Windows 11 Pro                            |

> Hoping to buy more RAM but... You know...

### Peripherals

| Part              | Model                                                        |
| ----------------- | ------------------------------------------------------------ |
| Primary monitor   | DELL U2724D - QHD                                            |
| Secondary monitor | DELL S3422DWG - QHD+                                         |
| Keyboard          | SteelSeries Apex RAW                                         |
| Mouse             | SteelSeries Rival 300                                        |
| Audio interface   | [Focusrite Scarlett 2i2 4th gen Audio Interface](https://focusrite.com/en/usb-audio-interface/scarlett/scarlett-2i2) |
| Microphone        | Focusrite CM25 mkIII microphone                              |
| Headphones        | JBL Live Flex                                                |

> Yeah the JBL Live Flex has nothing to do here, but I lent my *Focusrite HP60 mkIII headphones* to a friend, and always forget to ask for it back... Considering maybe buying a Sennheiser someday, like [these ones](https://www.sennheiser.com/fr-be/catalog/products/casque-decoute/hd-490-pro/hd-490-pro-700286).

## Laptop Dell Inspiron 16 7640

> Mainly used when visiting my mom and she has issues with her Internet.

### Specs

| Part    | Model                                  |
| ------- | -------------------------------------- |
| CPU     | Intel Core Ultra 7 (16-Cores @ 4.8GHz) |
| GPU     | Intel Arc Graphics                     |
| RAM     | 16Go LPDDR5X RAM                       |
| Monitor | 16" QHD MiniLED Touch display          |
| OS      | Linux Fedora 46                        |

## Homelab #1 - Intel NUC 7i7BNH

> Really energy efficient, small, quiet... The best for small utilities like DNS, VPN and even a NAS !

### Specs

| Part | Model                                |
| ---- | ------------------------------------ |
| CPU  | Intel Core i7-7567U (2C/4T @ 4.0GHz) |
| GPU  | Intel Iris Plus Graphics 650         |
| RAM  | 16Go DDR4 RAM                        |
| OS   | Proxmox VE 8.4.0                     |

### Services

- VM Debian with Docker
    - [WireGuard](https://www.wireguard.com/)
    - [Pi-hole](https://pi-hole.net/)
    - [Caddy](https://caddyserver.com/)
- [TrueNAS Community](https://www.truenas.com/)

### Notes

Yes, for a NAS a NUC seems like an *odd* choice, but if you didn't know, on this model you have a **full-sized M.2 slot with 4x PCIe 3.0** inside. I bought a cheap [M.2 to 6x SATA adapter](https://www.amazon.com.be/dp/B0BVMC37SX?ref=ppx_yo2ov_dt_b_fed_asin_title) from Amazon, scrapped the NUC's backplate and started working on a casing for my hard drives. More on that later !

## Homelab #2 - HP EliteDesk 800 G1

> Well, the most powerful machine I had lying around (among two other builds with i5 3rd gen, ferocious competition...), so I use it for remote dev and *(for now)* production. 

#### Specs

| Part | Model                               |
| ---- | ----------------------------------- |
| CPU  | Intel Core i7 4790 (4C/8T @ 4.0GHz) |
| GPU  | Nvidia Geforce GT 730               |
| RAM  | 32Go DDR3 RAM                       |
| OS   | Proxmox VE 8.4.0                    |

#### Services

- Debian VM with Docker *(prod)*
    - [MasonCMS](https://maximebrison.cc/?page=github1217274231)
- Debian VM with Docker *(dev)*
