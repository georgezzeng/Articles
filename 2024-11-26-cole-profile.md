---
short title: "A Spotlight on Cole Bollig"
title: "A Spotlight on Cole Bollig: Finding CHTC, Community, and Learning HTCondor"
author: Ria Dhingra
publish_on:
- chtc
- htcondor
- osg
- path

canonical_url: https://chtc.cs.wisc.edu/cole-profile.html

tag:
  - chtc_featured_article

image:
  path: "https://raw.githubusercontent.com/CHTC/Articles/main/images/cole/cole-card.jpg"
  alt: Image of Cole
  
type: news
excerpt: |
  "As a software developer, I could be working at a large tech firm or at Facebook or Google to create a new obscure feature that a few people interact with and feed the pockets of millionaires. Instead, I’m helping the scientific community. It feels awesome, important, to be a part of something like that" -Cole Bollig
---

___“As a software developer, I could be working at a large tech firm or at Facebook or Google to create a new obscure feature that a few people interact with and feed the pockets of millionaires. Instead, I’m helping the scientific community. It feels awesome, important, to be a part of something like that” - Cole Bollig___

<div class="row justify-content-center">
<div class="col-12 col-md-6">
<img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/cole/cole-party.png' class="figure-img img-fluid rounded" alt="Cole at party">
</div>
<div class="col-12 col-md-6">
<img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/cole/cole-hello.jpg' class="figure-img img-fluid rounded" alt="Fellows">
</div>
</div>

Graduating in the midst of a pandemic, Cole Bollig, like most young people, had to navigate the trials of finding employment. Hailing from Cross Plains, WI, Cole went to the University of Wisconsin-Whitewater from 2019-2022 and graduated with a degree in Media Arts and Game Development, with a Technological Emphasis.

Almost three years later, Cole is not only in the midst of his first semester of grad school, but he has been a valued member here at the Center for High Throughput Computing (CHTC) as an HTCondor Core Developer. Just this past Fall, Cole was one of five CHTC staff members to travel to Amsterdam for the HTCondor European Workshop despite being one of the younger members of the team. Cole is known around here for his Dad jokes, cargo shorts, his commitment to the HTCondor Software Suite tool DAGMan, and for organizing group CHTC lunches at UW-Madison nonprofit group, Slow Food.


This past week, I sat down with Cole to learn more about his story, from graduation to his first project and fixation: DAGMan, an HTCondor Software Suite (HTCSS) tool which assists users in automatically managing workflows of HTCondor jobs.

## Interview

R: Thanks for taking the time to chat with me today. So, I’m personally a recent graduate; I graduated this past May (2024) and went through the post-graduate panic of unemployment, a short barista stint, and considering grad school before I found this job here at CHTC. I know you’re also a younger member of our team. Tell me the story of how you went from graduation to working here at CHTC. What was that process like? How many places did you apply? How did you feel during all of it?



C: Well, first I graduated—yippie! Then I sort of went straight into applying for jobs after that. During that peak time, I was applying to maybe three of four places a day. Just sending stuff out; I was sort of in limbo for a little over half a year following graduation. Based on my degree and my interests, I really wanted to stay here in the Midwest, especially near Madison so I could still be close to my family and still continue to experience the four seasons. Initially, I was applying to all of the game studios in town here. Madison surprisingly has a decent number of them, including Raven Software, they work on Call of Duty. I applied basically everywhere, and didn’t hear back, you know how it goes *laughs*.



So, I decided to run with a backup plan. I had a minor in CS; I figured I could just do normal development. I ended up scoring this weird partial interview at an insurance company, which was just me video recording answers to questions instead of talking to real people. After that, I also applied to Epic.



R: As one does.



C: Right, as one does. I had a phone interview with them where they talked about how they wanted a full stack developer and all I could think during that call was: I don’t want to be a full stack developer. In the end, it was sort of a blessing I didn’t end up there.



Towards the end of the Summer, I got tired of filling out all these general applications, and I decided to slow down my rate and be more intentional towards applying to places where I thought the work would actually be interesting. When I was doing that, I saw a UW-Madison position here at CHTC. I had no idea what CHTC even was, but I trusted UW-Madison. They were looking for coders with C++ knowledge, and I really like coding in C++. So, I applied.



