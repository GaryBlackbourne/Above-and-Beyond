# Create: Above and Beyond

A fork of Create's official Challenge-pack

More information on the original Project Page: 
https://www.curseforge.com/minecraft/modpacks/create-above-and-beyond

## Getting Started

### Prerequisites

- [Minecraft 1.16.5](https://www.minecraft.net/)
- [GD Launcher](https://gdlauncher.com/) or any other modpack launcher

### Single player

Download the [latest release](https://github.com/kiskoza/Above-and-Beyond/releases) 
as a .zip and start it with your favorite launcher.

### Server

1. Install docker
2. Download the server zip and the docker-compose.yml file from the 
[latest release](https://github.com/kiskoza/Above-and-Beyond/releases)
3. Start it with `docker compose up`

## Development

Get an API key, and put it in `.env` file. The build script can generate two 
outputs, one for the `client`, and one for the `server`. You may specify whichone
you would like as an argument. To build a new release with both outputs, use:

``` shell
$ bash build.sh server client
```


### Dependencies

- bash
- zip
- wget
- curl
- jq

## Contributing

Feel free to open PRs ;)

## Versioning

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions
available, see the [tags on this repository](https://github.com/kiskoza/Above-and-Beyond/tags).
