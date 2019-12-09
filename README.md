# Camunda Modeler Plugin: Resize Tasks

A Camunda Modeler plugin that makes tasks resizable. In case your _Grundstücksverkehrsgenehmigungszuständigkeitsübertragungsverordnung_ doesn't fit.

![Screencast](docs/screencast.gif)

## Using the Plugin

1. [Download ZIP](https://github.com/philippfromme/camunda-modeler-plugin-resize-tasks/archive/master.zip)
2. Extract
3. Move to [user data directory](https://github.com/camunda/camunda-modeler/tree/master/docs/search-paths#user-data-directory)
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