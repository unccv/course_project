# Course Project

There are a large and rapidly growing number of remarkable applications of Computer Vision. From autonomous cars to smart manufacturing to augmented reality, inexpensive and ubiquitous cameras have made computer vision tools and techniques more relevant than ever. Cheap cameras and smart algorithms are empowering engineers to find creative solutions to important problems, provide real value to customers, and create products that simply could not have existed before.

# A Few Interesting Computer Vision Applications

# Mapillary 

![](graphics/github_lander_3.gif)

Mapillary is a service for crowdsourcing map photos and street view. Using simple tools like smartphones or action cameras anyone can collect photos that are combined into street view. Computer vision on the server-side automatically matches and combines photos across time and across users. Photos are processed with privacy preserving blurring using face detection and license plate detection.

Founded: 2015, Raised: $24.5M


# Osmo
![](graphics/github_lander_4.gif)

Osmo is an award-winning game system that will change the way your child interacts with the iPad and iPhone by opening them up to hands-on play.

Founded: 2013, Raised: $26.5M

# Mashgin
![](graphics/github_lander_5.gif)

Mashgin is building an object recognition technology that uses 3D reconstruction, computer vision and deep learning to identify items accurately. They are applying this technology to enable faster checkout in retail. Multiple items can be scanned simultaneously and in any orientation. No bar-codes or RFID are required.


# gumgum
![](graphics/github_lander_6.gif)

Gumgum serves contextual marketing messages in line with content users are actively engaged with, helps marketers and rights holders understand the full media value of their sponsorship investments across broadcast and social media, and analyzes visual content across social media in real time. 

Founded: 2007, Raised: $37M

