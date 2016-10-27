---
layout: default
---

## I get it Laszlo, but how do I get started?        

I got some nice feedback after the [three part Docker article series](Simple-Jenkins-and-Docker-workflow) and had the chance to have a few deeper 
chats with managers from companies big and small. 

They all had their unique situation and while they fight their own daemons day to day, 
they all have **developer experience** high on their agenda, and agreed that Docker has a huge part to play there.   

We talked about their team structure, their tech legacy and factors that prevent them from going full offense on old processes.

In those talks I emphasized a few things on **how to get started and build change from the ground up and have culture do the dirty work**. 
I also decided to share a few of those points in an article. So here it is.
 
 
---

## Tooling is a great culture barrier, invest in it
If there is anything I learned during the years of managing developers is that getting people to change is hard. 
I mean HARD in all caps, if not impossible.

[Changing their working environment](http://www.elidedbranches.com/2016/04/you-can-bring-horse-to-water.html) though yields better results faster, sometimes instantly. And the best news is that you have control over it.

Tooling is another great asset to achieve change. It's not hard to see that people do what is easier for them. 
You can fight the tide but why would you if at the same time you can **make the right thing easy** and have people naturally opt for the desired behavior.

It doesn't require to have a fully staffed platform team or toolsmith team - although it certainly helps, you can get started by having one of your engineer work a full day on the most annoying problem they face. 
Picking a problem or a person shouldn't be so hard, just follow the inside jokes or the wining and you quickly find good candidates. 

A lot of damage can be done in one day, and if you timebox the effort, you can be sure of finding a pragmatic solution to your most annoying problem. 
The only thing left is celebrating the small scripts and to promote sharing.

## Educate
Knowledge is never evenly distributed in your team, but plans always assume the cutting edge.
 
You would expect you have Git proficiency in the whole team, and everyone has multitude of scripts to automate their daily work. It's not quite true on the edges.
 
Therefor it is crucial to reinforce the knowledge of Git, Continuous Integration (CI) and have your team master Docker basics in order to not be bogged down with technicalities.

Tooling hides the complexity, but the listed skills will never be sparred from developers, and are a baseline in a nimble technical organization. 
Especially as Docker is becoming as ubiquitous as Git - despite the fact that Git was never as straightforward as Docker is today.

## Boom, profit!
Investing in your release process has multitude of upsides.

* It's good for retention. Developers just want to ship, and see the impact of their work. No developer ever complained about releasing too often. 
* It's good for time to market. Consistently. To paraphrase Dave Farley, **if something hurts in software, do it more often**. This is especially [true for releasing](http://martinfowler.com/bliki/FrequencyReducesDifficulty.html). 
The more often you release the less you have to deal with the unpredictability of the "code freeze", and the infamous merge problems. A good cadence of releases makes software delivery predictable.
* It's good for talent attraction. Once you nailed it all, documenting how you deploy software tells more to potential hires than any hiring pitch.

---

This is not rocket science, but hopefully commodity soon enough. Should you have any question, head over to [https://laszlo.cloud](https://laszlo.cloud)

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-84825803-1', 'auto');
  ga('send', 'pageview');

</script>