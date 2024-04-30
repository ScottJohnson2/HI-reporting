# NHS England's Statement on Information on Health Inequalities
## Elective recovery metrics
### _Age standardised activity rates: Outpatient appointment rates_

|||
| ------ | ------ |
| **`Data source`** | **Numerator:** Secondary Uses Services (SUS); **Denominator:** Spine Personal Demographics Service (PDS) |
| **`Data frequency`** | Monthly |
| **`Numerator definition`** | All outpatient appointments |
| **`Denominator definition`** | All currently registered patients where **_[Reason for removal] IS NOT NULL_** and **_[Date of death] IS NULL_** and **_[Invalid Flag] IS NOT NULL_** and **_[Gender code] IN ('1','2')_** |
|**`Standardisation methodology`**|Direct standardisation for age and sex was applied using `ageadjust.direct` function from [epitools](https://cran.r-project.org/web/packages/epitools/index.html) r package|
|**`Standard population`**|2013 European standard population|
| **`Notes`** |  |
| **`Caveats`** | <ul><li>Population data are taken from Spine Personal Demographic Service and are current populations only, as these are the only populations data available with the granularity required.</li><li>First iteration of this metric includes both aattended and not attended appointments. Further iterations will split these into separate metrics.</li></ul>|

