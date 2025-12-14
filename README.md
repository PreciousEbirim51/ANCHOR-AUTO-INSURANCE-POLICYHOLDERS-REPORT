<img width="1100" height="595" alt="image" src="https://github.com/user-attachments/assets/dfed4f14-60fa-4d3f-9661-15742477c017" />


<img width="1100" height="594" alt="image" src="https://github.com/user-attachments/assets/889884cb-0883-424a-95d9-6483b095b99f" />




INTRODUCTION

This report provides a detailed overview of claim patterns, customer segmentation, and risk distribution across our policyholder portfolio. The dashboard presents key metrics that reveal critical insights into our insurance operations, helping us understand both the financial impact of claims and the demographic factors influencing claim behavior.

This analysis will dissect each component of the policyholders data to provide actionable insights for underwriting, marketing, product development, and risk management stakeholders at Anchor Auto Insurance.

This analysis will help the business move from descriptive analytics to prescriptive strategies that enhance profitability while maintaining competitive customer offerings in the auto insurance marketplace.

PRE ANALYSIS

A pre-analysis phase was conducted to establish an analytical framework before the creation of the dashboard. This pre-analysis phase involves:

Project Split: The dataset was split into two variables which are independent and dependent variables and this helps in understanding the relationship between the data points and can provide hint on the type of insights that can be gotten from the dataset.
Potential Analysis/Questions: In this step, the questions that can be answered with the dataset were identified and it will serve as a bearing during the analysis.
Potential Insights: I was able to uncover some insights during this step just by observing the data split and it aided in my analysis by narrowing my focus on the important insights that can be gotten from the data set.
Storytelling: After the earlier steps described above, it became easier to tell a story from the dataset by relating the datapoints with each other.

TOOLS AND TECHNOLOGIES

Microsoft Power BI was the primary analysis and visualization tool used for this project, the Power BI features used include;

DAX Functions
Interactive Visualizations
Power Query
Calculated Columns and Measures

OBSERVATION

1. Overall Claims Overview

Total Claims: 38,000
Total Claim Amount: $1.88 billion
Average Claim Amount: ~$50,000
Total Household Income: $5.53 billion
Total Driving Kids: 16,000
Note: The total claim amount represents a significant portion (~34%) of the total household income, indicating substantial insurance payouts relative to income.

2. Gender Analysis

Female policyholders have a slightly higher claim amount ($940.5M) compared to male policyholders ($937.67M).
The difference is minimal (~0.3%), suggesting gender is not a major differentiating factor in total claim amounts.

3. Education Impact

Bachelor’s degree holders have the highest claim amount ($940.2M).
Followed by High School ($518M), Masters ($283.09M), and PhD ($136.87M).
Insight: Higher education (Bachelor’s) correlates with higher claim amounts, possibly due to higher-value insured assets or more frequent claims.

4. Car Use

Private car users claim significantly more ($1.50B) than commercial users ($0.37B).
This could reflect higher private car ownership, more personal claims, or higher coverage values.

5. Coverage Zone

Urban and Highly Urban policyholders have the highest claim amounts (~$374–382M each).
Rural, Suburban, and Highly Rural areas follow closely, with Urban being the highest.
Urbanization appears linked to higher claim amounts, likely due to higher traffic density, accident rates, or vehicle values.

6. Car Make Analysis (Top 5)

Ford leads with $165.58M in claims, followed by Chevrolet ($147.86M), Dodge ($92.91M), Toyota ($90.16M), and GMC ($87.40M).
Insight: American car brands dominate high claim amounts, possibly due to higher prevalence, repair costs, or risk profiles.

7. Key Takeaways

Urban, Bachelor’s-educated, private car drivers (especially of Ford/Chevrolet vehicles) represent high-claim segments.
Claim distribution is relatively balanced across gender and zones, but education and car use show strong disparities.
Potential actions: Risk assessment models could focus on urban areas, certain car makes, and education/usage segments for premium adjustments or targeted safety campaigns.

The Divorced segment is a significant, proportional subset of the portfolio in terms of volume, value, and risk (identical average claim cost). The primary differences lie in the compositional factors below.

2. Gender Analysis

Overall: Females ($940.5M) > Males ($937.67M) — nearly equal.
Divorced: Females ($162.42M) > Males ($155.99M).
Insight: The trend of slightly higher female claim amounts holds and is slightly more pronounced in the divorced segment (51% vs 49%). This could relate to custody patterns (more children primarily with mothers) affecting vehicle usage.

3. Education Impact

