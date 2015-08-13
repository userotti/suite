Having an outline is important for accessibility. Without this certain users will never know which elements has focus. 
Taking this away because of ill conceived esthetics is bad.

# How to Fix
Do not remove the outline but if you really have to you could replace it.
```
a:focus {
    border: 1px solid red;
    outline: none;
}
```

# Resources
* [https://github.com/CSSLint/csslint/wiki/Disallow-outline:none](https://github.com/CSSLint/csslint/wiki/Disallow-outline:none)
