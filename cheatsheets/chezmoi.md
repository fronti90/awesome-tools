# chezmoi cheat sheet

## get data

```bash
chezmoi data
{
  "chezmoi": {
    "arch": "amd64",
    "fqdnHostname": "FQDN",
    "group": "USER",
    "homeDir": "HOMEDIR",
    "homedir": "HOMEDIR",
    "hostname": "HOSTNAME",
}
```

## jump into local repository

```bash
chezmoi cd
```

## checkout remote repository

```bash
chezmoi init https://github.com/username/dotfiles.git
```

## add dotfile as template

```bash
chezmoi add --autotemplate ~/.ssh/config
```

## edit dotfile

```bash
chezmoi edit ~/.ssh/config
```

## apply configuration

```bash
chezmoi diff
chezmoi apply
```

## pull configuration

```bash
chezmoi update
```
