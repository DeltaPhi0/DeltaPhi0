# Hi there, I'm Ken J. V. S. (A.K.A DeltaPhi0) from Italy!

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=1AF72E&background=FF2A5500&width=435&lines=Linux+Enthusiast;Cybersecurity+Focus;SOC+Analyst+Aspirant)](https://git.io/typing-svg)

![Visitor Count](https://komarev.com/ghpvc/?username=DeltaPhi0&style=flat-square&color=blueviolet)

## About Me
I am an aspiring Cybersecurity Analyst who loves getting my hands dirty with real-world projects. I started my tech journey back in October 2024, and things have escalated quickly since then! Right now, my main focus is developing the core skills needed for Security Operations Centers (SOC).

**My Learning Journey**:
- Currently studying: Rust programming, database logic with SQL, and advanced automation with Bash/Python.
- Passionate about: InfoSec, building incredibly efficient workflows, and breaking/fixing my own servers.
- Goals:
    - Master Rust and Python.
    - [OverTheWire](https://overthewire.org/wargames/) Bandit challenge [![Progress](https://img.shields.io/badge/Progress-100%25-purple)]() (Finished it!)
    - Deploy my first web page to the wild.
    - Complete Google's Foundations of Cybersecurity and TryHackMe's SOC 1 courses.

<div align="center">

## Technical Toolkit
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

## GitHub Activity

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=DeltaPhi0&layout=compact&theme=tokyonight)](https://github.com/DeltaPhi0)

## Active Projects

### [The Homelab Evolution](https://github.com/DeltaPhi0/homelab)
[![Explore Repo](https://img.shields.io/badge/Explore_Repository-2D333B?style=for-the-badge&logo=git&logoColor=white)](https://github.com/DeltaPhi0/homelab)

</div>

Since I first wrote this README, my infrastructure has gone through a massive overhaul. I recently retired my Raspberry Pi 3 as the main brain (though a huge shoutout and special thanks to my friend Leonard for giving it to me—it started this whole addiction!) and migrated everything to an ex-gaming PC.

**My Current Architecture & Security Setup**:
- **Remote Access & Wake-on-LAN**: I run a secondary, lightweight server that acts strictly as a VPN gateway. When I need my main server online, I connect to the gateway and send Magic Packets to wake the gaming PC.
- **Pre-Boot Decryption**: Security is a priority. The main server uses LUKS full-disk encryption. When it boots, it halts at an initramfs environment running Dropbear SSH. I remote in, provide the passphrase, and the system continues booting.
- **Networking**: All local traffic routing and custom domains are handled by a combo of Pi-hole (for DNS) and Nginx Proxy Manager.
- **Automated Backups**: I wrote a custom service that automatically archives my critical configuration files and data into a `tar.gz` and pushes it directly to my Google Drive.

**The Docker Fleet**:
Everything is containerized and managed via Portainer. My current stack includes:
- **Media & Books**: Radarr, Sonarr, Lidarr, Bazarr, Prowlarr, qBittorrent, Jellyseerr, Navidrome, Audiobookshelf, and Kavita.
- **Productivity & Data**: Immich (running the machine learning container for photo tagging), Trilium for notes, Anki Sync Server, and Code-Server so I can code from any browser.
- **Management & Monitoring**: Homarr, Dashdot, Uptime Kuma, Dozzle, Watchtower, and Deunhealth to keep containers in check.
- **Custom Projects**: 4gaboards (paired with a PostgreSQL 16 database).
- 

## What's Next?
- Diving deeper into Rust.
- Rebuilding my automated "Now Playing" script for Navidrome so it shows up live on my profile again.
- Setting up proper CI/CD pipelines.
- Always open to open-source collaboration—if you have tips on vaultwarden deployments or cool self-hosted projects, let me know!

## Contact

[![Email](https://img.shields.io/badge/Email-kenetsokoli601@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kenetsokoli601@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@DeltaPhi001-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/DeltaPhi001)
[![Discord](https://img.shields.io/badge/Discord-deltaphi0-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/deltaphi0)
