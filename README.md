<p align="center"> <img alt="Space Station 14" width="880" height="200" src="https://github.com/funky-station/funky-station/blob/master/Resources/Textures/Logo/logo.png" /></p>

This is a fork from the Wizard's Den "Space Station 14" repo, called Funky Station. To prevent people forking RobustToolbox, a "content" pack is loaded by the client and server. This content pack contains everything needed to play the game on one specific server.

## Links

[Funky Station Discord Server](https://discord.gg/5FqgaAA2qF)

## Documentation/Wiki

The [Funky Station Developer Documentation](https://docs.funkystation.org/) has information on how to contribute to Funky Station. It contains guides, game design documents and helpful tips on how to contribute to a repository.

## Contributing

We welcome everyone to contribute to our fork. Please join our Discord for collaborating!
We recommend you read the contribution guidelines. [Contribution Guidelines](https://docs.spacestation14.com/en/general-development/codebase-info/pull-request-guidelines.html)

## Building

We provide some scripts shown below to make the job easier.

### Build dependencies

> - [Git](https://git-scm.com)
> - [.NET SDK 9.0.101](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)

### Windows

> 1. Clone this repository
> 2. Run `Scripts/bat/buildAllDebug.bat` after making any changes to the source
> 3. Run `Scripts/bat/runQuickAll.bat` to launch the client and the server
> 4. Connect to localhost in the client and play

### Linux

> 1. Clone this repository
> 2. Run `Scripts/sh/buildAllDebug.sh` after making any changes to the source
> 3. Run `Scripts/sh/runQuickAll.sh` to launch the client and the server
> 4. Connect to localhost in the client and play

### MacOS

> I don't know anybody using MacOS to test this, but it's probably roughly the same steps as Linux

If your changes are under the resources folder, you do not need to build more than once, only run.

[More detailed instructions on building the project.](https://docs.spacestation14.com/en/general-development/setup.html)

## License

This repository uses REUSE Specification headers to determine the appropriate license for each file. Supported licenses are can be found in the LICENSES/ directory. All contributions to this repository are assumed to be MIT unless otherwise specified by the author, which will be reflected in the REUSE Specification headers.

Most media assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and the copyright in the metadata file. [Example](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Note that some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.

If you find that your work is misattributed or someone elses work is misattributed, please create an issue on this repos GitHub page, or email the Funky Station Maintainers @ `maintainers@funkystation.org`.

