# MALib_V2
MALib dataset for third-party library (TPL) recommendation in mobile app development. This is a new version with 30,000+ apps and 500,000 TPL usage records.


[You may like to find the original MALib dataset here.](https://github.com/fio1982/MALib) This dataset contains 10000+ apps downloaded from Google Play and 160,000 TPL usage records extract from those apps via LibRadar.

In Version 2, we have extended the mobile apps to 60,000+ in total, and have manually inspected all the TPLs when extracting TPL usage records. Note that, LibRadar finds out the TPL usage through pattern comparison, therefore, the inspection can further improved the accuracy of our dataset.

For ease of use, we have omitted the lists of mobile apps and TPLs, only providing two files to present the app-library relationship, i.e., the TPL usage records, similar to that in the recommendation research field. We have removed those mobile apps using very limited TPLs and those TPLs that rarely being used. Now, we only keep mobile apps using at least 10 TPLs, and TPLs being used by at least 6 mobile apps.

Please feel free to contact us if you need the full version of our dataset.

It would be very much appreciated if you cite the following papers:

>He, Q., Li, B., Chen, F., Grundy, J., Xia, X. and Yang, Y., 2020. Diversified third-party library prediction for mobile app development. IEEE Transactions on Software Engineering.


>Li, B., He, Q., Chen, F.,  Xia, X., Li, L., Grundy, J.,and Yang, Y., 2021. Embedding App-Library Graph for Neural Third Party Library Recommendation. In proceddings of FSE 2021. DOI:[10.1145/3468264.3468552](10.1145/3468264.3468552)

