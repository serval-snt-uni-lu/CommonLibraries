# A repository of Android  common libraries and advertisement libraries

The packaging model of Android apps requires the entire code necessary for the execution of an app to be shipped into one single apk file. Thus, an analysis of Android apps often visits code which is not part of the functionality delivered by the app. Such code is often contributed by the common libraries which are used pervasively by all apps. Unfortunately, Android analyses, e.g., for piggybacking detection and malware detection, can produce inaccurate results if they do not take into account the case of library code, which constitute noise in app features.

Despite some efforts on investigating Android libraries, the momentum of Android research has not yet produced a complete set of common libraries to further support in-depth analysis of Android apps. In this paper, we leverage a dataset of about 1.5 million apps from Google Play to harvest potential common libraries, including advertisement libraries. With several steps of refinements, we finally collect by far the largest set of 1,113 libraries supporting common functionalities and 240 libraries for advertisement. We use the dataset to investigates several aspects of Android libraries, including their popularity and their proportion in Android app code. Based on these datasets, we have further performed several empirical investigations to confirm the motivations behind our work.


If you use our harvested libraries in your research, you can cite the following technique report:
* Li Li, Tegawendé F. Bissyandé, Jacques Klein, Yves Le Traon, An Investigation into the Use of Common Libraries in Android Apps, Technique Report, 2015 [[pdf]]()


# Common Libraries
* [cl_61:  1735](libraries/cl_61.txt)
* [cl_62:  3179](libraries/cl_62.txt)
* [cl_63:  4452](libraries/cl_63.txt)
* [cl_64:  5509](libraries/cl_64.txt)
* [cl_71:  1573](libraries/cl_71.txt)
* [cl_72:  2898](libraries/cl_72.txt)
* [cl_73:  4117](libraries/cl_73.txt)
* [cl_74:  5144](libraries/cl_74.txt)
* [cl_81:  1363](libraries/cl_81.txt)
* [cl_82:  2564](libraries/cl_82.txt)
* [cl_83:  3715](libraries/cl_83.txt)
* [cl_84:  4685](libraries/cl_84.txt)
* [cl_91:  1113](libraries/cl_91.txt)
* [cl_92:  2148](libraries/cl_92.txt)
* [cl_93:  3173](libraries/cl_93.txt)
* [cl_94:  4072](libraries/cl_94.txt)


# Advertisement Libraries
* [ad_1050:  1049](libraries/ad_1050.txt)
* [ad_240:  239](libraries/ad_240.txt)

# Comments & Suggestions
If you have any comments or suggestions related to our harvested libraries, you are welcome to discuss with us through the [issues track](https://github.com/serval-snt-uni-lu/CommonLibraries/issues).
