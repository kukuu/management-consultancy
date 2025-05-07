# Management Consultancy 

- Framework for Best Practices
- The 10 Commandments
- Key Considerations for Alignment (ICCS)
- Tools
- Negotiations - https://github.com/kukuu/AGILITY/blob/master/negotiation-skills.md

## Framework for Best Practices

Management Consultancy process involves a systematic approach to requirement gathering, technology alignment, planning, implementation, testing, training, and ongoing support. Throughout each stage, a combination of communication tools, project management platforms, development environments, testing frameworks, and monitoring solutions ensure a successful digital transformation aligned with client goals and industry best practices. Hereby explain the steps: 

- Initial Consultation:

Engage in initial meetings with key stakeholders to understand their business goals and pain points.
Tools: Video conferencing (Zoom, Microsoft Teams), collaboration platforms (Slack, Microsoft SharePoint). 

- Detailed Assessment: 

Analyze the client's existing systems, processes, and infrastructure to identify gaps and opportunities.
Tools: Data analytics tools (Power BI, Tableau, Google Analytics), documentation tools (Microsoft Word, Google Docs).

- Requirements Elicitation:

Conduct workshops, interviews, and surveys to gather detailed requirements from stakeholders.

		Tools: Online survey platforms (SurveyMonkey, Google Forms), collaboration tools (Miro,Figma, SKETCH, MURAL etc).

- Technology Alignment:

Recommend suitable technologies based on gathered requirements and industry best practices.

		Tools: Technology assessment frameworks, research databases.

- Planning and Roadmapping:

Develop an Agile project plan and roadmap outlining phases, milestones, and timelines.

	Tools: Project management tools (Jira, Trello), Agile methodologies (Scrum, Kanban).

1. https://github.com/kukuu/AGILITY
2. https://github.com/kukuu/AGILITY/blob/master/how-long-must-a-scrum-last.md


- Solution Design:

Collaborate with the team to design a comprehensive solution architecture aligned with client needs.

		Tools: Diagramming tools (Lucidchart, draw.io), architecture design tools (Microsoft Visio), Figma, SKETCH, etc.

1. https://github.com/kukuu/scalable-platforms-system-architecture

- Implementation and Integration:

Implement the solution using appropriate technologies and integrate them into the existing environment.

		Tools: Development platforms (IDEs like Visual Studio Code, IntelliJ IDEA), version control (Git).

1. https://github.com/kukuu/software-engineering-best-practices/blob/main/software-engineering-best-practices.md
2. https://github.com/kukuu/integration

- Quality Assurance and Testing:

Conduct thorough testing, including unit testing, integration testing, Pen Testing, Security testing, Compliance and user acceptance testing.
Tools: Testing frameworks (JUnit, Selenium), bug tracking tools (Bugzilla, JIRA), OWASP ZAP, NIST, SOC2.

NIST is a cybersecurity framework providing best practices for managing security risks, while SOC2 is a compliance standard ensuring organizations protect customer data through audited controls.

1. https://github.com/kukuu/AGILITY/blob/master/QA.md

- Deployment to Production

1. https://github.com/kukuu/CI-CD-pipeline-with-Jenkins
2. https://github.com/kukuu/devops.md

- Training and Handover:

Provide training sessions for end-users to ensure they understand and can use the new systems effectively.

		Tools: Learning management systems (Moodle, Canvas), training video platforms (Camtasia, Loom).

- Monitoring and Support:

Set up monitoring tools to track the performance and health of the newly implemented systems.

Tools: Application monitoring tools (New Relic, Datadog, Prometheus), incident tracking systems (ServiceNow).

- Continuous Improvement:

Continuously collect feedback from stakeholders and identify areas for further improvement.

Tools: Continuous improvement frameworks (Lean, Six Sigma), feedback collection tools (SurveyMonkey).

1. https://github.com/kukuu/CI-CD-pipeline-with-Jenkins

2. https://github.com/kukuu/digitalTransformationStrategies

By combining these tools with agile methodologies, DevOps practices, and continuous feedback loops, Solutions Architects can drive efficient, secure, and client-aligned digital transformation.


## The 10 Commandments:

https://github.com/kukuu/Technical-Consulting-Stakeholder-Management/blob/master/stakeholder-management-10-commandments.md


