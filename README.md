# dev-sec-opps

![DevOps Title image](/images/devops-process.png)

Place to collaborate on the DevOpd project
## List of goals:
###	Tech is easy people are hard (Culture Change) 

* In order to facilitate culture to change, I must create small “wins” in automation, then publicize it though demonstration and training as much as I can to try and spread the change. The cultural shift must occur at all levels including the senior management – How Sr. Mgmt. will adapt to interact and support the new culture can be taught through training sessions or table top exercises.

* Settle on a common tool set that integrates easily with tools developers currently use.

* Document current state and pain points, create a strategic plan.

###	How to boil the ocean (Implement DevOps CI/CD)

* Plan for small projects that we can demonstrate to Dev teams and Managers to support #1 goal.

* Look for opportunities to automate processes that are redundant or time consuming for potential pilot projects.

* Plan for Short term, Medium term and long term goals, and document our path(confluence project/Kanban?)

* Some “manual” interventions may still be needed. Stack manual processes based on mission, cost, and political capital to prioritize which manual process can be automated and which ones will need to be accepted for today and undergo future review.

###	Use peer pressure of tool adoption (Common Tools, processes, and Standards) 

* Once more dev teams adopt the CI/CD tools and approach there will be pressure to bring the more conservative teams on board.

* It’s easier to seek forgiveness than ask for permission or get concurrence.(a little scary here, but the point is understood)

* Strive for one repository one set of metrics. ( there can’t be multiple ground truths)
  
    * Key factor: Centralize the Dev/Test/deploy capabilities as much as possible
    
## Roadmap

### Map Our Development/ Delivery Process (SDLC)

* Let's ask ourselves, do we really understand everything that is happening in our delivery process and how long it actually takes? If we don’t really know or are not sure the first order of business is to bring stakeholders from across the Development/ Delivery lifecycle together and map the process out. Do this with all the stakeholders in the room. Techniques from Value Stream mapping may come in handy here.

### Identify Pain Points and Bottlenecks

* Once we have the map of the process, we need to add some quantifications on it like how often feedback loops are run through, the volume of requests, and cycle times. This is why ULM modeling would be helpfull. We will use this information to identify pain points and bottle necks in legacy processes. It will also help us with baselining some performance metrics that we want to improve. It is good practice to define metrics for bottlenecks so that you can see them being removed.

### Address the Minimum Viable Cluster of Applications for DevOps Shift

* Identify the minimum viable cluster that you can address and which will have significant meaning if we can improve it. The minimum viable cluster can be determined from your previous analysis of the process and the analysis of our application architecture as we are now able to identify a set of application that needs to be delivered together. The pain points and bottlenecks will give us an indication which integration points are important (like those for performance testing, or application deployment or integration testing) while others with systems that don’t change or dont have much data flow are less important. We need to make sure to challenge ourselves on the **minimal** set as casting the net too wide will hinder our progress and being too narrow will mean we wont demonstrate the benefit. For this minimum viable cluster we must integrate as early in the lifecycle as possible by deploying all the required tools from the common industry DevOps best practice to get the shortest possible feedback cycles.

A key factor of success lies in the development and execution of our roadmap and the right amount of governance. Making sure that we have tight feedback cycles and that the different groups remain aligned to the goals and the underlying technical architecture is going to be very hard work. We need to enlist our best change agents across the organisation to help. Even at HQ and NPPD levels.






