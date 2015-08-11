You shouldn't specify any units after a 0 value. So in other words do not:

```
.box{
  margin: 0px;
  padding: 0em;
  width: 0%;
}
```

This might be a bit pedantic but the CSS spec allows for no units after 0 values as it's redundant. 
Leaving them out will save bytes and saving bytes is good. Granted, it's not a lot of bytes but it also makes more sense.

# How to fix

Just remove all unit specifics after 0 such as `0px`, `0em` and `0%`. It's better that way.
