---
title:code-blocks
description:code-blocks
tags: [tutorial:interest/sap_cal, tutorial:interest/cloud]
---

Indent every line of the block by at least 4 spaces.

This is a normal paragraph:

    This is a code block.
    With multiple lines.

Alternatively, you can use 3 backtick quote marks before and after the block, like this:

```
This is a code block 

```

To add syntax highlighting to a code block, add the name of the language immediately
after the backticks: 

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```
```random
int [] mas = new int mas [x];
for(int i=0; i<=x;i++)
System.out.print(mas[i]);
};
```
Use the backtick to refer to a `function()`.
 
There is a literal ``backtick (`)`` here.