R: You mentioned in the past that you were surprised you got an interview here. How come? What was the interview and hiring process like here?



C: I have a degree that doesn’t exactly shout computer science, so I was ecstatic when I got an interview. Up until then, I hadn’t even had a real interview yet aside from that video thing and a phone call. It felt nice that this place trusted me and took a shot on getting to know me. Even if this didn’t go anywhere, it felt exciting to make it to that interview stage.



Originally, I was supposed to interview in person, but it was still the tail-end of peak pandemic times. So, we ended up having a zoom interview. It was honestly a bit nerve wracking. It was my first time doing an interview for a professional, full time, adult job. I was interviewed by three people, one of which is now my supervisor, another who is a close colleague, and another who subsequently left after I was hired, but who had five years of industry experience. And all three were watching me code–live! I didn’t even finish my coding project, they let me “do homework” and turn it in later that evening.



After sending in that homework, I was called back in for a second interview with Miron, the Director here at CHTC, I think this was less about discussing my qualifications more to deduce if I would be a good fit here at CHTC. Later, I got a call from Todd Tannenbaum, HTCondor Softwear Lead, and my supervisor, who offered me the job. I was so excited, I think I screamed and celebrated for about twenty minutes.



You just graduated with a degree, too, and we both want to do something in our fields; this, for me, really felt like the first step in the right direction.



R: So, you’ve been here just shy of three years, (congratulations by the way!), but backtracking a little to that first year: what was it like at CHTC as a HTCondor developer? Had you heard of HTCondor before?



C: Oh gosh. When I started I did not know what CHTC was, or what HTCondor was. It’s so strange to think that now, because I look at this code every day and think: this is over a million lines of code. Some of it is even older than I am! *laughs* No, seriously, there’s comments from my supervisor that are older than me. But those first few months were definitely a lot. I was a fresh graduate trying to prove myself. A lot of those early days were just learning. There is so much HTCondor can do, and I had to know that information on a technical level. I had to know not just what it can do for the user, but how to make that happen for the user. I think what’s always so interesting about being here is that no one developer knows all of HTCondor. We all just have this growing knowledge of it, we get an area of focus and learn to work on it.



R: What challenges did you face and how did you overcome them?



C: So it’s actually really funny. On my first day in the office, another developer, Mark Coatsworth, walks into my office to say hello to me. Mark was one of the people who interviewed me. So, he walks in and says, “Hey man, glad to see you here.By the way, I’m leaving in a couple months and you’ll be taking over my responsibilities. And I was like ”No!” *laughs*



R: Geez, that sounds like a crazy first day.



C: Yeah. But I mean I managed, I’m still here… So, I inherited a portion of code called DAGMan, this is a tool users describe their computational jobs to and it produces an ordered workflow.


<figure style="float: left; margin: 0 1rem 1rem 0;">
<img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/cole/cole-conf.jpg' height="420" width="300" class="figure-img img-fluid rounded" alt="Cole Presenting">
<figcaption class="figure-caption">Cole Presenting Dagman</figcaption>
</figure>

R: Yeah, I’ve been here a little over two weeks and heard from multiple people you’re really passionate about this project.


C: I think a lot about DAGMan, at this point I’m definitely a self proclaimed DAGMan expert.



R: *Laughs.* I noticed that! When I reached out to interview you, it was literally your Slack bio. But it makes sense now, you were assigned this on your first day, it’s like your mission.



C: There is an endless amount of work I want to do to DAGMan, but that’s true for all of HTCondor. It’s been a journey getting to know code, and then getting to know it at an intimate level. DAGMan is just the thing I got to know first.



So, in terms of challenges, I think it was just the learning curve. But that’s true anywhere. There was one circumstance where I programmed something to work, but I didn’t do it the proper way. We had to scrap the whole thing and start over, but mistakes are allowed here, especially when you’re still learning.



R: As a young software developer; how have you managed to find your place and community in a place like CHTC?



