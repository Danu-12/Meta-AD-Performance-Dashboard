[![Gemini-Generated-Image-zyt9tzyt9tzyt9tz.png](https://i.postimg.cc/VLphZXnP/Gemini-Generated-Image-zyt9tzyt9tzyt9tz.png)](https://postimg.cc/kBNwB6TT)

# Meta Ad Performance  Dashboard

Running paid advertising campaigns on platforms like Facebook and Instagram has become increasingly competitive and expensive. Marketing teams must ensure that their ad spend reaches the right audience segments, drives meaningful engagement, and ultimately leads to conversions such as clicks, purchases, or sign-ups.

However, with multiple campaigns, ad formats, and audience segments running simultaneously, it becomes difficult for marketing teams to quickly identify which campaigns are actually driving performance and which are wasting budget.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Structure](#data-structure)
3. [Executive Summary](#executive-summary)
4. [Insights Deep-Dive](#insights-deep-dive)
   - [Campaign Performance](#campaign-performance)
     - [Engagement & CTR Performance](#engagement--ctr-performance)
     - [High vs Low Conversion Campaign Performance](#high-vs-low-conversion-campaign-performance)
   - [Geographic Performance](#geographic-performance)
   - [Ad Format Performance](#ad-format-performance)
5. [Recommendations](#recommendations)
6. [Tech Stack](#tech-stack)
7. [Dashboard Preview](#dashboard-preview)
  
---

## Project Overview

This project analyzes over 80,000 Meta advertising performance records to evaluate the effectiveness of paid campaigns across key marketing funnel stages—engagement, clicks, and conversions. The analysis focuses on three **North Star metrics: Engagement Rate, Click-Through Rate (CTR), and Conversion Rate**, supported by additional metrics such as impressions, clicks, likes, shares, comments, and purchases.

To uncover deeper insights, campaign performance is analyzed across multiple dimensions including:     
  * **User demographics (Age, Gender)**
  * **Ad formats**
  * **Time of day**

By combining these metrics and dimensions into a structured performance view, the dashboard enables marketing teams to:
  * Identify high-performing audience segments
  * Compare campaign performance
  * Detect underperforming ads
  * Make data-driven decisions to optimize ad spend and improve campaign effectiveness

**This dashboard helps marketing teams answer questions such as:**

  * Which campaigns generate the highest CTR and conversions?
  * Which audience demographics engage the most with ads?
  * Which ad formats drive better engagement and purchases?
  * What time of day delivers the best campaign performance?

---
##  Data Structure

![Data_Structure](https://i.postimg.cc/4NzW4DLk/datastr.png)

---
## Executive Summary

![KPis](https://i.postimg.cc/HLMzY4fh/kpis.png)

Campaign performance shows **strong top-of-funnel engagement**, with an **Engagement Rate of 13.56%** and a **CTR of 11.76%**, indicating ad creatives are highly effective at capturing user attention & driving clicks. The overall **Purchase Rate remains low at 0.61%** of impressions, revealing a drop-off in the lower stage of the conversion funnel. 

Audience behavior highlights **young adults (20–30 age group) as  most responsive segmen**t, with engagement declining noticeably among audiences aged 35 and above. **Female audiences consistently show higher engagement** than males, indicating stronger resonance with this demographic.

Regionally, **India and the United States demonstrate strong engagement and reach,** while Germany and the United Kingdom show relatively stronger conversion potential, likely driven by higher purchasing power.

Among creative formats, **Story ads generate the highest impressions and conversion**, while Images and Videos higher enegaement and CTR, suggesting that multi-visual ad formats may be more effective in encouraging purchase decisions.

---
## Insights Deep-Dive
---

##  Campaign Performance

![Campign trend](https://i.postimg.cc/ZYgcC2K2/Campign-Trend.png)  


### Engagement & CTR Performance

**Key Findings**
  * Campaign 12 stands out as the strongest traffic driver, achieving the highest engagement (18%) and CTR (13%) among all campaigns. This shows that the creatives and targeting are effective in attracting user attention and encouraging clicks. However,despite generating strong interaction, the campaign delivers a modest conversion rate of 3%, suggesting high engagemnt is not converting into purchases.
    
  * In contrast, Campaign 45 shows lower engagement and CTR (16% and 11%) but achieves a higher conversion rate of 5%, suggesting that although fewer users interact with the ads, those who do are more likely to complete a purchase.
    
* This indicates that Campaign 12 is effective at driving engagement and traffic, while Campaign 45 performs better in converting interested users into buyers.

---
**Drilldown Analysis: Factors Driving Campaign Performance**

  * Campaign 12 primarily uses Facebook Story ads and focuses on male audiences with interests in photography, gaming, and sports. These interests naturally generate high engagement, which explains the strong interaction metrics.

However, the age targeting may not fully match purchasing behaviour. Photography is directed toward the 18–24 age group, which may have limited purchasing power for expensive equipment, while gaming and sports are targeted toward 35–44, which may be older than the most active segment for these interests. This mismatch likely reduces the campaign’s ability to convert engagement into purchases.

* In contrast, Campaign 45 focuses on female audiences with interests in health, sports, gaming, and technology, using both image and story formats across Instagram and Facebook. While this strategy generates slightly lower interaction, the higher conversion rate suggests stronger alignment between the ad messaging, product offering, and audience needs, leading to higher purchase intent among users who click the ads.

[![High-eng.png](https://i.postimg.cc/D0qv95jH/High-eng.png)](https://postimg.cc/2LSNvdf7)


--- 

## High vs Low Conversion Campaign Performance

**Key Findings**
* Campaign 27 emerges as the most effective campaign in driving purchases, achieving a conversion rate of 9% and a purchase rate of 1%. These metrics shows that a significant proportion of users who interact with the ads proceed to complete a purchase.

* While, Campaign 36 shows the weakest conversion performance, with a conversion rate of only 2% and a purchase rate of 0.4%. This highlights that although the campaign may generate some level of interaction, it is far less effective at converting that interest into actual transactions

* This pattern indicates that Campaign 27 is highly effective in driving purchases, while Campaign 36 struggles to convert audience engagement into actual sales.

--- 

**Drilldown Analysis: Factors Driving Conversion Differences**

  * Campaign 27 uses a mix of Carousel and Story ads while targeting female audiences with interests in travel, finance, fitness, and technology. These interests may align closely with the promoted product, while the use of Story ads — which often provide a more immersive and engaging viewing experience — may further support higher conversion rates.

  * By contrast, Campaign 36 relies on Image and Carousel formats while targeting a broader audience, including all users and females with interests in fashion, sports, and food. While these categories can generate general engagement, the broader targeting and interest selection may not strongly reflect purchase intent, which likely contributes to the lower conversion and purchase rates observed for this campaign.


        Campaign 27 → Targeted audience + high converting ad format → High conversion
        
        Campaign 36 → Broader targeting + lower converting formats → Low conversion

[![high-cr.png](https://i.postimg.cc/qq8JPQbb/high-cr.png)](https://postimg.cc/V0kPM9cn)

---
### Audience Insights
  * Female users account for approx. 64% of total engagement, while male users contribute around 34%, indicating that campaigns resonate more strongly with female audiences.
  * The audience of 20–30 age group generates the highest interaction levels, with particularly strong engagement among users in their early twenties, while engagement drops noticeably for audiences aged 35 and above. The pattern shows that young adults represent the primary audience segment driving engagement for the campaigns.

![Eng by gender](https://i.postimg.cc/6q77qL9P/age.png)   ![Eng by gender](https://i.postimg.cc/nzWzyj4x/of-gender-eng.png)

---
### Geographic Performance
  * **The United States, United Kingdom, and Canada** generate the highest engagement levels, indicating strong campaign reach and audience interaction in these regions. These markets appear to be effective for driving visibility and traffic to the platform.
  
  * However, **Japan and Mexico** record the highest conversion rates, suggesting stronger purchase intent among users who engage with ads. While engagement volume may be lower in these markets, users who interact with campaigns are more likely to complete purchases.

        High Engagement Market → Good for Traffic
        High Conversion Market → Good for Sales
    

        Traffic markets → optimize conversion
        Sales markets → increase reach

![Geo Perf](https://i.postimg.cc/9FgP9Tfw/country.png) 

---

### AD Format performance
  * **Image and video ads** are most effective at capturing user attention and driving interaction as they generate the **highest engagement and click-through rates.**
  * **Story ads** deliver the **highest impressions, clicks, and conversion rate**, likely because they appear in a full-screen format between user stories, which captures more user attention and encourages quicker interaction.
  * **Carousel ads** record the **second-highest conversion rate**, suggesting that showing multiple visuals in a single ad helps users understand the product better and increases the likelihood of purchase.
    
        More visuals → better product understanding → higher chance of buying

![ad_type](https://i.postimg.cc/RZvg6NHs/ad-type.png) 

---
## Recommendations

### Optimize Audience Targeting to Improve Conversions

   * Refine audience targeting for Campaign 12 to better align with high purchase-intent segments.    
         -For photography-related interests, increase the target age group to 24–35, where purchasing power for equipment is typically stronger.     
         -For gaming and sports interests, narrow the targeting to the 25–35 age group to focus on a more active and commercially responsive audience. 

   * Additionally, improving the product offer or messaging to better match these audience segments can strengthen purchase intent, helping convert the campaign’s strong engagement and traffic into higher conversion rates and increased purchases.

---

### Allocate More Budget to High-Converting Campaigns

   * Increase budget allocation toward high-converting campaigns such as Campaign 27 and Campaign 45 to maximize purchase outcomes.   
      -To further strengthen performance, prioritize Image and Video ad formats within these campaigns to leverage their higher engagement and CTR for driving traffic, while continuing to use Carousel and Story formats to maintain strong conversion performance. 
   * This balanced format strategy can help attract more users into the funnel while preserving conversion efficiency, ultimately improving overall purchase volume and return on ad spend.

---

### Align Ad Formats with the Marketing Funnel

   * Adopt a funnel-based ad format strategy to improve campaign efficiency.   
      -Use Image and Video formats in top-of-funnel campaigns to maximize engagement and CTR and attract new users.   
      -In the middle of the funnel, leverage Carousel ads to highlight multiple product features and help users better understand the product offering.   
      -For bottom-of-funnel campaigns focused on purchases, prioritize Story ads to drive quick actions through their immersive full-screen format.
   * Aligning ad formats with the appropriate stage of the marketing funnel can strengthen user progression from awareness to purchase, ultimately improving conversion performance and increasing overall purchase volume.

           Marketing Funnel Strategy
                 ↓
         Top of Funnel (Awareness)
         Images & Videos → strong engagement and high CTR → attract new users
                 ↓
         Middle of Funnel (Consideration)
         Carousel → showcase multiple product features → improve product understanding
                 ↓
         Bottom of Funnel (Conversion)
         Stories → immersive full-screen format → encourage quick purchase actions
                 ↓
         Right format at each funnel stage
                 ↓
         Higher campaign efficiency + more purchases

---

### Target High-Engagement Demographics to Strengthen Campaign Performance

   * Prioritize targeting younger audiences—particularly women aged 20–25—who represent the most responsive segment in terms of engagement. 
   * Tailor ad creatives, messaging, and visual themes to resonate with this demographic by focusing on content that aligns with their interests, lifestyle, and consumption patterns.
   * Concentrating campaign efforts on this highly engaged audience segment can amplify interaction levels, improve click-through performance, and increase the likelihood of moving users further down the marketing funnel toward conversions.

---

### Adopt a Region-Specific Campaign Strategy

   * Implement a region-specific optimization strategy based on market behavior.   
      -In high-engagement markets such as the United States, the United Kingdom, and Canada, optimize campaigns for conversions by prioritizing Story and Carousel ad formats, strengthening product offers, and improving the landing page to turn strong traffic into purchases.   
      -In high-conversion markets like Japan and Mexico, expand reach-focused campaigns using Image and Video formats to attract more users into the funnel.
   * Aligning campaign objectives and ad formats with regional performance patterns can improve both conversion efficiency and traffic acquisition, ultimately increasing overall purchase volume and marketing return.



---
## Tech Stack

The dashboard was built using the following tools and technologies:


| Tool / Technique | Purpose |
|------------------|---------|
| **Power BI Desktop** | Primary data visualization platform used to design and build the interactive dashboard. |
| **Power Query** | Used for data cleaning, transformation, and reshaping raw advertising data before analysis. |
| **DAX (Data Analysis Expressions)** | Created calculated KPIs such as Engagement Rate, CTR, Conversion Rate, and other performance metrics. |
| **Data Modeling** | Built relationships between campaign, audience, and performance tables to enable accurate filtering and analysis. |
| **Pivot Tables & Pivot Charts (Excel)** | Used for preliminary data exploration, aggregation, and storytelling during the early analysis phase. |
| **Drill-Down Analysis** | Applied to explore campaign performance across multiple dimensions and uncover deeper behavioral patterns. |
| **File Formats** | `.pbix` used for development and `.png` used for dashboard previews in the repository. |


---


---

## Dashboard Preview

![Dashboard Preview](https://github.com/Danu-12/Meta-AD-Performance-Dashboard/blob/main/Meta%20AD%20Performance%20Dashboard.gif)



---


