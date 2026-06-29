# get.plasma.sh

Install endpoint for [`plasmactl`](https://github.com/plasmash/plasmactl), the Plasma platform CLI.

```sh
curl -sSL https://get.plasma.sh | sh
```

Served via GitHub Pages. The root (`index.html`) and `get-plasmactl.sh` are the
same POSIX installer — it detects your OS/arch and downloads the matching
`plasmactl` binary from the latest GitHub release.

> The script is kept in sync with
> [`plasmash/plasmactl:get-plasmactl.sh`](https://github.com/plasmash/plasmactl/blob/master/get-plasmactl.sh).
