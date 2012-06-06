# Getting Started #

This chapter will be about getting started with monitoring. We will begin at the beginning by explaining some backgroun on monitoring tools and then move on to how to get both Ganglia and Icinga running on your system, and finally how to get them setup to start working with. At the end of this chapter you should understand why Ganglia is around, why you should use it and you should be all setup to do so.

## About Monitoring ##

What is monitoring, and why is it essential 

Our current monitoring setup consist of three primary components:

Ganglia     (trending)
Icinga       (events)
Pingdom   (external)
And two associated utilities:

Pagerduty (escalation)
Chef         (integration of the above)
Each of the above 