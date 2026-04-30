<img width="1116" height="392" alt="rebase" src="https://github.com/user-attachments/assets/91eccd27-9618-46ac-9d58-e67e2e9b0a42" />

# End Of Life Notice: Repository Rebase in Progress
This project is currently in process of being rebased on top of delta-v. This repository is no longer maintained and will be archived after our main server changes around 1st of March, 2026. Our new repository URL is https://github.com/Floof-Station/Panta-Rhei/ .

## Why are we doing this?
- First off, Wizden is planning to [dehub all servers that use an engine version older than 1 year](https://forum.spacestation14.com/t/we-will-now-have-an-engine-support-period-old-servers-must-update/25672/1), starting on the 1st of march, 2026. This means that this project cannot continue existing unless we upgrade 30+ engine versions up.
- We cannot update our engine version because of massive codebase incompatibilities. And we cannot merge wizden changes because EE made its codebase incompatible with wizden. And we are an EE fork.
- We cannot merge EE because our design and principles have diverged. EE focuses on writing sloppy code and unmaintainable code, and starting somewhere in 2025 began targetting LRP forks rather than MRP+ as its founders intended. Also, we are so far behind that even if we were to just merge with EE, it'd take us months to catch up.

As such, we've decided to rebase on top of Delta-v, the fork of Space Station 14 that Einstein Engines, the upstream of this fork, was based on.

This is a manual rebase, meaning that we are porting existing content on top of the delta-v codebase.

# Floof Station

<p align="center"><img src="https://raw.githubusercontent.com/Fansana/floofstation1/master/Resources/Textures/Logo/flooflogo.png" width="512px" /></p>

---

Floof Station is a whitelist-only 18+ Medium Roleplay furry-oriented server (ERP enabled), of the game [Space Station 14](https://spacestation14.com/). Anybody interested in checking us out or joining us, can apply for membership in our Discord linked down below.

Floof Station is a relaxing environment offering slow-paced, admin-driven events where members can develop their stories. The focus is on building meaningful interpersonal relationships, from friendships to romantic connections. This includes erotic roleplay, allowing members to explore and bring their wildest fantasies to life, all within a framework of mutual respect and consent.

Floof Station is a fork of [Einstein-Engines](https://github.com/Simple-Station/Einstein-Engines).

## Links

[Steam (WizDen Launcher)](https://store.steampowered.com/app/1255460/Space_Station_14/) (NOTE: in order to see us on the Hub, you will have to opt-in seeing 18+ servers in the filters!)

[Discord](https://discord.com/invite/floofstation) (NOTE: in order to access to the rest of the Discord, you will have to be whitelisted first!)

[Wiki](https://wiki.floofstation.com/index.php/Main_Page) (NOTE: you will need a SS14 account in order to access the Wiki!)

[Online Cookbook](https://heurl.in/ss14/recipes?fork=floof) (kindly provided by the wonderful Arimah <3)


## Contributing

We are happy to accept contributions from anybody, come join our Discord if you want to help!
We got a [list of issues](https://github.com/Fansana/floofstation1/issues) that need to be dealt with, which anybody interested is free to try and sort out. Don't be afraid to ask for help in the Discord if you need any!

## Building

Refer to [the Space Wizards' guide](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html) on setting up a development environment and for general information. But do keep in mind that Einstein Engines, the codebase Floof Station is based on, is an alternative codebase to the base one provided by WizDen, and many things may thus not apply nor be the same.
We provide some scripts shown below to make the job easier.

### Build dependencies

> - Git
> - .NET SDK 9.0.100


### Windows

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/bat/buildAllDebug.bat` after making any changes to the source
> 4. Run `Scripts/bat/runQuickAll.bat` to launch the client and the server
> 5. Connect to localhost in the client and play

### Linux

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/sh/buildAllDebug.sh` after making any changes to the source
> 4. Run `Scripts/sh/runQuickAll.sh` to launch the client and the server
> 5. Connect to localhost in the client and play

### MacOS

> I don't know anybody using MacOS to test this, but it's probably roughly the same steps as Linux

## License

Please read the [LEGAL.md](./LEGAL.md) file for information on the licenses of the code and assets in this repository.
