# HTML5/JavaScript implementation of iKuh

This repository is supposed to contain an HTML5/JavaScript implementation of iKuh that is open source and can be played on github pages. The original iKuh desktop version can be downloaded [here](https://github.com/ikuh/ikuh.desktop).

There already exists an HTML5/JavaScript version, which we implemented for the clay.io Got Game? competition. Unfortunately we can't just push the code to github. There are some things that we need to take care of:

1. Fixing the dependency to clay.io. Since July the API of clay.io seems to have changed. The previous path to the api library doesn't exist anymore. This leads to weird strict MIME-type checking errors, because clay.io returns a blank page instead of a 404. We want to have iKuh running on clay.io again before we start with moving it to github pages.

2. Removing the dependency to clay.io, because github pages has nothing to do with the clay-api. Unfortunately you can't use github pages with a private repository. We have to be able to open source the code before we can move to github pages.

3. Removing the dependency to ImpactJS, because the license doesn't allow us to open source its code and without the library no one would be able to just check out the code and run the game.

These steps have to be done in a private repository, because of the ImpactJS library.


## Contributors

[Martin Krueger](https://github.com/mkaydev)

[Marvin Killing](https://github.com/mkilling)

[Michael Goderbauer](https://github.com/goderbauer)

[Peter Retzlaff](https://github.com/peret)
