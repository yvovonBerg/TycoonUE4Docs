# Tycoon blueprint nodes

# TycoonUpdate

You can execute the "Update Track" command through blueprint as well using the TycoonUpdate blueprint node.
1. Create a reference to the Tycoon Main collection actor.
2. Search for Tycoon Update
Note: This will update the entire track, so it might be a slow operation. 

![](/img/tycoonupdatebp.PNG)


# Using the Tycoon spline

Tycoon will create a normal Unreal spline component that has correct upvectors for the entire track.
You can use this to create your own animation or game systems, take a look at the Tycoon animation pack as well. [Tycoon Animation](install_tycoon_animation.md)

1. Create a reference to the Tycoon Main collection actor.
2. Use the GetComponentByClass node and select SplineComponent from the dropdown.

![](/img/tycoonsplinebp.PNG)


Stuck?
Press the [Submit bug](https://tycoon.atlassian.net/servicedesk/customer/portal/3/group/3/create/10014) button and include as much information as possible.

Good idea?
Press the [Submit feature](https://tycoon.atlassian.net/servicedesk/customer/portal/3/group/3/create/10015) and tell me about it!
