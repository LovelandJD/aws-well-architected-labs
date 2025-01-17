---
title: "Level 200: Cost Visualization"
#menutitle: "Lab #1"
date: 2020-04-24T11:16:08-04:00
chapter: false
weight: 6
hidden: false
---
## Last Updated
May 2020

## Authors
- Spencer Marley, Commercial Architect
- Nathan Besh, Cost Lead, Well-Architected

## Feedback
If you wish to provide feedback on this lab, there is an error, or you want to make a suggestion, please email: costoptimization@amazon.com

## Introduction
 This hands-on lab will guide you through the steps to visualize your cost and usage. The skills you learn will help you analyze your cost and usage, in alignment with the AWS Well-Architected Framework.

![Images/AWSCostReadme.png](/Cost/200_5_Cost_Visualization/Images/AWSCostReadme.png)

## Goals
- Setup Amazon QuickSight
- Configure QuickSight to view your Cost and Usage reports
- Create a dashboard of cost and usage


## Prerequisites
- A management AWS Account
- Have your Cost and Usage Report (CUR) enabled [as per 100_1_Account Setup]({{< ref "/Cost/100_Labs/100_1_AWS_Account_Setup" >}})
- [AWS Account Setup]({{< ref "/Cost/100_Labs/100_1_AWS_Account_Setup" >}}) has been completed
- [Cost_and_Usage_Analysis]({{< ref "/Cost/200_Labs/200_4_Cost_and_Usage_Analysis" >}}) has been completed

## Permissions required
- Log in as the Cost Optimization team, created in [AWS Account Setup]({{< ref "/Cost/100_Labs/100_1_AWS_Account_Setup" >}})
- NOTE: There may be permission error messages during the lab, as the console may require additional privileges. These errors will not impact the lab, and we follow security best practices by implementing the minimum set of privileges required.


## Costs
- [QuickSight pricing](https://aws.amazon.com/quicksight/pricing/?nc=sn&loc=4)
- Standard Edition:  begins at $9-$12 / month per QuickSight user (Each user is an "author." "Readers" do not exist.)
- Enterprise Edition: begins at $18-$24 / month per author; additional users ("readers") billed per user or by capacity (# of unique sessions) 



## Time to complete
- The lab should take approximately 20 minutes to complete


## Steps:
{{% children  /%}}

{{< prev_next_button link_next_url="./1_create_dataset/" button_next_text="Start Lab" first_step="true" />}}