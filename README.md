# JavaScript - Truthy Value | Falsy Value

```javascript
/*
Falsy Values: false, 0, -0, 0n(BigInt Value), ""(empty string), null, undefined, NaN

Truthy Values: Everything Else

*/

if (true) {
  console.log(`this is a truthy value`);
} else {
  console.log(`this is a falsy value`);
}
//returns: `this is a truthy value`

if (false) {
  console.log(`this is a truthy value`);
} else {
  console.log(`this is a falsy value`);
}
//returns: `this is a falsy value`

0
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a falsy value`

1
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a truthy value`

"Noor"
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a truthy value`

-0
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a falsy value`

""
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a falsy value`

null
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a falsy value`

undefined
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a falsy value`

NaN
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a falsy value`

0n
  ? console.log(`this is a truthy value`)
  : console.log(`this is a falsy value`);

//returns: `this is a falsy value`
```
