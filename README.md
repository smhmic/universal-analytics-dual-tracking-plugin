# universal-analytics-dual-tracking-plugin
Repository for the online Google Analytics hackaton
URL: 
# H5
https://wwww.thyngster.com/


```javascript
ga('create', 'UA-286304-123', 'auto');
ga('require', 'dualtracking', 'http://www.yourdomain.com/js/dualtracking.js', {
    property: 'UA-123123123213-11',
    debug: true,
    transport: 'image'
});
ga('dualtracking:doDualTracking');
ga('send', 'pageview');
