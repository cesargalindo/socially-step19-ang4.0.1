# socially-19
Angular Meteor 2 Socially Tutorial - Step 19  - Angular2 Material
Angular version: 4.0.1
Meteor version:  1.4.3.2

App was copied from https://angular-meteor.com/tutorials/socially/angular2/3rd-party-libraries

To execute:

1) npm install

# Errors
- Here's a listing of npm WARNINGS of meteor modules that most like require an update?

npm WARN angular2-meteor@0.7.1 requires a peer of @angular/core@^2.0.0 but none was installed.
npm WARN angular2-meteor@0.7.1 requires a peer of angular2-meteor-polyfills@^0.1.1 but none was installed.
npm WARN angular2-meteor-accounts-ui@1.0.0 requires a peer of @angular/core@^2.0.0 but none was installed.
npm WARN angular2-meteor-accounts-ui@1.0.0 requires a peer of @angular/common@^2.0.0 but none was installed.

- According to angular2-google-map forums, Google Maps stills works. However it's not an issue related to Meteor.

npm WARN angular2-google-maps@0.17.0 requires a peer of @angular/common@^2.3.1 but none was installed.
npm WARN angular2-google-maps@0.17.0 requires a peer of @angular/core@^2.3.1 but none was installed.

2) Execute command:
 > meteor reset

3) Execute command:
 > meteor

#Errors 
- there appears to be an issue with angular2-compilers?  I haven't investigated it further than this...
                                 
Unable to resolve some modules:

  "@angular/animations" in /Users/cesargalindo/Downloads/SOCIALLY/socially-19b/node_modules/@angular/material/bundles/material.umd.js (web.browser)
                                              
If you notice problems related to these missing modules, consider running:
                                              
  meteor npm install --save @angular          
                                              
server/imports/publications/parties.ts (2, 24): Cannot find module 'meteor/tmeasday:publish-counts'.
=> Errors prevented startup:                  
   
   While processing files with angular2-compilers (for target web.browser):
   /client/main.scss: Scss compiler error: File to import: {}/node_modules/@angular/material/core/theming/all-theme not found in file:
   /Users/cesargalindo/Downloads/SOCIALLY/socially-19b/{}/client/main.scss
   
   
=> Your application has errors. Waiting for file change.