## Key Considerations for Alignment (ICCS)

**Integration:** Ensure tools like Jira ↔ Confluence ↔ Slack or GitHub ↔ Jenkins ↔ Datadog integrate seamlessly.

**Compliance:** Use tools that meet industry standards (e.g., GDPR, HIPAA) and client security policies.

**Client Collaboration:** Prioritize platforms with client-friendly interfaces (e.g., Miro for workshops, Confluence for transparent documentation).

**Scalability:** Adopt cloud-native and modular tools (e.g., Kubernetes, Terraform) for future-proofing.




## DORA

_DevOps Research Assessment_

The primary goal of DORA is to help organizations understand and improve their DevOps capabilities through evidence-based research and data-driven insights

DORA provides valuable benchmarks and best practices for seeking and optimising DevOps initiatives.

### Key Metrics:

Lead Time: The time it takes to convert a customer request or idea into a production-ready feature or service.

Deployment Frequency: The frequency at which an organization deploys changes or releases to production.

Change Failure Rate: The percentage of changes or releases that result in failure or negatively impact the system's stability.

Time to Restore Service: The time it takes to recover from a service disruption or failure and restore normal operations.


## How long should a sprint planning meeting last?
In your experience, how long should a Sprint Planning meeting (Scrum) last? 8 hours? Or should it be shorter (succinct) and further discussions should be planned as part of the sprint? Our Sprints are 10 days long.


8 hours per a 10 day sprint definitely sounds too much to me. Discussions which don't require the whole team should be taken out into separate sessions, only for the members involved

So you plan other meetings instead of discussing everything in the planning?

Discussions should happen about upcoming ideas and plans so that most team members have some basic and shared understanding about them. The criterion is this: during the planning meeting, nobody should be surprised because of hearing a certain thing for the first time. Whenever such "surprise" happens, adjust by increasing the amount of communication that happens before the next planning meeting. (Exceptions to this are truly groundbreaking announcements coming from project owners.) 

According to the Scrum Guide:

The Sprint Planning Meeting is time-boxed to eight hours for a one-month Sprint. For shorter Sprints, the event is proportionately shorter. For example, two-week Sprints have four-hour Sprint Planning Meetings.


Probably a good starting point, but it should also be noted that you do need to tailor the process to your project, team, and organization so that it works for you. Just because other people have had luck with it doesn't mean it will work for you right out of the box. – Thomas Owens♦ Sep 13 '11 at 20:21


However, if you're going to try Scrum, you should probably try it based on the defined guidelines first. Then, if something isn't working, refine it. If you change the rules before you even start, you're disregarding the empirical evidence that made the folks who devised Scrum recommend what they recommended--without any empirical evidence to show that that's the wrong thing for you.


In my team of 3, we usually only had half-hour long sprints, and when the team was 7, it was usually only an hour for two week long sprints


As long as it needs to last, no less and no more. Anything else isn't Agile.

If you have a team of 2 - 3 developers and are doing 1 week sprints anything more than a hour is probably counter productive.

If you have a team of 15 people and 2 weeks sprints you are looking at all day, anything less isn't detailed enough.

It takes experience to get it mostly right, and that is what retrospectives are for, the team decides what is too long or too short.

Don't worry about getting it perfect or sticking to what some book says, try something and refine it


SCRUM is about refining the process in iterations as much as it is about refining your code in iterations.

An hour seems a bit short for 3 developers / 1 week sprints. Then again, I just finished a relatively small project where we did a 5-minute weekly sprint planning. It depends on the project, and on the cards, because sometimes more (or less) discussion is needed during sprint planning.

One of the key ideas of Scrum, as an Agile framework, is that you time-box activities, such as the sprint, the sprint planning meeting, and the daily stand-up/scrum. The point is to keep things focused. Time-boxing does not mean that you cannot take less time than is designated. Just that you should not take more, as that tends to make people lose focus and also reduces the amount of time the team has to actually do the work.


Do not mold your business around the process. The process supports your business. The moment you're doing process for its own sake it's time for the process to get the axe. To that end, there is no "right" way. Meetings should only go as long as you are accomplishing something in them. If it takes you 30 minutes or 4 hours, as long as it works then go with it. Ignore what some book/blog/coach tells you and do what is right for you.


