# gpt-load-freebsd

FreeBSD amd64 binary builds of [gpt-load](https://github.com/tbphp/gpt-load), automatically compiled for [serv00](https://www.serv00.com/) (FreeBSD 14.x amd64).

Releases are checked and published weekly. You can also trigger a build manually via [Actions](../../actions).

## Download

Get the latest binary from [Releases](../../releases).

## Usage on serv00

```bash
# Download the binary (replace vX.X.X with the actual version)
wget https://github.com/KiritoXDone/gpt-load-freebsd/releases/latest/download/gpt-load-freebsd-amd64

# Make it executable
chmod +x gpt-load-freebsd-amd64

# Run
./gpt-load-freebsd-amd64
```

For configuration and advanced usage, see the [gpt-load documentation](https://www.gpt-load.com/docs).
