### lodjs
---
https://github.com/yanhaijing/lodjs

```
<script src="lodjs.js"></script>
```

```
bower install lodjs
bower install git://github.com/yanhaijing/lodjs.git

bower register lodjs git://github.comyanhaijing/lodjs.git
```

```js
define(function(){
  return 123;
});

lodjs.use('mod', function(mod){
  console.log(mod);
});

```


