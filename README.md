# IntegralUI Web - RadioButton, v22.2

IntegralUI Web - RadioButton is a native Web Component that represents a radio button. 

![IntegralUI Web - RadioButton, 22.2 - a native Web Component that represents a radio button for Angular, React and Vue](https://www.lidorsystems.com/products/web/studio/images/integralui-web-radiobutton.png)

<b>Note</b> This component is part of [IntegralUI Web](https://github.com/lidorsystems/integralui-web.git) library.

Here is a brief overview of what is included:


## Components

[RadioGroup](https://www.lidorsystems.com/products/web/studio/samples/#/radiogroup) - Allows you to create a group of radio buttons

[RadioButton](https://www.lidorsystems.com/products/web/studio/samples/#/radiobutton) - Represents a radio button


## Services

<b>Common</b> - Includes a set of common functions usable in most applications


## Dependencies

IntegralUI Web is built on top of [LitElement](https://github.com/Polymer/lit-element). All necessary files from that library are already included in the /external subfolder of this repository.


## DEMO

[Online QuickStart App](https://www.lidorsystems.com/products/web/studio/samples/) - An online demo of RadioButton component is included


## Installation

Install the repository by running

```bash
npm install https://github.com/lidorsystems/integralui-web-radiobutton.git
```

or directly from NPM

```bash
npm i integralui-web-radiobutton
```


## How to Use IntegralUI RadioButton component

<b>Note</b> A detailed information is available here: [How to Use IntegralUI Web Components](https://www.lidorsystems.com/help/integralui/web-components/introduction/installation/). Explains how to setup and use components for each framework: Angular, React or Vanilla JavaScript.

In general, you need to open your application and add a reference to a component you want to use. For example, if you are using the IntegralUI RadioButton component:</p>

### Angular

```bash
import 'integralui-web-radiobutton/components/integralui.radiobutton.js';
import 'integralui-web-radiobutton/components/integralui.radiogroup.js';
```

Depending on current version of TypeScript, you may need to add some settings in tsconfig.json, under "angularCompilerOptions":

```bash"angularCompilerOptions": {

    . . .

    "suppressImplicitAnyIndexErrors": true,     // solves implicit any values
    "noImplicitAny": false,             // solves angular could not find a declaration file for module implicitly has an 'any' type
    "strictNullChecks": false           // solves type null is not assignable to type

}
```

### React

```bash
import IntegralUIRadioButtonComponent from 'integralui-web-radiobutton/wrappers/react.integralui.radiobutton.js';
import IntegralUIRadioGroupComponent from 'integralui-web-radiobutton/wrappers/react.integralui.radiogroup.js';
```

<b>Note</b>   Currently [ReactJS doesn't have full support for Web Components](https://custom-elements-everywhere.com/#react). Mainly because of the way data is passed to the component via attributes and their own synthetic event system. For this reason, you can use available wrappers located under /wrappers directory, which are ReactJS components that provide all public API from an IntegralUI component.</p>

### Vanilla JavaScript

```bash
<script type="module" src="integralui-web-radiobutton/components/integralui.radiobutton.js"></script>
<script type="module" src="integralui-web-radiobutton/components/integralui.radiogroup.js"></script>
```

## QuickStart App

There is a demo application with source code that contains samples for each component included in the IntegralUI Web library. It can help you to get started quickly with learning about the components and write tests immediatelly. 

From [IntegralUI Web - QuickStart](https://github.com/lidorsystems/integralui-web-quickstart) you can download a demo app for Angular, AngularJS, React and Vanilla JavaScript. A detailed information about each of these quick-start demos is available in ReadMe file, located in the root folder of the demo app.


## License Information

You are FREE to use this product to develop Internet and Intranet web sites, web applications and other products, with no-charge.

This project has been released under the IntegralUI Web Lite License, and may not be used except in compliance with the License.
A copy of the License should have been installed in the product's root installation directory or it can be found here: [License Agreement](https://www.lidorsystems.com/products/web/lite/integralui-web-lite-license-agreement.pdf).

This SOFTWARE is provided "AS IS", WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License for the specific language governing rights and limitations under the License.