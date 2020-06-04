# typescript-npm-module
This is a template, for creating a typescript module, which can be published to npm.

I recommend changing the name in package.json, to uniquely identify your library.

Run "npm watch", to watch for changes.

Run "npm link", to publish it locally, only you have access to it.

Run "npm link <library name>", to install the library locally,
be aware that you will NOT be able to publish to providers like heroku this way, as your library is not added to package.json.

Run "npm publish", to publish the library publically to npm, this way you can use it with providers like heroku, but be aware it is publically available to everyone!

To publish your package privately, use a scoped package name, <npm username>/<library name>.

For more information regarding private packages check out https://www.youtube.com/watch?v=O6JoXGnHK_Y.

Regards!
