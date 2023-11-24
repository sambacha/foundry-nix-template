# [nix : foundry template](https://github.com/sambacha/foundry-nix-template/)

![](https://img.shields.io/badge/license-UPL--1.0-black) [![nix - flakes](https://img.shields.io/badge/nix-flakes-black?logo=nixos&logoColor=white)](#)  [![solidity - > 0.9.0](https://img.shields.io/badge/solidity->_0.9.0-2ea44f?logo=solidity)](#)

## Requirements

### Nix

[Use the Determinate Systems Installer](https://github.com/DeterminateSystems/nix-installer#usage)

```bash
curl --proto '=https' --tlsv1.2 -sSf -L https://install.determinate.systems/nix | sh -s -- install
```

### Foundry
```bash
curl -L https://foundry.paradigm.xyz | bash
```


## Usage

>**Warning**
> Must have Nix

in `/nix/packages.nix`

Change this to your package name
```nix
pname = "foundry-nix-template";
```

## License
 
 Licensed under

 * Universal Permissive License 1.0
   ([LICENSE-UPL](LICENSE-UPL) or https://opensource.org/licenses/UPL)

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Universal Permissive License v 1.0 
license, shall be dual licensed as above, without any additional terms or conditions.