Why not start the process as designed and adapt from there? If you decide to use agile practices and haven't molded your business in that direction, you're already in trouble.

Take as long as you need so that you select enough that your team thinks they can reasonably achieve in the sprint. But you should be spending time during the (previous) sprint refining the backlog: estimating and refining stories.

### Product Backlog Refinement
One of the lesser known, but valuable, guidelines in Scrum is that five or ten percent of each Sprint must be dedicated by the Team to refining (or “grooming”) the Product Backlog. This includes detailed requirements analysis, splitting large items into smaller ones, estimation of new items, and re-estimation of existing items.

Scrum is silent on how this work is done, but a frequently used technique is a focused workshop near the end of the Sprint, so that the Team and Product Owner can dedicate themselves to this work without interruption. For a two-week Sprint, five percent of the duration implies that each Sprint there is a half-day Product Backlog Refinement workshop.

This refinement activity is not for items selected for the current Sprint; it is for items for the future, most likely in the next one or two Sprints. With this practice, Sprint Planning becomes relatively simple because the Product Owner and Scrum Team start the planning with a clear, well-analyzed and carefully estimated set of items. A sign that this refinement workshop is not being done (or not being done well) is that Sprint Planning involves significant questions, discovery, or confusion and feels incomplete; planning work then often spills over into the Sprint itself, which is typically not desirable.


Doing this means you can focus on planning during planning, and it doesn't take all day and the team starts to lose focus and get bored.

### Duration
In Scrum, when working to 2 week sprints, the sprint planning is time-boxed at 4 hours, making it a half day event. One reason for the relatively large amount of time is that the development team must be able to confidently agree that all items being pulled into the sprint backlog can be delivered, which means they need to know the detail. It is not uncommon as part of sprint planning for teams to break off from the meeting space for periods of time in order to investigate items further and ensure that they are "Ready" to go into the sprint backlog. (It can help to think of sprint planning as an event, rather than a meeting.)

Use your "Definition of Ready" and the length of time that the sprint planning event allows to ensure that all backlog items going into the sprint are both feasible and ready. i.e. They can be done (completely, as per "Definition of Done") within the sprint, and there is enough information for the team to be able to do them right now. Note of course that you probably don't want to be doing this for ALL items during the sprint planning, as it can be very time consuming. Do try and have regular backlog grooming (outwith sprint planning) where you can breakdown backlog items, and estimate items not yet estimated using planning poker for example. (I've found this can be a effective activity for over a working dinner with the development team, should you have the luxury of your team's availability at dinner time!)

High priority items can often be added to the product backlog by the product owner just prior to sprint planning though, and whilst routine backlog grooming can, and normally should, be done before the sprint planning event, there will always be new items like this where the team needs to spend time working out the detail and estimating complexity during the sprint planning event, hence why it can stretch to 4 hours for 10 day/2 week sprints.

If you need to take longer discussions out of this event, then you might have a backlog item in the sprint backlog to "have such and such a discussion to establish x", but you should avoid including sprint items to do whatever you are going to determine needs done during that discussion, as those are not "ready" backlog items to go into the sprint.

As people have said, there are reasons you might want to change the way you run Scrum if the process isn't working effectively for you. Scrum is however, a very well thought out and tested framework to start with so I would make sure your reasoning is justified before changing the process.

The SPRINT agenda
In the Sprint Planning Meeting, the team has to determine two sets of things:


A) What will be developed by the team during this Sprint

B) How it will be developed

This meeting must be time-boxed, up to two hours for each week of the Sprint, split evenly for each part (part A and Part B) of the meeting.

So, for a Sprint of 4 weeks, this meeting should be no longer than 8 hours, up to 4 hours for part A and up to 4 hours for part B.

During part A, the dev team has to estimate the team velocity that they consider they will have during this Sprint. They also have to estimate the top priority user stories, and choose enough of these (already estimated) user stories to complete in line with their own estimated team velocity.

In part B, the dev team will discuss how to develop the more challenging user stories already selected to be developed. Most probably, the dev team will not have enough time to discuss how to develop all the selected user stories, so, the team has to choose the most challenging user stories.

During the Sprint, the dev team has enough time to complete this discussion.

##  Related resources
https://github.com/kukuu/AGILITY/blob/master/manage-sprint-backlog-effectively.md
