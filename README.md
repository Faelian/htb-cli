# htb-cli

As I do more and more hackthebox, I grew tied of launching a browser every time to power up a machine, and remembering openvpn command.

This tool let you power up a machine from command line.

```bash
htb bashed up
```

## Configuration

To use this tool, you will need to define your API key. You will find it at [https://www.hackthebox.eu/home/settings](https://www.hackthebox.eu/home/settings).

```bash
htb config api-key [your api key]
```

It will be stored in the `.htb-config.json` in your home directory.


