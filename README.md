# ApplejuiceCLI
ApplejuiceCLI is the backbone of Applejuice's interface, you can either use the interface or if you're big brain, you can use the CLI. (**Less bloat! Wow!**)

*Applejuice is a manager to get Roblox to run on Linux using Valve's Proton.*

## Installation

### Using the install script

1. Clone this repository.
2. Run `./install.sh`. (You may need to run `chmod +x ./install.sh` first)
3. Enter your sudo password to continue after the binary compiles.
4. Run `applejuicecli --install client` to install the Roblox!

### Manual

1. Clone this repository.
2. Make sure you have Rust installed.
3. Run `cargo build --release` in the repository.
4. Copy the compiled binary from `./target/release/applejuice_cli` to `/usr/local/bin` with the name `applejuicecli`.
5. Run `applejuicecli --init` to initialise the configuration directory.
6. Run `applejuicecli --install client` to install the Roblox!