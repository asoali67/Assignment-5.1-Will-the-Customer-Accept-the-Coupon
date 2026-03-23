# Assignment-5.1-Will-the-Customer-Accept-the-Coupon
In this first practical application assignment of the program, you will seek to answer the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not

### Data for Bar coupon
|              data retrieval condition           |   Drivers accepted coupon    |   Drivers did not accept coupon    |Ratio drivers accepted to not accepted|
|                   :---:                         |           :---:              |             :---:                  | :---: |
|What proportion of the total observations chose to accept the coupon? |0.5675654242664552| ---  | --- |
|What proportion of bar coupons were accepted?                         |0.4099502487562189| ---  | --- |
|                   :---:                         |           :---:              |             :---:                  |:---: |
|acceptance rate went to a bar 3 or fewer times                        |0.8143203883495146|0.9612141652613828|0.8471789|
|acceptance rate went to bar more than 3 times.                        |0.18567961165048544|0.0387858347386172|4.7873047699|
|Ratio of went to bar 3 or less and 3 or more                          |4.38562091503268|24.782608695652176|---|
|                   :---:                         |           :---:              |             :---:                  |:---: |
|go to a bar more than once a month and are over the age of 25|0.35436893203883496|0.10792580101180438|3.2834496359|
|go to a bar Less than once a month and are over the age of 25|0.15655339805825244|0.16779089376053963|0.9330267844|
|Ratio between over age 25 and under age 25|2.2635658914728682|0.6432160804020101|---|
|                   :---:                         |           :---:              |             :---:                  |:---: |
|go to bars more than once/month, no kids, not farming|0.47694174757281554|0.13322091062394603|3.58008172545|
|go to bar one time or less, with kids, farming|0.0012135922330097086|0.0016863406408094434|0.71966019|
|Ratio of two above|393.00000000000006|79.0|---|
|                   :---:                         |           :---:              |             :---:                  |:---: |
|go to bars more than once a month, no kid, not widowed|0.47694174757281554|0.13322091062394603|3.58008172545|
|go to bars more than once a month and are under the age of 30|0.30218446601941745|0.11650485436893204|2.59375|
|go to cheap restaurants more than 4 times/month and income is less than 50K.|0.14927184466019416|0.1239460370994941|1.2043293|

#### Note : 
Left Ratio is the ratio between drivers accepted and not accepted the bar coupon. under each sectiom the Ratio column
is for both constraints above it.

### Analyzing the BR data 
\* In case of diver accepting coupon. we notice the coupon did not have much effect when the number of going to bar 3 times or less, however the coupon did have significant effect on drivers visiting more than 3. When the drive did not accept the coupon, the ratio between going less than 3  or more is much larger. Than indicates the coupon had major role for drivers to go more than 3 times to Bar 

\* For drivers accepting coupon, for people age greater than 25 there are more than twice of driver went more than once to the Bar, the effect of coupon was no to entice drivers to go to Bar when the number of visits were once or less

\* in both accepting a coupon and not, No kids in the car had a major effect of having a driver visits a bar even more than once

\* The coupon seem to have significant effect on visiting a bar more than once when not having a kid in the car and not being widowed, also the coupon have significant effect drivers under the age of 30. However the coupon did not have an impact on drivers visiting cheap restaurants

### Data for Carry Away coupon
|              data retrieval condition           |   Drivers accepted coupon    |   Drivers did not accept coupon    |Ratio drivers accepted to not accepted|
|                   :---:                         |           :---:              |             :---:                  |:---: |
|What proportion of Carry Away coupons were accepted?                         |0.7337883959044369| ---                       |--- |
|                   :---:                         |           :---:              |             :---:                  |:---: |
|acceptance rate went to a Carry Away 3 or fewer times                        |0.5226744186046511|0.5576923076923077         |0.9372052574010651|
|acceptance rate went to Carry Away more than 3 times.                        |0.47732558139534886|0.4423076923076923        |1.07917|
|Ratio of went to Carry Away 3 or less and 3 or more                          |1.0950060901339829|1.2608695652173914         |---|
|                   :---:                         |           :---:              |             :---:                  |:---: |
|Carry Away more than once a month and are over the age of 25|0.6343023255813953|0.594551282051282                   |1.066858898|
|Carry Away Less than once a month and are over the age of 25|0.04534883720930233|0.038461538461538464              |1.179069767|
|Ratio between over age 25 and under age 25|13.987179487179487|15.458333333333334                                     |---|
|                   :---:                         |           :---:              |             :---:                  |:---: |
|Carry Away more than once/month, no a kids, not farming|0.7912790697674419|0.7451923076923077                        |1.061845461368|
|Carry Away one time or less, with kids, farming|0.0012135922330097086|0.014423076923076924                            |0.0841423948|
|Ratio of two above|680.5|51.666666666666664                                                                          |---|
|                   :---:                         |           :---:              |             :---:                  |:---: |
|Carry Away more than once a month, no kid, not widowed|0.2941860465116279|0.1063953488372093                         |2.76502732229|
|Carry Away more than once a month and are under the age of 30|0.1755813953488372|0.06511627906976744                 |2.696428571428|
|cheap restaurants more than 4 times/month and income is less than 50K.|0.1436046511627907|0.045930232558139536|3.126582278|


### Analyzing the Carry Away data
\* coupons did not make much difference for drivers doing carry away, when they did 3 or less times or more than 3 times. in all it does not seem that coupon has effect 

\* coupons did not have much effect on drivers with age over 25 doing carry away

\* Coupons did not have effect in case of visiting more than once or less than one time.  However with having no kids in the car and not farmer, the number of carry out was much significant than with kid and farming.

\* The coupon seem to have significant effect doing a carry out more than once when not having a kid in the car and not being widowed, also the coupon have significant effect drivers under the age of 30 and going cheap restaurants
