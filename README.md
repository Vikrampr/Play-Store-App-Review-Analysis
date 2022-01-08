# Play-Store-App-Review-Analysis

# Introduction

Application distribution platform, for example, Play Store gets overwhelmed with millions of new applications being launched on the platform regularly. Lots of designers and developers work on it to make an app successful on the Play Store. In this highly competitive world, it is an immense challenge for a developer to know whether they are focusing on the right path to make their app successful on the platform. To launch themselves successfully and create an identity for themselves in this oversaturated market, they need to ensure that majority of the essential factors are incorporated while designing and developing an app that would play an important role in customer's decision-making process. However, the lack of a clear understanding of the inner working and dynamic of popular app markets impacts both the developers and users.

# Objective

The main objective of this exploratory data analysis project is to understand customer demands better and thus help developers to popularize their product on the Play Store. One day on the evening of 8th August 2021, AlmaBetter plans to debut into the Android application by developing a mobile application on the play store platoform. They approaced us "Data Diggers" to help with building their technical know how about building a good android application. They wanted us to study current trends and insights of Play Store. We were given with two datasets i.e., Play Store & User Reviews. Before jumping into the data's provided, let me first explain you about the EDA analysis.

# Problem Statement

What are the top categories on Play Store?

Are majority of the apps Paid or Free?

How importance is the rating of the application?

Which categories from the audience should the app be based on?

Which category has the most no. of installations?

How does the count of apps varies by Genres?

How does the last update has an effect on the rating?

How are ratings affected when the app is a paid one?

How are reviews and ratings co-related?

# What is Exploratory Data Analysis?

Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets for patterns, and anomalies (outliers), and form hypotheses based on our understanding of the dataset and summarize their main characteristics, often employing data visualization methods. It is an important step in any Data Analysis or Data Science project. It helps determine how best to manipulate data sources to get the answers you need. EDA involves generating summary statistics for numerical data in the dataset and creating various graphical representations to understand the data better and make it more attractive and appealing.

# Various steps involved in the EDA process:

Problem Statement - We shall brainstorm and understand the given data set. We shall study the attributes present in it and try to do a philosophical analysis about their meaning and importance for this problem.

Hypothesis - Upon studying the attributes present in the data base, we shall develop some basic hypothesis on which we can work and play with the data to look for the varied results which we can get out of it.

Univariate Analysis - It is the simplest form of analyzing the data. In this we would initially pick up a single attribute and study it in and out. It doesn't deal with any sort of co-relation and it's major purpose is to describe. It takes data, summarizes that data and finds patterns in the data.

Bivariate Analysis - This analysis is related to cause and the relationship between the two attributes. We will try to understand the dependency of attributes on each other.

Multivariate Analysis - This is done when more than two variables have to be analyzed simultaneously.

Data Cleaning - We shall clean the dataset and handle the missing data, outliers and categorical variables.

Testing Hypothesis - We shall check if our data meets the assumptions required by most of the multivariate techniques.

# Data exploration, cleaning and insights:

App - It tells us about the name of the application.

Category - It tells us about the category to which an application belongs.

Rating - It tells us about the ratings given by the users for a specific application.

Reviews - It tells us about the total number of users who have given a review for the application.

Size - It tells us about the size being occupied the application on the mobile phone.

Installs - It tells us about the total number of installs/downloads for an application.

Type - It tells us whether the application is free or a paid one.

Price - It tells us about the price of the application.

Content_Rating - It tells us about the target audience for the application.

Genres - It tells us about the various other categories to which an application can belong.

Last_Updated - It tells us about the when the application was updated.

Current_Ver - It tells us about the current version of the application.

Android_Ver - It tells us about the android version which can support the application on its platform.

# Data Cleaning - Univariate & Bivariate Analysis

The number of null values in play_store dataframe are:

Rating has 1474 null values which contributes 13.60% of the data.
Type has 1 null value which contributes 0.01% of the data.
Content_Rating has 1 null value which contributes 0.01% of the data.
Current_Ver has 8 null values which contributes 0.07% of the data.
Android_Ver has 3 null values which contributes 0.03% of the data.

# Data Cleaning – Univariate Analysis

Findings • Reviews column was converted to a numeric type. • Size column had ‘M’, ‘k’ & ‘Varies with device’ which were all converted to a numeric variable. • Installs column has ‘+’ & ‘,’ characters present in it, which were removed, and then the column was converted to a numeric type. • Type column has only two strings i.e., Free & Paid which were relevant and retained as it is. • Price column had ‘$’ symbol present, which was removed and then the column was converted to a numeric type. • Content_Rating column has relevant variables present in it and thus were retained as it is. • Genres column also had relevant variables present in it and thus were retained as it is. • Last_Updated column has the dates in string format, these were converted to datetime format. • Current_Ver column refers to the latest version of the app and it had all relevant data in it, so it was retained. 8 null values were present, which were removed.

# EDA INSIGHTS AND CONCLUSION:

 In this project of analyzing play store applications, we have worked on several parameters which would help AlmaBetter to do well in launching their apps on the play store. • In the initial phase, we focused more on the problem statements and data cleaning, in order to ensure that we give them the best results out of our analysis. • AlmaBetter needs to focus more on : • Developing apps related to the least categories as they are not explored much. Like events and beauty. • Most of the apps are Free, so focusing on free app is more important. • Focusing more on content available for Everyone will increase the chances of getting the highest installs. • They need to focus on updating their apps regularly, so that it will attract more users.
