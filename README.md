getting-and-cleaning-data-course-project
• run_analysis.R 
        r script to processes data and generate required tidy dataset. 
• CodeBook.md 
        Describes the variables, the data, and other work that performed to clean up the data
• README.md 
The required data can be obtained from 
"https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
Following tidyData set is obtained using the script run_analysis.
dim(tidyData)
[1] 180  21
head(tidyData)
 activityId subjectId timeBodyAccMagnitudeMean timeBodyAccMagnitudeStdDev
1          1         1              -0.13697118                 -0.2196886
2          1        10              -0.12740091                 -0.1856024
3          1         8               0.05167863                 -0.1804073
4          1        17              -0.15115149                 -0.4618379
5          1        15              -0.18651465                 -0.3238783
6          1         4              -0.31205057                 -0.5276791
  timeGravityAccMagnitudeMean timeGravityAccMagnitudeStdDev
1                 -0.13697118                    -0.2196886
2                 -0.12740091                    -0.1856024
3                  0.05167863                    -0.1804073
4                 -0.15115149                    -0.4618379
5                 -0.18651465                    -0.3238783
6                 -0.31205057                    -0.5276791
  timeBodyAccJerkMagnitudeMean timeBodyAccJerkMagnitudeStdDev
1                  -0.14142881                    -0.07447175
2                  -0.13262499                     0.03760834
3                  -0.06683224                    -0.18457105
4                  -0.30109327                    -0.27567279
5                  -0.32012932                    -0.31007143
6                  -0.36670088                    -0.31691896
  timeBodyGyroMagnitudeMean timeBodyGyroMagnitudeStdDev timeBodyGyroJerkMagnitudeMean
1              -0.160979553                  -0.1869784                    -0.2987037
2              -0.156458730                  -0.4020251                    -0.4403636
3              -0.003102438                  -0.2387467                    -0.3391293
4              -0.335009837                  -0.5224948                    -0.5171674
5              -0.243711124                  -0.4257985                    -0.5439795
6              -0.497792201                  -0.5531161                    -0.6813040
  timeBodyGyroJerkMagnitudeStdDev freqBodyAccMagnitudeMean freqBodyAccMagnitudeStdDev
1                      -0.3253249              -0.12862345                 -0.3980326
2                      -0.5010279              -0.09302374                 -0.3704719
3                      -0.5029573              -0.09521728                 -0.3608190
4                      -0.5397085              -0.42938004                 -0.5651625
5                      -0.6377860              -0.27515624                 -0.4583448
6                      -0.7301464              -0.45080456                 -0.6511726
  freqBodyAccJerkMagnitudeMean freqBodyAccJerkMagnitudeStdDev
1                  -0.05711940                    -0.10349240
2                   0.02051895                     0.05020876
3                  -0.12383441                    -0.27643613
4                  -0.33593889                    -0.21123186
5                  -0.28975395                    -0.34241193
6                  -0.31858781                    -0.32045870
  freqBodyGyroMagnitudeMean freqBodyGyroMagnitudeStdDev freqBodyGyroJerkMagnitudeMean
1                -0.1992526                  -0.3210180                    -0.3193086
2                -0.4126169                  -0.4997598                    -0.5150653
3                -0.3012418                  -0.3274596                    -0.4730262
4                -0.5186181                  -0.6153201                    -0.5827119
5                -0.4891664                  -0.4817502                    -0.6450752
6                -0.6092856                  -0.5939372                    -0.7243274
  freqBodyGyroJerkMagnitudeStdDev activityType
1                      -0.3816019      WALKING
2                      -0.5176758      WALKING
3                      -0.5812402      WALKING
4                      -0.5203855      WALKING
5                      -0.6540101      WALKING
6                      -0.7577681      WALKING

