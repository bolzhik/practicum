## Project description

You work for a startup that sells food. You need to understand how users of your mobile application behave. Analyze the sales funnel and evaluate the results of A/A/B testing based on the data of mobile application for selling food products.

Explore the sales funnel. Find out how users reach a purchase, how many users reach the purchase, and how many get stuck on the previous steps? Which ones exactly?

After that, explore the results of the A/A/B experiment. Designers wanted to change fonts throughout the application, and users were divided into 3 groups: 2 control groups with old fonts and one experimental group with new ones. We have to make a decision about which font is the best and give recommendations according to the results of the A/A/B test.

### Data description

Each entry in the log is a user action, or event.

* `EventName` — event name;
* `DeviceIDHash` — unique user identifier;
* `EventTimestamp` — event time;
* `ExpId` — number of the experiment: 246 and 247 are the control groups, and 248 is the experimental group.
