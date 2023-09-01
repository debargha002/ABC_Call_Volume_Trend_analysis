# ABC Call Volume Trend Analysis

## Overview

This repository contains data and analysis for a Customer Experience (CX) Inbound calling team's performance over 23 days. The dataset includes various attributes such as Agent_Name, Agent_ID, Queue_Time, Time, Time_Bucket, Duration, Call_Seconds, and call status (Abandon, answered, transferred).

## Dataset Description

- **Agent_Name**: Name of the agent.
- **Agent_ID**: Unique identifier for each agent.
- **Queue_Time**: Duration for which customers have to wait before they get connected to an agent.
- **Time**: Time at which the call was made by the customer in a day.
- **Time_Bucket**: Time bucket for ease of analysis.
- **Duration**: Duration for which a customer and executives are on call.
- **Call_Seconds**: Duration of the call in seconds.
- **Call Status**: Indicates whether the call was Abandoned, Answered, or Transferred.

## Objectives

We aim to use this data to answer the following questions:

### 1. Average Call Time Duration

We will calculate the average call time duration for incoming calls in each Time_Bucket using the provided data.

### 2. Total Volume of Calls

We will create charts and graphs to visualize the total number of calls vs. Time using time buckets, providing insights into call patterns throughout the day.

### 3. Manpower Plan (Daytime)

To reduce the abandon rate to 10% during daytime (9 am to 9 pm), we will calculate the minimum number of agents required in each time bucket, ensuring that at least 90 out of 100 calls are answered.

### 4. Manpower Plan (Day and Night)

Taking into account nighttime calls (9 pm to 9 am) and aiming for a maximum abandon rate of 10%, we will propose a manpower plan required during each time bucket in a day.

### Link to the dataset- [Click here to show the Excel File](https://docs.google.com/spreadsheets/d/1XlFpdAguLh54RbsOvQuV0Fr9yfZ8lK9i/edit?usp=sharing&ouid=111193544763207162166&rtpof=true&sd=true)

