Introduction
------------
Recently I have started working for a new company, which included going through a training process for entering the R&D department. At the end of it I was requested to give some feedback, but while going over what I have been through it got me pondering about "what makes a training process a good one?" for the trainee and trainer (the employee and employer) and what is a “good training process”. So I tried to think about all the previous training processes that I have been through or had the chance to design by myself, and I have come to several observations about what worked for me (or didn't) and what seems to work for others from my perspective.

“Good training process” what do you mean?
-----------------------------------------
Before getting to what is contained in a "good training" we need to define it's goals, we won’t be able to tell whether we are heading the right way.
And well this’s a pretty hard question to answer, when you think about it and also a very subjective one. So let’s start by looking at a simpler question of what do we want to gain from a training process.
As I see it the big picture targets are:
* Gain an effective team member, which means that they can handle any task that you would normally give (from the first second after the training of course). While in realistic perspective, it will probably take them more time to complete than an experienced team member.
* The training process should happen in the shortest time frame possible (for obvious reasons).
* Gain a team member socially wise, we want the new person to fit in because that will help to make the workplace nicer to be in. Which will likely improve collaboration and in turn could improve productivity.

In most cases from my experience, most people will not reach those high in the sky goals after any training. Because of several reasons:
* People don’t like long training, so they tend to rush to finish the tasks even if they don’t finish just to mark it as done and to make a good impression at the new company/team.
* People cannot remember everything that they learn in the training, and in most cases, the important info to remember is not pointed out to them or what they should not remember.
* Set clear and transparent goals for the training from the trainee, like gaining basic knowledge in a new language vs learning specific X number of topics in that language, not clear exercise (like giving an exercise to write an HTTP server that does some logic, but the trainee spends most of the time to raise the server rather than focusing on writing the logic). NOTE to self: this point needs clear examples that will make the point.

As I see it, these should be what the trainee gains from the training process:
* Knows where to look for info, and not just his closest team member.
* Knows who and how to ask questions (TODO: probably not relevant because this is not important in the training level).
* Understand the team’s code flow, for example when giving a bug knows where to start looking (which could be the wrong place).
* Can do simple tasks, quick wins, grunt work at least.
* Can understand team design docs.
* Knows what is the basic workflow in the team, for example, scrum and things alike.
* Feeling able and understand the motivation to keep the docs and training up to date.
* Takes initiative and feel safe to, passion is important.
* Ideally team member socially.

So after we figured out our more detailed goals from the traning process, we need to think and design what a "good training process" will contain. As I see it. the following observations are a part from any "good training process" that I have been through.

Training planning
-----------------
* Each training step should have a clearly stated learning goal, like "getting to know framework X" or "getting familiar with workflow Y (like updating a message schema)". This is important for several reasons:
  * For the trainer side, you would know what is covered in every step and manage it's coverage on it's target goal (very much like a unit tests' coverage). So you won't have duplication in your exercises (which equals to a waste of time), won't have unintentionally uncovered topics. Like a software project, knowing the current level of tests coverage and making it run more efficiently it will gain more positive results for you.
  * For the trainee side, they will know exactly what you are going to go through next on the training (which could peak their interest and maybe lead them to explore further by themselves, which is excellent of course). And should provide them a clear guidance on what to focus on and help them to ask more "interesting" (relevant) questions.
* Every training goal should have an exercise to showcase it, so the trainee will get his/her "hands dirty" and raise questions early on. Of course, one exercise can cover more than one goal, so you will not end up with a lot of exercises that will tire your hard working trainee.
* Different seniority levels require different knowledge levels, so design accordingly which could mean having more exercises or even totally different ones probably with the same core. This is for not "wasting" the time for the senior people with simpler exercises or get in too deep fairly quickly for less experienced people, this will probably simplify the training and shorten it. This can also mean in lesser need to monitor the trainee or asking them different questions for seeing what they learn.
* Allow trainees to do things in their own style, like doing tasks linear or in parallel, learn by visually/reading/writing of course as currently possible. So they could start to see how their work style will fit in the team (or not, which could mean for them to find a way to adapt to it).
* The training process mostly should be a self serve with the buddies support (see the clause about buddies later on), this is very important for serval reasons:
  * This will allow some degree of independence to the trainee, and as we talked about earlier they could do the exercises in their own style or maybe peak their interest to explore. And of course will lower the loud on the trainer, because allegedly everything is written down.   
  * This forces you to maintain all the training material in some form of writing and not in the mind of a specific trainer (better bus factor).
  * Allows to also expose the entire training to the all company and get constant feedback from them, because they know pretty much what goes on in the training (of course there could be some variance). And maybe manage training material update as merge requests, which can help immensely in my mind.
* In case of more than one person (trainee) in the process Ideally in the same or close stages, you should try to create a group environment if by setting them together or even fun activities special for them. This is beneficial for serval of reasons:
  * This will contribute to a more fun process (having someone that is going through the same things is prone to inside humor, which is mostly funny).
  * In case the trainees will go to different teams in the company, which could help to spread knowledge across the company ("I just heard from Bill that they have started to use framework X in their team and they are very impressed from it") of course this should not be the single mean of sharing knowledge in the company.
* The total sum of the current observations is to show the trainee a clear roadmap, and Ideally with a range of time for each task so they could raise a flag that they need help and for the trainer to ask what's up. Ideally by this, they will learn that it’s ok to raise a flag in the culture of your company/team and how. And also people tend to think that they are underperforming although they are on track.

During Training
---------------
* Basic code examples - reduce the amount of boiler code, for example, there is no point to make someone write an HTTP server from scratch. Choose what you want the trainee to learn, maybe go through the template
* Check-in with the trainee to see it’s progress via the buddy or the instructor, but in a longer period (so the trainees will have a chance to complete tasks even small ones, and feel they are making progress) to accustom them to a company normal team workflow.
* The trainee at the end of the training should learn where to look (google, wiki or the person next door) and how+when to choose which one.
* Using as much as possible prod development standard (and probably you should have one :) ) in every ex, toy ex are not interesting and will slow the progress
* If you have a code style in use, it should be applied from the first second. If a trainee can go to several teams in the company that has different style guides, in my view don't put the little mistakes on focus because it's a matter of opinions (Ideally this should be a cross company *one* standard from internal mobility concerns).
* *Everything* should be in the Wiki, constantly updating it which means that every time someone needs information will look firstly in the wiki, if there is none then ask and update the wiki himself/herself or open a task with priority high.
* Training instructor, buddy, the "go to person" for question (for any kind, social or technical) does not have to know everything but can point to the right place to seek answers. So it's important to choose the right people in terms of knowledge and character for the success of the process.
* Incorporate as much as possible production “real” tasks as a part of the training in service of the ideal of "first day an effective team member".

After Training
--------------
* Learning from first hand experience trainees, team members, buddies, and team leader at different time points (For example, at the end of the training and after six months), so you could see:
  * What was relevant or not to learn, in the sense that the trainee had used it at least more than once after the training of course this depends on when you check in with the trainee. I recommend after a period of six months to check in and see their feedback, because if the trainee only used some training subject once it's a sunk cost because that knowledge will be lost over time. That could happen for a couple of reasons:
    * The subject was too advance and you preferred to be done by someone more senior in the team, so it's a good inductor that you can not include that subject in your training.
    * The subject needs to be handled once in a blue moon, so it could be a good idea to invest time to automate it completely.
    * And of course just a matter coincides, so always take into consideration the circumstances.
  * What was not enough, overlocked, or needs to be preserved as is- well this is a very hard meter to gauge, but the best effort in my mind is to try to understand this from the feedback from all stakeholders. This could help what to filter out or beef out insight of our main goal to get a productive team member at the end of the training. By asking the following questions:
    * What was hard and what was easy.
    * What the trainee needed more to hold his hand and what less.
    * What to took more the original estimations by the trainee and the team leader (or other team members).
    * What was different from the actual team's practices, which could mean wasting time to unlearn something by the trainee and not learning something new.
  * Always improve the training cycle, because "the only constant is change" (not my quote, but believe in it fully) which comes to expression by for example changing training plan and the actual trainees' background which is not the same.

Conclusions
-----------
I don’t think there is a silver bullet, like everything in the programming world there is more than one way to do things (and that’s what makes this fun and interesting to do :) ), but I think there are a couple of basic big ideas that will increase the chances for a successful training process according to your view:
* Design the process, as a whole down to basic exercises (the knots and bullets), insight of your training's goals.
* Manage your goals down to earth, down to the level of achievable targets, and leave room for surprises.
* Always take feedback from trainees and other stackholders (team leader of the trainee, team members, and buddies) and try to improve.
Let me know what you think.

Until next time :)
