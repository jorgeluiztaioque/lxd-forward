
# lxd-forward

A simple script to simplify port forward for LXD containers.

![https://www.ubuntu.com/containers/lxd](https://github.com/jorgeluiztaioque/lxd-forward/blob/master/lxd.png?raw=true)

## Download

```bash
wget https://raw.githubusercontent.com/jorgeluiztaioque/lxd-forward/master/lxd-forward
chmod +x lxd-forward
```

## Usage

```
./lxd-forward

Usage: lxd-forward
  list
  add [ip_version v4/v6] [container] [port] [host port]
  del [ip_version v4/v6] [rule_number]

  Example:
  list
  add v4 ubuntu 80 80
  add v6 ubuntu 80 80
  del v4 1
  del v6 1
```