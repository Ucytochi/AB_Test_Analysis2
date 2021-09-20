## Project Description

Given a dataset from a startup that sells food products. We are to investigate users' behavior for the company's app and recommend the optimal fonts for the entire 
app from the A/A/B test carried out on 3 different groups of the users. 

The users are split into three groups: two control groups get the old fonts and one test group gets the new ones. We found out which set of fonts produces better 
results. Creating two A groups has certain advantages. We made it a principle that we will only be confident in the accuracy of our testing when the two control 
groups are similar. If there are significant differences between the A groups, this can help us uncover factors that may be distorting the results. 
Comparing control groups also tells us how much time and data we'll need when running further tests. 

After preprocessing the dataset, we looked at the events and their frequencies, user behaviour (paying and returning users), ran some statistical hypotheses and 
then made our conclusions and some recommendations.

---
### Dataset Description

This dataset was made available by - [Practicum by Yandex](https://www.practicum100.com/)

It contains 4 columns - event name, user id, event time, and group id. The event name has 5 main events while the group id has 3 main groups (two control 
group (246 and 247) and one test group(248)). Each log entry is a user action or an event.

`EventName` — event name

`DeviceIDHash` — unique user identifier

`EventTimestamp` — event time

`ExpId` — experiment number: 246 and 247 are the control groups, 248 is the test group

I do not have the rights to share the dataset used in this analysis

---

### Libraries Used

pandas, datetime, matplotlib.pyplot, plotly.express, scipy, stats, numpy, math
