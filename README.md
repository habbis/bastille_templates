# Bastille Templates

based on bastille [templates](https://github.com/BastilleBSD/templates/tree/main)


## Usage
To use templates you must have git installed on your system.
```shell
pkg install git
```

## Bootstrap
```shell
bastille bootstrap https://github.com/bastillebsd/templates
```

## Bastille Usage
```shell
bastille template TARGET [category/port]
```

## Rocinante Usage
```shell
rocinante template [category/port]
```

### Bastille Examples
```shell
bastille template TARGET www/nginx
bastille template TARGET shells/zsh
bastille template TARGET lang/python311
bastille template TARGET databases/mariadb1011-server
...etc...

```

### Rocinante Examples
```shell
rocinante template x11/slim
rocinante template net/openntpd
```
