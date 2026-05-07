Final Project 
I decided to work with the H1B data, getting insights into which industries have the most visa approvals, which organizations get the most approvals and which states are these concentrated in in the United States. This was a crucial decision for me because as an international student, it is very important to understand these insights so that a targeted job search can be conducted, specially when the international students are on a clock for their visa. My intended audience for this project was International students seeking a job.

I started this project with looking at different data sets. I wanted to make sure that the information that my audience needed was conveyed. I finally settled on the USCIS datahub datasets - H-1B Employer Data Hub | USCIS - for the purpose of this project.

The primary question that I was looking to answer through this project was - what have the H1b data trends been like over the past 6 years, what industries have seen the highest number of H1b approvals? What cities and states have seen the highest H1b activities?

During the course of this project, I had to take certain decisions based on how my visuals would turn out. I started with the process of Data wrangling. I first made my dataframe from the csv file, had to work on the encoding since it was not UTF-8. Then I changed some columns, made sure the name of the variables did not have any extra spaces or characters. The data already followed tidy data principles.

I started building multiple visuals to understand my data better. Along the way I had some realisation as well. For example, I was using .count() to group my data but that would only count the number of values in a column. It was not add the values. So I started grouping my data with .sum() function. 

I finally decided to narrow my scope to focus only on the states which had the most number of visa approvals (for this project I only focused on the new approvals). With that I started building more visualizations and then I decided on all the charts that would go into the final dashoard. 

I started building the dashboard with the skeleton developed in class and using guidance from the course materials. I then filled the skeleton with the figures, adjusting the layout accordingly.

My vision was to first show a choropleth map which highlighted all the states with the number of approvals with gradient coloring, then focusing on the trends of H1b over the past 5 years. I narrowed the focus of this trend to the Top 10 states to accommodate the visual. Then see what percentage of the total new H1b visa approvals were concentrated in the top 10 states. It turned out it was almost 70%. So I focused on the top 2 states. California comprised of almost 20% of the total new H1b visa approvals and Texas focused on around 11%. 

Then I visualized the top 10 employers and the industries based on the total number of approvals in each state.

The dashboard clearly answered my primary question – I was able to identify California and Texas with the most number of visa approvals and consistently being on top since the past 4 years. 2021 was the only year where New Jersey had a greater number of new visa approvals than Texas. New Jersey comes a close third in the number of visa approvals. I could also analyse the top 10 industries and the employers in terms of visa approvals. In California, Apple Inc had the highest number of visa approvals, with Qualcomm Technologies a close second. In Texas, it was Oracle, which had the highest number of visa approvals. 

 For future work, it would also help to focus on other variables like denials, continuation approval and other variables and other datasets could also be added to get a more comprehensive view. This dataset did not contain any demographic information. Adding that information (using census data or LCA data), I could get even more insight into H1B approvals and bring the information to a smaller number of audience. 


