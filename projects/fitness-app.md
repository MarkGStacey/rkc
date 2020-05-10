---
thumbnail: '/uploads/physio-virtual-feature.jpg'
title: Fitness app
date: 2020-05-02
categories:
- digital-innovation
project_bg_color: ''
project_fg_color: ''

---
![](/uploads/physio-virtual-feature_small.jpg)
# Coach@Home
In this post I'm introducing a new solution for the fitness world, an ecosystem of mobile and web applications, as well as a Chrome extension - called, collectively "Coach@Home".
For editing, Coach@Home is open to 3rd party editors - such as [StackEdit.IO](https://stackedit.io/) or [Forestry.IO](https://forestry.io/) and others. 
For coaches, physiotherapists, and personal trainers, but firstly for the person trying to improve their well-being and fitness, Coach@Home is present wherever you are - with a  focus on at home training, remote video assessments, and allowing for on the spot customisation based on what equipment you have available, any pain, or time constraints.


## The changing fitness and rehab space - technology, COVID and beyond
Traditionally fitness and rehab have focused on brick and mortar gyms, and in-person assessments - even when assisted by tools such as [Coaches eye](https://www.coachseye.com/) or evaluation tools such as DrGoniometer [Review](https://bjsm-bmj-com.salford.idm.oclc.org/content/51/23/1703).
In a COVID world, home exercise, and online injury assessment and coaching are all seeing massive uptake, as can be seen in Google trends:

#### Google trends
*All graphs are run 2015-04-04 to 2020-04-04, for the global region - and the note at 2016/1/1 indicates a Google change in collection stats. Obviously these results will be skewed for english language countries*

[Home fitness](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=home%20fitness)
![](/uploads/g_home_fitness.png)

Note the annual new years spike in interest in Home Fitness!

[Dumbells](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=dumbells)
![](/uploads/g_dumbells.png)

[Exercise band](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=exercise%20band)
![](/uploads/g_exercise_band.png)

These examples all show that interest in training at home just spiked recently - but other data show that it is the acceleration of a pre-existing trend.

[Online coaching](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=exercise%20band)
![](/uploads/g_online_coaching.png)

[Workout with me](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=Workout%20with%20me)
![](/uploads/g_workoutwithme.png)

#### Youtube

YouTube's interactive [With me](https://youtube.com/trends/articles/with-me-interactive/) infographic highlights a broader movement of online, not just fitness, learning. 

![](/uploads/all-withme.jpg)


Another analysis by YouTube, looking at the searches for "[Workout at home](https://youtube.com/trends/articles/stay-home-workout-at-home/)" shows a massive increase since the lockdown started:

"*Global average daily views of videos with 'workout at home' in the title have increased by over 200% since March 15 compared to their average views for the rest of the year.
Six of the year's top 20 biggest live streams, based on peak concurrent viewership, have been [PE With Joe live streams](https://www.youtube.com/channel/UCAxW1XT0iEJo0TYlRfn6rYQ)*"

![](/uploads/y_15_2.png)



People are working out at home, they can't come to you for advice in person - you need to be able to work with them easily, through video and instructions.



## Ease of use and user experience - focusing on the practitioners as well as the end user
A British medical journal [analysis](https://bjsm.bmj.com/content/51/16/1237) found 150 000 health apps in Europe - of varying quality. That article says""People choose health apps the same way as they choose any apps - quality of design and how easy they are to use".
While the article is bemoaning the success of non-evidence based apps, the counter-point is that evidence based apps have not been designed well!

One leading app brags that it "is the only exercise prescription software designed by physiotherapists" - my contention is that the rehab protocols should be designed by physios - but that the software itself should be designed by UX experts instead!

And so Coach@Home takes a different approach.

### For physios, coaches and other practitioners - creating a plan
Creating an exercise plan doesn't force you to use a rigid template - you write freely in a text area, inserting exercise links easily. These exercises can be from our library (summarised but with a link), or an external link - pasted, or from the APIs of integrated services such as [Pocket](https://getpocket.com/developer/), [Feedly](https://developer.feedly.com/) or [Zotera](https://www.zotero.org/support/dev/web_api/v3/start).
Alternatively, simply add a quick text description, or use our SketchIt addin to draw, before scheduling the exercise.

![](/uploads/cms_ex.png)

### For the end user - working out on your own
Your Coach@Home plan is flexible - sometimes you don't have the equipment, or a movement feels painful and you need to substitute it - or perhaps switch out the entire workout! This is all intuitive and straightforward, and integrates with your own training plan



## Video and messaging
While informal chats (IM and video) are a growing part of fitness practice, as discussed in [The need for speed](https://bjsm.bmj.com/content/early/2020/04/28/bjsports-2019-101707.full), recording some interactions is still a regulatory requirement - and so Coach@Home integrates full integration of IM chats and video calls that can be recorded automatically to case notes. As the assessments are done through the app's video function, these automatically are saved too - saving time for each assessment.


## Chrome extension
Coach@Home has a chrome extension that will remind you to get up and do an activity. Unlike other extensions, Coach@Home pulls a customised list for you of exercises, stretches and mobilisations that you are able to do easily and are suited for any restrictions you have.
For coaches, you can submit your exercises to be included in the library of suggestions - along with a link to your site or program!
As [Dr Ken Powell](https://www-sciencedirect-com.salford.idm.oclc.org/science/article/pii/S209525461930119X) said "Some activity is better than none, and more is better than less"
Exercises can be text, images, or videos such as the ones below:
#### Video examples
`youtube:https://www.youtube.com/watch?v=8IbNN6BBhco`

`youtube:https://www.youtube.com/watch?v=VEzKPTMWng8`

#### Instructive image example 
![](/uploads/l_pic.jpg)

#### Animation example
![](/uploads/l_anim.gif)

# Technology stack
For those who want to dive deeper into how Coach@Home is built, we will have a deep dive into our architecture as a follow up post - for now, here is a diagram.


![](/uploads/SolutionArchitecture.png)