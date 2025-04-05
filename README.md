# PeerFLow
A BitTorrent client built in Go that enables efficient file downloads through the BitTorrent protocol. It supports .torrent files and HTTP trackers while offering a straightforward command-line interface.

## Features

- **Lightweight and Minimalistic:** Focused solely on the essential functionality of a BitTorrent client.
- **Written in Go:** Leverages Go’s powerful concurrency model and simplicity.
- **.torrent File Support:** Downloads files using .torrent files.
- **HTTP Tracker Communication:** Connects to HTTP trackers to find peers.

## Install

```sh
go install github.com/ypratik817/PeerFLow@latest
```

## Usage
Try downloading [Debian](https://cdimage.debian.org/debian-cd/current/amd64/bt-cd/#indexlist)!

```sh
peerflow debian-10.2.0-amd64-netinst.iso.torrent debian.iso
```


## Contact

If you have any questions, suggestions, or feedback, please feel free to contact me at ypratik817@gmail.com.
