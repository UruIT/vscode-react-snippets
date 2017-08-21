# React Snippets for Visual Studio Code

[![](https://vsmarketplacebadge.apphb.com/version/UruIT.uruit-react-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=UruIT.uruit-react-snippets)
[![](https://vsmarketplacebadge.apphb.com/installs/UruIT.uruit-react-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=UruIT.uruit-react-snippets)


Extension for Visual Studio Code to add snippets for React in ECMAScript 6.

![Extension demo](./images/snippet-demo.gif)

## Usage

Type the snippet prefix and press enter.

* General
```javascript
u-ci                // console.info
u-cn                // JSX element class name
u-ctor              // Class constructor
u-impt              // Import module statement
u-rcc               // Class component (stateful)
u-rfc               // Functional component (stateless)
```

* PropTypes
```javascript
u-pt                // Generic PropType
u-pta               // Array PropType
u-ptany             // Any PropType
u-ptarrayof         // Array Of (PropType)
u-ptb               // Bool PropType
u-ptcustom          // Custom PropType
u-ptcustomarrayof   // Custom ArrayOf PropType
u-pte               // Element PropType
u-ptf               // Func PropType
u-ptinstanceof      // Instance Of (PropType)
u-ptn               // Number PropType
u-ptnode            // Node PropType
u-pto               // Object PropType
u-ptobjectof        // Object Of (PropType)
u-ptoneof           // One Of (PropType)
u-ptoneoftype       // One Of Type (PropType)
u-pts               // String PropType
u-ptshape           // Shape PropType
u-ptsymbol          // Symbol PropType
```

* Redux
```javascript
u-actions           // Redux actions (including import statements)
u-action            // Redux action
```

* Testing
```javascript
u-it                // Jest test `it`
u-desc              // Jest test `describe`
u-suite             // Jest test suite (including import statements)
u-afterEach         // Jest afterEach function
u-beforeEach        // Jest beforeEach function
```

## Installation

Install through VS Code extensions. Search for UruIT React Snippets

[Visual Studio Code Market Place: UruIT React Snippets](https://marketplace.visualstudio.com/items?itemName=UruIT.uruit-react-snippets)

Can also be installed using

```bash
ext install uruit-react-snippets
```

## Troubleshooting

If the snippets prefixes do not show up when typing them, make sure you have the tab-completion enabled in your settings: `"editor.tabCompletion": true`.

Alternatively, you can choose *Insert Snippet* in the Command Palette (`Cmd+Shift+P` on Mac, `Ctrl+Shift+P` on Windows or Linux).

## Author

* [UruIT](https://github.com/UruIT)

### Contributors

* [Matias Delgado](https://github.com/matiasdelgado)
* [Carloluis Rodríguez](https://github.com/carloluis)

