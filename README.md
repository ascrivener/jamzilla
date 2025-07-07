# jamzilla
🦖

## Quick Start
```
./jamzilla -socket /path/to/socket -data /path/to/data
```

## Options
- `-socket <path>`: Unix socket path (default: /tmp/jam_target.sock)
- `-data <directory>`: Data directory (default: ./data)

## Notes
- This binary is built for Linux AMD64
- Expects messages sent over the socket to conform to the protocol defined in https://github.com/davxy/jam-stuff/blob/main/fuzz-proto/README.md.
