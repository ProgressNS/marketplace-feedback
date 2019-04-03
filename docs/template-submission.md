## How to Submit Your App Template to NativeScript Marketplace?

* Do publish your app template to npm (https://www.npmjs.com/) using **tns-template-[custom-template-name-goes-here]** format for the npm package name.

* Do provide a screenshot preview to be used in a future NativeScript Marketplace integration under **tools/assets/marketplace.png** in your app template folder structure.  
> NOTE: Check [hooks/after-createProject/after-createProject.js](https://github.com/NativeScript/nativescript-app-templates/blob/master/packages/template-master-detail/hooks/after-createProject/after-createProject.js) that implements a mechanism for removing the "tools" infrastructure folder from the generated app.

* Do provide correct `repository` property value in the root package.json file of your app template (see the "Package.json guidelines" section in our [App Template Style Guide](https://github.com/NativeScript/nativescript-starter-kits-utils/blob/master/docs/style-guide-app-template-ng.md#packagejson-guidelines)).

* Make sure your template comply with the [App Template Style Guide](https://github.com/NativeScript/nativescript-starter-kits-utils/blob/master/docs/style-guide-app-template-ng.md)

* Apply by sending an email with link to your template's repository to nativescriptplugins@progress.com!
