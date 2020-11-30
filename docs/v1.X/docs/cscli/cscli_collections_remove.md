## cscli collections remove

Remove given collection(s)

### Synopsis

Remove given collection(s) from hub

```
cscli collections remove collection [flags]
```

### Examples

```
cscli collections remove crowdsec/xxx crowdsec/xyz
```

### Options

```
      --all     Delete all the files in selected scope
  -h, --help    help for remove
      --purge   Delete source file too
```

### Options inherited from parent commands

```
  -b, --branch string   Use given branch from hub
  -c, --config string   path to crowdsec config file (default "/etc/crowdsec/config.yaml")
      --debug           Set logging to debug.
      --error           Set logging to error.
      --info            Set logging to info.
  -o, --output string   Output format : human, json, raw.
      --trace           Set logging to trace.
      --warning         Set logging to warning.
```

### SEE ALSO

* [cscli collections](cscli_collections.md)	 - Manage collections from hub

