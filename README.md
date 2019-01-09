# Angular ie9 support

This project is a demo for angular IE9+ support

## install

    npm install --save-dev babel-polyfill
    
## modify polyfills.ts  close 'web-animations-js' add 'babel-polyfill'

    // import 'web-animations-js';  // Run `npm install --save web-animations-js`.
    
    /** for IE9 + . */
    import 'babel-polyfill';
    

