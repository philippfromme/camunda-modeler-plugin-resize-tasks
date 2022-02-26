[![Compatible with Camunda Modeler version 4.0](https://img.shields.io/badge/Camunda%20Modeler-4.0+-blue.svg)](https://github.com/camunda/camunda-modeler)

# Camunda Modeler Plugin: Resize Tasks

A Camunda Modeler plugin that makes tasks resizable. In case your _Grundstücksverkehrsgenehmigungszuständigkeitsübertragungsverordnung_ doesn't fit.

![Screencast](docs/screencast.gif)

## Using the Plugin

1. [Download ZIP](https://github.com/philippfromme/camunda-modeler-plugin-resize-tasks/archive/master.zip)
2. Extract
3. Move to [app data directory](https://github.com/camunda/camunda-modeler/tree/master/docs/search-paths#app-data-directory) or [user data directory](https://github.com/camunda/camunda-modeler/tree/master/docs/search-paths#user-data-directory) (make sure to move the plugin, not its parent directory)
4. Restart Camunda Modeler

## Building the Plugin

Install dependencies:

```sh
npm install
```

Package plugin to `client/client-bundle.js`:

```sh
npm run bundle
```

or

```sh
npm run bundle:watch
```

## Additional Resources

* [Plugins documentation](https://github.com/camunda/camunda-modeler/tree/master/docs/plugins)

# Licence

MIT
