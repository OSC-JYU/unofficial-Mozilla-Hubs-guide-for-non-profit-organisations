# Unofficial guide for Mozilla Hubs for non-profit organisations

WORK IN PROGRESS, currently more or less random thoughts...

This guide is not a tutorial or techinal documentation of Mozilla Hubs. Things change fast in Hubs - and VR in general - and maintaining detailed tutorials would be too big task. Instead, this document tries to give an overview of things one must be aware of when utilisng Hubs for events or public VR spaces.

This document is focusing browser-based usage of Hubs, and more or less ignores VR-glasses.


## Why?
> Dull slides are dull slides also in virtual reality

You may (and you should) wonder what new virtual reality might bring to your event. Is it really worth of extra effort? This document tries to give you some starting points so that you could judge yourself.

As on organisation, you can use Hubs in couple of roles.

1. event host
In the role of event host, the organisation is active actor
2. educational space provider (gallerist)
This is a passive role, where organisation creates a place (scene) where users can study different kinf of materials on their own.
4. self promotion space
5. ...



### Hubs - Browser-based virtual reality
Mozilla hubs is a browser-based VR platform developed by Mozilla. 
 > take control of your online communities with a fully open source virtual world platform that you can make your own.
 
The key here is the word "browser-based" because it means that anyone that can participate to a video conference, can also participate to virtual reality event in Mozilla Hubs. Basically, its "just" a webpage, no tedious registatrations or software installs required. You can think Hubs as an "one click vr-meeting platform". 

The word "immersion" is often attached to virtual reality. If you have ever tried good VR-glasses, you know what I am talking about. But how about VR in browser? There is no such immersion available that VR-glasses can offer. Does it even make sense to speak about virtual reality on browser? 

Maybe we should leave the term "virtual reality" to immersive VR systems and start to speak merely about virtual spaces in the context of web-based systems. A flat web page is not a "place", but virtual landscape in that page is. Using three dimensional space for displaying data hugely affects how we remember things ("it was on the yellow room"), how we refer things ("the third object on the right in the main hall") and what order we receive information.

When virtual space is connected to real-time communication, then VR starts to show its best parts. "Come with me". That's the key, we can go together and share "virtual togetherness". 

So, the immersiviness is not what browser-based VR essentially is.

### If not immersion, then what?

One way to think about browser-based VR is to think it as a **contextualised space for disccussions**. It is a "space" where you can bring any digital content. By placing items in space, you'll create a potential for fruitful discussions where people form groups naturally because they share the same environment. 



Of course, if you are in the field of architecture, then its obvious what you can do with virtual spaces: You can bring people in the buildings to explore instead of just showing pictures! For example, check out this magnificent church: https://hubs.mozilla.com/vjpXfuH/karjasillan-kirkko

But the field is new, and You might be the person that invents some new ways to use browser-based VR!

### What's wrong with VR glasses?

Nothing, they are great! 
But there are two cons with them. Firstly, not everyone has them. Secondly, NO ONE will participate your three hour webinar while wearing VR glasses three hours. (Maybe some day this is reality)

## Spatial sound

Surprisingly, the most comprehensive aspect of communication in VR is how user sounds are handled. In most VR-systems (including Mozilla Hubs) sound is spatial. This means that sounds behave like in a real world: if someone speaks on my left side, then I hear the sound from my left speaker or headphone. And if someone is screaming far a way from me, I can only hear a faint murmuring.

When I first tried Mozilla Hubs with small group of people, I was annoyed because of spatial sound. We all kept running around virtual space and then tried to speak each other without hearing each other after all. Swithing from video meeting to VR was bad experiense. I kept wondering why spatial sound is used. It did not seem to work, it just made our communication difficult. So, why is it used?


Spatial sound is not a technical requirement of virtual reality, it is purposely built feature. One can think of couple of reasons why spatial sounds are used in VR.

1. Mimicking real world

Like I stated earlier, spatial sound works like sounds in real life. And if one wants to mimic reality, then also the behaviour sounds should mimic reality. But virtual reality does not have to mimic reality but instead one can choose what kind of reality one want. So if spatial sound is not what users want, then there is no reason to use it just because we have to mimick real world.
But there is another reason that justifies the use of spatial sound.

2. Contextualising conversations

What do you do when you go to the museum with someone? In addition of enjoying services of the museum cafeteria, you propably wonder around, watch things and discuss about them with your company. And this is the purpose of spatial sound in VR. It contextualise conversations. It's like saying: "Here, in this corner of virtual space we discuss about this thing hanging on the wall". 

3. Natural grouping

This one is close related to previous one. Spatial sound allows natural grouping of people without the need of breakout rooms. People in groups can have discussions without disturbing another groups and changing group is as easy as moving close to the group of avatars. 



### Ways to deal with spatial sound
Spatial sound is essential part of communication in virtual reality, but sometimes that is not what we want. Let's say you want to organise a meeting with group of people. Then it's desirable that we can have continous sound connection like in a video meeting so we can hear everyone's opinnions. Or maybe we are building the the VR space and we want to be able to discuss during construction. 
There are couple of ways to bypass spatial sound.


#### External audio
External audio means that one use something else than VR application itself for audio connection. For example, users can fist join to Google Meet session and then open Hubs room in a different browser tab with microphone and speakers muted in Hubs room. 
External audio can be achieved also naturally if all participants are physcally in the same room (for example in class room). Then people can speak in IRL and still share the same virtual space.


#### Audio Zones
https://hubs.mozilla.com/labs/creating-speaker-stages-and-manipulating-audio-in-hubs/

#### Virtual microphone + speakers
Virtual microphone is a special case of audio zone. Virtual microphone is a special area that that can be used to emit user's speach to virtual speakers. This allows to build large areas where speaker's speach can be heard without attenuation while other user sound behave normally.

TECH TIP: Currently microphone setup can be build only with Blender addon.

RULE: If your audience are meant to communicate by speaking, then you must pay great attention to sound design. This also means that the area of the virtual field should be suitable for communication.

## When not VR?

If you only want to keep a meeting, then VR might not be the best solution. Meeting in the virtual meeting room that mimics real meeting room is just ... well, why would you do that?

## Difference between scene and room

Note: This is important!
When you get a link to VR-meeting in Hubs, you'll get a link to a room, that points to a scene under the hood. So you can consider a room as an URL. You can have unlimited amount of rooms that are pointing to a certain scene.

There two important facts to remember:
1. If the scene changes, also the room changes. (The room is not a copy of scene)
2. The scene that the room is pointing to, **can be changed by the room owner**. This means that the SAME link can lead to totally different place!

[https://hubs.mozilla.com/labs/what-is-a-scene/] read more about scene


## Contextualising space (Information decoration)

Let's say you are going to host a remote meeting that involves some visual data.
You can grab a scene with with media frames, create a room, put some of your images to the walls and share the url to the participants in 10 minutes. You just contextualised the space for your meeting.


