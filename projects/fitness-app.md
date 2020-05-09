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
For coaches, physiotherapists, and personal trainers, but firstly for the person trying to improve their well-being and fitness, Coach@Home is present wherever you are - with a  focus on at home training, remote video assessments, and allowing for customisation based on what equipment you have available.

A comprehensive review of potential [competitors]('/competitors') and parallel software products, as well as evaluating the size of the potential market has guided the design of an innovative and unparalleled solution.

## The changing fitness and rehab space - technology, COVID and beyond
Traditionally fitness as well as rehab work has focused on brick and mortar gyms, and in-person assessments (for rehab and coaching). Often assisted by tools such as [Coaches eye](https://www.coachseye.com/) for coaching or video evaluation tools such as DrGoniometer [Review](https://bjsm-bmj-com.salford.idm.oclc.org/content/51/23/1703) for movement assessment, these are all still in-person, high personal contact areas, and so are the gyms.
In a post COVID world, home exercise, injury assessment and coaching are all going to see massive uptake. 
This trend is immediately apparent by looking at Google trends for selected terms:

*All graphs are run 2015-04-04 to 2020-04-04, for the global region - and the note at 2016/1/1 indicates a Google change in collection stats. Obviously these results will be skewed for english language countries*

[Home fitness](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=home%20fitness)
![](/uploads/g_home_fitness.png)

Note the new years spike in interest in Home Fitness!

[Dumbells](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=dumbells)
![](/uploads/g_dumbells.png)

[Exercise band](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=exercise%20band)
![](/uploads/g_exercise_band.png)

These examples all show that interest in training at home just spiked recently - but other data also show that is the acceleration of a pre-existing trend, rather than a blip to go away on discovery of a vaccine.

[Online coaching](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=exercise%20band)
![](/uploads/g_online_coaching.png)

[Workout with me](https://trends.google.com/trends/explore?date=2015-04-04%202020-04-04&q=Workout%20with%20me)
![](/uploads/g_workoutwithme.png)

YouTube's interactive [With me](https://youtube.com/trends/articles/with-me-interactive/) infographic highlights a broader movement of online, not just fitness, learning. 

An example of the excellent charts linked in that article:
![](/uploads/all-withme.jpg)

Staying with YouTube

Another analysis by YouTube, looking at the searches for "[Workout at home](https://youtube.com/trends/articles/stay-home-workout-at-home/)":
"*Global average daily views of videos with 'workout at home' in the title have increased by over 200% since March 15 compared to their average views for the rest of the year.
Six of the year's top 20 biggest live streams, based on peak concurrent viewership, have been PE With Joe live streams*"


## Ease of use and user experience - focusing on the practitioners as well as the end user
A British medical journal analysis of fitness, health and medical apps found 150 000 of them in Europe - of varying quality. One quote in that article says ""People choose health apps the same way as they choose any apps-quality of design and how easy they are to use," explains Satish Misra, cardiology fellow at the Johns Hopkins Hospital in Baltimore and managing editor at app review site iMedicalApps."
While the article is bemoaning the success of non-evidence based apps, the counter-point is that evidence based apps have not been designed well!

One leading app brags that it "is the only exercise prescription software designed by physiotherapists" - my contention is that the rehab protocols should be designed by physios - but that the software itself should be designed by UX experts instead!

And so Coach@Home takes a different approach.

### For physios, coaches and other practitioners
When creating an exercise plan, we don't force you to use a rigid template, with forms and pickers for exercises.
Instead, you are given a text area based on markdown, but with the ability to insert controls that add in exercises. These exercises can be from our library, or from your own copy of our library format - which will be neatly divided into a thumbnail and title to be displayed inline, and then a link to a full page broken up into regressions, alternatives, detailed explanations. However, exercises can be added as links - pasted, or from the APIs of services such as [Pocket](https://getpocket.com/developer/), [Feedly](https://developer.feedly.com/) or [Zotera](https://www.zotero.org/support/dev/web_api/v3/start) that you can link to your account. You can also simply add a text description, or use our SketchIt addin to draw something you've done for that particular client. Any of these can then be clicked on and assigned a schedule (sets/reps/number of times a week). This flexibility lets you give your clients the prescriptions they need without holding you back fussing with a tool to make it do what you need!

### For the end user
Our software does the magic for you - it takes the items from the plan you were given, loads up a database, and let's you log 
When you receive a plan, it is loaded 