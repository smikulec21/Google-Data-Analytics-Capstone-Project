# Google-Data-Analytics-Capstone-Project
Google data analytics capstone project: How Does a Bike-Share Navigate Speedy Success?

# Cyclistic Bike-Share Analysis Case Study

## Introduction

Welcome to the Cyclistic Bike-Share Analysis Case Study! In this project, we will step into the shoes of a junior data analyst working at Cyclistic, a bike-share company based in Chicago. Cyclistic offers a wide range of bicycles, including traditional bikes, reclining bikes, hand tricycles, and cargo bikes, making it an inclusive option for people with disabilities and various rider preferences. The majority of Cyclistic users ride for leisure, while about 30% use the bikes for their daily commutes.

Our main objective is to support Cyclistic's marketing team in designing a new strategy to convert casual riders into annual members. The company's success is closely tied to maximizing annual memberships, and we must provide data-driven insights and professional visualizations to back up our recommendations.

## Scenario

- **Cyclistic:** A bike-share program with more than 5,800 bicycles and 600 docking stations. Cyclistic is known for its inclusivity, offering various types of bikes, and serving both leisure and commuter riders.

- **Lily Moreno:** The director of marketing and our manager. Moreno is responsible for developing marketing campaigns and initiatives to promote Cyclistic's bike-share program.

- **Cyclistic Marketing Analytics Team:** A group of data analysts responsible for collecting, analyzing, and reporting data to guide Cyclistic's marketing strategy. We joined this team six months ago.

- **Cyclistic Executive Team:** The decision-makers who will approve our recommended marketing program.

## About the Company

Cyclistic launched its bike-share offering in 2016 and has since grown to a fleet of 5,824 bicycles across 692 stations in Chicago. Customers can unlock bikes from one station and return them to any other station in the system. Cyclistic's pricing plans include single-ride passes, full-day passes, and annual memberships. Casual riders purchase single-ride or full-day passes, while annual members are Cyclistic's most profitable customers.

Cyclistic's finance analysts have highlighted the profitability of annual members, making it essential to focus on maximizing their numbers for future growth. Instead of targeting all-new customers, we aim to convert casual riders into annual members, leveraging the fact that casual riders are already aware of Cyclistic.

## Key Questions

We will address three key questions to guide our marketing program:

1. **How do annual members and casual riders use Cyclistic bikes differently?**
2. **Why would casual riders buy Cyclistic annual memberships?**
3. **How can Cyclistic use digital media to influence casual riders to become members?**

Let's dive into the data analysis process to find answers to these questions and provide valuable insights for Cyclistic's marketing strategy.

# The problem that we are solving
## Problem Statement

In the Cyclistic Bike-Share Analysis Case Study, our primary challenge is to devise strategies for maximizing annual memberships at Cyclistic, a prominent bike-share company operating in Chicago. Lily Moreno, the Director of Marketing, underlines the significance of increasing the annual membership base for the company's future success.

## Objective

Our overarching objective is to create a data-driven marketing strategy that effectively encourages casual riders to transition into annual members. By achieving this, we aim to bolster Cyclistic's revenue and profitability.


# Process

1. Appending files in MS Access
2. Checking data types
3. Checking if there are duplicated rows
4. Deleting the rows with null values (with sql)
5. Exporting the concatenated file
6. Uploading the file into Power BI
7. Splitting the started_at and ended_at columns into started_date/started_time and ended_date/ended_time
8. Adding a ride duration column
9. Adding a support column to count all the visits to the start stations
  ![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/052ec0bc-7607-4215-a1e7-bef893876474)
10. Adding a support column to split the rideable types into normal and electric bicycles
    ![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/2472c81d-51ff-4299-9519-38bd1e4e977b)

11. Making visualizations on the dashboard

# Dashboard
1. Making a pie chart to show the difference between the casual drivers and members.
   
![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/918e8f32-5485-4c39-a533-3998218627cc)
2. Making a slicer to enable selecting the starting station

![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/654f234d-722e-4633-a4c7-f0660a5f5025)
3. Making a treemap to vizualize the size and number of the people at starting stations

