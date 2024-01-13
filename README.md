# Social-Media-Content-Analysis

## Business Case Study
### Accenture Internship Project: Social Buzz - Analyzing Content Trends (June 2020 to June 2021)

Social Buzz, a new social media platform focusing on user anonymity and diverse content reactions, presents a dataset encompassing all contents from June 2020 to June 2021. With over 100 ways for users to react, the platform aims to uncover insights into top content categories and user engagement patterns. This analysis provides valuable information to enhance platform performance and elevate the overall user experience.

## Business Problem
The analysis aims to address key questions for Social Buzz, uncovering insights to enhance platform performance and user engagement.

   - Identify and analyze the top 5 content categories by popularity score on Social Buzz.
   - Determine the percentage distribution of content by popularity score within the identified top 5 categories.
   - Identify the most frequently used user reactions on Social Buzz contents.
   - Analyze the prevalent content types posted by users on the platform.
   - Determine the day of the week that performs best in terms of user engagement and post frequency.

## Tools Used in the Analysis

#### Excel:
  - Utilized XLOOKUP for efficient data retrieval and merging across sheets using the Content ID and Reaction Type as a connector.
  - Used SUMIF to calculate the total score for each content category.
  - Removed blank rows to ensure data integrity.
  - Utilized Find and Replace for necessary data adjustments.
    
    ![Excel 1](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/f7afad80-c535-463a-849a-f602ba5b2d11)
    ![Excel 2](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/8514e320-2619-420a-8c90-5704b3c340fb)
    ![Excel 3](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/e24c589c-6662-4ec1-9b61-aa3af0ca4f88)
    ![Excel 4](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/1bb0a196-732d-4dd7-8d16-8384098dbe17)


#### Tableau:
  - Implemented Table Calculation (Rank) to analyze and rank Contnet Category Popularity Score.
  - Used COUNT, SUM and AVG functions for aggregating and summarizing the Content Category, Reaction Types, Reactions and Score.
    
    ![Tableau 1](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/20bee7ca-e1a0-40b2-a0a4-89243b453d3d)
    ![Tableau 2](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/04a61366-00d6-4f3d-b4a0-9b495eca519e)
    ![Tableau 3](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/aed1bbf2-714b-43d5-b5d6-a982ac0976c6)
    ![Tableau 4](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/a89b5657-014f-4226-9072-12855a738105)

These tools facilitated a comprehensive analysis, providing valuable insights for decision-making.


## Findings
1.  #### Identify and analyze the top 5 content categories by popularity score on Social Buzz.
    ![Top 5 content categories](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/c158851b-424f-482b-b13c-359629f3cf0a)
    
    Animals is the most popular content category with a high popularity score of 74965, indicating significant user engagement. This is followed by Science, Healthy Eating, Technology 
    and Food which all demonstrates a substantial users interest in wellness, tech, and culinary contents. 


2. #### Determine the percentage distribution of content by popularity score within the identified top 5 categories.
   ![Social Buzz 9](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/b35d062a-558c-47f2-a764-66c9f665a2d3)

   This distribution highlights the fairly balanced popularity among the top 5 categories, with Animals leading by a small margin, providing a diverse engagement across these content 
   categories.


3. #### Identify the most frequently used user reactions on Social Buzz contents.
   ![Social Buzz 10](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/36850ad4-7691-48b4-8dff-63a584a33b24)

   Among various user reactions, 'heart', 'scared', 'peeking', 'hate' and 'interested' reactions stand out.
   These reactions showcase the diverse range of user responses, emphasizing the need to understand the context and content associated with each reaction for a comprehensive analysis.

   ##### Correlation of Top Content Categories with Most Used Reaction Type
   In analyzing the association between the top 5 content categories and the most used reaction types, the following insights were revealed:

     - Animals Content: The top reaction type is 'Scared,' indicating a strong emotional response to content related to animals.
     - Science Content: 'Interested' is the predominant reaction type, suggesting an intellectual or curious engagement with scientific content.
     - Healthy Eating Content: Surprisingly, 'Hate' emerges as the top reaction type, potentially reflecting polarized opinions or debates on healthy eating topics.
     - Technology Content: 'Interested' is the leading reaction type, showcasing user engagement and curiosity in technology-related posts.
     - Food Content: 'Hate' is the top reaction type, which could indicate strong opinions or critiques associated with food-related content.

   These findings underline the diverse nature of user reactions across different content categories, reflecting a mix of emotions, curiosity, and, in some cases, polarized sentiments.


4. #### Analyze the prevalent content types posted by users on the platform.
   ![Social Buzz 11](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/2ee7879c-c8fa-4f83-af81-5f5a81d602f3)

   The analysis reveals the different content types posted by users on the Social Buzz platform.
   Understanding this distribution of content types provides insights into the diverse ways users engage with and share content on the platform. The higher count of photos suggests 
   that photo-based content is more popular among users.
   

5. #### Determine the day of the week that performs best in terms of post frequency across all contents and specifically among the top 5 content categories.
    ![Untitled 11](https://github.com/tolulopeoa/Social-media-content-analysis/assets/102050942/a1b41623-a6b6-4e57-b41c-88eb9d6530f9)

    In analyzing the post frequency across different days of the week, we observed the following patterns:

    - **Overall Post Frequency:**
      Highest on Monday with 3,581 posts and closely followed by Friday and Sunday.

    - **Post Frequency Based on Top 5 Content Categories**
      
       Animals
       - **Peak Days:** Friday and Sunday. 
         This suggests that users engage more with animal-related content over the weekends.

       Science
       - **Peak Days:** Saturday and Sunday. 
         Science content sees increased posting and engagement on these days.

       Healthy Eating
       - **Peak Day:** Sunday.
         Users show more interest in healthy eating content towards the end of the week.

       Technology
       - **Peak Day:** Tuesday.
         Technology-related posts gain traction on Tuesdays.

       Food
       - **Peak Days:** Monday and Wednesday.
         Food-related content peaks at the beginning and middle of the week.

   These patterns help us understand the temporal dynamics of user engagement, enabling strategic content planning for maximum impact.


## Conclusion

The analysis of Social Buzz's content data from June 2020 to June 2021 has provided valuable insights into user interactions, popular content categories, prevalent reaction types and weekly post frequencies. Animals, Science, Healthy Eating, Technology, and Food are the most popular content categories, with varying popularity scores. 'Interested,' 'Hate,' 'Peeking,' 'Scared,' and 'Heart' are among the most frequently used reaction types.

## Recommendations

   - Tailor content strategies based on the identified top 5 categories to enhance user engagement.
   - Monitor and respond to prevalent reaction types to gauge audience sentiment and preferences.
   - Consider strategic partnerships or collaborations related to these top 5 categories for increased visibility.
   - Leverage insights from post frequency by weekdays to optimize content scheduling for higher visibility and engagement.
   - Conduct seasonal and trend analyses to identify shifts in user behavior and preferences over time.
   - Stay adaptable and responsive to emerging content trends and user interests.

In conclusion, the insights obtained from this analysis provide a foundation for informed decision-making and strategy refinement for Social Buzz. Continuous monitoring and adaptation to user preferences will be key to maintaining and growing engagement on the platform.
