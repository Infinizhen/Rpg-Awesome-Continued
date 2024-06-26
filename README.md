# [RPG Awesome Continued](http://nagoshiashumari.github.io/Rpg-Awesome/)
### A fantasy themed font and CSS toolkit.

RPG Awesome is a suite of 495 pictographic, rpg and fantasy themes icons for easy scalable vector graphics on websites, continued by [Miguel Rodríguez](https://github.com/Infinizhen) and originally created by [Daniela Howe](https://github.com/nagoshiashumari) and [Ivan Montiel](http://github.com/idmontie).

Super shoutout to [Game Icons](https://game-icons.net/) for providing a library of SVG icons that we used to create this project 🎉.

## Installation

### NPM

```
npm add --save @infinizhen/rpg-awesome-continued
```

Then in your code, you can use rpg-awesome by pathing to it:

```
./node_modules/rpg-awesome/css/rpg-awesome-continued.min.css
```

If you are using Sass, you can import it directly:

```
@import "node_modules/@infinizhen/rpg-awesome-continued/scss/rpg-awesome-continued";
```

## Developing

This project uses NPM and Grunt to compile SCSS into CSS usable by browsers.
The project also requires for you to have Ruby installed:

```sh
npm install
gem update --system && gem install scss-lint
grunt
```

## Generating and Adding New Icons

We have split up the generation process of the `/fonts` directory to
[this repo](https://github.com/nagoshiashumari/rpg-awesome-raw).

Any new icons will need to be added to that repo first. Then follow the steps located in that repo's documentation for generating new `.eot`, `.svg`, `.ttf`, and `.woff` files.

Note that when adding new icons to the font files, you will need to update the `scss/_variables.scss` file with all of the new offsets.


## License
- The Rpg Awesome font is licensed under the SIL OFL 1.1:
  - http://scripts.sil.org/OFL
- Rpg Awesome Continued CSS and SASS files are licensed under the MIT License:
  - http://opensource.org/licenses/mit-license.html
- The Rpg Awesome Continued documentation is licensed under the CC BY 3.0 License:
  - http://creativecommons.org/licenses/by/3.0/
- Attribution is appreciated but not required
- Full details: https://github.com/infinizhen/Rpg-Awesome-Continued/blob/master/LICENSE.md
