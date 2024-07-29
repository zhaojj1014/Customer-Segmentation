# Customer Segmentation Analysis
Customer segmentation analysis of an online learning platform

This is a practice project from Data Science 365

I have a different approach than the solution provided by the course (which clustered the customers into 8 segments), but I think mine makes sense and the resulst are clean and actionable. 

# Customer Segments
- 0 "low value learners": avg minutes, low CLV, mostly from outside North America/UK/AUS
- 1 "high value learners": short minutes, high CLV, mostly from North America/UK/AUS 
- 2 "friend referrals": avg minutes, avg CLV, mostly from non-social media (friend, other)
- 3 "serious learners": long minutes, high CLV, smallest population

Total CLV generated by each segment


# Recommendations for Marketing Strategies

Based on the clustering results, I recommend the following marketing strategies for the learning platform:

- Focus on consumers in North America/EURO/AUS, who yields the highest spending
- Target these consumers through social media channels such as Youtube, LinkedIn, Google, since these are how most of our target customers are acquired.
- Possible marketing strategies include ads and data science influencers. 

Next step:
Collect demographic data about these consumers, such as their gender/age/education/geographic location/current occupation/etc. This info would help us choose ads channels and influencers. 

____________________________________________________________________________________________
### About the data:
- minutes_watched: The number of minutes a student has watched since joining the program
- CLV: The Customer Lifetime Value, or CLV, shows the total amount of revenue generated by that customer
- Region: This is the geographical region where the student comes from.
  
  0: USA, Canada, United Kingdom, Australia
  
  1: Western Europe
  
  2: Rest of the World
  
- Channel: This is the channel through which the customer has learned about the 365 program
  
  1: Google
  
  2: Facebook
  
  3: YouTube
  
  4: LinkedIn
  
  5: Twitter
  
  6: Instagram
  
  7: Friend
  
  8: Other

