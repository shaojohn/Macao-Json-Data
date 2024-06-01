# Intro

data source
* https://www.dicj.gov.mo/web/cn/information/DadosEstat_mensal/2023/index.html
* https://data.gov.mo/Detail?id=6b64c0f8-8b44-4fa7-9e9a-87bb7b06be5e

# Data

format

```json
[
    {
        "Year": 2023,
        "YearAmount": 999999,
        "Months":
            [
                "Month": 1,
                "MonthAmount": 999999
            ]
    }
]
```

* amount in million MOP
* Months may appear, also may not be full 12 months
* YearAmount is the sum of all Months' amount