Overall: Bachelor’s ($940.2M) > High School ($518M) > Masters ($283M) > PhD ($137M).
Divorced: Bachelor’s ($83.32M) > High School ($46.48M) > Masters ($23.27M) > PhD ($11.27M).
Insight: The rank order is identical. Bachelor’s degree holders are the highest claiming group regardless of marital status. The distribution is consistent, suggesting education is a stronger independent risk factor than marital status.

4. Car Use

Overall: Private ($1.50B) >> Commercial ($0.37B) — an 80/20 split.
Divorced: Private ($0.26B) >> Commercial ($0.06B) — an 81/19 split.
Insight: The split is almost identical. Divorced individuals are not significantly more or less likely to use their vehicle for commercial purposes.

5. Coverage Zone

Overall: Amounts were very evenly distributed (~19–20% each) across all five zones (Urban, Highly Urban, Rural, Suburban, Highly Rural).
Divorced: Shows a clear shift:
Urban (21.26%) and Highly Urban (20.73%) now lead, together making up 42% of claims.
Suburban, Rural, and Highly Rural are lower (~19% each).
Insight: This is a major differentiator. Divorced policyholders are disproportionately concentrated in urban centers. This aligns with demographic trends and could influence risk due to urban driving conditions (congestion, theft, accidents).

6. Car Make Analysis (Top 5)

Overall Top 5: Ford, Chevrolet, Dodge, Toyota, GMC.
Divorced Top 5: Ford, Chevrolet, Dodge, Toyota, Mitsubishi.
Insight: The top 4 are identical, confirming Ford and Chevrolet as high-exposure makes across the board. GMC drops out for the divorced segment, replaced by Mitsubishi. This suggests potential differences in vehicle preference or affordability post-divorce.

The Married segment is the largest single cohort in the portfolio (~34%). Like the Divorced segment, their risk profile in terms of claim severity is identical to the overall book. The business impact is driven by volume, not severity.

2. Gender Analysis

Overall: Females ($940.5M) ≈ Males ($937.67M)
Divorced: Females ($162.42M) > Males ($155.99M)
Married: Females ($318.56M) > Males ($314.19M)
Insight: The pattern holds. In both married and divorced segments, female policyholders have a slightly higher total claim amount. This could be due to being the primary insured on family vehicles or different risk profiles.

3. Education Impact

Rank Order (All): Bachelor’s > High School > Masters > PhD
Married Amounts: Bachelor’s ($310.97M) > High School ($178.87M) > Masters ($95.02M) > PhD ($47.88M)
Insight: Education remains the dominant, consistent risk factor across all marital statuses. The distribution is stable, reinforcing that education level is a more powerful predictor of claim volume than marital status.

4. Car Use

Overall Split: ~80% Private / ~20% Commercial
Divorced Split: ~81% Private / ~19% Commercial
Married Split: ~79% Private / ~21% Commercial (based on chart: 0.50bn vs 0.13bn)
Insight: The private/commercial use split is remarkably stable across all groups. Marital status does not significantly influence whether a vehicle is used for commercial purposes.

5. Coverage Zone (The Most Revealing Difference)

Overall: Very even distribution (~19–20% each across all 5 zones).
Divorced: Skewed Urban (Urban + Highly Urban = 42% of claims).
Married: Skewed Suburban/Rural (Suburban 20.44% + Rural 20.24% + Highly Rural 19.87% = ~60.5% of claims).
Insight: This is the most significant segmentation finding. Divorced policyholders cluster in urban cores, while Married policyholders dominate suburban and rural areas. This has major implications for risk type (urban: theft, collisions vs. rural: animal strikes, higher-speed accidents).

6. Car Make Analysis (Top 5)

Overall Top 5: Ford, Chevrolet, Dodge, Toyota, GMC
Divorced Top 5: Ford, Chevrolet, Dodge, Toyota, Mitsubishi
Married Top 5: Ford, Chevrolet, Dodge, Toyota, GMC
Insight: The Married segment’s top 5 matches the overall list perfectly, confirming they are the driving force behind the overall portfolio’s make distribution. The replacement of GMC with Mitsubishi in the Divorced top 5 is a clear signal of different economic or lifestyle preferences post-divorce.

Single policyholders are the dominant force in the portfolio by volume. They define the “average” because they are the plurality. Their risk profile (severity) is standard.

2. Gender Analysis

Single: Females ($389.33M) ≈ Males ($385.47M) — Most balanced of all segments.
Married: Females ($318.56M) > Males ($314.19M)
Divorced: Females ($162.42M) > Males ($155.99M)
Insight: While females lead in total claim amount across all segments, the gap is smallest among Singles. This suggests more equal car ownership and usage patterns among single men and women.

