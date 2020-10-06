# Real Time Traffic Information Sharing Between Autonomous Vehicles

### Project Report
PDF version avaliable at: https://bit.ly/3iFR1jM

## Overview
The current detection system used by autonomous vehicles, which relies on their own camera and radar, does not make good advantage of the vehicle-to-vehicle network and thus is inefficient. With inter-vehicle network, vehicles can share traffic information more efficiently to improve their performance and prevent potential accidents. Sharing real-time data between vehicles on the road will  also reduce delays and speed up traffic safely.

Research has been done on constructing a network of cars. Vehicular Ad-hoc Network (VANET) is proposed to connect moving cars as nodes in a wireless network. This network investigates the vehicle-to vehicle (V2V) aspect of the road network system to improve transportation operations [1]. However, this technique will require car computers to support network connection [2], which is not yet completely achieved. 

## Methodologies and Evaluation
The plan is to build a new peer-to-peer protocol based on the current application layer in the networks. It will be an overlay on the existing mobile networks but with better adaptability to fit the special requirements of running environment of self-driving vehicles. The final deliverable outcome of this project will be represented in an emulation prototype. The expected result varies depending on the actual process of this project.

## Tentative Schedule
| Weeks          | Milestones      | Notes  |
| :------------: |:---------------:| :-----:|
|Feb 3 - Feb 16|Research on related papers||
|Feb 17 - Feb 23|Draft idea for the model|(Reading Break)|
|Feb 24 - Mar 8|Build the first theory model|(Midterm presentation)|
|Mar 9 - Mar 22|Implement simulations||
|Mar 23 - Apr 3|Final delivery|(Final presentation)|

## References
[1]	T. L. Willke, P. Tientrakool and N. F. Maxemchuk, “A survey of inter-vehicle communication protocols and their applications”,  in IEEE Communications Surveys & Tutorials, vol. 11, no. 2, pp. 3-20, Second Quarter 2009. DOI: 10.1109/SURV.2009.090202

[2]	Steven E. Shladover, “Connected and automated vehicle systems: Introduction and overview”, Journal of Intelligent Transportation Systems, 22:3, 190-200, DOI: 10.1080/15472450.2017.1336053

## Terminology correction:
In the project proposal we used the term “autonomous vehicles”. After doing more research in this area, we realize that “autonomous system” describes systems that can make decisions independently. However, since the system our work is based on is not just about decision making, it’s more accurate to use “automated vehicles” instead.

## Specified goal
Our plan, as specified in the proposal, is to build a new peer-to-peer protocol based on the current application layer in the networks. The feedback from our professor is to consider V2X (vehicle-to-everything) connection. Taking the feedback into consideration, we further specify our goal as to build a new P2P protocol based on the automated vehicles, pedestrians, and road infrastructure network connected using DSRC and WIFI. We are still on our way to deciding whether we should take cellular communication (4G/5G) into the scope of our project.

## Results of literature study
During the past few weeks, our main task was to do literature study on this topic to see where we are currently at. For automated vehicle systems, we are at the fourth wave of its development, which began with the Defense Advanced Research Projects Agency (DARPA) Challenges in the 2000s. Right now, we divide the automation systems into 5 categories, ordered by their level of automation. This five-level classification is brought up by Society of Automotive Engineers (SAE) International and provides examples of how the system would operate for each level. 
We are especially interested in connecting the automated vehicles using some P2P protocol, so it is necessary to study the connected vehicle system. The concept of dedicated short-range communications (DSRC) is introduced in this area. DSRC is the foundation of such connected systems, and it will be the main thing we put our new layer on.

