[![Screenshot Generator Logo](https://imgur.com/bi7t3XU.png)](https://github.com/mvaneijgen/screenshot-generator-app)

> An app that will generate screenshots of all pages of a website on multiple devices

[![Screenshot Generator App Preview](https://i.imgur.com/pTSFKqk.png)](https://github.com/mvaneijgen/screenshot-generator-app)

## Getting Started

The app has a build in list of devcies of which you can select the once you want screenshots of. After that you can add a sitemap.xml of the site you want to generate a screenshot of. This can be h

## Table of Contents (Optional)

- [Installation](#installation)
- [Built With](#built-with)
- [Todo list](#todo-list)
- [FAQ](#faq)
- [Authors](#Authors)
- [Contributing](#contributing)
- [Support](#support)
- [License](#license)

## Installation

Download the latest version from the [Github Releases tab](https://github.com/mvaneijgen/screenshot-generator-app/releases)

### Want to edit the project?
#### Build Setup
##### Electron 
``` bash
# install dependencies
yarn
# or 
npm install

# serve with hot reload at localhost:8080
yarn electron:serve
# or 
npm run electron:serve

# build electron application for production
yarn electron:build
#or
npm run electron:build
```

##### Basic Vue.js
``` bash
# install dependencies
yarn
# or 
npm install

# serve with hot reload at localhost:8080
yarn run serve
# or 
npm run dev

# build electron application for production
yarn run build
#or
npm run build
```



## Todo list 

- [x] User interface
- [x] App icon
- [x] Node.js Puppeteer child process 
- [ ] Create a loading animation while node script is running

## Built With

* [Vue CLI Plugin Electron Builder](https://nklayman.github.io/vue-cli-plugin-electron-builder/guide/#installation) - Easily Build Your Vue.js App For Desktop With Electron
* [Puppeteer](https://github.com/puppeteer/puppeteer) - Puppeteer is a controllable Chrome browser this is what generates the screenshots 
* [Streamline Icons](https://streamlineicons.com) - Icon set 

## FAQ

- **Does this project work?**
    - Nope. Sadly it is stuck on running a Node.js Puppeteer script from Electron-vue. If that is fixed it will work like a charm.

## Authors
| [mvaneijgen](https://github.com/mvaneijgen) | 
| :---: |
| [![mvaneijgen](https://avatars1.githubusercontent.com/u/3217544?v=4&s=200)](http://fvcproductions.com)    |
| <a href="http://github.com/mvaneijgen" target="_blank">`github.com/mvaneijgen`</a> |
| Design & Development |

See also the list of [contributors](https://github.com/mvaneijgen/screenshot-generator-app/contributors) who participated in this project.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) - see the [LICENSE.md](LICENSE.md) file for details

