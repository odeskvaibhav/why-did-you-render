1. Open Package.json & add this in devDependencies

    ```"why-did-you-render-ui": "https://github.com/odeskvaibhav/why-did-you-render-ui"``` 

2. Open index.js and add

    ```import whyDidYouRender from 'why-did-you-render-ui' in your index.js```
    
    ````
    whyDidYouRender(React, {
      trackAllPureComponents: false,
      componentToShowAlerts: 'ExampleView', // name of the View for which you want to check the count of Re-Renders
    })

    ````

