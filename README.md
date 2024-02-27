# user_behavior

## Introduction <a id='data_review'></a>

Investigation into user behavior for a company's app

### Project Puropse

Make a decition based on the test results of the user behavior analysis

### Project Description

You work at a startup that sells food products. You need to investigate user behavior for the company's app.
First study the sales funnel. Find out how users reach the purchase stage. How many users actually make it to this stage? How many get stuck at previous stages? Which stages in particular?

Then look at the results of an A/A/B test. (Read on for more information about A/A/B testing.) The designers would like to change the fonts for the entire app, but the managers are afraid the users might find the new design intimidating. They decide to make a decision based on the results of an A/A/B test. 

The users are split into three groups: two control groups get the old fonts and one test group gets the new ones. Find out which set of fonts produces better results.

Creating two A groups has certain advantages. We can make it a principle that we will only be confident in the accuracy of our testing when the two control groups are similar. If there are significant differences between the A groups, this can help us uncover factors that may be distorting the results. Comparing control groups also tells us how much time and data we'll need when running further tests.

You'll be using the same dataset for general analytics and for A/A/B analysis. In real projects, experiments are constantly being conducted. Analysts study the quality of an app using general data, without paying attention to whether users are participating in experiments.


### Data Description

- Each log entry is a user action or an event. 
    - `EventName` — event name
    - `DeviceIDHash` — unique user identifier
    - `EventTimestamp` — event time
    - `ExpId` — experiment number: 246 and 247 are the control groups, 248 is the test group

    
## **Task decomposition:** <a id='data_review'></a>
- Step 1. Open the data file and read the general information
- Step 2. Prepare the data for analysis
- Step 3. Study and check the data
- Step 4. Study the event funnel
- Step 5. Study the results of the experiment
