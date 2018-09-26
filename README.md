# pull-scale-banner
a pull down scale the banner effect script.

## use like this:
```javascript
var pull = new pullScaleBanner({
    drager: '.main',
    scaler: '.banner-img'
});
pull.on('refresh', function () {
    console.log('pull begin');
    setTimeout(function () {
        pull.emit('success');
    }, 100)
});
```

## License
> * copyright(c) 2018 XXX Licensed under MIT license.
