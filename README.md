[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/bluewatertracks/paper-countries)

# paper-countries

## Example 

<!--
```
<custom-element-demo>
    <template>
      <script src="../webcomponentsjs/webcomponents-lite.js"></script>
      <link rel="import" href="paper-countries.html">
      <style>
        paper-countries {
           height: 330px;
	   overflow:hidden;
        }
      </style>
      <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
 -->
 
```html
<paper-countries label="Country name" placeholder="Enter country name..."></paper-countries>
```

## About
 paper-countries is a typeahead component based on Polymer; it allows users to select a country from a list. Think of it as a fun and interactive version of the select input field. We at Blue Water Tracks developed it because we were bored with the usual dropdowns selects fields and wanted to something that was fun using Polymer.

 Credit goes out to the creators of [flag-icon-css](https://github.com/lipis/flag-icon-css) without which we never would have had those beautiful flags.

![paper-countries](paper-countries.gif)

## Installation

The element can be installed using bower

    bower install paper-countries

If you want to save it in bower.json file, remember to add flag `--save`

	bower install --save paper-countries

## Usage

- Following code is required to place in the polymer web component.
```html
	<paper-countries country="[[country]]" auto-validate="true"></paper-countries>
```		
- It is used to select timezone offset from dialog or dropdown.
Check out the [getting started guide](http://bluewatertracks.github.io/paper-contries/components/paper-countries).

## Demo

[Documentation and Demo](http://bluewatertracks.github.io/paper-countries/components/paper-countries/)

To run the demo locally, install using the installation command above and  then, go into the components folder and run ```polymer serve```    

## Contributors

|||
|----------|:-------------:|------:|
| [![@bhargavkonkathi](https://avatars2.githubusercontent.com/u/24550636?v=3&u=ddd3f64f6888100d6eebd283768b61dabc6f495d&s=80)](https://github.com/bhargavkonkathi) |  Programming is like playing chess; each line is as important as each step to determine what kind of player or programmer you are. When ever not playing chess, it's Javascript, Java and mongodb.
| [![@maisnamraju](https://avatars2.githubusercontent.com/u/2786378?v=3&s=80)](https://github.com/maisnamraju) |  Javascript Ninja; saving the world with one line of javascript at a time. ;) 
| [![@dhrytsenko](https://avatars0.githubusercontent.com/u/12988041?v=3&s=80)](https://github.com/dhrytsenko) | What is my opinion about JavaScript, NodeJS, MongoDB and Polymer? Building blocks to the future! Allowing me to help make the world a better place.
|

## Pull Requests are welcome
If you feel that you have something that could improve the component, please feel free to send a PR or create an issue with an explaination.

## License

This project is licensed under the terms of the MIT license.
