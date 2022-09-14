# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
Overview of Project:
The purpose of this project is to track and analyze data for various Kickstarter campaigns to help shed light on what range of finance is most successful, an optimal launch date and what type of media garners the best results. We can also formulate opinions through our data and filter through various countries around the globe.

Analysis and Challenges:
By creating subcategories and filters to help isolate data that corresponds to what Louise wants to focus on, we were able to contrive a multitude of observations. By separating the types of media used in our data, we were able to learn that theatre had the highest volume of Kickstarter campaigns out of the group. We can also learn through our conditional formatting a rough estimate of what type of media has the highest percentage of success. The Music category seems to have the highest success rate at-a-glance.

![Parent_categories_outcomes_snapshot](https://user-images.githubusercontent.com/80132877/190068420-624d8dda-7d17-43aa-a32e-a19f7e7fc41d.png)

One of the challenges we encountered was correctly charting theatre outcomes based on their launch date. After some troubleshooting and some friendly help from our peers, we learned that filtering the main Kickstarter sheet wasn’t sufficient to what we wanted to create. We needed our formula to extract the data from each column associated with the data we were working with. Once we were able gain ground on this issue, the project was seamless moving forward.  

![Countifs_formula](https://user-images.githubusercontent.com/80132877/190069188-da69cc1f-09ab-44d7-b3fc-24c13fd4a1be.png)

Results:
One conclusion we can gather from the Theater Outcomes by Launch Date sheet is that the months from April to August seems to have the highest volume of Kickstarters launched. At a glance we can see that May has the highest amount of successful Kickstarters launched as well. If Louise wants her play to have the highest probability of being funded, the data indicates that the month of May would be her optimal option.
Conversely December is the least successful month to launch a Kickstarter that bears resemblance to the one Louise has in mind. As we can see the failed rate and successful rate are almost parallel during that time period. 

Through our outcomes based on goals graph we can learn that asking for a reasonable amount of money to fund this project might be the best case scenario. Asking between $1 and $,4999 has the highest successful-to-failed ratio in our data. In the $5,000-$24,999 range we notice more of a 50/50 split in percentages, with a flip in those positions at the $15,000 to $19,999 range. We can also notice that Kickstarter campaigns regain a positive success rate at $35,000 and remain in that position until the $44,999 mark.   
