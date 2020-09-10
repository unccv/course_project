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

As part of this course, students work to build a solution to a **real computer vision problem** as part of a semester-long group project. The technology developed by the companies shown above is intended to show the broad range of possible computer vision applications, and give a little taste for what's happening in the industry right now. Of course, these companies have built some truly remarkable technology that will take longer than a single semester to implement. However, all these companies did start somewhere, likeley with a **Minimum Viable Product (MVP)**. 

This is the project. Find a real problem, and create an MVP that provides real value for someone. 


Projects will be broken into and evaluated in 4 stages:

|         |   Stage     | Description                 | Deliverable           | Due Date      | Percent of Course Grade    | 
| ------- | --------------- | --------------------------- | --------------------- | -------------- | ---------   |
|    1    | Topic Selection | What CV problem will you go after?  | 1 page writeup | 9/21   |  1%  | 
|    2    | Research + Data Collection | Who are your customers? (Talk to them for extra credit)| Writeup summarizing  research, and visualizing dataset | 10/19 | 10% |
|    3    | Modeling | Build and train your models. Experiment. | Well-documented, visually pleasing, and clear jupyter notebook presenting results. | 11/9| 15% |
|    4    | Presentation + Storytelling | Craft your story. Create videos + visuals. Document your project. | Public Github repo with well-documented implementation of your solution, final presentation, and deliverables from previous stages | 12/16| 14% | 


## Meetings 
Throughout the course of the semester, your team will meet individually with their supervising TA and Instructor to review your progress several times during the semester. One of the team members from each team has to schedule meetings via Calendly (a link will be provided). The team members receive credits for each stage only after individual team meetings. 

## 1. Topic Selection
There are a wide range of interesting applications in the domain of computer vision. Good course project topics will have to meet few mandatory criteria: 

1. Use image or video data as primary data source
2. Leverage Computer Vision algorithms on top of data
3. Provide value to someone, solve a real problem. 


### Deliverables
A printed one page proposal submission + resume(s) of individual team members on Canvas. If you already have team members in mind, you may submit a single proposal as a group. Submissions should inlcude your name(s), grad/undergrad status, phone number and email, a writeup of your topic proposal, a proposed final technology demo, and your resume(s). If you would like to collaborate with an industry partner (listed on Canvas), include the partner you would like to collaborate with, and tailor your proposal to your partner. Keep in mind that your partner may wish to change your topic. Given more demand than industry partners, groups will be selected for partnerships based on the quality of proposal. 

### Final Team Creation
The final decision on the team creation is with the professor and TAs. Ideally, each group will be composed of 3-4 graduate students and 1 undergraduate student. We will do our best to put you with your requested team members, and assign you to the topic of your interest. 


## 2. Research + Data Collection

### 2.1 Research

Your research should be spread accross a few key areas. Depending on your project, your research may be more "business focused" or more "academically" focused. You should address at least 10 of the questions below, and must choose and review 3 academic papers. 

#### 2.1.1 Business/Customers
- What problem will your Computer Vision solution solve, and for whom? 
- What value will it provide them? What are their pain points? 
- How big is the potential market? 
- Do other similar solutions exist? 
- Would your business have any competitors? Who are they? How are they doing? 
- How are potential customers dealing with these issues now? 
- How much would customer be willing to pay for your product? 
- Are your customers individuals or businesses? Be sure to cite the sources you reference in your research. 

#### 2.1.2 Academic Literature Review
A thorough literature review can save weeks of wasted time implementing dead-end solutions or re-doing work that others have already done. You should pick 3 academic papers (we can help you with this, if needed), and do a "deep-dive" on these publications. 

- What academic work is relevant to your project topic? Pick 3 papers, ask us for help if you need it.
- What makes these papers important/relevant? 
- What are their results and how did they achieve these results?
- What's different/unique about these approaches?

#### 2.1.3 Open Source 
- What open source code is available that are relevant to your topic? 
- How active are the communities around this code? 
- What data is available for testing and/or training algorithms? 
- Is labeled data available? How much? How is the data licensed? Is it under copyright protection?

### 2.1.4 Industry Solutions
- What companies are solving similar problems to yours? 
- It can be tough to tell exactly how proprietary solutions work, but what can you find on the internet? 
- Has anyone reverse engineered these products?
- If you have access to the product, what can you learn from using it? 
- Are there available talks, documentation, or other resources from their engineering teams?

