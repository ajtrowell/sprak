# Sprak Tools



### References

- [SPRAK Manual](https://steamcommunity.com/sharedfiles/filedetails/?id=546973541)

- [Full SPRAK Command Reference](https://steamcommunity.com/sharedfiles/filedetails/?id=612257262%20)

- [Coding Guide - Not just first Steps](https://steamcommunity.com/sharedfiles/filedetails/?id=528554774)

- [Advanced Coding Guide](https://steamcommunity.com/sharedfiles/filedetails/?id=1114716699)

- [Basic Lockpick Guide](https://steamcommunity.com/sharedfiles/filedetails/?id=526540395)

- [Magic Lockpick Guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3062026819)

- [Unlimited modifier at the beginning](https://steamcommunity.com/sharedfiles/filedetails/?id=528436484)

  

### Other Repos

- https://github.com/nothingnesses/else-Heart.Break

- https://github.com/28/else-Heart-Break

- https://github.com/dznz/awesome-sprak

  

### Snippets

Loop over array elements

```
loop ArrayName
Print(@)
end
```

Similar to

```
loop x in a
Print(x)
end
```

Get all modifiers with drink

```
var m = Connect("MainFrame")
array h = m.GetThingsOfType("Hackdev")
loop h
m.SetPosition(@, "Sebastian")
end
```



### Notes

- StringContains(string s, string substring)
- GetTypeOfThing()
- ZapPersonGently() - works even when in different room
- FinanceServer - custom GetBalance





#### Map of Dorisburg

![](https://steamuserimages-a.akamaihd.net/ugc/199677810875802598/B82F4E38CD45916C18449ABED4A0334A9FEE1D48/)