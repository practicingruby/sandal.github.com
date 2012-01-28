---
title: Reflections on how I teach
category: essays
layout: main
---

## {{ page.title }}

<hr>

Figuring out how to improve the way that we teach at Mendicant University is a constant challenge for me, especially given my lack of formal teaching experience. But as luck would have it, [Greg Wilson is teaching a free course at P2PU](http://p2pu.org/en/groups/how-to-teach-webcraft-and-programming-to-free-range-students/content/getting-started-some-things-to-read-some-things-to-think-about/) that directly addresses the problem of teaching programming outside of the traditional classroom setting. Since that is exactly what I'm trying to do, I signed up for his class in a heartbeat.

The first task for the course is for students to reflect on their own way of teaching and compare their methods to [a set of researched-based educational best practices](http://ies.ed.gov/ncee/wwc/practiceguide.aspx?sid=1) outlined by the [Institute of Educational Sciences](http://ies.ed.gov). While the practices outlined by the IES are primarily targeted at K-12 education in a traditional classroom environment, several of them seem universal enough to be worth thinking about in a wide range of educational settings.

The main concern I have about comparing the practices that the IES outlined to what I've been doing is that to the best of my knowledge, our style of teaching is not directly comparable to anything else out there. Mendicant University's courses are entirely project-based and discourse-oriented. Our core method of teaching is to provide a handful of extremely open ended challenges at the start of a session, and then provide continuous feedback as our students attempt to build several real (or at least realistic) programs. Our courses are only three weeks long, but the typical student is expected to spend 15-20 hours a week of dedicated practice during that time. This is only the tip of the iceberg when it comes to what makes us different, but it should give a rough sense of how far we've deviated from the traditional model of classroom learning.

However, if I tilt my head sideways and stretch things in places, I can see at least tangential connections between what the IES recommends and what we actually do. There are also areas where we are struggling that might be improved by introducing some of these practices. For that reason, it makes sense to work our way down the list and see if and how the [ideas outlined in the IES report](http://ies.ed.gov/ncee/wwc/practiceguide.aspx?sid=1) apply to Mendicant University's context.

**1. Space learning over time**

A downside of running a three week course is that no matter how much you try to introduce things at an even pace, everything still ends up blending together. Our weekly checkpoints do provide a bit of opportunity for spaced review in the sense that if we see a problem resurface in the second or third week that we originally discussed with the student in the first week, we can try to address it again from a different angle. But three weeks isn't a whole lot of time for a student to internalize the concepts we're trying to teach, and so we don't get the benefits that long-running courses might get from this practice.

To address this issue, we may be able to run follow up courses that build on and review the concepts that we focused on in our core skills course, but our volunteer staff is not nearly well equipped enough to do anything like that right now. 

**2. Interleave worked example solutions with problem-solving exercises.**

Because the courses we run are project-based and very open-ended, its somewhat hard to provide well-defined "worked examples" that would map onto the problems students are dealing with in their projects. However, many issues do come up in student projects that can be addressed by pointing to a bit of open source code or an article that deals with a related problem or concept. 

Our continuous feedback process makes it pretty easy to identify problems students are having and allows us to quickly point the student to relevant resources that may help them. Common questions from our students are often answered in my subscription-based journal [Practicing Ruby](http://practicingruby.com), and as that library grows, it becomes easier to share bits and pieces of information with students that allow them to compare their own problem to a similar problem that I've analyzed and worked through myself. This resource is so important to our sessions that it's one of the main reasons why it's so easy to share links from Practicing Ruby with non-subscribers: I use these materials in our courses constantly.

The real issue is that many of the problems students are trying to solve fall outside of the nicely packaged set of examples that we've been compiling over time. This is to some extent the nature of the course, but is a real challenge that we face because of the fact that we use open-ended problems and do not re-use problem scenarios from session to session. Some of our best learning comes from this "off the map" phenomenon, but it is also consistently the greatest source of frustration for both students and staff.

**3. Combine graphics with verbal descriptions.**

Our courses are entirely text-based, with all communication happening through either our mailing list, IRC channel, or home-grown classroom administration software. This does make explaining certain concepts more challenging, and is something I want to think about improving if we can.

Our issues with Mendicant University are somewhat unique, given our ethical concerns. In our attempt to make our courses as universally available as possible, we have to consider things like folks with limited bandwidth, or censored internet access. We also strive to make it possible to participate in our courses using nothing but free software, both client-side and server-side. This makes multimedia presentations more challenging for us than they might be for folks teaching in other environments.

That having been said, I think that there are areas of our teaching that could be improved via the use of informal sketches or graphical slideshows/screencasts. If we used these materials as supplementary learning resources rather than making them central to our teaching style, we might be able to produce a higher quality experience for those who are able to make use of these resources. This is an issue we'll continue to think about in the future, because it does seem like another weakness of ours.

**4. Connect and integrate abstract and concrete representations of concepts.**

Maintaining a balance between the abstract and the concrete is something I feel Mendicant University does well. While we have a bias towards concrete examples (i.e. programs that actually do something useful), we try wherever possible to help students recognize the deep structures that lie below the surface of our practical applications. We do this in both directions: starting with an abstract concept and asking students to apply it in a real program, and starting with a real program and discussing how some aspect of it relates back to an abstract concept.

In particular, I think that the open-ended prompts work well here. As an example, we have one exercise currently being worked on in the January 2012 session in which we've asked students to build applications which make use of [Markov Chains](http://en.wikipedia.org/wiki/Markov_chains) in an interesting way. We introduced the concept by simply sharing a link to the wikipedia article, and then encouraged students to study the concept together and each propose a project which made use of the construct in some way. Because our students do their work out in the open, they are able to not just relate the abstract concept to the single idea that they came up with, but also with a dozen other projects that their classmates came up with. Once the students have made signficant headway on their projects, we'll go back to the abstract concept in retrospect and be able to notice subtleties about it that weren't apparent at the onset of the course.

This practice in particular is one that I feel is absolutely essential for teaching students about software development. I'm hoping that we explore it in more detail during the P2PU session, and would be happy to share more of my thoughts on the topic if anyone is interested in hearing them.

**5a. Use pre-questions to introduce a new topic**

Asking warmup questions is something that we sort of do, but not in the best possible way. We provide a review of entrance exam problems for each of our students, and through that process, we do get an opportunity to talk with students about things like code conventions and architectural questions that will resurface during our sessions. However, our entrance exams aren't especially representative of the format and contents of our courses. We can probably do a better job at coming up with an interesting set of warmup questions which strike more at the core of the topics we plan to emphasize on during our courses.

This practice is one that we simply haven't implemented formally because I've never really thought about doing it. That means that it'll be easy to introduce and experiment with, and definitely sounds like something worth trying. I'll see if I can incorporate this into the next session we run in some way or another.

**5b. Use quizzes to re-expose students to key content.**

We don't have any formal quizzes or tests, but we do have informal and formal reviews at various intervals throughout the course. During these reviews, we continue to emphasize things that may have been brought to light in early stages of the course, but mostly expect students to avoid repeating similar mistakes in their successive reviews.

This is one area in which teaching online in a purely text-based environment may actually serve as an advantage. It is harder for students to forget issues that we pointed out, because they can always revisit their old reviews before submitting new work for review. However, even in the span of three weeks, it seems like students are only able to keep track of a limited amount of information. For this reason, we've found that we need to be a bit more careful about what issues to emphasize and focus on.

One idea we have for addressing these issues is to write up summarized reports of the problems we've unconvered in our weekly checkpoints. This would allow us to focus on important issues that are shared among several students, or issues that a single student seems to continously struggle with. In the past, all of our feedback has been greatly individualized and focused on a single review at a time, so it'll be interesting to see what this aggregation process will do for us. It may even be possible to use this report as a basis for coming up with something like a mid-session review quiz, based on the key concepts students seem to be struggling with.

There is probably some room for improvement here, though we'll need to make a philosophical adjustment to introduce testing into our courses. So far, we've done everything through direct feedback and reviews, so it's hard to think of creating a formal test for our students to work through. But it seems like something that is at least worth thinking about if it has the potential to improve the effectiveness of our teaching.

**6a. Teach students how to use delayed judgements of learning to identify content that needs further study.**

Our process of providing on-demand feedback to students does to some extent allow the student to express when they feel they've mastered a certain set of topics and then get feedback from us as to what extent that is the case. However, the compressed nature of our courses makes it hard to draw any conclusions about how well we're helping students assess whether they've actually internalized the ideas rather than just learning them well enough to make it through an evaluation.

I suppose this is another limitation of our very short timeline for our courses, and I don't have any immediate ideas for how to resolve the issue. As I mentioned before, I could see followup sessions being a possible remedy for this problem at some point in the future, but we're simply not geared up for them at this point in time.

**6b. Use tests and quizzes to identify content that needs to be learned**

While we don't do any formal testing, our continuous feedback approach makes me feel that we do a good job at helping students identify what they need to learn. The average Mendicant University student interacts with fellow students, alumni mentors, and instructors several hours per week, and in that time is provided direct guidance about where to find resources that will help them meet the requirements of the course.

When we do our formal reviews, we provide clear explanations of what the student is not doing well, and recommend how to go about resolving those issues. The high degree of individualization that we do makes it possible for us to give targeted advice and guidance to students that wouldn't be practical in a traditional classroom environment.

To the extent that we don't use "tests" for this purpose, I think it's because we have the time and resources to do even better than that. The only discomfort I have with that claim is that I haven't yet found a way to evaluate/measure whether our approach is objectively better than formal testing for the goals that we are trying to accomplish. I hope to figure out ways to do that during the P2PU course, as it's a belief I currently hold that is solely based on anecdotal evidence. However, my personal experience has lead me to believe that our review process is quite effective at helping students direct their studying efforts.

**7. Ask deep explanatory questions.**

The entire experience of a Mendicant University session is discourse-oriented. This means that we do not only regularly ask questions like "Why?", "How?", and "What are the trade-offs between X and Y?", but that these kinds of questions form the bulk of the learning experience for our students.

We try to set a good example by asking these questions ourselves, but because this kind of investigation quickly becomes the social norm for our sessions, we end up relying on student and volunteer mentor participation just as much as our own prompting to create this sort of environment. The end result is that many excellent conversations happen, and the impact of those discussions are directly visible in the quality of the work our students produce during our sessions.

Our greatest challenge has not been getting students to engage in these sorts of discussions, but instead has been figuring out how to balance a spirit of deep investigation with an ability to stay on task. Some of our conversations spiral out of control, and leave us out in the weeds pursuing topics that are interesting but not especially relevant to the main topics we want to focus on. The benefits of this practice seem to outweigh those drawbacks, but careful attention needs to be given to this issue.

This is another one of the practices I think ought to be central to any software development education program. I'm looking forward to hearing what the other P2PU participants, as well as Greg Wilson, have to say on this topic.

**Reflections**

All in all, I think Mendicant University embodies some of the IES recommended practices while ignoring or failing to integrate others effectively. To some extent, the patchwork relationship to these practices is because Mendicant University is a weird, experimental, and messy program that I've found hard to relate to other common methods of online education. Then again, that's the view from inside the walls, and perhaps I'm overstating just how unique we are.

The reason why I am participating in Greg Wilson's P2PU session is to get some exposure to how other folks are doing things, with the hopes that I'll be able to bring some fresh new ideas back to Mendicant University. I'd also be happy to help others try out some of my own ideas, if they are interested in them. But in the end, what I really would like to see is a way to measure the benefits of these practices that isn't hand-wavey and based solely on anecdotal evidence. While I feel the IES report is great because it seems to address these issues in a fairly rigorous way, I feel like my extrapolations of these practices to Mendicant University's context are too much of a stretch to consider anything I've said here to be evidence based. 

Suggestions are welcome for experiments or quasi-experiments that I could conduct to test these ideas and practices. While I am confident that at least some of what we're doing at Mendicant University is effective in a measurable fashion, that's based solely on my intuition and makes it hard for me to judge how repeatable my results would be in other contexts. If you have an idea and are participating in the P2PU course, be sure to catch up with me via the course communications channels, otherwise feel free to [contact me directly](/discussions.html).

---

<p style="text-align: center; font-size: 1.0em">Written by Gregory Brown on {{ page.date | date_to_long_string }}. If you enjoyed this essay, please share it with your friends.</p>
