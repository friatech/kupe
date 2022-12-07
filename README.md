# kupe

**kupe (Kubernetes profile exchanger)**  is a simple and handy tool for managing multiple kubernetes configuration files
and switching among them.


If you want to manage kubernetes contexts or kubernetes namespaces. You can check [kubectx](https://github.com/ahmetb/kubectx).

# Usage

```
Usage:
  kupe                                    list all available profiles
  kupe <profile name>                     switch to the <profile name>
  kupe -                                  switch to the previous profile
  kupe .                                  show the current profile name
  kupe <options>
Options:
  -s, --switch <profile name>             switch to the <profile name>
  -c, --current                           show the current profile name
  -r, --rename <new name>                 rename the current profile
  -r, --rename <profile name> <new name>  rename the given profile
  -d, --delete                            delete the current profile
  -d, --delete <profile name>             delete the <name> profile
  -a, --add <config file> <profile name>  add config file as given profile name
  -h, --help                              show the usage
  -v, --version                           show the version info
```
