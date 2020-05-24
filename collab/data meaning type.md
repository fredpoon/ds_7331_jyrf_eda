The data set contains 9,731 records and 259 attributes that are comprised of factors, numbers, and characters. A data definition sheet can be found in Dr. Drew's github repository, [https://github.com/jakemdrew/EducationDataNC](https://github.com/jakemdrew/EducationDataNC/tree/master/Data%20Documentation). To scale the data to be more manageable, our data set includes 17 of the 259 variables. These variables were chosen after initial EDA and correlation visuals were generated between SPG and all predictors. The data type, category and description are displayed in the following table.

### Attributes
| Attribute | DataType | Description |
|---|---|---|
| SPG Score | float64 | School Performance Grade (number) |
| SPG Grade | object | School Performance Grade (Letter Grade) |
| avg_daily_attend_pct | float64 | Average daily attendance percentage |
| category_cd | object | Category Code of the school level E=Elementary, M=Middle, H=High School, I=Elem/Mid Combo, A=All Schools |
| category_cd_modified | object | New attribute - simplified category_cd to distinguish between school types vs combined school levels |
| crime_per_c_num | float64 | Number of crimes or acts of violence per 100 students at the school level |
| ___**EVAAS Growth Status**___ | object | ___**Moved to Appendix**___ |
| ___**lea_federal_perpupil_num**___ | float64 | Federal expense per pupil at LEA level |
| Majority_Minority | object | New Feature - classifying students into either majority or minority category |
| MinorityFemalePct | float64 | Percentage of femail minorities at the school level |
| MinorityMalePct | float64 | Percentage of male minorities at the school |
| MinorityOverallPct |  | New Feature |
| ___**Proficient_TCHR_Standard 1_Pct**___| float64 |  |
| school_type_txt | object | Description of school type |
| ___**Science Score**___ | float64 | Science score at the school level |
| short_susp_per_c_num | float64 | Short term suspensions per 100 students at the school level|
| SPG_Met | object | New Feature |
| student_num | float64 | School size or number of students at the school level |
| tchyrs_0thru3_pct | float64 | Percentage of teachers with 0-3 years of teaching experience |
| Year | int64 | School Year |