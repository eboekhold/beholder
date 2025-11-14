# Beholder

An Ionic application to show monsters created on the [Monster Maker](https://github.com/eboekhold/monstermaker) website.

## License

All source code is available under the GNU General Public License. See [LICENSE](LICENSE) for details.

## Dependencies

* Node 11
* Cordova
* Ionic 4.0.0
* Firefox*
* Chrome*

*Either of these dependencies can be skipped by removing the browser you do not want to test for in `karma.conf.js`.

## Getting Started

Firstly, make sure you have a local version of [Monster Maker](https://github.com/eboekhold/monstermaker) running.

To run Beholder yourself, clone the repo and then install the needed dependencies.
```
npm install
```
Finally, run the test suite to verify that everything is working correctly.
```
npm test
```
If the test suite runs correctly, you'll be ready to run the app.
```
ionic serve
```