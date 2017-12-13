# City of Phoenix Public Data

Phoenix has published csv relevant for the years 2017.  I've translated that to JSON and published it as an NPM module.  Pull requests welcome if you notice discrepancies.

# Usage

Here's some examples of querying the data using lodash.

```javascript

[
  {
    "INC NUMBER": 201500002101405,
    "OCCURRED ON": "11/01/2015  00:00",
    "OCCURRED TO": "11/01/2015  05:00",
    "UCR CRIME CATEGORY": "MOTOR VEHICLE THEFT",
    "100 BLOCK ADDR": "102XX W MEDLOCK AVE",
    "ZIP": 85307,
    "PREMISE TYPE": "SINGLE FAMILY HOUSE"
  },
  {
    "INC NUMBER": 201500002102668,
    "OCCURRED ON": "11/01/2015  00:00",
    "OCCURRED TO": "11/01/2015  11:50",
    "UCR CRIME CATEGORY": "MOTOR VEHICLE THEFT",
    "100 BLOCK ADDR": "69XX W WOOD ST",
    "ZIP": 85043,
    "PREMISE TYPE": "SINGLE FAMILY HOUSE"
  }
]

```