3. Education Impact

All Segments: Bachelor’s > High School > Masters > PhD
Single Amounts: Bachelor’s ($387.2M) > High School ($213.67M) > Masters ($119.34M) > PhD ($54.58M)
Insight: The rank order is immutable. The proportional spread for Singles looks similar to others. Education is the universal, dominant risk/volume factor, transcending marital status.

4. Car Use

All Segments: ~80% Private / ~20% Commercial
Single Split: ~80% Private / ~20% Commercial (0.65bn vs 0.13bn implied)
Insight: Extremely stable. Vehicle use (personal vs. commercial) is completely independent of marital status. This is a business-wide constant.

5. Coverage Zone (The Critical Differentiator)

Single: Perfectly even distribution (~19.8% — 20.2% across all 5 zones).
Married: Skewed Suburban/Rural (~60% in Suburban + Rural + Highly Rural).
Divorced: Skewed Urban (~42% in Urban + Highly Urban).
Overall (from 1st report): Even distribution — because Singles pull the average to even.
Insight: This is the most actionable finding. Singles are geographically dispersed, Married live in suburbs/rural areas, Divorced concentrate in cities. Marital status is a strong proxy for location.

6. Car Make Analysis (Top 5)

Single Top 5: Ford, Chevrolet, Dodge, GMC, Toyota
Married Top 5: Ford, Chevrolet, Dodge, Toyota, GMC (matches Single order)
Divorced Top 5: Ford, Chevrolet, Dodge, Toyota, Mitsubishi
Overall Top 5: Matches Single/Married (Ford, Chevy, Dodge, Toyota, GMC)
Insight: The Single and Married segments define the mainstream market (Ford, Chevy, GMC). The Divorced segment is the outlier, with Mitsubishi replacing GMC in the top 5, signaling a distinct economic or lifestyle shift.

1. Overall Claims Frequency Overview

Total Claims: 38,000 (matches the total from the first severity report).
Key Insight: We now have the denominator for all our previous analyses. We can start calculating claim frequency rates.

2. Gender Analysis (Claims Count)

Chart Data: The bar chart shows Female ~20K claims vs. Male ~18K claims.
Previous Finding (Severity): Females also had a slightly higher total claim amount.
New Insight: The higher total claim amount for women is driven by a higher number of claims (frequency), not by more expensive claims. Their claim frequency is ~10% higher than men’s.

3. Education Impact (Claims Count)

Chart Data: Bachelor’s (~19K) >> High School (~10K) > Masters (~6K) > PhD (~3K).
Previous Finding (Severity): Bachelor’s degree holders also had the highest total claim amount.
New Insight: Again, the pattern is driven overwhelmingly by frequency. Bachelor’s holders file over 3x the claims of PhD holders. Education is the single strongest predictor of claim frequency.

4. Car Use (Claims Count)

Chart Data: Private (~30K) >>> Commercial (~8K). This is a ~79%/21% split.
Previous Finding (Severity): The split of total claim amount was ~80%/20%.
New Insight: The frequency split matches the severity cost split almost exactly. This means the average cost per claim is similar for private and commercial use. The difference is purely volumetric.

5. Coverage Zone (Claims Count)

Data: The distribution is nearly perfectly even: Rural (7.45K), Highly Urban (7.59K), Suburban (7.47K), Urban (7.51K), Highly Rural (7.52K). All are ~19.8–20.2% of total claims.
Previous Finding (Severity): The total claim amount was also evenly distributed.
Critical New Insight: This reveals that the average claim severity ($50K) is constant across all geographic zones. Urban zones do not have more expensive claims on average they just have more policyholders (or riskier exposure) leading to higher total amounts.

6. Car Make — Top 5 by Claims Count

Rank by Frequency: Ford (2.95K) > Chevrolet > Dodge > Toyota > GMC (1.75K).
Previous Finding (Severity): The rank by total claim amount was identical: Ford > Chevrolet > Dodge > Toyota > GMC.
New Insight: Ford’s top position is due to it having the highest claim frequency. The average cost per claim for each make must be relatively similar, as the frequency rank mirrors the severity rank.

7. Integration with Marital Status Slices (Crucial Synthesis)

Now we can combine frequency and severity data for a full risk assessment.

Recall our key marital status finding: Marital status segments customers by geography (Urban Divorced vs. Suburban Married vs. Dispersed Single).

New Frequency Data says: Claim frequency and severity are evenly distributed geographically.

The Powerful Conclusion:

