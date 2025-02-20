---
title: "Review customer satisfaction for your chatbots in Microsoft Teams"
description: "See how well customers are interacting with your bot, and identify areas for improvement in the Power Virtual Agents app in Microsoft Teams."
keywords: "PVA, teams"
ms.date: 01/23/2023

ms.topic: article
author: iaanw
ms.author: iawilt
manager: shellyha
ms.custom: analysis, ceX, teams
ms.service: power-virtual-agents
ms.collection: virtual-agent
---

# Analyze customer satisfaction for Power Virtual Agents bots in Teams

Select the version of Power Virtual Agents you're using here:

> [!div class="op_single_selector"]
>
> - [Power Virtual Agents web app](../analytics-csat.md)
> - [Power Virtual Agents app in Microsoft Teams](analytics-csat-teams.md)

The **Customer Satisfaction** tab on the **Analytics** page provides a detailed view of customer satisfaction (CSAT) survey data, including the average CSAT score over time and the topics that are having the most impact on the CSAT score. This page includes various charts with graphical views of your bot's customer satisfaction indicators.

The **Customer satisfaction drivers** chart shows you the topics that are having the most impact on customer satisfaction.

By default, the page shows you key performance indicators for the last seven days. To change the time period, use the date-time pickers at the top of the page. You can retrieve data for any period within the last 45 days.

## Prerequisites

- [Learn more about what you can do with Power Virtual Agents](fundamentals-what-is-power-virtual-agents-teams.md).

## Customer satisfaction drivers chart

The **Customer satisfaction drivers** chart uses AI to group related support cases as topics. This chart then displays topics in order of their impact on customer satisfaction over the specified time period. The report only lists topics that have had at least one survey response within the report period.

| Description | Details |
| --- | --- |
| Topic | A Power Virtual Agents topic. |
| Engaged sessions | The number of engaged sessions for the topic within the specified time period. |
| Resolution rate | The percentage of engaged sessions for the topic that are resolved. |
| Abandon rate | The percentage of engaged sessions for the topic that are abandoned. |
| Escalation rate | The percentage of engaged sessions for the topic that are escalated. |
| Avg CSAT | The average CSAT survey score for the topic. |
| Impact | The topic's customer-satisfaction impact score. The customer-satisfaction impact score is the overall average CSAT survey score including the topic minus the overall average CSAT survey score excluding the topic. |

The chart displays the impact score. Topics with a positive impact percentage are topics with a higher than average CSAT survey score&mdash;they increased the overall score of your bot.

Increase the average CSAT survey score of topics with high negative impact percentages to more quickly improve the overall CSAT score for your bot.

To see additional information about each topic, select the **Detail** link to display the Topic details page. For more information, see the [Topic details page](analytics-topic-details-teams.md).

## Scores over time chart

The **CSAT scores over time** chart provides a graphical view of the average CSAT score over the specified time period.

## Average CSAT score chart

The **Average CSAT score** chart provides a graphical view of the average of CSAT scores for sessions in which customers respond to an end-of-session request to take the survey. The CSAT survey asks customers to rate their experience on a scale of on a scale of 1 to 5. If an end user responds to more than one survey in the same analytic session, only the most last value is used.

## CSAT survey response rate chart

The **CSAT survey response rate** chart shows the number of CSAT surveys that were presented and the percentage of surveys that were completed.

[!INCLUDE[footer-include](../includes/footer-banner.md)]
