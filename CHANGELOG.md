## Changelog

### 2.1.0
  * added: the possibility to instantiate the `Parallax` class with out DOM selectors
  * updated: improved the destroy method restoring the initial DOM elements state
  * fixed: https://github.com/GianlucaGuarini/parallax/issues/7 thanks to https://github.com/GianlucaGuarini/parallax/pulls/14

### 2.0.2
  * fixed: missing minified version of the script

### 2.0.1
  * added: the `will-change` attribute hoping to gain better performances

### 2.0.0
  * updated: updated riot-observable using the latest version
  * updated: use `transform: matrix()` for better performances
  * fixed: [#5](https://github.com/GianlucaGuarini/parallax/issues/5)

### 1.1.0
  * fixed: https://github.com/GianlucaGuarini/parallax/issues/4 adding the `safeHeight` option

### 1.0.4
  * updated: riot-observable dependency to get faster performances (30% faster)

### 1.0.3
  * fixed: destroy method

### 1.0.2
  * updated: switched from webpack to rollup to get a cleaner dist code

### 1.0.1
  * added: the parallax `update` event
  * added: the `bower.json` file
  * fixed: smoother errors when no images are found