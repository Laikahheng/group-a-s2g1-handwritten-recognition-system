# PROJECT OVERVIEW
## B. PLANNING THE PROJECT

### Project Management Life Cycle:

The project management life cycle is represented and documented in the form of a Gantt chart, which allows us to follow the guidelines and achieve the milestones from time to time. A Gantt chart is a project management tool that assists in planning by showing start and end dates, as well as dependencies, scheduling, and deadlines, including how much of the task is completed per stage and who is the task owner. The project management WBS is shown in the Gantt Chart below:

<img src="assets/wbs_gantt_chart1.JPG" width="100%">
<img src="assets/wbs_gantt_chart2.JPG" width="100%">

The WBS stands for Work Breakdown Structure. It is a hierarchical representation of the elements (tasks) that comprise a project. The WBS of our project is shown below:

<img src="assets/wbs_tree.png" width="100%">

### Scope

As for the scope, our team has come up with a work breakdown structure (WBS). The WBS consists of all the priamry tasks of the project and has the hierarchical and gradual decomposition of the project into phases, deliverables, and work plans. 

### Risk Chart

| Control Element | What is likely to go wrong? | How and when will I know? | What will I do about it? |
|-----|----|-------|-----|
|Quality <br> (Poor attitude toward quality; substandard design, materials, and workmanship; inadequate quality assurance program)|1. Inadequate Quality Assurance Program: The system confused with car plate number recognition <br> (Ex. digit 0 and letter o) <br><br> 2. Inadequate Quality Assurance Program: The quality of the AI model is biased towards a certain design of the car plate.  |How: The output result always segmented the wrong part of the car plate <br> <br> When: The quality problem of will be determined during the unit testing phase|Assign one member to keep on collecting the data day to day and increased the dataset until a satisfied result is determined.|
|Cost <br> (Estimating errors; inadequate productivity, cost, change, or contingency)|1. Contigency: The costing of the server will be spike if one of the developer forget to shutdown the EC2 instance when not using it. <br><br> 2. Inadequate productivity: Team members are affected by covid-19 and unable to deliver what they suppoosed to deliver which lead to extra cost need to allocated for the cloud servers. |How: The monthly bills shows unexpected extra charged to the bills.<br><br>When: The problem most probably will be encountered during the project execution and project implementation.|Notify the owner through email or discord whenever budget exceed threshold in the AWS cloud computing service.
|Time <br> (Errors in estimating time or resource availability; errors in determining the critical path; poor allocation and management of float; early release of competitive products) | 1. Project not able to reach the milestone set  as described in the Gantt Chart. <br><br> 2. Erros in estimating resource availability: There are not enough server to be used to run the car plate recognition model training  |How: The members are stuck with a certain problem and drag all the other team members <br><br> When: The problem will be encountered during the project excution and monitoring phase.| Ask support from the other team member and switch their task or job to other job to avoid him/her to stuck in the problem loop.|

 



<br><br><br>
##### Next: [Project Implementation](C-PROJECT_IMPLEMENTATION.md)

