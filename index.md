# Energy Tracking App

App to track your energy, water, gas or whatever consumptions.

## Import / Export

### Data

data could be exported in `CSV` format. The linke consists of a date in format `YEAR-MONTH-DAY` and a value, separated by `TAB`
```
2011-01-25 6556
2011-01-28 6700
```

to import use the same format.


### Backup

You can backup your meters with all data, and later import it. The data in backup is saved in `JSON` format and contains both, meter details and all data.

```
{
  "meter":{
    "title": "Water Home 1",
    "units": "m3"
  },
  "values":[
    {
      "date": "2019-01-11",
      "value": 1334
    },
    {
      "date": "2019-02-10",
      "value": 1500
    }
  ]
}
```
