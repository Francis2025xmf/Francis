# Evaluating the State of Seniors Healthcare in Canada: Challenges, Innovations, and Policy Recommendations

*By: Francis Ankona Diawuoh*

Executive Summary
Canada’s aging population is growing rapidly, with seniors (65+) projected to make up 25% of the population by 2036. The fastest-growing demographic is those aged 85 and older, with over 62,000 Canadians expected to be 100+ by 2063. However, increased lifespan brings rising healthcare challenges, including a 40% surge in cancer cases by 2030 and a 66% rise in dementia over the next 15 years.

Canada’s healthcare system, originally designed for acute care, struggles to meet seniors’ complex, chronic care needs, with nearly 80% of seniors managing at least one chronic condition. This project examines the state of seniors’ healthcare, identifies key challenges, and explores innovations and policy solutions to ensure accessible, high-quality care for Canada’s aging population

[Read detailed background](Background.md)

## Key Performance Indicators
1.Ability to Perform Oral Hygiene Independently
This indicator assesses seniors' capacity to maintain personal oral hygiene without assistance, reflecting their physical dexterity and cognitive function. While specific statistics on Canadian seniors' ability to perform such tasks independently are limited, understanding this aspect is crucial. It highlights their level of independence and can signal the need for additional support services when declines are observed.

2.Access to Health Support
This metric evaluates the extent to which seniors receive assistance from healthcare professionals or informal caregivers for health-related issues. Data from the National Institute on Ageing indicates that up to 58% of Canadians aged 50 and older have experienced loneliness, which can be exacerbated by limited access to health support. Ensuring adequate support is vital for managing health conditions and maintaining quality of life.

3. Interest in Social Engagement
This indicator measures seniors' desire to participate in social or group activities, reflecting their social well-being. According to Statistics Canada, nearly one in four seniors reported barriers to social participation in 2019 and 2020, with those facing such barriers being almost three times as likely to experience loneliness. Encouraging social engagement is essential for mental and emotional health.

4.Fall Incidents
This metric tracks the prevalence of falls among seniors, a significant health concern due to the risk of serious injury. While specific statistics on fall incidents were not found in the provided sources, monitoring this indicator is crucial for implementing preventive measures and ensuring seniors' safety.

5.Healthcare Utilization
This indicator reflects the frequency of seniors' interactions with healthcare services. According to the National Institute on Ageing, as many as 41% of Canadians aged 50 and older are at risk of social isolation, which can lead to increased healthcare needs. Regular healthcare utilization is important for early detection and management of health issues.

6.Feelings of Isolation
This metric assesses the prevalence of loneliness among seniors. A study by Statistics Canada revealed that almost one in five Canadian seniors (19%) aged 65 and older reported experiencing loneliness in 2019 and 2020, with senior women more likely to report being lonely than senior men (23% versus 15%). Addressing feelings of isolation is crucial for seniors' mental and physical health.

7.Perceived Health Decline
This indicator captures seniors' subjective assessment of their health over time. While specific statistics on perceived health decline were not found in the provided sources, understanding this perception is important for identifying areas where healthcare interventions may be needed to improve seniors' well-being.


## Technical Details:

    - $Rate = {Count Of Admissions \over SeniorPopulation}$ 
    - Dimensions: By province
    - Frequency: Yearly?

# Analysis

Some text or whatever

![Map of Canada](img/fig1.png)
By evaluating these indicators collectively, the project will provide a comprehensive analysis of the state of seniors' healthcare in Canada. It will highlight areas for policy improvement, identify gaps in healthcare access and social support, and offer data-driven recommendations for enhancing the quality of life for Canadian seniors


![Map of       ](img/fig2.png).
The proportion of seniors who received assistance from nurses, Continuing Care Assistants (CCAs), or friends for health problems or limitations in the past 12 months.

Explanation of figure above
![Map of](img/fig3.png).
The percentage of seniors who expressed a desire to participate in recreational, social, or group activities in the past 12 months.

![Map of](img/fig4.png).
The proportion of seniors who experienced a fall in the past 12 months.

![Map of](img/fig5.png).
The percentage of seniors who required a visit to a doctor or consultant in the past 12 months.

![Map of](img/fig6.png).
The proportion of seniors who reported feeling isolated from others.

![Map of](img/fig7.png).
The percentage of seniors who perceive their health as worse or somewhat worse compared to a year ago.

![Map of](img/fig8.png).
According to a 2023 study by Statistics Canada, almost one in five Canadian seniors (19%) aged 65 and older reported experiencing loneliness in 2019 and 2020. Senior women were more likely to report being lonely than senior men, with 23% of women and 15% of men indicating feelings of loneliness.

![Map of](img/fig9.png).
Perceived health status is a vital self-assessment reflecting an individual's overall health and well-being. Recent data from Statistics Canada indicates a notable decline in the proportion of seniors reporting very good or excellent health. Specifically, this percentage decreased from 49.9% in 2021 to 40.5% in 2023 among Canadians aged 65 and older.

# Causal Inference and Correlation Analysis

## Heat Map

![Map of](img/fig21.png).

This heatmap shows how three senior health factors are connected in Alberta and British Columbia. It reveals that older adults who are able to brush their teeth without help are much less likely to experience falls or feel lonely—which makes sense, since being more independent often goes hand-in-hand with better overall well-being. On the flip side, there's a strong link between falling and feeling lonely; seniors who’ve had a fall are more likely to also feel isolated. It highlights how physical ability and emotional well-being are closely tied together in older age.
## Causal Graph

![Map of](img/fig22.png).

This diagram shows how different factors might influence seniors' health and emotional well-being. It suggests that where someone lives (their Province) can affect their ability to take care of themselves—specifically, whether they can brush their teeth without help. That level of independence, in turn, may influence whether they’re likely to experience a fall or feel lonely. In other words, seniors who are more self-sufficient tend to be safer and feel more socially connected. The province itself may also directly impact the chances of falling or feeling isolated, possibly due to differences in healthcare access, support services, or community engagement.

## Refute Analysis

The analysis looked at whether a senior’s ability to brush their teeth on their own affects their chances of having a fall, while also considering which province they live in. The result showed a positive causal effect — meaning that as independence (in this case, brushing teeth) goes up, the likelihood of experiencing a fall also slightly increases (about 19.8%).

## Conclusion

At first glance, this finding feels surprising. You’d expect that seniors who are more independent would actually be less likely to fall. But this result might suggest that those who are more mobile and self-sufficient could also be more active or take more risks — which might lead to more falls. It could also mean that we’re missing other important factors (like health conditions or home environment) that weren’t included in the analysis. So while the data shows a link, we should take this result with caution and explore it further before drawing strong conclusions.

