# WireGuard Mesh Configurator

## 1.1.2 (October 15, 2018)

1. Added output path detection.
1. Added profile exporting path detection.
1. Ask user if a output directory should be made if it doesn't exist.

## 1.1.1 (October 15, 2018)

1. Added endpoint generation.
2. Added "ShowPeers" command to show current config.
3. Added "AddPeers" command to append peers to current config.

## Introduction

WireGuard mesh configurator is a tool that will help you generating peer configuration files for wireguard mesh networks. You generate configuration files for a large amount of peers easily and quickly via this tool.

## Gallery

![new_profile](https://user-images.githubusercontent.com/21986859/46922682-bb7aaf80-cfda-11e8-812e-b2458009302a.png)
*Creating a new mesh profile*

![save_load](https://user-images.githubusercontent.com/21986859/46922686-c9303500-cfda-11e8-9685-062a8a24ed27.png)
*Saving and Loading Profiles*

![generated_configs](https://user-images.githubusercontent.com/21986859/46964450-17464680-d076-11e8-9306-bfe69a88c858.png)
*Generated configuration files*

## Usages

Clone the repository and enter it.

```
$ git clone https://github.com/K4YT3X/wireguard-mesh-configurator.git
$ cd wireguard-mesh-configurator/
```

Create a temporary folder for exporting configuration files.

```
$ mkdir /tmp/wireguard
```

Run the tool.

```
$ python3 wireguard_mesh_configurator.py
```

Then you will find all the generated configuration files under `/tmp/wireguard`.