### 2.2 Data Collection
Your project will involve either collecting your own data or using publically available data. Getting your dataset nailed down early is critical to success. For most problems, you will need some type of labels to go with your images or videos. If you're creating your own dataset, you'll likely need to do your own labeling. There are great open source tools to help you with this like [labelme](https://github.com/wkentaro/labelme). 


### Deliverables:
Printed writeup addressing research questions above, and a jupyter notebook visualizing and summarizing your dataset. 

## 3. Modeling
This is the fun part! Build your models, conduct experiments, look at the literature you reviewed for ideas. 

### Deliverables
Well-documented, visually pleasing, and clear jupyter notebook presenting results.



## 4. Final Pitch + Demo


### Deliverables
A video recording of the presentation + demo of your technology. Briefly tell the story of the problem you set out to solve, what you learned about the problem in each of the previous stages, and demo the solution that you have developed. In addition to the presentation, final deliverables include a public Github repo containing a well-documented, visually pleasing, and clear implementation of your solution, final presentation, and deliverables from previous stages. Here are the guidelines for the video recording:
- Every member of the project records a video explaining the part he/she contributed to the project.
- One of the team members stitches all the videos and send it to us.
- The final stitched video should have a proper flow of the entire project.
- Here are some tools that are available online for stitiching the video:

  - For Windows OS:

   - Stitching can be done using the default 'Photos' app.
   - More details are in the following link:
    https://www.msftnext.com/merge-videos-windows-10-photos-app/
   - Students can download the following free application that is available in the Microsoft store:
    https://www.microsoft.com/en-us/p/simple-video-trim-merge/9pfdgvnpd3zc?activetab=pivot:overviewtab
    
  - For MAC OS:

   - Students can use the QuickTime player and stitch videos:
    https://help.vyond.com/hc/en-us/articles/115005667026-How-do-I-merge-two-or-more-videos-in-QuickTime-

- Students can use any other video editing tool they prefer to.

## Guidelines for Groups with Industry and Community Partners
Some groups will work with industry and community partners on projects. Clearly and consistently communicating with your partners is key to a successful project. After your initial kick-off meeting with your partners, you are expected to send short update emails to your partners every 2-3 weeks for the duration of your project. This will help keep your work aligned with your partners, and help break up the project into "sprints". Email updates should include: 

1. What you have accomplished since the last update. Specific details about learnings/ideas/approaches/things that are or are not working. Share images/vidoes or other intermediate results if you have them. 
2. What you are planning to accomplish before the next update. 
3. Any questions you have for your partners, and in the event that you need to meet/call with your partner in the next 2 weeks, a few proposed meeting times. 

Please copy your TAs + instructor on industry partner update emails. Partners are expected to meet with groups three times per semetester, including final presentation, but may meet more frequently if time permits. 


## Fall 2019 Projects

| Group Number | Project Name |
|--------------|--------------|
| 1 | [RNA Classifier](https://github.com/rishi-koushal/Ribonucleic-Acid-Vision-Classifier) |
| 2 | [Lucid Drones](https://github.com/yuryi-malakhau/facadeSegmentation) |
| 3 | [2U Laundry](https://github.com/thaotrongtran/GRINN) |
| 4 | [Vishion](https://github.com/amitdshetty/Color_Variation_Detection_Project) |
| 5 | [Crowd Emotion Recognition](https://github.com/PranotiDesai/Crowd-Emotion-Recognition) |
| 6 | [UI Wireframe to Prototype](https://github.com/sameershanbhag/UIWireframes2Mockup) |
| 7 | [ Attribution of private Images to GANS](https://github.com/bhanu566/CV_GAN) |
| 8 | [Hand Signal recognition for Drones](https://github.com/AishwaryaParaspatki/Hand-Gesture-Recognition-for-Drones) |
| 9 | [Drone Stabilization](https://github.com/Divya27mb/Drone-Stabilization) |
| 10 | [Good Roads](https://github.com/mattwells19/USRoadSignRecognition) |
| 11 | [Lowes](https://github.com/rnair3/Computer-Vision) |
| 12 | [Distracted Driver Detection](https://github.com/hdetroja/Distracted-Driver-Detection) |
| 13 | [Traffic Signal Prioritizer](https://github.com/storm-king/TrafficSignalPrioritizer) |
| 14 | [Combat Finder - Find Fight Scenario in Real Time](https://github.com/nomdebrew/JeastyPy) |




## Fall 2018 Projects

| Group Number | Project Name |
|--------------|--------------|
| 1 | [Video Stabilization](https://github.com/Thorsten007/unccv_image_stitching) |
| 2 | [Food Identifier](https://github.com/sanchi36/project) |
| 3 | [Autonomous Boat Project](https://github.com/imishra23663/PoseEstimation/blob/master/README.md) |
| 4 | [Facial Emotion Recognition for Retail Analytics](https://github.com/Tabish06/FERRA) |
| 5 | [Traffic Sign Recognition](https://github.com/whytheevanssoftware/4152Project) |
| 6 | [Signature Verification](https://github.com/jadhavnikhil78/Signature-Verification) |
| 8 | [Lung Cancer Detection](https://github.com/quaiquai/LCD-radIO-unccv) |
| 9 | [DeepFect](https://github.com/adhishthite/uncc-cv-vitro/) |
| 10 | [Vishion](https://github.com/wilsnat/unccv_course_project/) |
| 11 | [Lucid Drone](https://github.com/narendravankayala/lucid.git) |
| 12 | [Traffic Sign Classification](https://github.com/uncctrafficsigndetection) |
| 13 | [Skin Cancer Detection](https://github.com/mmehedin/derma_diagnosis) |
| 14 | [JeastyPy](https://github.com/nomdebrew/JeastyPy) |
| 15 | [US Speed Limit Sign](https://github.com/rguptha95/Classifying-Speed-Limits) |
| 16 | [Face Recognition based Attendance System](https://github.com/adu81020799/Face-Recognition-based-Attendance-System) |
| 18 | [Audience Polling](https://github.com/AddisonCurtis/computer-vision-project) |




















