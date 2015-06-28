# Public assets folder

A publicly accessible folder within which assets (images, css, etc.) are stored.

**DO NOT STORE SENSITIVE ASSETS HERE!** For sensitive assets which is used internally in the application, use the "/private" folder.

## Permission problems? Remember to chmod

If files are unreachable, remember to apply correct permissions:

```
# chmod -R 755 public/
```
This commonly happen if you add files downloaded from the Internet or if you create a file using an application, e.g. an image produced in Photoshop.
