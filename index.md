# Energy Tracking App

App to track your energy, water, gas or whatever consumptions.

## Backup

You can backup your meters with all entries using `backup` function in the Meter-List view. The data in backup is saved in JSON format.
The format of the date is always `YEAR-MONTH-DAY`

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
