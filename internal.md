# Maintenance and Upkeep

## Updating

To push an update, use the vsce command line tool. It uses an azure personal access token for the [codifyberkeley organization](https://dev.azure.com/codifyberkeley/). 

```bash
vsce publish --no-dependencies
```

If the PAT is out of date, it will prompt you to enter a new one.

Reference [publishing an extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

The marketplace page can be found [here](https://marketplace.visualstudio.com/items?itemName=CodifyBerkeley.codify-extensions).

With each new push, you must update the version number in the package.json file.