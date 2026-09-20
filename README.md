# Technical-Report-Forbes-2018-Athletes-Pay-Analysis-

Technical Report: Forbes 2018 Athletes Pay Analysis Using Power BI

1. Outline
Introduction
Story of Data
Data Splitting and Preprocessing
Pre-Analysis
In-Analysis
Post-Analysis and Insights
Data Visualizations & Charts
Recommendations and Observations
Conclusion
References & Appendices

2. Introduction
Objective of the Project:
To analyze the pay distribution among top athletes listed in Forbes 2018, understanding the impact of salary versus endorsements, and identifying patterns across different sports.
Problem Being Addressed:
Disparities in earnings across sports and athletes raise questions about the influence of brand endorsements, sport popularity, and geography on total pay.
To visualize the income distribution of top athletes in 2018, as reported by Forbes.
To distinguish between earnings from salary/winnings vs. endorsements.
To identify the top-earning athletes and the most lucrative sports.
To analyze the influence of sport type on athlete ranking and income.

Key Datasets and Methodologies:
Dataset: Forbes 2018 Athletes Pay List
Tool: Power BI
Key Calculations: Total Pay = Salary/Winnings + Endorsements
Visualizations used: Bar charts, Treemap, Gauge, Donut charts, Matrix
3. Story of Data
Data Source:
Public Forbes dataset listing top-paid athletes in 2018.
Data Collection Process:
Data collected from Forbes' official publication and uploaded into Power BI.
Data Structure:
Rows: Individual athlete records
Columns: Name, Sport, Salary/Winnings, Endorsements, Total Pay

Important Features and Their Significance:
Name: Unique identifier for each athlete
Sport: Category to analyze trends across disciplines
Salary/Winnings ($M): Key indicator of direct sports earnings
Endorsements ($M): Branding and sponsorship income
Pay ($M): Combined compensation

Data Limitations or Biases:
Only includes the top earners; does not represent average athlete pay
Endorsement valuations might be estimated and not actual contracts
Year-specific (2018) - doesn't account for trends over time

Potential Challenges or Limitations
Data Currency: The dataset is from 2018 and may not reflect current trends.
Missing Data: Some athletes or sports may be underrepresented or omitted.
Data Ambiguity: The meaning of "Rank by Sport" is not clearly defined - is it popularity, number of athletes, or earnings?
The overlap between salary and endorsements may be unclear in aggregate figures.
Outliers and Skew: A few athletes with massive endorsement deals (e.g., Usain Bolt) could skew average values.
Categorization Inconsistencies: Similar sports (e.g., boxing vs. MMA) may be listed separately, reducing comparative insights.

4. Data Splitting and Preprocessing
Data Cleaning:
Removed missing values and duplicate athlete entries
Standardized currency metrics to millions ($M)

Handling Missing Values:
No imputation required as the dataset was clean and complete

Data Transformations:
Calculated Total Pay = Salary + Endorsements
Used DAX to generate the % difference between salary and endorsements

Data Splitting:
Dependent variable: Total Pay
Independent variables: Salary, Endorsements, Sport, Name

Industry Context:
Sports, Media, and Entertainment - focusing on athlete branding and income distribution.
Stakeholders:
Sports managers, agents, marketing strategists, brand sponsors, and sports economists.
Value to the Industry:
Helps understand ROI on athlete sponsorships, guides salary negotiations, and assists brands in selecting sports for influencer marketing.
5. Pre-Analysis
Identify Key Trends:
Basketball leads all sports in total pay, especially through endorsements
Certain athletes earn more via endorsements than salary (e.g., Usain Bolt)

Potential Correlations:
Strong link between fame (measured indirectly via endorsements) and total income
Sports with lower salary payouts sometimes make up for it through endorsements (e.g., Tennis)

Initial Insights:
Athletes in individual sports (Tennis, Track, Cricket) often rely more on endorsements
Team sports show higher salary dependency

6. In-Analysis
Unconfirmed Insights:
Some high-paid athletes earn disproportionately from endorsements, possibly due to global popularity (e.g., Virat Kohli)
Athletes like Trumaine Johnson appear in both top endorsement and salary brackets - outlier or trend?

Recommendations:
For brands: Invest in athletes from sports with global appeal (Track, Tennis, Cricket) for maximum endorsement impact
For agents: Encourage athletes in lower-visibility sports to boost social media and branding presence

Analysis Techniques Used in Power BI:
Donut gauges for comparing salary and endorsement ranges
Stacked bar charts to visualize athlete-by-sport comparisons
Treemaps for proportional pay analysis
Tooltips and filters to allow cross-comparison of athletes by multiple metrics

7. Post-Analysis and Insights
Key Findings:
LeBron James, Stephen Curry, and Federer are among the top earners
Some athletes (e.g., Usain Bolt, Roger Federer) earned nearly all their income from endorsements
Endorsements form a critical revenue stream, often exceeding direct salaries

