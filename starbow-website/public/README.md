# Public assets folder

A publicly accessible folder within which assets (images, css, etc.) are stored.

**DO NOT STORE SENSITIVE ASSETS HERE!** For sensitive assets which is used internally in the application, use the "/private" folder.

## Permission problems? Remember 0777

If files are unreachable, remember to apply correct permissions:

```
# chmod -R 755 public/
```
