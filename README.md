# JS-readabilityGuide

## Basic Variable Names

**All variable names should be concise but descriptive**

```
//good
let userDetails;
let socket = new io();
throw new Error({ message: "Error", stackTrace: err });

//bad
let a;
throw new Error({ message: "Error", obj: err }); //`obj` is vauge
```

**[⬆ back to top](#js-readabilityguide)**
