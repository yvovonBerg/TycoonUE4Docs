# Using the animation pack

1. In the content browser -> Enable the sources panel.
2. Click on TycoonTool C++ classes -> TycoonAnimation -> Public -> TycoonAnimationController and drag it into your current level.
3. In your level blueprint -> Create a reference to the TycoonAnimationController.

# Animate basic actors:

1. Add an actor to the world, this will act as the main group / parent actor for the animated objects. (For example a train.)
2. Parent the object that you would like to animate under the main actor.

![](/img/TycoonAnimationStartActor.PNG)

3. Create a reference to the main parent object in the level blueprint.   
4. From the TycoonAnimationController node -> TycoonSwitchTrain.   
To the Train pin connect the main parent object.   
4. From the TycoonAnimationController node -> TycoonChangeSpeed.  
Set the intial speed value. For example 1.0.   
5. Form the TycoonAnimationController node -> TycoonStartAnimation.  
 Set the current spline value, you can use the Spline generated from the TycoonMain Collection actor. (Get a    reference to the Tycoon collection actor and use the GetComponentByClass node (Class = SplineComponent))   

Full blueprint example:

![](/img/TycoonAnimationExample.PNG)

6. Press play.


Troubleshooting:   
Is the object not following the track? 
1. Did you create a child actor under the main group actor?
2. Is the object set to Movable?
3. Press "Update Track" again in the Tycoon UI.

# Custom train setup

1. The above example can be extended to create more realistic train setups.
2. Each animated actor can have another child under it.  
(This can act as an offset node to make sure that your object isn't fully clipping through the track.)

![](/img/trainexample1.PNG)



Stuck?
Press the [Submit bug](https://tycoon.atlassian.net/servicedesk/customer/portal/3/group/3/create/10014) feature and include as much information as possible.





