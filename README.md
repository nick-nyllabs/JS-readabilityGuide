# JS-readabilityGuide

## Basic Variable Names

**All variable names should be concise but descriptive**

```javascript
// good
let userDetails;
let socket = new io();
throw new Error({ message: "Error", stackTrace: err });

// bad
let a;
throw new Error({ message: "Error", obj: err }); //`obj` is vauge
```

Regarding amount of words for a variable, Eisntein once said:
> Everything should be a simple as possible, but not simpler.

When they really need to be longer, they can be.

**Variable names should use an unapproved abbrivation**

```javascript
// good
function(err, data){}

// bad
function(eor, dta){}
```

**Variable name should be free of "versioning"**

```
// good
let adminProfile;

// bad
let adminProfileNew;
let adminProfile_v2;

```

**[⬆ back to top](#js-readabilityguide)**
