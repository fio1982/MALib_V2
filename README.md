# MALib_V2
MALib dataset Version 2.0 for third-party library (TPL) recommendation in mobile app development. This is a new version with 56,000+ apps and 700,000 TPL usage records.


[You may like to find the original MALib dataset here.](https://github.com/fio1982/MALib) This dataset contains 10000+ apps downloaded from Google Play and 160,000 TPL usage records extract from those apps via LibRadar.

In Version 2, we have extended the mobile apps, and have manually inspected all the TPLs when extracting TPL usage records. Note that, LibRadar finds out the TPL usage through pattern comparison, therefore, the inspection can further improved the accuracy of our dataset. [This dataset can also be found here.](https://github.com/malibdata/MALib-Dataset)

## Content
Similar to classical recommendation databases, MALib contains three table / files, namely Apks.csv, Libs.csv and Relation.csv respectively.

## Data Format
### Lib_info.csv

Column 1|Column 2
---|---|
Library Id|Library Name

### Apk_info.csv

Column 1|Column 2
---|---|
App Id|Apk filename

### Relation.csv

Column 1|Column 2
---|---|
App Id|Library Id

Relations is always 1 as we only include the positive invoking relation.

For ease of use, we also provides two files to that solely presenting the app-library relationship, i.e., the TPL usage records, similar to that in the recommendation research field. In this two files, we removed those mobile apps using very limited TPLs and those TPLs that rarely being used, and only keep mobile apps using at least 10 TPLs, and TPLs being used by at least 6 mobile apps.

## Citations

It would be very much appreciated if you cite the following papers:

>He, Q., Li, B., Chen, F., Grundy, J., Xia, X. and Yang, Y., 2020. Diversified third-party library prediction for mobile app development. IEEE Transactions on Software Engineering.


>Li, B., He, Q., Chen, F.,  Xia, X., Li, L., Grundy, J.,and Yang, Y., 2021. Embedding App-Library Graph for Neural Third Party Library Recommendation. In proceddings of FSE 2021. DOI:[10.1145/3468264.3468552](10.1145/3468264.3468552)