[PPT with 40 More Interesting Companies](http://www.welchlabs.io/unccv/course_project/interesting_startups_and_businesses.pptx)


# About the Course Project 

As part of this course, students work to build a solution to a **real computer vision problem** as part of a semester-long group project. The technology developed by the companies shown above is intended to show the broad range of possible computer vision applications, and give a little taste for what's happening in the industry right now. Of course, these companies have built some truly remarkable technology that will take longer than a single semester to implement. However, all these companies did start somewhere, likely with a simple demo, or **Minimum Viable Product (MVP)**. 

This is the project. Find a real problem, and create a MVP/Simple demo that provides real value for someone. 


Projects will be broken into and evaluated in 5 stages:

|         |   Stage     | Description                 | Deliverable           | Due Date      | Percent of Course Grade    | 
| ------- | --------------- | --------------------------- | --------------------- | -------------- | ---------   |
|    1    | Topic Selection | What CV problem will you go after?  | 1 paragraph writeup |    |  5%  | 
|    2    | Customer Research | Who are your customers? (Talk to them for extra credit)| 3-5 page writeup summarizing customer research + learning | | 7.5% |
|    3    | Literature Review | What academeic literature and existing code/tools will help solve the problem for your customer? How are other organizations solving similar problems? | 3-5 page writeup | | 7.5% |
|    4    | Technical Planning | How will you solve this problem? What tools will you use? How will you divide the work across your group? | 2 page planning document | | 5% | 
|    6    | Final Pitch + MVP Demo | 10 minute presentation + demo of your technology to your peers  | Public Github repo with well-documented implementation of your solution, final presentation, and deliverables from previous stages| | 15% |


## 1. Topic Selection
There are a huge number of interesting applications of computer vision. Good course project topics will meet a few criteria: 

1. Use image or video data as primary data source
2. Leverage Computer Vision algorithms on top of data
3. Provide value to someone

[Here are 50+ project ideas](https://docs.google.com/spreadsheets/d/1ihH5_DdFyn5M0yv9maoYeqpiFoL4fL5jLYOeC4IgN0s/edit#gid=0)

Group + topic assignment details will be discussed in class. 

**Deliverables:**
A printed one page writeup with including your team name, group member names, grad/undergrad status, a "primary contact" member of your group with phone number and email listed, a one-paragraph writeup of your chosen topic, and a proposed final technology demo. 


## 2. Customer Research
Here we will generally follow the [Lean Startup](https://en.wikipedia.org/wiki/Lean_startup) methodology. A nice summary of the relevant key ideas is Steve Blank's Customer Development Manifesto:

---

**A Startup Is a Temporary Organization Designed to Search for A Repeatable and Scalable Business Model**

1. There Are No Facts Inside Your Building, So Get Outside
2. Pair Customer Development with Agile Development
3. Failure is an Integral Part of the Search
4. Make Continuous Iterations and Pivots
5. No Business Plan Survives First Contact with Customers So Use a Business Model Canvas
6. Design Experiments and Test to Validate Your Hypothesis
7. Agree on Market Type. It Changes Everything
8. Startup Metrics Differ from Those in Existing Companies
9. Fast Decision-Making, Cycle Time, Speed and Tempo
10. It's All About Passion
11. Startup Job Titles Are Very Different from a Large Company's
12. Preserve All Cash Until Needed. Then Spend.
13. Communicate and Share Learning
14. Customer Development Success Begins With Buy-In

---

A nice intro the these ideas can be found in Steve Blank's [The Four Steps to The Epiphany](https://web.stanford.edu/group/e145/cgi-bin/winter/drupal/upload/handouts/Four_Steps.pdf).

**Scope**
Now, this is of course a Computer Vision course, not an Entreprenuership Course. The expectation here is that spending some time conducting customer research will make your engineering work more interesting, relevant, and focused. 


**Deliverables:**
Printed 3-5 page writeup summarizing customer research + learning. Strong writeups will provide well-researched answers to these questions: What problem will your Computer Vision solution solve, and for whom? What value will it provide them? What are their pain points? How big is the potential market? Do other similar solutions exist? Would your business have any competitors? Who are they? How are they doing? How are potential customers dealing with these issues now? How much would customer be willing to pay for your product? Are your customers individuals or businesses? Be sure to cite the sources you reference in your research. 


**Extra Credit**
There's nothing quite like talking to **real potential customers**. Earn 0.5 pts on your final grade for each potential customer interview you conduct, for up to 3 interviews. Interviews cannot be with people you knew before starting the class - you have to find your own leads. Interviews may be conducted in person or over the phone. Interviews should focus on the customer's problems and how your particular computer vision solution could help them. Record your interview and include a transcript of your interview questions and your interviewees responses as an appendix to your writeup. 


## 3. Literature Review
Part 2 was all about people, Part 3 is all about technology. A thorough literature review can save weeks of wasted time implementing dead-end solutions or re-doing work that others have already done.

### **Deliverables**
Printed 3-5 page writeup, citing 10+ sources. Writeup sections should include: 

###Academic Literature 
This section should read like the introduction to an [academic paper](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf). What academic work is relevant to your project topic? How do these approaches inform yours? What are the strenghts, weaknesses, and history of these techniques? 


###Publically Available Tools and Code
What open source code and tools are available that are relevant to your topic? How long have they been around? How active are the communities around these tools?


###Industry Solutions
What companies are solving similar problems to yours? It can be tough to tell exactly how proprietary solutions work, but what can you find on the internet? Has anyone reverse engineered these products? If you have access to the product, what can you learn from using it? Are there available talks, documentation, or other resources from their engineering teams?


## 4. Technical Planning
What will a successful demo look like? What are the 3-6 milestones to a completed demo? How will you break up the work accross your team members? What programming languagues are you planning to develop your solution in? What open source tools will you use (opencv, tensorflow). What's your technical plan B if you run into issues?


**Deliverables**
Printed 2 page planning document. 


## 5. Final Pitch + MVP Demo


**Deliverables**
10 minute presentation + demo of your technology to your peers. Public Github repo containing well-documented implementation of your solution, final presentation, and deliverables from previous stages.


# Industry Partnerships

![](graphics/old_charlotte_map.png)

Where possible, group projects will involve working directly with a local business or startup. Industry partners will select computer vision "side problems" or ideas that they find interesting but don't have time to explore, but could be relevant to thier business one day. Ideally, industry partners will meet with student groups 2-3 times throughout the semester to provide feedback + direction. When possible, partners may provide data for students to use. 

## Benefits to Industry Partners
- Groups may come up with interesting approaches that may be worth pursuing further
- Partners may identify well-qaulified potential interns or hires

## Benefits to Students
- Get work on a real problem
- A little guidance along the way
- Exposure to intersting places to potentially work
- A strong resume booster

## Expectations

Due to time constraints - this project is only one piece of one course - it's important to keep project expectations reasonable. These partnerships are far less extensive than, for example, industry-sponsored graduate level research. The hoped for outcomes here are outlined in the benefits above. Finally, by their very nature, many of these topics are relatively unexplored, meaning that good solutions may not be possible, especially in the course of a semester. This is what make entrepreneurship + research exciting, but also risky. One of the reasons this project is a semester long it to give you the time to pivot or change your scope if your first appraoch doesn't pan out. 















