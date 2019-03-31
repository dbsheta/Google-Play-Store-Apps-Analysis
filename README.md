### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
Python 3.* is required to run this Project. If you are running Anaconda, then you'll need two extra libraries (4 & 5):
1. Pandas
2. Numpy
3. Matplotlib
4. Plotly
5. Wordcloud
Install above dependencies using ```pip install <dependency>```

## Project Motivation<a name="motivation"></a>

I used to be an Android developer, so this use case comes naturally to me. Following are the questions I'm looking to answer:

1. What category of apps should a developer target for bursting onto the scene?
2. Does size of an app affect its popularity and rating?
3. How do paid apps fare against free apps in terms of populariy and sentiment?
4. What makes an app 'successful' on play store?

## File Descriptions <a name="files"></a>

All my work is in the notebook. Data folder contains two files, both of which are required by the notebook

## Results<a name="results"></a>
1. A Developer should target categories which have high demand but lack of quality apps like Entertainment and Travel
2. Users don't usually care about app size, but lighter apps do have higher average rating. Most of the top rated apps are light.
3. Paid apps are not much downloaded by users. Whenever possible users opt for free alternatives.
4. Reviews of free apps often contain words like bugs, problems and ads. However, such words are not present in reviews of paid apps. Since, both types of apps have similar ratings, we can say that people tend to critize free apps more than paid apps.
5. Developer should opt for a business model which is not fully paid (as it will lead to less downloads), and not fully adsupported as well (which leads to lower ratings). A sweet spot between both is having ads in free version and an option for user to remove those by paying a premium.

A complete blog on the same can be found [here](https://medium.com/@dsheta/data-science-of-a-successful-android-app-e737519db21b)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Licensing for the data and other descriptive information is available [here](https://www.kaggle.com/lava18/google-play-store-apps).  Feel free to ping me in case of doubts


