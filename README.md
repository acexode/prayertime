# prayertime

## Quick start
    $ npm install prayertime

```javascript
    import prayer from 'prayer'
    var time = pray.getTimes(new Date(), [43, -80], -5);
    console.log(time)
```
There are several functions for adjusting calculation parameters. For example, we can call the following function (before calling getTimes) to change the calculation method to ISNA:

```javascript
    prayTimes.setMethod('ISNA'); 
```
see link for detailed doc [link to Documentaion!] (http://praytimes.org/manual)

#Credits =>  [link to Pratimes!] (PrayTimes.org)