[![docs](https://img.shields.io/badge/docs-passing-success?style=flat-square)](https://discord.com/developers/docs/game-sdk/getting-started) [![npm (custom registry)](https://img.shields.io/npm/v/com.discord.gamesdk/latest?label=unity%40latest&logo=unity&registry_uri=https%3A%2F%2Fupr.iosoft.works&style=flat-square)](https://upr.iosoft.works/-/web/detail/com.discord.gamesdk)

# Discord Game Sdk

The Discord Game Sdk, repackaged for Unity.

## Documentation

Discord provides official documentation on the [Discord Developer Portal](https://discord.com/developers/docs/game-sdk/getting-started).

## Support

Official support for the Discord Game SDK can be found in the [Discord Developers](http://discord.gg/discord-developers) server.

## Installation

Inside Editor:

1. Add the scoped registry.
   ![](https://cdn.iosoft.works/assets/upr/docs/com.discord.gamesdk/add-scoped-registry.png)

2. Add the dependency.
   ![](https://cdn.iosoft.works/assets/upr/docs/com.discord.gamesdk/install-package.png)

or just modify your `manifest.json`:

```json
{
  "dependencies": {
    ...
    "com.discord.gamesdk": "3.1.0"
  },
  "scopedRegistries": [
    {
      "name": "io Softworks Registry",
      "url": "https://upr.iosoft.works",
      "scopes": [
        "com.discord"
      ]
    }
  ]
}
```
