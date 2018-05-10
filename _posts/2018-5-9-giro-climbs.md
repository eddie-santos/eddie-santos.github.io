---
layout: post
title: The summit finishes of the Giro
---

As noted in my last entry, this year's Giro d'Italia offers no less than 7 stages ending with substantial climbs. Summit finishes are great as they offer a unique opportunity to glimpse into the capabilities of the overall contenders, as if you're contending, you pretty much have to go full gas uphill! 

In today's entry, I'll introduce the summit finishes as well as show data from actual riders with power meters (and their associated masses) for these climbs. I also provide the equations for each climb to determine a riders average power-to-mass ratio for a climb given their time to finish, and vice-versa, this way we can analyze a rider's performance after each of these climbs is completed. 

As noted in my last entry, the requisite equation between these power-to-mass and time is given by *time* = *A*/(*\<power\>*/*mass*-*B*), where *time* is given in seconds, *\<power\>* denotes average power over the climb in Watts, and *mass* is the mass of the rider in kilograms. *A* and *B* are coefficients determined from Strava data for each climb, only from riders who have used a power meter and their associated mass. Note that the model implicitly takes into equipment mass, so the mass here is strictly the mass of the rider. 

This equation can also be inverted to give *\<power\>/mass* = *A*/*time*+*B*, which is probably of more interest given that we'll know or can infer climbing times for riders.

| **stage** | **climb**            | **A**    | **B**    |
| :--------:  | ----------------------- | :------------: | :------------: |
| 6     | Etna             | n/a | n/a |
| 8     | Montevergine     | 14047 | -1.1574 |
| 9     | Campo Imperatore | 9034.7 | -1.3181 |
| 14    | Monte Zoncolan   | 14539 | -0.5088 |
| 18    | Prato Nevoso     | 12117 | -0.4951 |
| 19    | Monte Jafferau   | 10069 | -1.1169 |
| 20    | Cervinia         | 14977 | -0.5875 |

As an example of how this works in practice, let's say Tom Dumoulin completes Zoncolan in a time of 38:30, which equates to 2,310 seconds. Using the coefficients above, his estimated *\<power\>/mass* for the climb would be 14977/2310 + (-0.5875) = 5.896 W/kg. At an estimated race weight of 71 kg, we could estimate his power about to be 419 W over that 38:30. This applies for any rider of any mass, if we know their time on the climb.

### Stage 6: Etna
#### [Strava segment](https://www.strava.com/segments/17456582): 19.2 km, 7% average gradient, 1,254 m elevation gain


The Giro this years ascends Etna from the South, instead of the more popular route from the East, thus making it difficult to provide much of an analysis since currently there are only 7 riders who have completed this segment! Still, the climb looks intimidating, as it's a roughly 12 mile slog up an average gradient of 7%. My guess is that this will slightly favor the climbers, particularly the ramp of 14% at roughly 5km to go, which we might see a few attacks. The climb gets ever so slightly at the top, so expect a group finish if there's not much fireworks on the lower-to-mid slops. 

![stage-6-etna]({{ "/images/giro2018/profiles/stage-6-etna.jpg" | absolute_url }})

### Stage 8: Montevergine
#### [Strava segment](https://www.strava.com/segments/8296241): 14.8 km, 5% average gradient, 762 m elevation gain

At an average and fairly consistent gradient of 5%, except the Montevergine to end in a bunch finish. A few contenders may slip due to tired legs, but the easier gradient allows for aerodynamics to come more into play, making it easier for the bigger guys to stay in contention.

![stage-8-montevergine]({{ "/images/giro2018/profiles/stage-8-montevergine.jpg" | absolute_url }})

![curve-montevergine]({{ "/images/giro2018/curves/montevergine.png" | absolute_url }})

### Stage 9: Campo Imperatore
#### [Strava segment](https://www.strava.com/segments/1607020): 7.7 km, 6% average gradient, 478 m elevation gain

![stage-9-gran-sasso]({{ "/images/giro2018/profiles/stage-9-gran-sasso.jpg" | absolute_url }})

![curve-campo-imperatore]({{ "/images/giro2018/curves/campo-imperatore.png" | absolute_url }})


### Stage 14: Monte Zoncolan
#### [Strava segment](https://www.strava.com/segments/657601): 7.5 km, 13% average gradient, 1,018 m elevation gain

![stage-14-zoncolan]({{ "/images/giro2018/profiles/stage-14-zoncolan.jpg" | absolute_url }})

![curve-monte-zoncolan]({{ "/images/giro2018/curves/monte-zoncolan.png" | absolute_url }})


### Stage 18: Prato Nevoso
#### [Strava segment](https://www.strava.com/segments/1747235): 10.6 km, 8% average gradient, 805 m elevation gain

![stage-18-prato-nevoso]({{ "/images/giro2018/profiles/stage-18-prato-nevoso.jpg" | absolute_url }})

![curve-prato-nevoso]({{ "/images/giro2018/curves/prato-nevoso.png" | absolute_url }})

### Stage 19: Monte Jafferau
#### [Strava segment](https://www.strava.com/segments/4106767): 6.7 km, 9% average gradient, 610 m elevation gain

![stage-19-jaggerau]({{ "/images/giro2018/profiles/stage-19-jafferau.jpg" | absolute_url }})

![curve-monte-jafferau]({{ "/images/giro2018/curves/jafferau.png" | absolute_url }})

### Stage 20: Cervinia
#### [Strava segment](https://www.strava.com/segments/9604560): 17.8 km, 5% average gradient, 958 m elevation gain

![stage-20-cervinia]({{ "/images/giro2018/profiles/stage-20-cervinia.jpg" | absolute_url }})

![curve-cervinia]({{ "/images/giro2018/curves/cervinia.png" | absolute_url }})