![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/dda207f7-aba7-4e3c-babb-2d493105c8b4)
4. Making a card that showcases casual riders and members in numbers

![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/13e32049-73a6-4eba-a3f6-bb34accac152)
5. Making a pie chart to showcase the difference in electric and normal bicycles

![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/8a503e64-5489-4a2d-b81c-668e2af2be7d)
6. Making a stacked bar chart to showcase the duration of the rides based on starting time

![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/73a37474-8b4c-4061-b400-8bacc39532ff)
7. Making a stacked column chart to showcase how start station visits differ by months

![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/6ccc3e8c-394b-418e-891a-2c2b713f76c2)

## Final Dashboard look and use
![image](https://github.com/smikulec21/Google-Data-Analytics-Capstone-Project/assets/126814016/99341335-5fa2-4198-a081-76fee37deb6e)
**Real-time Data**
- Power BI provides real-time data monitoring. Bike companies can track bike availability and rider activity instantly. For example, they can filter the dashboard by time of day to understand rider demand fluctuations.

**Customization**
- Customize Power BI dashboards to align with branding. Create user-friendly filter controls tailored to the audience's preferences, enhancing the user experience.

**Interactivity**
- Power BI offers interactive filtering. For instance, bike companies can use filters to show data by rider category, answering questions like, "Which stations are popular with annual members?" or "Preferred stations for casual riders?"

# Answering the questions

1. **Usage Patterns of Annual Members and Casual Riders**:
   - Annual members and casual riders often use Cyclistic bikes differently. Annual members are more likely to be regular commuters who use the service frequently for their daily transportation needs. They typically have a routine and prefer using the bikes for both short and long trips. On the other hand, casual riders are occasional users, often tourists or individuals who use the service sporadically for leisure or specific short-term needs. The duration of casual rider trips may vary, with some opting for short rides, while others explore the city with longer rides.

2. **Motivations for Casual Riders to Purchase Annual Memberships**:
   - There are several reasons why casual riders might decide to purchase annual memberships with Cyclistic:
     - **Cost Savings**: Annual memberships are cost-effective for frequent riders compared to paying per ride. Casual riders who find themselves using the service regularly may see an annual membership as a way to save money in the long run.
     - **Convenience**: An annual membership provides the convenience of quick and easy access to bikes without the need to purchase individual ride passes each time, which can be appealing to riders who use the service frequently.
     - **Health and Environment**: Cyclistic may promote the health and environmental benefits of cycling, encouraging casual riders to opt for annual memberships to support a more sustainable and healthy lifestyle.
     - **Exclusive Features**: Offering exclusive features such as reserved bikes or priority access for annual members can entice casual riders to upgrade their memberships.
     - **Promotions and Discounts**: Cyclistic can run promotional campaigns, discounts, or special offers to incentivize casual riders to commit to annual memberships.

3. **Using Digital Media to Attract Casual Riders as Members**:
   - Cyclistic can utilize digital media to influence casual riders to become annual members through various strategies:
     - **Targeted Advertising**: Run targeted online ad campaigns to reach casual riders with tailored messages, showcasing the benefits of annual memberships, including cost savings, convenience, and special features.
     - **Engaging Content**: Create engaging content such as blog posts, videos, or social media updates highlighting the advantages of membership, sharing success stories from current members, and providing tips for getting the most out of their membership.
     - **Email Marketing**: Implement email marketing campaigns to communicate directly with casual riders, offering promotions, discounts, and relevant information about annual memberships.
     - **User-Friendly Website**: Optimize the Cyclistic website with a user-friendly interface that makes it easy for casual riders to explore membership options and sign up seamlessly.
     - **Referral Programs**: Encourage existing annual members to refer casual riders to join, offering incentives or discounts for successful referrals.
     - **Social Proof**: Showcase positive reviews, ratings, and testimonials from satisfied annual members on digital platforms to build trust and credibility.
     - **Customer Support**: Provide excellent customer support through digital channels, addressing inquiries and concerns promptly to assist casual riders in making informed decisions.

These strategies aim to leverage digital media to convey the value and benefits of annual memberships to casual riders, ultimately encouraging them to convert and become loyal Cyclistic members.






   