C: I think the tail end of the pandemic definitely affected my adjustment into CHTC socially. The first day I came in there were only 3 or 4 people in the office besides me. But, as more people came in, I think it was actually relatively easy. Especially in the developer team. We’re all a bunch of nerds, and nerds are easy to get along with when you put them in a room together. We joke, we mess around, we spend a lot of time just talking and working on problems in the hallways.

I think just getting out there and chatting is important. We play sheepshead at lunch on Fridays, we have lengthy conversations about minecraft. CHTC also has annual events like the OSG School and the HTC Week conference, which is also a great opportunity to meet new people.



R: What’s your favorite part about working at CHTC?



C: I overall really like it here! The coworkers, the organization, all of it is so gratifying. We’re an open source group, which means so many people can use us. As a software engineer, I could be working at a large tech firm or at Facebook or Google to create a new obscure feature that a few people interact with and feed the pockets of millionaires. Instead, I’m helping the scientific community. It feels awesome, important, to be a part of something like that”



Specifically though, one of my favorite things is the HTCWeek that we host here in Madison. We get to go and present all the cool stuff we are doing with HTCondor and then we get a lot of admin who come up here and talk to us. I love hearing users come in and tell us why they use HTCondor. And it’s so funny, a common thing you see is users who will do the math and tell you how much computational time has been saved by HTCondor. It’s so gratifying to sit down with researchers and see how me clicking away directly helps them do so many cool things.



R: You’re a grad student now! What was the decision process behind going back to school here at UW-Madison while working at CHTC?



C: I guess to start off, when I graduated, I had no desire to go to grad school. I got my degree and I got this job. Plus, I have learned so much just from working here. But, you know, I sat on campus for five days a week for two years…And kept thinking that I had this opportunity right in front of me, so I might as well take it.



My supervisor Todd Tannenbaum actually did the same thing; he worked here and continued school at

at the same time. So that idea had been stewing in my brain for a while. So, now I’m in a Professional Masters Program for Computer Science



R: How’s grad school going? How are you doing? As a recent undergrad, I know November almost always felt like the most brutal month.



C: Really well actually. I’m taking it all super slowly; I’m actually only taking one class a semester. Right now, that’s CS640: Intro to Networking.  Despite the program only being 30 credits, it will probably take me four or five years to get the degree. Which is fine for me because I’m still working here and in this for the long game.

R: On that note, What’s the future, the next couple of years, look like for you?

C: I can honestly see myself going to retirement here. I don’t like changing jobs much and I care a lot about what I do here. Personally, my goals are wanting to graduate, stay working here, and I’m currently saving up for a house. Project wise, there is so much I want to do with DAGMan alone. I want to improve how DAGMan parses workflow files provided by the user.I would love to be able to improve that process and make it more efficient. And that’s just one of many projects, There is no shortage of work or ideas or bugs or personal pet projects here.

<figure style="float: right; margin: 0 1rem 0 1rem;">
 <img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/cole/cole-nerd.jpg' height="420" width="300" class="figure-img img-fluid rounded" alt="Cole dressed up for Halloween">
  <figcaption class="figure-caption">Cole Dressed up for Halloween</figcaption>
</figure>

R: What are your hobbies like outside of work?



C: Well, not as much nowadays because I’m in school, but I was an avid gamer. I still game, just not as much. I’m also now a nerd with money, so I’ve been getting into retro gaming. Like, I’m in a position right now where I can drop more money than I should on an old pokemon game. *Laughs.* Why not? I also actually just finished purchasing my collection of handheld Nintendo devices.



R: That’s lovely. What’s something about you that you think people at work would be surprised to know about you?



C: Well, I’m really such an open book at work here. I’ve gotten to know people and let them get to know me. I’m just a social guy in this environment.



R: Right, I’ve noticed you’re pretty active on the Slack.



C: Exactly. So, something that’s not surprising about me is how many dad jokes and puns I make at work. I’m kind of known for it around here.



R: *Laughs* Well, thanks for taking the time to chat with me today Cole. I know you have class in about thirty minutes, so I’ll let you go.



C: Thank you and welcome to the team.