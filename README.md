# wifi-password

> Get password of your wifi using its ssid.

## Install

You can install `wifi-password` using one of the options listed below

| Source | Command |
| --- | --- |
| curl | `curl -L https://raw.githubusercontent.com/ziishaned/wifi-password/master/installer.sh \| sudo sh` |
| npm | `npm install -g wifi-password` |
| manual | Clone and run `make install` |

## Usage

Simply run it inside your terminal and it will give you the output:

```bash
wifi-password <wifi-ssid>
```

## Options

You can pass several options to modify how `wifi-password` behaves

```bash
wifi-password [-i <wifi-ssid>] 
              [-v]
              [-h]
```

Here is the detail for each of the options 

| Option | Description |
| --- | --- |
| i | Specify the SSID of the network you want to get the password |
| v | Output version of bash script |
| h | Display the help screen |

For the basic usage, all you have to do is run `wifi-password` inside your terminal.

## Contributions

Feel free to submit pull requests, create issues or spread the word.

## License

MIT &copy; [Zeeshan Ahmad](https://twitter.com/ziishaned)
