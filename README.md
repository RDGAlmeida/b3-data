<p align="center">
  <img src="./b3-investors-logo.png" height="196.5" width="127" alt="Relectron" />
</p>

<h3 align="center">
  Total people and money at B3
</h3>

<br>

# B3 Data
This repository contains files in json format with historical data of natural people registered at B3.
All data comes from [B3](http://www.b3.com.br/) and is converted to json format
## File name structure
The file names follow the pattern: **YYYYMMDD-b3-investors**
## Data structure
The structure of data follow the snippet
``` json
{
  "date": "YYYY-MM-DD",
  "mans_investors_total": 9999,
  "womans_investors_total": 9999,
  "all_investors_total": 9999,
  "mans_money_total": 9999,
  "womans_money_total": 9999,
  "all_money_total": 9999,
  "investors": [
    {
      "order": 9999,
      "state": "State",
      "region": "Region",
      "mans_investors": 9999,
      "womans_investors": 9999,
      "total": 9999,
      "mans_money": 9999,
      "womans_money": 9999,
      "money_total": 9999,
      "percentage": "100 %"
    }
  ],
  "ages_range": [
    {
      "order": 9999,
      "age_range": "Age range",
      "mans_investors": 9999,
      "womans_investors": 9999,
      "total": 9999,
      "mans_money": 9999,
      "womans_money": 9999,
      "money_total": 9999,
      "percentage": "100 %"
    }
  ]
}
```
