# NHS England's Statement on Information on Health Inequalities
## Elective recovery metrics
### _Age standardised activity rates: Elective admission rates_

|||
| ------ | ------ |
| **`Data source`** | **Numerator:** Secondary Uses Services (SUS); **Denominator:** Spine Personal Demographics Service (PDS) |
| **`Data frequency`** | Monthly |
| **`Numerator definition`** | All elective admissions **_[Admission Source Code] IN ('11','12','13')_**, and **_[Is dominant episode] = '1'_** and **_[Gender code] IN ('1','2')_** |
| **`Denominator definition`** | All currently registered patients where **_[Reason for removal] IS NOT NULL_** and **_[Date of death] IS NULL_** and **_[Invalid Flag] IS NOT NULL_** |
|**`Standardisation methodology`**|Direct standardisation for age and sex was applied using `ageadjust.direct` function from [epitools](https://cran.r-project.org/web/packages/epitools/index.html) r package|
|**`Standard population`**|2013 European standard population|
| **`Notes`** |  |
| **`Caveats`** | Population data are taken from Spine Personal Demographic Service and are current populations only, as these are the only populations data available with the granularity required |