Divorced policyholders are concentrated in Urban areas.
Urban areas have a proportional share of claims (neither more nor less frequent than average).
Therefore, Divorced policyholders, as a group, should have a claim frequency rate that matches the portfolio average.
The same logic applies to Married (Suburban/Rural) and Single (dispersed) segments.
This means the primary risk difference between Married, Single, and Divorced is NOT their likelihood of having a claim (frequency) or the cost of that claim (severity), but rather the TYPE of risk they are exposed to due to their geography (e.g., urban theft vs. rural animal strike).

RECOMMENDATION

Based on Integrated Analysis of Claim Frequency & Severity by Marital Status

1. Underwriting & Pricing Strategy

Immediate Actions:

Remove Marital Status as a Direct Rating Factor for base premium calculations, as it does not correlate with higher claim frequency or severity.
Implement Geographic Rating Tiers based on density (Urban, Suburban, Rural) to align with the different peril exposures (theft/vandalism vs. animal collisions).
Strengthen Weight of Education Level in risk models — Bachelor’s degree holders file significantly more claims across all segments.
Use Vehicle Make/Model as Key Rating Variable — Ford and Chevrolet dominate both frequency and severity; consider adjusters for makes with higher exposure.
Long-Term Pricing Model Review:

Develop a multi-dimensional pricing model that combines:

Geographic zone
Education level
Vehicle make
Car use (private/commercial)
Test telematics or usage-based insurance (UBI) offerings for high-frequency segments (e.g., Bachelor’s holders in urban areas).

2. Marketing & Customer Segmentation

Targeted Campaigns by Segment:

Married Policyholders (Suburban/Rural):
Focus on family safety bundles, multi-car discounts, and teen driver monitoring.
Partner with suburban retail chains, schools, and family-oriented media.
Divorced Policyholders (Urban):
Promote simple, affordable coverage with urban-specific benefits (rental car, roadside assistance).
Use digital marketing in metro areas and social platforms frequented by single adults.
Single Policyholders (Nationwide/Neutral):
Highlight flexibility, digital tools, and value — appeal to a broad, mobile demographic.
Use broad-reach channels: streaming ads, search engine marketing, and mobile apps.
Brand Positioning:

Position the company as geographically intelligent — “We understand your drive, wherever you live.”

3. Product Development & Innovation

New Product Ideas:

Urban Driver Package: Includes enhanced glass coverage, theft protection, and congestion-related roadside assistance.
Suburban/Rural Family Package: Bundles auto with home insurance, includes animal collision waiver, and offers teen driver coaching apps.
Education-Based Loyalty Program: Offer premium discounts or safe driver rewards for advanced degrees (Masters, PhD) who show lower claim frequency.

Technology Integration:

Invest in AI-driven claim triage to handle high-frequency segments efficiently.
Develop a customer portal that provides personalized risk insights based on education, location, and vehicle type.

4. Risk Management & Loss Prevention

Preventive Programs:

Launch “Safe City Driving” workshops in urban centers targeting Divorced and Single segments.
Create “Rural Road Ready” kits for Married policyholders — include animal alert whistles, emergency blankets, etc.
Partner with vehicle manufacturers (Ford, Chevrolet) to offer discounted safety features (e.g., collision avoidance systems) to policyholders.

Fraud & Claims Management:

Focus fraud detection on high-frequency segments (Bachelor’s, Urban zones).
Streamline claims process for low-severity, high-frequency claims to improve customer satisfaction and reduce handling costs.

5. Portfolio Diversification & Growth

Strategic Growth Areas:

Expand in Urban Markets with tailored products for Divorced and young Single professionals.
Strengthen Suburban/Rural Agent Networks to serve Married families more effectively.
Explore Commercial Line Expansion — commercial use claims are less frequent but stable; consider bundling commercial auto with business insurance.

Monitor Exposure:

Keep a close watch on Ford and Chevrolet claims — any recalls or model-specific issues could impact a large portion of the book.
Track economic shifts that may affect marital status distributions (e.g., marriage rates, urbanization trends).

6. Communication to Stakeholders

Key Messages:

To Investors: “Our book is geographically and demographically balanced. Risk is predictable and manageable.”
To Regulators: “Our pricing is based on objective, non-discriminatory factors (education, geography, vehicle) backed by data.”
To Customers: “Your premium is fair and based on how, where, and what you drive — not your personal life.”

CONCLUSION

This comprehensive analysis of Anchor Auto Insurance’s policyholder data — spanning claim severity, claim frequency, and demographic segmentation by marital status — provides a clear and actionable portrait of risk, behavior, and opportunity within the portfolio.
