[README.md](https://github.com/user-attachments/files/35046062/README.md)
# Cooperative Warfare - Launcher

One launcher (Windows, Go + embedded web UI) for all four co-op projects: MW3 (TeknoMW3), Black Ops 1, NX1 and Blacksmith/S1 (ReXGlue). Handles game paths, launch options, the S1 GPU presets and keyboard/mouse layout, and installs the S1 Fusion patch sets.

**No game data is in this repo**, and the S1 patch sets are not embedded: build them with the tools in the S1 repo and put them in `launcher/s1patch/<set>/` before building.

Build: `cd launcher && GOOS=windows GOARCH=amd64 go build -ldflags "-H=windowsgui -s -w"`.

Related repos: `cooperative-warfare-s1`, `-mw3`, `-bo1`, `-nx1`.

Licence for our own code: MIT (see LICENSE).
