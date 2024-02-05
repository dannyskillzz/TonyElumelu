# Tony Elumelu's H1 2023 LinkedIn Analysis

Tony O. Elumelu C.F.R is one of Africa’s leading investors and philanthropists. He is the Founder and Chairman of Heirs Holdings, his family-owned investment company, committed to improving lives and transforming Africa, through long-term investments in strategic sectors of the African economy, including financial services, hospitality, power, energy, technology, and healthcare.

As one who inspires me so much, I decided to dedicate my first-ever personal data analytics project to analyzing the tremendous impact he made with his LinkedIn content for the first six months of 2023.

# Gathering the Data

I sourced my data directly from LinkedIn. This was done on Saturday, July 1st, 2023. I did some cleaning on the Data on Microsoft Excel to change some datatypes, shorten some post descriptions, and ensure there are no duplicates.

I wanted to perform a time analysis using the time and days of the week each post was made. So I employed the use of a [tool](https://ollie-boyd.github.io/Linkedin-post-timestamp-extractor/) to help me extract the time and date from every post.

After the data gathering and cleaning, I proceeded to Microsoft Power BI to build my dashboard.

# Creating the Dashboard

To build the dashboard, I decided to go for a portrait-sized dashboard, so I set the canvas settings on PowerBI to a “letter type” rather than the default “16:9” size. I also chose to make the dashboard appealing by introducing an image of Tony Elumelu to the canvas background.

For the colours, I chose a red colour for all charts because this is Tony Elumelu’s brand colour. I specifically used the exact shade of red from the Heirs Holdings logo.

The icons used for the card visuals were all gotten from Canva, a design platform, except for the three reactions icons (like, love, and celebrate) which were gotten from LinkedIn.

Now let’s dive deeper into the technicalities and analyze the various charts and trends from this analysis with some major insights below:

# Engagements

I created a line chart for various engagements to show the month-on-month trend for reactions, comments, and reposts. I also showed the trend for the number of posts made every month. In terms of engagements, April was the least-performing month across all engagements while June showed the highest values in reactions and reposts, and March took the lead for the highest comments.

If I were to select the best-performing month from this analysis, it would definitely be March because this month had less number of posts as compared to June. But, it ranked high in terms of comments and reactions.

# Top 5 Posts

I noticed some similarities in the top 5 posts based on engagements. The top post with 37K engagements was a throwback post to TOE’s NYSC days in Sokoto. Another throwback post to age 34 as CEO of Standard Trust Bank came as the №3 post in terms of engagements.

A birthday post of Oge, TOE’s first daughter, came in second place among the top 5; and another birthday post (video) of TOE himself came in 4th place. Coming in 5th place among the top 5 was a video post on an interview with BBC News Africa.

From these insights, it is right to say that the LinkedIn community enjoy more throwback content from Tony Elumelu and video posts may tend to perform better than picture posts for TOE, depending on the content of the post.

# Time Series Analysis

I also took out the time to make good use of the timestamp data I extracted to analyze the number of posts made and the total engagements gained with respect to days of the week and specific timeframes of posting. I achieved this using the SWITCH function (DAX) on Power BI to return the days of the week and time groups (using a 6-hour timeframe) on separate columns respectively.

The analysis showed that posts made on a Wednesday got the highest engagements (95K) even though it is one of the days with the second least number of posts made (5 posts). Monday and Friday also showed good numbers with 66K and 65K engagements respectively from posts made on these days.

In terms of timing, over 50% of the posts were made between 12PM to 6PM with a total engagement of 235.2K. 6PM to 12AM may not be the best timeframe to make a LinkedIn post as this timeframe generated 44.7K engagements as compared to equal number of posts made between 6AM to 12PM.

# Relevant Links:
[Medium Article](https://dannyskillzz.medium.com/tony-elumelus-h1-2023-linkedin-analysis-c9bb4fe6de4)
[LinkedIn](https://www.linkedin.com/in/daniel-chukwuma/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BsZCTdWVsR2SNKmh0WP32Jg%3D%3D)



