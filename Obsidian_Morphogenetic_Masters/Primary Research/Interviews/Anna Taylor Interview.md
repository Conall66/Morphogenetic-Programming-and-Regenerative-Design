## Question Topics

- Introduction of project stage
- Ask about Anna's work with ACC
- Pathways to Transformative Adaptation of South African Cities
	- Possibility of creating agent based models to demonstrate the potential gains of TA (optimisation)
	- How complex are these systems? How easy would it be to model?
	- How are these cities adapting at the moment and why is it unsustainable?
	- How is climate change affecting these cities? Where is it affecting most heavily?
	- Does there exist information on the growth of existing water infrastructure for example? If not, how useful would a toy model be, taking synthetic cities to demonstrate potential growth patterns?
	- How do communities interact with one another?
	- Would it be useful to highlight the most important infrastructure points, now and in the future? (Markov Chains)
	- Would it be valuable to demonstrate why institutions should work together (possibility for Shapley values/game theory use in pricing models)
- Would it be better to design models informing general city development measures informed by TA (i.e. )
## Interview
### Key Points

- Anna was keen on modelling how city expansion is going to influence water demand by region/morphological structure
- The state often tries to impose laws on city growth, but the development of informal settlements underwrites a lot of those restrictions
- Cities are looking to promote densification
- Water scarcity is being exacerbated by climate change, but the sources come from far away from the major cities themselves
- Tourism is driving rapid growth
- 
### Transcription

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image004.gif)**Templeman, Conall**   0:04  
OK, good stuff. So I'm just going to start by talking about the project that I had in mind.  
And then I'm going to ask you to sort of explain your role at the ACC and then hopefully we can sort of discuss some of the intricacies of the project. I've got some things I want to learn about sort of the mechanisms behind city expansion, particularly in different regions of South Africa and how.  
The rapid population rise is gonna influence that urban city growth, basically. And then how that might have a recursive impact on, say, water scarcity and other like climate driven factors. So if you could start just by saying.  
Who you are, what you do that would be really helpful.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image006.gif)**Anna Taylor**   0:47  
Yeah, sure. Yeah. You've raised some big themes there.  
Yeah. So I'm Anna. I work at the University of Cape Town.  
I am affiliated with the African Centre for Cities, which is a research unit centred around urban studies, sustainable urbanism in the global South.  
My primary research home the so I work kind of across the urban space but.  
Climate, space. And so we we actually have 3 research units within the University of Cape Town that kind of intersect. And so I've set a little bit across them. And so that the Africans at the cities, but actually the what's called the African climate and development initiative, ACDI is actually kind of my physical home as in I sit in their offices.  
And then just to mention a third research unit, which is more the climate science.  
Like the the climatologists and the meteorologists and the people doing that work at the University of Cape Town are in the climate system analysis group. And so I've kind of over the last, maybe nearly 12 years, I can move between those three groups, kind of doing my PhD attached to the ACC, but then doing a postdoc with the climate scientist and now primarily working in this so.  
The Acdi African Permanent Development Initiative is is meant to sit at a more kind of.  
It's a faculty, so a kind of even a higher level of integration across the different climate related topics. So I focus on the urban aspects, but obviously there there are lots of other aspects to it and my research. So my entry point is climate adaptation. So the kinds of things that are done to address climate risks.  
And primarily in cities. Although my work, as soon as you start looking at things like.  
I have had a particular focus on water related climate risks, particularly flooding and drought as like the two extremes.  
And I guess, yeah, my sort of entry point is, is one around how public decision making happens. So, so looking at decisions that city governments are responsible for making, whether those are planning, special planning decisions, infrastructure investment, upgrading expansion decisions.  
And really trying to understand.  
How climate?  
Needs to should factor into those decisions and then and then how do they and if we say that climate information is inadequately being brought to bear within these decision making processes, how could that be done more effectively? So that's kind of the topic that I look at, but I was just going to say from a spatial perspective, you know as soon as you start dealing with water, for example, immediately you have to look.  
At the city in its bigger regional context, because water's obviously being brought in and out from well beyond the the the administrative boundaries of the city. So it's also that question around sort of multi scale governance, I guess and how decisions like that shape up. So that's kind of been and most recently I've been looking.  
So so a lot of my work is rooted in Cape Town.  
Well, I've done projects where we've looked at other mainly primary cities, although more recently I've been working with a secondary city in South Africa, but sort of looking at Southern African.  
Primary or I mean not all the capital cities, but mostly the the bigger cities in the countries in our region.  
But with Cape Town as my like, that's always kind of my my.  
First point of reference and a lot of the more in depth work I've done here and then kind of contrasting that with how it looks elsewhere because.  
Because you realise how important. Yeah, I mean demographics, but the regulatory environment in which all of this urban growth happens is quite different like South Africa.  
Is different compared to some of our neighbouring countries and then is kind of similar and different from countries elsewhere in the world.  
So a lot of it is really trying to understand how that plays out, but I I mean I've I'm a sort of a geographer, environmental scientist by background, but I've kind of moved deeper and deeper into like the social dimensions of decision making to try and figure out how these more biophysical factors really.  
Yeah, are brought to bear in how urban decisions are made. So yeah, maybe that's useful to stop there.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image007.gif)**Templeman, Conall**   5:51  
I mean this actually this sounds perfect. Maybe because so one of the approaches that I'm looking to take is it's this modelling or simulation process known as agent based modelling where you can you can basically assign like relatively simplistic rules to different agents in like a wider simulation, right that might resemble the how the built environment is transforming or how.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image008.gif)**Anna Taylor**   6:12  
Yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image007.gif)**Templeman, Conall**   6:17  
You're seeing like certain migration pockets forming and how like obviously new like informal settlements are forming around the city?  
And then try and use that to inform like city growth. That way I do want to ask because this might help define some of the rules for how the city actually grows. You mentioned that you don't think climate change is often brought into the conversation enough when they're deciding on these sort of broader policy decisions. Can you give an example of how that is?

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image009.gif)**Anna Taylor**   6:46  
Yeah, I mean well, the first thing to say is, is that that is in the process of changing like if you know, rewind 10 years, it was hardly considered. There've been huge efforts in Cape Town to make it more considered.  
And an example, I mean, yeah, a few example. One early example from the Cape Town sort of adaptation story is looking quite carefully at coastal.  
Inundation flood risk partially linked to sea level rise, but also looking at the the interaction between rainfall related flooding and.  
Storm surges, maybe more than general sea level rise and and then trying to demarcate on maps where the hotspots are, and look at what it takes from a special planning perspective to create these sit back zones to try and limit further growth into because obviously.  
You know, coastal property development is is quite sought after and kind of quite high stakes.  
In. Yeah, I mean, Cape Town has a particularly big coastline as a city because we sort of on a peninsula.  
And so that's an example.  
Of where they've been these very clear efforts by.  
Environmental management, with the climate change climate change.  
Sort of.  
Strat like a climate change lens trying to influence spatial planning decisions that get made to varying degrees of success and subsequent to that, yeah, I mean the same thing around.  
Sort of buffer zones and setbacks around wetlands and rivers and recognising the importance that you know flood patterns are likely to be changing and we need to revisit.  
The way that that those zones are delineated and rethink what some of the rules are. So, so there's interesting stuff happening in the formal planning space.  
Of course that is.  
In constant flux with the more informal post Urban Development processes and Cape Town is full of examples of.  
Both older and newer.  
Normal settlement, occupation, home, informal home building on areas that are formerly designated to be left as open spaces because they are high flood risk areas, or because there are environmentally sensitive and under conservation protection. And so there's this, this this.  
Yeah, this the formal and informal planning processes kind of constantly.  
Running into each other in a way, and so then climate as over the last 10 years or so, like another example of from my more recent work of looking at drought, is it now there's increasing use of groundwater and there's been a very recent effort at delineating.  
Sort of protection zones around aquifers that the city's becoming more reliant on pumping that groundwater out to supplement or to to add to the municipal municipal water supply system. And so if it's now at trying to integrate some level of protection of the recharge zones and the areas where contamination is likely to be.  
Of particular concern building things like that into also spatial planning processes.  
But but then the recognition that you know it's one thing doing that at the policy and sort of macro planning scale often those.  
Stated objectives are are even in the formal development processes, sometimes overridden.  
So it's not only in the informal occupation of land where.  
Where climate considerations are not, you know, are not heated in a way it it. There are examples that would also happening in the formal.  
Planning and regulatory space.  
Where where other where priorities for, you know, there's huge demand on property for.  
Commercial development to to create more jobs because unemployment is very high and for more housing stock because there's lot, you know there's a huge demand and so even when there's sort of a policy, a stated policy priority to protect certain land because of either its risk, its climate related risk profile or because of its stated importance in reducing.  
Risk that gets overridden at the stage of like development application approvals because.  
Other factors like job creation and housing provision are considered more important.  
You know, so, so there are lots of, yeah, there are a lot of dynamics at play and and climate related ones are increasingly recognised. But I wouldn't say they are prioritised when.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image010.gif)**Templeman, Conall**   12:27  
Yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image011.gif)**Anna Taylor**   12:39  
You know the rubber really hits the road on decisions being made around urban expansion and growth and densification.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image010.gif)**Templeman, Conall**   12:45  
11 Avenue One Avenue I was exploring was this idea that obviously, like the population is rising extremely fast in southern Africa and a lot of urbanisation is to be centred in in southern African regions.  
And so I was thinking about modelling the idea of so Cape Town as an example, right, because you have the coastal barrier, there's only sort of One Direction that you can expand, which is back it back towards the mainland, right?  
And we had, like, there's a number of green areas in and around the outskirts of Cape Town. And I basically read the idea that like, if if the city was to expand into these green regions, obviously it has sort of adverse climate effects anyway, but also a lot of say, like, wetlands or other like water related natural forms, if they become compromised, that has like a self fulfilling cycle where it then compromises the water security even further. And so.  
Keen to potentially go down the route of modelling like OK, what does unrestricted growth look like for somewhere like Cape Town? What kind of impact could this have on water infrastructure? And then how could we instead take more informed growth to work around these? Or how maybe would we target growth in other regions so that you don't have to expand? And then I was going to consider a more like multi settlement multi city approach.  
And see if that made more sense. Do you have any thoughts? Is it? Is it fair to assume that with the rising population, places like Cape Town?

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image012.gif)**Anna Taylor**   14:17  
Yeah, I mean.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image013.gif)**Templeman, Conall**   14:23  
We're going to expand drastically in order to meet the demand because there are some reports basically saying the city won't expand, but you'll see a rise of more informal settlements or you'll see the population density grow drastically in those regions. But the infrastructure won't grow with it, yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image014.gif)**Anna Taylor**   14:41  
Yeah, I mean the these are very live debates, you know, both processes and policy debates in Cape Town. So there's no simple answer. So there's a big policy.  
Push towards trying to effectively.  
Internalise to to densify rather than sprawl further. So just like I was describing the you know.  
Coastal process that I described at the beginning as an example that actually was mirroring it, it was taking up the lead from if it's from spatial planners to actually develop.  
An urban expansion boundary to try and.  
Create a disincentive to discourage development from happening way beyond the kind of roughly current it you know. Accounting for a little bit of growth around the edges, but you know they were.  
The the spatial plans were trying to create a planning mechanism to push growth internal and sort of upwards as opposed to outwards.  
But so. So those things exist and there's a huge both policy rhetoric and and attempt at developing the instruments, the sort of market and regulatory instruments to to.  
To encourage info growth and density growth rather than.  
Your outward growth of the city.  
But the reality is that there is a lot of Greenfield development going on, particularly around the edges. So, so.  
What's happening and what's intended to be happening are of course not perfectly aligned. I mean, I don't know if there are any cities that where that is perfectly aligned, but.  
So when so I mean that that introduces, I mean maybe that's a great reason to do agent based modelling in the like the agents in the model are trying to achieve different outcomes and like you know it's a messy like how that plays out or adds up is quite hard to.  
Predict in a way or you know you can see forces acting in different directions. Which one is going to become more dominant over time because obviously it's hard. It's hard to build up a picture. One can look historically, but to look into the future on how is this going to add up over, you know, 1020 years like getting.  
Yeah. I mean, if if, if the modelling can help explore that, I think it has value.  
But just on your point about water infrastructure and then the multi city?  
So.  
A lot of Cape Town's water.  
Is drawn from quite far afield, like it's not the catchments that we are heavily reliant on for water supply are actually out well outside of the footprint of the city like the the.  
Urban growth is, I mean yes it will. It will.  
Affect a lot of that land that it's growing into is not sort of pristine natural environments, it's farmland mainly.  
And it will absolutely affect the water cycle. But but the the the water that we relying on to to feed the city with its supplies.  
Are are beyond like. We also hemmed it. Not only do we have coastline around a fair amount of the city, but on on a fair part of the other side is a huge mountain range.  
And and most of our water comes from the other side of that mountain range, which is outside of like the metropolitan spatial boundary. And there's quite a big sort of geographical divide. So it's so it's interest in a way, if you're concerned about implications on water.  
The the concern has to be around the growth of other nodes in our region rather than Cape. I mean in in addition to the city's growth, it's like the towns like there is an interesting example. So to extend what I was saying a little bit earlier about the groundwater story, so you know.  
90.  
5% roughly of our water comes from big, some really big dams that are far outside of the city, but but slowly some of that is being that proportions being slightly reduced as groundwater is added to the mix.  
Some of that groundwater comes from within the spatial footprint of the city, and that's about protecting it from urban pollution primarily, and some other uses. But there's a second source that's that's in those mountains next to Cape Town.  
And interestingly, the concern around that water is is from growth and pollution from.  
Partially informal, but linked to formal growth in a in a town called Crabot which is on the other side of the mountain. So that is very interesting and and that is an, you know, that is a receiving area that is a big agricultural hub where a lot of people are moving informally looking for work in the agricultural fruit farming sector.  
So it's also a big receiving area in addition to the city where people are.  
Moving to for urban employment opportunities.  
So I would, I mean I think there is something very interesting to be said for your idea of modelling urban or or urbanisation growth, not just in one city but in, you know, not just in Cape Town but in Cape Town and a few nearby towns that, I mean, they're not even cities. They really are towns, but they're towns, they're towns that are growing super fast that are.  
Equally, if not more, overwhelmed by trying to to formally plan for service, regulate supply, that that growing population and there are clear connections between, you know, what happens like, particularly from a water perspective like, you know, the water that we rely on are shared between these different.  
Like we're connected into a big regional supply scheme.  
So they'll water. That's serving. Cape Town is also serving Crab Bow and a whole lot of other big towns that are growing.  
So I think taking a more there's more interconnected, multinodal urban growth story would be even more. I mean, it's even more difficult to model, I would imagine, but it's even more interesting in terms of, like, exploring how it might play out and like, where the conflicts will be, where the trade-offs and the.  
Yeah, conflicts will be.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image015.gif)**Templeman, Conall**   22:28  
Yeah, well, a lot of firstly, I mean a good thing is that I found a data set, I think it's called the global. What is it, global human settlement database that basically has a record of the urban morphology for like different regions throughout the whole of southern Africa. That's fantastic data set that I can train models on in order to discern like patterns on urban grass. And I imagine you'll see like much faster urban growth in the small assessments on the outside. And then as they get bigger that.  
Development slows down.  
Based on something that you said before, do you think it's worth constraining a sort of boundary? If I'm looking at somewhere like Cape Town constraining a boundary region and saying like, OK, all urban growth has to happen within this boundary region? I know they've done something similar. I think it was in Japan where they basically said like 67% of land in Japan has to be green space.  
But all densification, urbanisation can take place in the other 33%.  
Do you think it's worth modelling if we were to constrain that boundary, what urbanisation would look like and then also consider how, say, like towns or informal settlements, will ignore that boundary region and excel it like expand anyway outside, and then how that growth might be accelerated because the urban cities aren't expanding into those same regions?

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image016.gif)**Anna Taylor**   23:52  
I mean, I think what is true to say is that what's clear in South Africa is that.  
As I mentioned before, both the formal and the informal development processes are like we are weak at enforcement, so we have some pretty good rules, but, but actually even the formal decision making process is often override the rules that that's those same bodies have made.  
Which I think is an important reality. Like maybe that's different.  
From Japan, I mean, it's definitely different from places like China where you know, rules the environment in which rules hold weight and are enforced and respected like those realities are very different. If you want your modelling to be.  
In a way, beyond an academic exercise, like if you want any decision makers to take seriously your results, you have to account for those kinds of things, which is, which is the big difference between, you know, something that's intellectually interesting but like completely hypothetical because it's never, you know, so. So I think I think modelling those different, those different scenarios you've suggested.  
Makes sense to because in a way, what the research can do is show like this is.  
This is what could happen under these different scenarios, and I think that is valuable if you know if you can convince people that the methodology is robust enough to.  
To broadly represent like the sum total of what would like what these, what patterns would emerge in reality if these conditions were met? I think that is useful, but I would I would definitely build into your design of your scenarios this reality.  
That rules.  
Are.  
Are not.  
Heavily enforced.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image017.gif)**Templeman, Conall**   26:05  
OK.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image016.gif)**Anna Taylor**   26:08  
Yeah, I don't. I don't know if that exactly answers your original question, but it because in a way, I mean what the way you asked it made me think, you know, like that in a way that is happening like all these processes I've described of like trying to draw lines on maps to say like, with on this side of the line, we shouldn't develop more or we shouldn't allow any additional development or you know, I mean.  
In the back of people's minds, there's like, OK, well, you know that what's happening in in.  
Australia and America, where people like actually government needs to buy back private land that's already been developed over that line. Like we we we don't have the wherewithal to go that far yet, partly because it's pretty much unaffordable. You know I think in Australia and the US they've been pretty much doing it at semi market value and the state can afford to.  
Hand that money over to to private land owners to kind of put.  
That so, so that that we we can't we're not there.  
But but I I mean particularly in Cape Town, I don't know actually the extent to which it's happening in other municipalities.  
Some metros, but yeah, Cape Town is is definitely doing kind of what you describe, which is trying to draw lines on maps saying don't let development happen in this place or in that place or in this direction. Try and try and crowd it into these areas.  
I mean, not at the proportion that you mentioned in relation to Japan. It's like, you know, the undeveloped Boland is marginal proportional to what is.  
But I think, yeah, maybe playing around with what those proportions are and where those boundaries are drawn and then how enforceable, how enforced those boundaries are like that would generate an interesting set of scenarios that could then be discussed like, you know what what would be the implications of these different?  
Patterns playing out.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   28:14  
Yeah, that's exactly what I was going to suggest that I could model almost different scenarios where those boundaries are heavily enforced and the city never expands beyond those limits. Then as somewhat enforced and you start to see a bit of creep and then are not enforced whatsoever and you see like free rapid expansion.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   28:32  
Mm hmm.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   28:33  
And then, yeah, maybe I kind of want to tie it back in to water whenever I can or I want to have some kind of like grounding that proves the potential impact of these projects, right. Do you think water is the best way to go about doing that or are there other like, because I know.  
I've read a report and it was discussing how effectively with urbanisation you'll see like contradictions in the United Nations Sustainability Development Goals like it's no way that there's no way that you can expand the city without then influencing wage inequality or increasing like the transportation distances with that, like emissions, obviously. Do you think water is the best route to go down like water scarcity? Because I'm thinking particularly as the population is rising so.  
Basically like I mean as someone that doesn't live in in South Africa. So correct me I'm wrong, but that seems to be like the kind of factor that I could imagine lots of people reacting to, particularly in more like rural environments where if they're heavily dependent on farmland or things like that up until then, then climate change is going to have a huge impact for those people, which means you'll see them all moving towards urban areas.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   29:27  
Hmm.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   29:45  
For more like resilient lifestyles, but then I wonder if in those regions water scarcity will just be driven higher.  
Or will be proportional in some sense to like wage inequality.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   30:00  
Yeah, it's a difficult one to answer. I mean, I I water is very topical in Cape Town.  
Particularly I mean.  
Because we had this.  
And extreme drought not long ago.  
And that was shown. You know that the the stats were roughly like pre industrial. It would have been about a one in 300 year drought. But because of climate change, it was roughly A1 in 100 year drought. So it's still unusual, but obviously that brought into sharp focus like what happens in a city when there's not enough water.  
And and the need to prepare, you know. So there. So there's lots, there's lots. It's it's very much in the public consciousness that climate change and urban growth are kind of both.  
Ratcheting up and and are contributing to that a situation like that that has been recently experienced, like manifest people know what it feels like that that's that. That is the risk of that is mounting. So I mean I think so from that perspective there's some sense to focus on water because.  
Yeah, because it's very topical.  
Yeah. And we know it. We know it's gonna be a a kind of concern for many cities.  
I mean it it and it's a bit, it's a bit of a bias of mine 'cause I my research interest is in that direction. So obviously I I've explored it heavily, which is also why loom's large in my thinking. But compared to others I mean.  
I mean, I think they are your mention about sort of transport, transport and emissions.  
Is is also, you know could also be an equally valid 1.  
It because the way in which our urbanisation happens with pretty weak public.  
Such a complicated picture, not quite informal, mainly vehicle based, you know, like not much rail transport, so it our form of urbanisation almost by default is quite high carbon intensity.  
So I mean, yeah, that could also be a focus, but yeah, it probably probably any of them could be. But I think water is an easy if that was your original sort of like I think it's very justified and makes a lot of sense to focus on water. So there's no reason not to, I would say even though there are many other things you could also focus on. But I think if.  
If you have an interest in that, by all means is your plan to do multiple.  
City regions, or are you going to do focus just on Cape Town and surrounds?

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   33:01  
I mean, in theory, given that the underlying mechanisms will likely be the same for a lot of these different cities, particularly if I was to focus on South Africa like, I mean all the regulatory stuff will be the same.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   33:12  
Yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   33:13  
I'd be keen to model it for multiple different places. I mean, there's a part of me that wants to explore like how these things interconnect, but I wonder if.  
There are so few, like major cities that are close to one another, that it would only really be valuable to model the like smaller settlements and how those are interacting with one another. Because I don't see like the way that somewhere like Johannesburg is interacting with Cape Town for example, like, I don't know, particularly within like the water framework what that would mean unless you have any suggestions.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   33:48  
Yeah, I mean that's interesting because, yeah.  
There is a lot of talk and an experience, you know.  
People in South Africa at the moment joke a lot about this immigration that people are moving from, because Joburg and the housing region has been the primary kind of economic hub of South Africa.  
But that a lot of people particularly kind of with means on our and and jobs and you know, particularly the wealthy residents, many there's a, there's a fairly I mean I don't know the numbers.  
That sort of a fairly considerable movement of people for various reasons, but one of them is, because Joburg is going through its water crisis and it's, you know, and it's not in the Johannesburg case, it's a bit different in that it's not just a supply crisis, it's more of a service provision crisis. So it's not just that they're having a massive drought and the dams are empty. It's like the infrastructure that, that.  
Processes and distributes that water has been crumbling and poorly managed, and so there's a sense that that, that internal migration is being sort of accelerated because there's a there's an erosion of trust that basic services are being adequately provided. So in that respect, the cities are kind of being connected in that there's a sense that, you know.  
A downward turn in one and a relatively good performance in another.  
Means that people make choices to move between the two.  
But but it's so it's not from like a. It's not from the water, the physical, you know, catchment.  
Water cycle interruption, perspective of growth, it's more around.  
Yeah, trust in in service provision, really. But I don't know how. So I mean, that becomes interesting from your PERS from the.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   35:49  
Like crowd modelling. Yeah, yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   35:58  
Agent based modelling perspective as to like you know, are those the kind of decisions that you represent in models in the model like what yo, what's the scale, is the agent an individual household business owner is it like?  
And and why they make decisions around where to move and where to buy a property or whatever, or rent a property or.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   36:25  
Yeah, so I mean.  
One one thing that you're saying that I think is actually useful is you can interconnect the cities based on sort of crowd modelling and migration patterns. And then if I can infer that with an influx of people you'll see faster urbanisation in that area where there is like a higher density of people, then I can use that to inform city growth. There's the potential for lots of different approaches. So I'm thinking.  
Maybe something Asian based to represent the actors. The people in the system.  
I don't think it will be like an individual person, but household is probably a good way to.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   37:02  
So yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   37:04  
Adapt to the computational structure, but then there's also the potential for something like cellular automata or some kind of machine learning model that actually predicts how the city itself grows. And all I need to know is how many people are in that place in the 1st place and how that is accelerating growth in those regions, I guess.  
One of the avenues I wanted to explore at first, and I was a bit hesitant to go down.  
Because this idea that like access to key water infrastructure will influence migration patterns which will adjust. But I didn't know how I would, I couldn't find any sort of data on the quality of water infrastructure by city. For example. Is there any way that you think I could model that or is there any way I could sort of predict that maybe?

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   38:00  
I mean, my first thought is around it's not.  
It would be.  
In one indicator of the quality of the infrastructure is leaks. Data like, you know, reported leaks in the distribution network.  
And.  
The the density of those.  
Could be an indicator of the quality of the service and the network, and that data is held by each municipality.  
To what quality? I mean, Cape Town's I think is pretty good and and probably if you made an application so that that kind of data is not publicly available but but but there is a mechanism by which you can apply to access that data from the municipality.  
So that would be one way.  
Yeah, in a way, you'd have to talk to the the water engineers. You know, they have ways of prioritising where they do their upgradeing. And you know, they've got quite sophisticated.  
Like I know the person caitan, you'd have to speak to basically who could give you the answer to that question. I'm not best placed to do that.  
But.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   39:26  
I mean, if you if you could put me in contact with that person, that would be amazing. Like it would actually open up that Ave quite substantially, which would be good for me.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   39:36  
Yeah, I just have to. I I need to get a few other things out of him. First, for the project that I'm busy with.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   39:42  
OK. Yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   39:43  
But but if you circle back to me like once, I've got what I need out of him. I'm happy to. Then ask him to give you what you need.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   39:50  
Yeah, that's fair enough.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   39:51  
Actually not that you know the way, probably the proper way to to do it.  
Would be to go through so that there's a. There's a sort of official in in the Cape Town Municipality who's responsible for being the interface between research and.  
People just doing their job as government employees in the water or any other space, and probably rather than putting you directly in contact with like the head of the bulk water technical who works with all of that data you would you probably must need to go through because she's the person who would be able to. It's a bit of a chicken and egg.  
That's the difficulty is in a way, you need to know what you asking for to be able to go through their process of like asking for it. Can I get permission to get this data? But often we're like, well, we don't know what we know roughly what we're looking for, but we need to talk to somebody about what data exists before we can ask for the right thing. And that's always a bit of a tricky thing because in a way, Cape Town's also getting so much research requests that understandably, they're trying to put.  
A bit of a not a gatekeeper, but a bit of a barrier between.  
The people you know, under huge pressure to deliver on their day jobs and all of the research is asking for help around what data they got and can they use it and can they see it? But but as I say, like it's a bit hard when you don't, you need to talk to somebody like that to know what they've got before you talk to the person to say, can I get permission to get us?  
But but yeah, I mean there are.  
I don't know how else.  
Rather than talking to people, I mean The thing is to look into some of their this the Cape Town has got much better at putting out some of their technical.  
Some of their technical information Doc, I would suggest just if you Google City of Cape Town Water Outlook report for example like that's a report that the engineers put out on how well they're doing to deliver on.  
The priorities that are listed in our Cape Town water strategy, the city government's water strategy that gives you some clues as to like what they doing and it so it doesn't give you.  
But it gives you a sense of what they collecting data on, how they making decisions based. So it's almost like, yeah, going and doing a bit of that background work so that you can ask a very pointed question might be a good place to start.  
But yeah, that's where I would. Or you can, as I say, you can circle back. It's just that.  
I I'm very.  
Conscious of.  
Overwhelm of, as I say, like I'm busy trying to do a kind of exchange with the city on things on one project. And the more we lump in different things under it, the harder it gets for, you know, it puts strain on that relationship basically. So I'm happy to make the introductions once I've finished doing what I'm doing with them currently.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   43:11  
Yeah, I mean it, it may turn out. I wouldn't want to like compromise your your work just to to do me a favour. I mean, it's not an Ave I have to go down. It's kind of why I stayed away from it in the 1st place because I thought getting all of this information would be a lot of work. And the truth is I have to have a more rigid proposal in the next couple of weeks anyway. And so if I haven't had a chance to speak to them before then, then I wouldn't be able to make the case that I can build anything from it.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   43:11  
Just to not muddy the waters.  
I mean.  
But maybe yeah, yeah, yeah. The, the other place. I mean, again, it depends what kind of data that you need, but.  
I mean, just looking at the census data that comes out around.  
There are questions in our national census that asks about water.  
Service sort of quality access because in a way what would be better for you is a publicly available national scale database, because it's also if you are, if you are going to look beyond.  
The municipal boundaries, then any data that you only get for one municipality. If you're looking for a bigger area is not that helpful 'cause. You can't then get it for all of the spatial extent that you are modelling for. So there's an argument to stay away from.  
Sub municipal data that's only available in given municipalities because it won't be.  
Yeah, it'll be patchy.  
But yeah.  
I'm trying to think what other sources.  
It's so complicated.  
Just thinking about, you know about the water supply side kinds of data and the water service provision kinds of data like data about how people experience access to water versus like what's happening behind the scenes in the system that, that, that supplies that sources and treats and distributes that water. And those are like two totally different types of data as you can imagine.  
That are held by different kinds of people.  
I mean, maybe if you are interested in the slightly looking a bit.  
The city in its city regional so more city regional.  
Kind of modelling then looking at the data that's available for the Western Cape.  
To supply system, which is this kind of integrated bulk network of supplies that Cape Town draws, you know Cape Town draws something like 67% of that water, but the rest of it goes to agriculture and the towns around. And so. And that's sort of administered more at the provincial government scale. So there might be a reason to look more at that.  
Level of what data is around in that space than in the municipal space.  
But you know, I don't know.  
It really does depend on what you need.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   46:21  
Yeah, I I mean.  
The key for this project is that I I do want it to have like some kind of relevant impact. I don't really want it to just be some kind of like academic study, but also like, as you've pointed out, the complexities of these systems are so great and trying to capture something like that in say an agent based modelling system where you have to define like pretty reductive rules.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   46:38  
It's not great.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   46:47  
That govern how the system operates. I'm a bit cautious. I mean, I read a report the other day that was just, it was just tracking like urban proof.  
Urban expansion in some region of South Africa.  
Using sort of machine learning based studies that actually take took that same like global human settlement database and then used a sort of Markov chain, informed cellular automata model to track like critical nodes in the system and then informed like sustainable actions. As a result, I haven't had chance to go like properly through the paper yet, but it's it's that kind of thing.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   47:08  
OK.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   47:26  
That I'm trying to accomplish, but I really want it to be able to have an impact that like say someone in South Africa could read my report and be like, oh, this is actually really helpful. Could inform like city growth mechanisms. But what firstly, what level of accuracy do you think I need to be at in terms of reflecting like because because I mean I'll do the standard thing where you you split your your data set up into.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   47:26  
MMM.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   47:52  
Test validation and like feed data basically.  
But what level of accuracy do I need to be at reflecting like previous growths using whatever model it is, I choose to go with before it can actually have an impact on policy making for example.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   48:10  
Yeah. Look, I'm coming, having spent a long time trying to work this versions of this question out.  
I think we often over.  
Of.  
We we expect.  
Impact. We hope for impact, that's not really.  
Feasible like.  
You know, because the first question is, OK, who?  
Who are these people that might use? You know, that might read it and say, wow, this is really useful for what I do.  
And and that's I mean I think maybe at the provincial scale is more realistic than at the fatigue scale because of the city scale. It has to be, you know, they planning, I mean what you should do? What if you really want to understand the Cape Town?  
If you want to get into the mind.  
Of the kind of person you think you might like to have impact or how who I imagine a study like yours would want to have impact with.  
Is to read.  
The spatial development framework so Cape Town's taking this approach of kind of nested nested spatial development framework. So they did a municipal scale one and then they do district ones and then they do local and even precinct level special development frameworks and that is really their effort at saying like the the.  
So in that you'll see.  
Not a researcher's attempt, but a government officials attempt at doing some of the kinds of projections that you would do in a totally different way. But but you really see like the there how the scale at which they trying to.  
To.  
Shape the decision making space. As I say. I mean what's frustrating is even they struggle to have impact like we're trying to impact them and they're trying to impact like either the household or the property developer who's building something.  
To sell or to rent to somebody. And what's interesting is like there's very weak, like the consequence of us to them and them to the person who's actually physically building something on the ground is pretty tenuous at best. But of course, that none of that. I mean, that's not a reason not to do it. Like there's a little bit of connection and like maybe.  
Sometimes I think academics best role is a little bit to like. Challenge some fundamental assumptions rather than get. It's almost like we can never get to the level of resolution that they want to see results at. So actually not trying to do that, but rather trying to just probe or question or highlight some bigger.  
Assumptions that may or may not turn out to be true is a better is more useful to decision makers.  
Than trying to like model reality at the scale at which they trying to decide like should we let this person build a block of flats on this property or not kind of thing.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   51:33  
Yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   51:35  
We so. So I was think trying to be more impactful actually at a slightly more macro scale. So maybe at the provincial scale where it's like deciding on you know incentives or disincentives for.  
Apportioning budget around.  
Bulk water infrastructure investments like should we be prioritising this town and its municipality over this urban area? And it's, you know, those kind of quite macro decisions maybe are a better scale at which to try and influence than.  
The the very.  
Granular.  
Like Earth property scale decisions.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   52:28  
I mean, if I if I went down a direction like that, I wouldn't. The way I see it, I wouldn't even need to necessarily model the city itself. I would just need to have knowledge of like a budget for water infrastructure per year. I would need to have an understanding of the impact of that investment in different types of regions based on a certain like population density. And then it would just be a relatively straightforward like optimization model for how you allocate that money each year.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   52:43  
Mm hmm.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   52:57  
To.  
Best equip or best provide security for as many people as possible, but that actually could be quite a nice Ave to go down.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   53:06  
That's. Yeah, I mean that that is quite useful, I think actually.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   53:11  
Yeah.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   53:14  
Partly because because of the way you've just described it, is is not traditionally how budget gets allocated in a way so, so that is providing new information that can be put alongside how budgets are traditionally constructed, which is more kind of demand driven like you know, how much have we given to each municipality before can they absorb this amount of you know it's it's with a different logic.  
So so there might be something, yeah, to be said for that as as a sort of set of information that could have impact with decision makers just because it's giving them a different perspective on how they should, how they could be thinking about.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   54:00  
The nice thing about that.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   54:00  
Resource allocate, whether it's budget allocation or actual water allocations. You know the the resource itself and how it gets, because that's also clearly having.  
You know, there's clearly a growing competition over a very finite volume of water, and there's demand from different urban there's like Cape Town as the Big city urban centre. But then these growing kind of towns, large towns and servicing their needs.  
And then a very water intense agricultural sector that operates in and around these towns. So it's like that's what's happening in between.  
All of these urban nodes is pretty water, intense agriculture, and so the strain on the allocation of that resource is just like being ratcheted up and up and up because there's lots of pressure to to grow the economy, which is partially based. And I should say, I mean, the other big factor in Cape Town that again, I mean, there's a bit of a curveball, but is is tourism like the other?  
Massive growth area, which which is being promoted because there's lots of jobs attached to it.  
Is tourism so like holiday visitors, which are basically hotels and guest houses going up, which are also, yeah. And then kind of confront like, work tourism so big, you know, conference facilities like and this movement of visitors in and out of the city on top of like the the residential growth of the city and this. So I don't know how that plays, you know, whether you can explore those sort of tensions and trade-offs around.  
Yeah, like either land allocation and or water allocation.  
Between so. So it's not just seeing growth as any kind of growth. It's like these different kinds of growth that are competing for the same space and the same physical resources. And then how like how do, if you let tourism grow unchecked, what does that mean for the residential sector or vice versa? Yeah, I mean it's.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   56:13  
Well, that that could be a more interesting like that again brings this whole like morphological programming stuff back into focus because it's then like a better analysis it if it were a sort of like cellular automata model with a transformation matrix, you're effectively tampering like the probability that each cell turned into a hotel rather than like a house for example. And then.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   56:20  
OK.  
OK.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   56:37  
What kind of impact? I guess that has on, I mean I could look at it from a water standpoint or maybe wage inequality or like one or the other key metrics that.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   56:45  
I mean water demand, like trying to see how the changing size and shape and density of Cape Town translates into water demand.  
That could that could be very interesting and impactful in a way, because it it would then talk into. So it would be like how's the yeah, the the changing morphology of the city translating into.  
A changing demand profile because in a way very basic assumptions are made around.  
Almost just like percentage growth, oh, water demand is growing at 5% a year. Oh, we thought it was going to be 9% a year. We've managed to slightly constrain it through demand management measures, but it's like a super crude estimate of what that.  
Growth in need for supply is.  
So if you could offer into that whole area of literature, like actually a much more nuanced set of projections around, well, we know that hotels.  
On average have this, you know, volume of water per square metre whatever as compared to a suburban house as compared to a block of residential flats as compared to a light industry. And if you look at the city 'cause, then you're also being able to say not just like total the city's growth as demand the the city's water demand is growing like this. But you're actually saying within the city like this area.  
A lot of that growth is likely to be in this area because we're seeing a conversion from this to that or whatever, I mean.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   58:20  
I like that direction a lot actually.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   58:22  
That would be super useful.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   58:23  
Yeah, yeah, I think I might. I think I might go down that Ave.  
Yeah, great.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   58:28  
Cool. Good. OK. Well, let me know how you go. I need to run, but yeah, if it's useful to circle back.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   58:33  
Yeah, yeah. I didn't want to run over too much.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   58:38  
On anything specific, but yeah, have a look. Have a look at the water outlook and have a look at the spatial development.  
Frameworks and plans that are all on the city's website like that will give you a good insight into like what the water, the bulk water, people to supply and demand are thinking about in the water space.  
And it'll give you a good flavour of what the spatial planners are thinking about, like when they trying to workout and influence how the city's growth and densification is going and what's cool is if you could like those two generally operate in their separate logics and.  
If you could, if you could, through your modelling, effectively create a bit of a bridge between those two conversations to say like, hey, you know, this is how those two things play out between each other.  
That would be very useful.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   59:35  
Yeah. Amazing, right. Yeah. I don't wanna keep you too long, but you've been a massive help. Thank you very much.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   59:38  
True pleasure.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   59:40  
If I have any other more, any more questions would you prefer I e-mail them to you or I mean I get the impression you might not be around in the next couple of weeks for another call. So if if you're happy to answer any emails, that'd be that'd be great.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   59:54  
Yeah, yeah, yeah. No, it's fine to drop me an e-mail. I like we rushing. You know, as we have our summer Christmas break. Like middle of December to middle of January. So it's kind of an intense like we all just kind of head down trying to finish all of the accumulated things we should have done throughout the year that are now need to be done before the year ends and and our our academic year also runs. So we've got like a whole lot of postgraduate students trying to submit their draught PCs because they want to hand in before the new year starts.  
Re. Register. So it's kind of a crazy like if you're interacting with anybody in this environment like just know that that's the that's the circumstance into which you're communicating. The same is true for the, you know, the government officials and like, everybody's just desperately trying to hold on and wrap things up till they collapse in a heap for the summer holidays. But but I'll do my best to to respond if as much as possible.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   1:00:50  
Yeah, that's all right. Yeah. Anything you can.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   1:00:53  
Come back again in January like then it'll be like, OK, Foof, we like slightly regrouped. Maybe we can help more.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   1:00:56  
Yeah, I'm free now.  
Yeah, alright, perfect. Thank you. Anna, you've been a huge help. Yeah. Hope everything goes well.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif)**Anna Taylor**   1:01:01  
Cool.  
Yeah. Good luck with the next steps. Yeah. And and do keep me. I mean, I'm interested to see how it, how it pans out for you. So please do keep me updated every now and again.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   1:01:16  
Thanks.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image021.gif)**Anna Taylor**   1:01:16  
Cool, just kinda.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image018.gif)**Templeman, Conall**   1:01:19  
Right.

![](file:///C:/Users/conal/AppData/Local/Temp/msohtmlclip1/01/clip_image022.gif)**Templeman, Conall** stopped transcription

### Further Research
