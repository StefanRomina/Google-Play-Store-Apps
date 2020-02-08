# Google Play Store Apps
Analysis of the android market

In the Python Notebook, the Play Store Apps Dataset, taken from Kaggle, is analysed with various Plots and Conclusions. 
The Dataset has data about more than 10,000 apps in the Store.

**Dataset Link** : https://www.kaggle.com/lava18/google-play-store-apps

**Language** : Python

**Tool/Environment** : Jupyter Notebook

**Packages Used** : pandas, numpy, matplotlib, seaborn, plotly, cufflinks, iplot


**Motivation:**

Android operating system is one of the most popular operating system in the world. As a result, mobile app distribution platform such as Google play store is getting flooded due to daily increase
 in the number of new applications. This has led to immense pressure on the app developers due to increase in the competition all over the globe. 
To survive this competition, it is important for the developers to study the information about apps concerning their users, important app features and business focused attributes. 

User information contains details related to ratings and reviews accorded to the app by the users who have already used it. This can provide quantitative as well as qualitative data about the users’ perception
 regarding the app. 

Significant app features can contribute in app success and its popularity. And business information concerns number of downloads of the app. 

### Analysis Questions :

1. Which Google Play store app categories have the greatest number of apps?
2. Which Google Play store app category has a greatest number of apps with hight ratings?
3. How is the Rating distribution?
4. Which Google Play store app categories have the greatest number of reviews?
5. Is there a relation between number of reviews and number of rating on apps?
6. How is price distribution?
7. Is there a relation between price and rating on apps?
8. Which age group is targeted in apps as the most frequent ?
9. What is the proportion of free and paid apps?
10. What is the frequency in installs section? Which apps are the most installed free and paid?
11. Which are the best Apps on App Store?

For visualization I use different plots to better reprezent connections or not between
categories, numbers and types of data.


### Conclusions :

1. Maximum number of Apps in the Store are from the 'Family' , 'Game' , 'Tools', 'Business' and 'Medical' Category.
2. Apps with maximum rating of 5.0 are found most in categories like: Family, Lifestyle, Medical, Business, Tools.\
   A total of 271 Apps have 5.0 rating.
3. Most of the Apps hold a rating of above 4.0 easily.
4. Maximum number of reviews we found in 'Social', 'Communication', 'Game' , 'Tools' categories.\
   The most famous Apps like Facebook, WhatsApp and Instagram are the most reviewed ones.
5. Higher the number of reviews, more likely the apps will have an average rating above 4.0.
6. Paid apps are usually between 0.99 $ and 30 $, most of them are bought for 0.99$, 3.02$, 5$ and 2$, there also
expensive ones at 100$ and more, but we find the most expensive one at 400$ which is 'I am Rich- Trump Edition' app.
7. Great ratings (4.00-5.00) we observe at free apps and some paid apps in large number with price between 1$ - 30$.
8. We can see 6 types of age group : 'Everyone', 'Everyone 10+' , 'Teen', 'Mature 17+', 'Adults only 18+', 'Unrated' where
'Everyone' (81.82%) constitute the majority Content Rating of all the apps. Unrated and Adults ony 18+ have count less then 10.
9. Free apps (92.17%) is more predominant than paid (7.83%).\
   With such a big difference developers should take care if they design paid apps.
10. Most of the apps in the dataset have 1 million installs followed by 10 million and 100k.\
   The most installed aplications are also free, some have many reviews and are related to Google like:
- Google Play Books,
- Google Play Movies & TV,
- Google Drive,
- Google Street View,
- Google Photos,
- Google Play Games,
- Google News

The 2 most installed Paid Apps are both games(Minecraft and Hitman:Sniper)\
The majority of most installed free Apps lie in the Communication Category.\
The majority of most installed paid Apps lie in the Gaming Category.

11. The criteria I have selected are:
- Number of Installs should be equal to or greater than 1,000,000
- Average Rating of an app should be equal to or greater than 4.5
- Minimum number of Reviews should be 10,000.

Best Performing Apps (Free) : Subway Surfers (game), Instagram, Google Photos, My Talking Tom.
Best Performing Apps (Paid): Minecraft, Hitman Sniper, Threema, Where's My Water?\

Gaming Apps outruns other categories by huge margin in the criteria of our most LIKEABLE category followed
by Family and Tools.

