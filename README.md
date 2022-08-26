# Site-Status

## Funcionality ⚙️

Checks the status codes of websites (domain) and their subdomains, to see if they are up or down on the Internet.

## Requirements 🔧

```bash
┌─[root@kali]─[/]
└──╼ apt install jq
```

## Usage 📋

```bash
┌─[root@kali]─[/]
└──╼ ./sitestatus.sh <domain>
```

if you want to save it to a file, the use of ```tee``` is recommended.

```bash
┌─[root@kali]─[/]
└──╼ ./sitestatus.sh <domain> | tee status.txt
```