Key Financial Metrics
Total Pay: $270.21M (out of a possible $540.43M max on the gauge
Total Endorsements: $5.24K (likely symbolic; possibly $5.24 billion or $5.24 million if interpreted realistically)
Total Salary/Winnings: $190.5K (likely $190.5M if corrected for unit mismatch)

Top Earners - Salary/Winning
Matt Ryan - $6.2M
Matthew Stafford - $5.8M
Alex Smith & Derek Carr - $4.0M each
Trumaine Johnson - $3.7M
Stephen Curry - $3.5M
These athletes are primarily from the NFL (football).

Top Endorsements
Usain Bolt - $30M
Virat Kohli - $20M
Wayne Rooney, Yoenis Cespedes, Zack Greinke - $5M each
Von Miller - $2M
These athletes represent diverse sports such as athletics, cricket, soccer, baseball, and football.

Overall Pay (Salary + Endorsements)
LeBron James - $8.55K
Roger Federer - $7.72K
Stephen Curry - $7.69K
Matt Ryan - $6.73K
Matthew Stafford - $5.95K
Kevin Durant - $5.73K
Russell Westbrook - $4.76K
This treemap highlights the combination of performance and marketability.

Rank by Sport
Basketball dominates with 2,135 total ranks, showing high representation.
Followed by Football (906) and Soccer (357).
Niche sports like Track, MMA, and Cricket have fewer entries (under 50).

Insights:
Basketball and Football dominate in earnings and representation.
Endorsement leaders often come from global sports (e.g., athletics, cricket, tennis), not just American leagues.
Athletes like LeBron James and Federer balance elite performance with strong brand presence.

Comparison with Initial Findings:
Initial assumption that team sport athletes dominate overall pay was nuanced - endorsement-heavy individual sports athletes also rank high

8. Data Visualizations & Charts
Visuals Included in the Dashboard:

Donut Gauge (Top Left):

Total Pay ($M): $219.6K to $439.2K
Shows the overall range of earnings

2. Bar Chart (Top Center)
Salary/Winnings ($M) by Name
Top: Matt Ryan ($6.2K), Matthew Stafford ($5.8K)

3. Funnel Chart (Top Right)
Endorsements ($M) by Name
Top: Usain Bolt ($30M), Trumaine Johnson ($25M)

4. Treemap (Bottom Right)
Pay ($M) by Name
Area indicates contribution to total pay

5. Column Chart (Bottom Left)
Rank by Sport
Basketball dominates ($92K), followed by Football ($49K)

<img width="1050" height="568" alt="image" src="https://github.com/user-attachments/assets/68e9b6e6-f3cd-4df0-9146-9c5bea536cb0" />


Key Takeaways from Visuals:
Endorsement-heavy athletes dominate global perception and total income
Basketball and Football are leading team sports in raw salary terms
Athletes from less commercial sports (e.g., Track, MMA) earn low on both fronts

9. Recommendations and Observations
Actionable Insights:
Brand marketers should focus on high-profile athletes even in lower-salary sports
Athletes can increase earnings by investing in personal branding and media presence

Optimizations or Business Decisions:
Sponsors can diversify into underutilized sports with rising stars for lower-cost visibility
Agents and sports organizations should build endorsement packages for lesser-known athletes

Unexpected Outcomes:
Athletes like Trumaine Johnson (not globally known) rank high in both salary and endorsements, indicating anomalies worth exploring

Observations
1. Earnings Distribution
Matt Ryan leads in salary/winnings with $6.2M, closely followed by other NFL players.
LeBron James has the highest total pay ($8.55K), combining salary and endorsements.

2. Endorsements Dominate for Global Athletes
Usain Bolt ($30M) and Virat Kohli ($20M) top endorsement charts, showing strong global brand value.
These athletes outperform others in endorsements despite not being part of high-salary leagues.

3. Sport-Specific Trends
Basketball ranks highest in athlete count and total earnings.
Football (NFL) has more athletes with high salaries/winnings but fewer endorsements.
Tennis (e.g., Federer) shows a high endorsement-to-salary ratio.

4. Pay Structure Differences
Some athletes (e.g., Stephen Curry) have balanced income from both salary and endorsements.
Others rely heavily on endorsements (e.g., Usain Bolt, Roger Federer).

5. Limited Representation in Niche Sports
Sports like MMA, Track, and Cricket have fewer high-earning athletes, but individual stars still attract strong endorsements.

Recommendations Board
1. Diversify Income Streams
Athletes should build personal brands to tap into endorsement opportunities, especially those in high-salary leagues like NFL, where off-field income is lower.
2. Maximize Global Appeal
Organizations and agents should leverage international markets (Asia, Europe) for endorsements, following models like Virat Kohli and Usain Bolt.
3. Strategic Brand Partnerships
Focus on long-term partnerships with global brands for top athletes, especially in less commercialized sports, to maintain high endorsement value.
4. Invest in Media Presence
Encourage athletes to increase visibility through social media, documentaries, and philanthropy (e.g., LeBron's model), enhancing endorsement value.
5. Target Growth in Emerging Sports
Sponsorship agencies should scout underrepresented but high-potential sports (e.g., MMA, Cricket) for hidden marketing potential through standout athletes.
6. Data-Driven Contract Negotiations
Use salary and endorsement data in negotiations with teams and sponsors, especially when balancing both revenue streams (like Stephen Curry).
10. Conclusion
Key Learnings:
Endorsements are a critical component of an athlete's total income
Certain sports disproportionately favor branding over actual sport-related pay

Limitations:
Focused only on 2018; no trendline analysis
The top 100 list excludes mid-tier athletes who may show different patterns

Future Research:
Longitudinal study across multiple years
A deeper comparison between global and domestic athlete earnings

11. References & Appendices
References:
Forbes 2018 Athletes Pay List
Power BI documentation on DAX and visual formatting

Appendices:
DAX expressions used in calculated columns
Screenshot of Power BI data model
Raw data tables
