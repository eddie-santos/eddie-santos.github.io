---
layout: post
title: Giro 2018: Montevergine & Gran Sasso
---

This weekend featured two summit finishes, up the Montevergine and Campo Imperatore (Gran Sasso) on Saturday and Sunday, respectively. As I expected, the Montevergine proved to be a non-factor in the battle for the overall, save for the young Ecuadorian Movistar rider, Ricard Carapaz jumping out of the pack late in climb to take 7 seconds over his competitors. At 5%, Montevergine is more of a power climb, where the big riders aren't as hampered by their larger weight if they can apply more apply, and moreover aerodynamics becoming a non-neglibible factor provided the climbing speed is high enough, which it turned out to be on a relatively easy gradient.

Today's climb up Campo Imperatore in the Gran Sasso range proved to be more exciting, with a ever increasing gradient towards the line. Simon Yates further demonstrated his excellent form by taking the victory ahead of Thibaut Pinot and teammate Esteban Chaves, to further gain time on pre-race favorites Tom Dumoulin (12") and Chris Froome (1'07"), the latter of whom who got dropped withover 2 km to go. At this point, perhaps the more interesting plot-line regarding Froome is if/when Team Sky will pull the plug on their Giro ambitions, and allow Froome time to rest and recover ahead of the Tour de France, as it appears even a podium spot at this point is out of the question.

Perhaps intriguing is the level of performance we have seen out of the traditional group of climbers, Yates, Pinot, Chavez, and Pozzovivo, all of whom put in relatively strong performances in the opening time trial and have maintained form through the first 9 stages. Yates maintains he believes he'll need minutes over Dumoulin to feel safe with his lead before the flat 34.2 km time trial on stage 16, and it is fairly likely he or another of the aforementioned climbers will be able to manage to pull more time on Dumoulin on Zoncolan, given the sharp profile of the climb.

What does this all mean? This is going to be a wide open Giro, and the winner will have certainly earned it. With that said, let's take a look at the Strava data from this weekend's two summit finishes, as well as estimate the performance of key riders on the climbs. For reference, an over of the climbs is given in [one of my entries](https://eddie-santos.github.io/giro-climbs/) from last week.

### Montevergine

Though long at 14.8 km, Montevergine proved not to be steep enough for the leaders to separate themselves, with a pack finish amongst the favorites. With that said, let's still take a look to see how time of completion maps to average power-to-mass over the climb to get an idea of their performances. As described in my [Giro climb summary entry](https://eddie-santos.github.io/giro-climbs/), power-to-mass for a rider up Montevergine can be described by their completion time given the equation

$$ \<power\>/mass = A/time + B$$

The fit to the data is remarkably good, and so now the fun begins. We know that the group of favorites started the segment at more or less the same time, though differences in placement at the beginning and end of the segment can lead to modulations of a few seconds, in regards to Strava segment times. The equation obtained for estimating power-to-mass from time on the climb from fitting to the data, is given by:

*\<power\>/mass* = (14888 W/kg\*s)/(*time in seconds*) + (1.05431 W/kg)

Combining this equation Strava times and the official results on the stage, we can infer the following results. Note that the rider masses were obtained from (in order) their Strava profiles, procyclingstats.com, or via Google searching.

| Place 	| Name               	| Stage time 	| Strava Etna time 	| Est. Etna time 	| Est. \<p\>/m (W/kg) 	| mass (kg) 	| Est. \<p\> (W)|
|-------	|--------------------	|------------	|------------------	|----------------	|-------------------	|---------------|--------------	|
| 2     	| Simon Yates        	| 4:16:11    	|                  	| 34:25          	| 6.06              	| 59.65   	    | 360          	|
| 3     	| Thibaut Pinot      	| +26\"       	| 34:51            	|                	| 5.97              	| 65      	    | 388          	|
| 4     	| George Bennett     	| s.t.       	|                  	| 34:52          	| 5.97              	| 58      	    | 346          	|
| 5     	| Domenico Pozzivivo 	| s.t.       	|                  	| 34:52          	| 5.97              	| 53      	    | 316          	|
| 6     	| Miguel Angel Lopez 	| s.t.       	|                  	| 34:53          	| 5.96              	| 65      	    | 388          	|
| 8     	| Tom Dumoulin       	| s.t.       	|                  	| 34:53          	| 5.96              	| 71      	    | 423          	|
| 9     	| Fabio Aru          	| s.t.       	|                  	| 34:54          	| 5.96              	| 66      	    | 393          	|
| 10    	| Chris Froome       	| s.t.       	|                  	| 34:54          	| 5.96              	| 68      	    | 405          	|
| 12    	| Ben O'Connor       	| +43\"       	| 35:00            	| 35:06          	| 5.92              	| 66      	    | 391          	|
| 16    	| Michael Woods      	| +57\"       	| 35:20            	|                	| 5.87              	| 63      	    | 370          	|
| 21    	| Rohan Dennis       	| +1\'04\"     	|                  	| 35:27          	| 5.85              	| 71      	    | 415          	|

#### Discussion

Overall, these results look pretty reasonable. Yates had an incredible performance of 6.06 W/kg, which is consistent with a clean performance of this caliber of athlete. His estimated raw power of 360 W, based on a self described mass of 131.5 lbs, is pretty good considering his diminuitive stature. The others finishing in the pack come in about 5.97 W/kg, which feels about right, considering that the two main favorites, Dumoulin and Froome, have appeared to in peak shape this Spring. Dumoulin's mass is a bit harder to find, but I'd guess he's about 71 kg, putting his power output at 423 W, and Froome at a noted race weight of 68 Kg, at 405 W. Froome's performance is fairly consistent with other power outputs we've seen from him: [414 W on the final climb](http://www.cyclingnews.com/news/team-sky-reveal-froomes-tour-de-france-data-from-stage-10/) of Stage 10 of the 2015 Tour de France, and expectedly lower given that he doesn't appear to be in top form. More than anything, Froome appears to be missing that top end speed used to attack rivals, and he's just using his massive engine to hang on right now. This makes sense given his plan to try to race into form during the final week of the Giro, and try to hold form into the Tour de France.

Of these riders, only two (O'Connor & Woods) recorded their power performances on Strava, and they're a bit lower than those given here, however I have reason to suspect it's a problem with their power meters. For example, analyzing Wood's effort on the segment reveals that there was as 30" period at the end of the climb that he didn't record any cadence or power, which is more or less impossible when going uphill. It was likely a malfunction with his Vector pedals, or perhaps well known helicopter interference. If his 335W could be believed, it would correspend to a 5.3 W/kg performance, which would put him into the strong amateur racer bucket, of which he's way beyond.

Thus far, Yates is looking like a serious challenger. He's really come into this race in great form, and this may be when we see him ascend from fringe contender to favorite in future races. It would be surprising if he doesn't manage to put time into Dumoulin and Froome during the coming climbs, notably Zoncolan, for which raw power means far less than power-to-mass, though he'll have to hope to put in enough to fend them off in the time trial.

Stay tuned! This weekend holds two great climbing stages, and I'll post analysis shortly after the conclusion of each stage. 