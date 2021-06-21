## hamonikr-cli-tools

하모니카OS에서 사용할 수 있는 유용한 CLI 프로그램을 설치하는 패키지입니다.

이 패키지는 CLI 에서 사용할 수 있는 아래와 같은 프로그램을 포함하고 있습니다.

Include packages
----------------
- icdiff (color diff)
- jq (json parser)
- D2Coding Regular font (Korean font)
- remote-share-cli (easy file share to remote)
- hamonikr-ff (fzf and bat features)
- speedtest-cli (network speed benchmark)
- w3m (terminal web browser)
- mtr (traceroute)
- network-manager nmtui (network setting tui)
- systemd-tui (systemd service management tui)
- ncdu (disk usage analysis)
- mc (terminal file manager)
- tldr (manual for command)
- fsarchiver (partition backup and restore)
- starship (mordern prompt for shell)
- htop (process viewer)
- glances (system monitoring tool)
- lazydocker (TUI for both docker and docker-compose)
- tmux (terminal multiplexer)
- ttyd (Share terminal over the web)
- aria2 (download utility - HTTP/HTTPS, FTP, SFTP, BitTorrent, Metalink)
- asciinema (Record and share terminal sessions)
- neofetch (show system infomation)
- web-search-cli (web search in your terminal)


# Install

## HamoniKR (>= 4.0)
```
sudo apt update
sudo apt hamonikr-cli-tools
```

## Ubuntu, LinuxMint (>=Ubuntu 20.04)

```
wget -qO- https://pkg.hamonikr.org/add-hamonikr.apt | sudo -E bash -
sudo apt hamonikr-cli-tools
```

# Remove
```
sudo apt purge -y hamonikr-cli-tools
sudo apt -y autoremove
``` 

## LICENSE
[LICENSE](./LICENSE)


