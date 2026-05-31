# Shotokan

Shotokan is a custom fighting game project based on the open source engine [Ikemen GO](https://github.com/ikemen-engine/Ikemen-GO).

This project is not the original Ikemen GO engine. It is a modified and customized version created for our own game project. We changed the branding, added our own launcher files, adjusted the start experience, implemented custom characters, changed icons and names, and added custom keybinds and abilities.

## Project Changes

Compared to the original Ikemen GO project, Shotokan includes several custom changes:

* Custom project name: **Shotokan**
* New project icons and branding
* Custom start animation
* Custom `Shotokan_launch.command` file for starting the game
* Modified keybinds
* Custom abilities and gameplay adjustments
* Added and implemented characters, including:

  * Joe Biden
  * Ryu
  * Blu
  * Sol Red Guy
* Changed names and visual elements inside the project
* Adjusted files and resources for our own game version

## Legal Notice

Shotokan is based on Ikemen GO, which is open source and licensed under the MIT License.

All original Ikemen GO engine rights belong to the original Ikemen GO contributors. This project does not claim ownership of the original engine.

Some included or referenced assets, characters, names, images, sounds, animations, or icons may belong to their respective owners. These assets are used for educational, non-commercial, parody, fan-project, or demonstration purposes where applicable.

If any copyrighted material is included, the rights remain with the original creators or owners. This project should not be sold or distributed in a way that violates copyright, trademark, personality rights, or other applicable laws.

For public releases, every third-party asset should be checked carefully. Only assets with proper permission, open licenses, original creation, or legally allowed usage should be included.

## Setup

## Windows

To run Shotokan on Windows:

1. Download and unzip the zip in Releases
2. Start the game by running the Shotokan/Ikemen_GO executable or launcher command file.

Required files:

```text
lib/
Ikemen_GO.exe
```

The project folder should contain the required engine files, custom resources, characters, icons, and launcher files.

## macOS / Linux

On macOS or Linux, use the included `Shotokan_launch.command` file.

You may need to allow execution first:

```bash
chmod +x Shotokan_launch.command
```

Then start the game:

```bash
./Shotokan_launch.command
```


## About Ikemen GO

Ikemen GO is an open source fighting game engine that supports resources from the [M.U.G.E.N](https://en.wikipedia.org/wiki/Mugen_%28game_engine%29) engine. It is written in [Go](https://go.dev/) and is a complete rewrite of an earlier engine known as Ikemen.

Shotokan uses Ikemen GO as its technical base and builds a custom game project on top of it.

## Features

Shotokan aims to provide a customized fighting game experience based on Ikemen GO.

Main features include:

* M.U.G.E.N-compatible fighting game engine base
* Custom character roster
* Modified branding
* Custom icons
* Custom start animation
* Custom launcher
* Modified controls
* Custom abilities
* Own project structure and presentation

Ikemen GO itself aims for compatibility with M.U.G.E.N 1.1 Beta while also adding new features. More information about Ikemen GO can be found in the official Ikemen GO wiki.

## Running

Download or prepare the project folder for your operating system.

On Windows:

```text
Ikemen_GO.exe
```

or:

```text
Ikemen_GO.exe
```

depending on your build setup.

On macOS or Linux:

```text
Shotokan_launch.command
```


## Developing

This project contains custom content and modifications based on Ikemen GO.

For engine-level development, build instructions should follow the original Ikemen GO build process.

For Shotokan-specific development, you can edit:

* characters
* stages
* screenpack files
* icons
* launcher files
* keybinds
* abilities
* project branding
* start animation

## Troubleshooting

If the game does not start, check the following:

* Is the `lib/` folder included?
* Is `Ikemen_GO.exe` included on Windows?
* Are the `.command` files executable on macOS or Linux?
* Are all custom characters placed in the correct folder?
* Are character definitions correctly referenced?
* Are all required assets included?
* Are paths written correctly for your operating system?

On macOS or Linux, fix launcher permissions with:

```bash
chmod +x launcher.command
chmod +x Shotokan.command
```

## References

* [Original Ikemen GO repository](https://github.com/ikemen-engine/Ikemen-GO)
* [M.U.G.E.N engine information](https://en.wikipedia.org/wiki/Mugen_%28game_engine%29)
* [Go programming language](https://go.dev/)

## License

The original Ikemen GO engine is licensed under the MIT License.

Shotokan contains custom modifications and project-specific files. Custom files created by the Shotokan team belong to their respective creators unless stated otherwise.

Bundled third-party assets may use different licenses. Each asset should be checked separately before public distribution.

This project may statically link or use dependencies such as FFmpeg depending on the build. For original Ikemen GO licensing and dependency details, refer to the official Ikemen GO repository and release information.
