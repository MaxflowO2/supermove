# Supermove
## Source [here](https://serverfault.com/a/882821) by Peter
### How-to use
And make it executable:
`chmod +rx supermove`
And run it
`./supermove src/ dest/`
Now src/ should be just empty dirs. If so, you can `rm -r src` to clean up.

### Addons (from comments)
For mv pick one:
```
-f  force (always overwrite)
-i  interactive (ask whether to overwrite)
-n  no clobber (no overwrite)
```
And this is good too:
```-v  verbose```
