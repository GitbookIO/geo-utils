# Geo Utilities

[![NPM version](https://badge.fury.io/js/geo-utils.svg)](http://badge.fury.io/js/geo-utils)

This node package contains multiple utilies to manage GEO data such as countries, languages and US states.

### How to install it?

```
$ npm install geo-utils
```

### How to use it?

Include the library:

```js
var geo = require("geo-utils");
```

Countries:

```js
var countries = geo.countries;

// List of all countries
countries.LIST;

// Get a country
countries.get("FR");
```

Languages:

```js
var languages = geo.languages;

// List of all languages
languages.LIST;

// Get a language
languages.get("fr");
```

US States:

```js
var usstates = geo.usstates;

// List of all US states
usstates.LIST;

// Get a US state
usstates.get("CA");
```
