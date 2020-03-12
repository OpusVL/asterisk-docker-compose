# Asterisk PBX

Docker compose container set based on [`andrius/asterisk`](https://hub.docker.com/r/andrius/asterisk) tag `:latest` (Asterisk 15.x). Using Alpine Linux.

Only base Asterisk packages installed. If you want to add sounds, it's recommended to mount them as volume or data container, however you may install additional packages with `apk` command.

## Environment

Create a `.env` with the local users UID and GID.

See [`.env.example`](.env.example)

## Configuration

`./etc/asterisk` contains the original container configuration files.