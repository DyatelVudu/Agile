# Agile 

Just open index.html and enjoy:)



Hi, i’m Ilya and  today we are going to talk about Agile and firstly you need to know that Agile is a term used to describe approaches to software development emphasizing incremental delivery, collaboration and continual learning.
Let’s talk about Agile software development from the perspective of the Product Owner.
Here’s Pat. She’s a product owner. She has a product vision that’s she’s really passionate about. She doesn’t know the details of what her product is going to do, but she knows why we’re building the product, what problem it is going to solve, and for whom.
Here are the stakeholders. The people who are going to use, support, or in any way be affected by the system being developed. 
The stakeholder needs are expressed as user stories. The stakeholders have lots of ideas, Pat helps them divide these into fairly distinct user stories.
Now, somebody has to BUILD the system. Here they are, the development team.
Since this is an agile team, they don’t save up for a big bang release at the end. Instead, they release early and often. 
They usually release 4-6 stories per week, so that is their capacity. It is easy to measure, just count the number of stories released per week. Some stories are big, so they count as two, some are small and count as a half. 
In order to maintain this pace, and not get bogged down by manual regression testing, the team invests heavily in automated testing and continuous integration. Every feature has automated acceptance tests, and most of the code has automated unit tests.
The problem is, here are bunch of stakeholders asking for all kinds of stuff, and they sure aren’t going to be limited to 4-6 ideas per week.
So what happens if we try to do everything they ask for? We’ll get overflow. 
Suppose the team starts working on 10 new stories per week. If the input is 10, and the output is 4-6, the team will get overloaded with work. That will cause multitasking, demotivation, and ultimately lower output and lower quality. It’s a lose-lose proposition.
The Scrum and XP way of avoiding this problem is called “yesterday’s weather”. The team says “well, the past few weeks we’ve finished 4-6 features per week. So which 4-6 features shall we build this week?”.
The Kanban way is to limit work-in-progress. Suppose the team decides that 5 is the optimal number of stories to be working on simultaneously, just enough to keep everyone busy without causing overload.
Both of these approaches work fine. And they will cause a queue to form in front of the team, which in Scrum is called a Product Backlog.
This queue needs to be managed. If stakeholders keep asking for 10 new stories every week, and the teams deliver 4-6, the queue will keep getting longer and longer. Before you know it, you have a 6 month long wish list in the backlog.
There is only one way to stop the queue from going out of the control. That is the word No. 
It is the most important word for a product owner. Saying yes to a new feature request is easy. The most important job for a product owner is to decide what NOT to build, and take the consequences of that decision.
The product owner decides what goes in, and what goes out. The product owner also decides the sequencing – what do we build now, what do we build later? This is a hard job, and needs to be done in collaboration with the team and stakeholders.
To be able prioritize, the product owner must have some idea of the value of each story, as well as the size. Some stories are critically important, others are really just bonus features. Some stories take just a few hours to build, others take months.
Guess what the correlation is between story value and story size? That’s right – None! Bigger doesn’t mean better.
But how does she know the value of a story? How does she know the size? Well, here’s the bad news – she doesn’t. It’s a guessing game.
And it’s game that everyone is involved in! Pat continuously talks to stakeholders to find out what they value. She continuously talks to the team to find out what they think is big or small, in terms of implementation effort.
At the beginning of a new project our guesses will inevitably suck. But that’s OK, the biggest value is really in the conversations rather than in the actually numbers. And every time the team delivers something to real users, we learn something and get better at guessing both value and size.
Prioritization is not enough though. In order to deliver early and often, we need to break the stories down into bite-sized pieces, preferably just a few days of work per story. We want this nice funnel shape, with small, clear stories at the front and more vague stories at the back. By doing this break-down in a just-in-time fashion, we can take advantage of our latest insights about the product and the user needs.
All this stuff I’ve been talking about – estimating the value and size of stories, prioritizing, splitting – all that is usually called “backlog grooming”. The whole team is usually there, and sometimes a few stakeholders as well. Communication! Product Ownership is really all about communication. When I ask experienced product owners what it takes to succeed, they usually emphasize passion and communication.
There are number of tradeoffs that need to be made by Pat and the team. Let’s look at a few.
First of all, there’s the tradeoff between different types of value. Early on in a project, uncertainty and risk is our enemy.
There’s business risk: are we building the right thing? There’s social risk: can these people build it? There’s technical risk – will it work on the platform that we want to run it on? Will it scale? And there’s cost and schedule risk. Can we finish the product in a reasonable amount of time, for a reasonable amount of money?
From a customer value perspective, the curve looks like this in the beginning.
As uncertainty is reduced, we gradually focus more and more on customer value. We know what we’re going to build and how, so just do it! And by doing the highest-value stories first, we get this nice steep value curve.
So when I talk about Value here, I mean Knowledge value + Customer value. And we need to find a tradeoff between these two.
Another tradeoff is short term vs long term thinking. What should we build next? Should we do that urgent bug fix, or build that awesome new feature that will blow the users away, or do that difficult platform upgrade that will enable faster development in the future? We need to continuously balance between reactive work and proactive work.
This is related to another tradeoff. Should we focus on “building the right thing”, “building the thing right”, “building it fast”? Ideally we want all three, but it’s hard to find the balance. 
Suppose we are here – trying to building the perfect product. If we spend too much time to trying to get it perfect, we may miss the market window or run into cash-flow problems.
Or suppose we are here, rushing to turn a prototype into a usable product. Great for the short term, perhaps, but in the long term we’ll be drowning in technical debt and our velocity will approach zero.
Or suppose we are here, building a beautiful cathedral in record time. Except that the users didn’t need a cathedral, they needed a camper van.
There is a healthy tension here between the Scrum roles. POs tend to focus on building the right thing. Teams tend to focus on building the thing right. And Scrum masters, or agile coaches, tend to focus on shortening the feedback loop.
Speed is worth emphasizing. Because a short feedback loop will accelerate learning, so you will more quickly learn what the right thing is, and how to build it right.
Finally, there is the tradeoff between new product development and old product improvement. A product is never really “finished” there’s always maintenance and improvements to be done. So when a team starts developing a new product, what happens to their last one? Handing off a product from one team to another is expensive and risky. A more common scenario is that the team continues maintaining the old product while developing the new one. So it’s not really a product backlog, it’s more like a team backlog – a list of stuff that the product owner wants this team to build, and it can be a mix of stuff for different products. And the product owner needs to continuously make tradeoffs between these. Once in a while, a stakeholder will call Pat and say “Hey, when will my stuff be done?” or “How much of my stuff will be done by christmas?”. As PO, Pat is responsible for expectations management! Or, more importantly, realistic expectations management.
Look at the burn up chart and draw an optimistic and pessimistic trend line.The gap between these lines is of course related to how wavy and unpredictable your velocity is.
Suppose the stakeholders ask Pat “When will all of THIS stuff be done?”. “When will we be here?”. That’s a fixed-scope, variable time question. Pat uses the two trend lines to answer. “Most likely sometime between April and mid-May”.
Suppose the stakeholders ask Pat “How much will be done by christmas?”. That’s a fixed time, variable scope question.
The trend lines tell us “We’ll most likely finish all these, some of these, and none of these.”
Suppose the stakeholders say “Can we THESE features by christmas”. That’s a fixed time, fixed scope question. Looking at trend lines, Pat says “Nope, sorry, it ain’t gonna happen”, followed by “here’s how much we can get done by christmas” or “here’s how much more time we need”. It’s generally better to reduce scope than to extend time, because if reduce scope first, we still have the option to extend the time later and add the rest of the stories.
The calculations are simple to do, so Pat updates the forecast every week.
The important thing here is that Pat is using empirical data to make the forecast, rather than wishful thinking. This is a very honest way of communicating with stakeholders, and they usually appreciate that a lot. If your organization doesn’t like truth and honesty, it won’t like agile.
 What if we have a larger project with multiple teams? Instead of one team with 5 people here, we might have 3 teams. And we might have several product owners, each with their own backlog for a different part of the product.
Overall, the model is really the same. We still need capacity management, we still need stakeholder communication, we still need product owners who can say No, we still need backlog grooming. Velocity is the sum of all output, and can be used for forecasting.
In a multi team scenario, however, the POs have an important additional responsibility – to talk to each other! We should organize the teams and backlogs to minimize dependencies. In large projects, this usually calls for some kind of Chief Product Owner role to keep the product owners synchronized.
OK, that’s it!
