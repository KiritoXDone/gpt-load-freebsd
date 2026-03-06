# cli-proxy-api-plus-freebsd

FreeBSD amd64 binary builds of [CLIProxyAPIPlus](https://github.com/router-for-me/CLIProxyAPIPlus), automatically compiled for [serv00](https://www.serv00.com/) (FreeBSD 14.x amd64).

Releases are checked and published weekly. You can also trigger a build manually via [Actions](../../actions).

## Download

Get the latest binary from [Releases](../../releases).

## Usage on serv00

```bash
# Download the binary (replace vX.X.X with the actual version)
wget https://github.com/KiritoXDone/gpt-load-freebsd/releases/latest/download/cli-proxy-api-plus-freebsd-amd64
# (Repository name remains historical: gpt-load-freebsd)

# Make it executable
chmod +x cli-proxy-api-plus-freebsd-amd64

# Run
./cli-proxy-api-plus-freebsd-amd64
```

For configuration and advanced usage, see the [CLIProxyAPIPlus documentation](https://github.com/router-for-me/CLIProxyAPIPlus).
