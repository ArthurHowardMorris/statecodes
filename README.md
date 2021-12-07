# State names and codes

- `statecodes.csv` provides a simple crosswalk between full state names, str2 state names, and and 2digit fips codes.

[Source](https://www.nrcs.usda.gov/wps/portal/nrcs/detail/?cid=nrcs143_013696)

[raw download link for `statecodes.csv`](https://raw.githubusercontent.com/ArthurHowardMorris/statecodes/main/statecodes.csv)

```Stata
import delimited "https://raw.githubusercontent.com/ArthurHowardMorris/statecodes/main/statecodes.csv", clear
```

## TODO:
- [ ] Add a simple zip-state crosswalk for ea. decade using [this](https://www.huduser.gov/portal/datasets/usps_crosswalk.html)
