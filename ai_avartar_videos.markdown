---
layout: page
title: AI Generated Avatars
permalink: /ai-avatar-videos/
---

Never in my life has there been a faster moving field than Generative AI. As such, this content is current as of February 2025, and is probably old and irrelevant any time after that. _What LLMs struggle with today, they tend to be better at tomorrow._

As someone who produces educational videos for a living, this topic cuts a little close to home, and maybe that clouds my judgment. I do certainly have a higher bar than most as to what I consider "good enough" when it comes to the quality of AI-generated video, but the quality issue is one that will disappear with time. While today's models might still make videos that give people the heebie-jeebies, tomorrow's ones won't. 

So with that in mind, what are the plausible use cases in the now and near future of GenAI authored videos in higher ed? And how will do they work *today*, and how might they work *tomorrow* in this near future?

## 1: Lecture Content
When first coming to this topic, everyone immediately thinks "AI can replace my leuutres!". To me, this is the last place you'd want to use synthetic video - if you care about teaching[^1]. [Research abounds](https://staff.acu.edu.au/our_university/centre-for-education-and-innovation/educational-technologies/creating-video-resources/multimedia-design-principles) as to how we can make video-based learning more effective for student learning [(Mayer, 2024)](#references) and how we can use it to build social connection with the students, even in a one-way delivery mechanism like flipped classrooms. This is important to get right, and it's not something I'd trust to the synthetic videos of today. Gestures [(Li et al., 2019)](#references) can have a marked effect on learning, as can your tone [(Suen & Hung, 2024)](#references)] and your facial expressions [(Schneider et al., 2022)](#references). With synthetic video, you loose control of all of that and more. When you're explaining tricky concepts, the way you present can have a really big impact on how that information is perceived by your audience. 

Compare *Fake Jacob* and *Real Jacob* below. Which one do you think is the stronger or clearer delivery?

<iframe height="420" width="640" allowfullscreen frameborder=0 src="https://echo360.net.au/media/cb4ded53-86dd-487e-a165-592fccbb1bab/public?autoplay=false&automute=false"></iframe>
<iframe height="420" width="640" allowfullscreen frameborder=0 src="https://echo360.net.au/media/9cf93d6f-f0fd-48b7-98f5-71c984df19e8/public?autoplay=false&automute=false"></iframe>

On an infinite timeline, these models will get better, and the presentation style of the avatars will improve. They'll lose the ['uncanny valley'](https://en.wikipedia.org/wiki/Uncanny_valley) stigma, and be indistinguishable even to ourselves. But will they ever understand your domain to the extent that they can explain it better than you? Well, probably, but just how soon I guess depends on your skills as an instructor. But if you're a teacher at heart, why outsource the actual teaching? Here's what happened when I fed my PowerPoint to an AI video generator:

<iframe height="420" width="640" allowfullscreen frameborder=0 src="https://echo360.net.au/media/f95ec5d1-313a-484f-8ff1-6c6b08fd0306/public?autoplay=false&automute=false"></iframe>

For now I give synthetic video 2/5 stars for creating lecture content.

## 2: Student Feedback
One thing that my avatar can do that I cannot is scale. I only have so much time in the day, but if I can mass-produce some scripts for my avatar, I can happily generate as many videos as my wallet can bear. I tested this by having Claude 3.5 generate feedback scripts for my third-year education essay. Compare the AI-generated feedback with my lecturer's actual feedback:

<iframe height="420" width="640" allowfullscreen frameborder=0 src="https://echo360.net.au/media/1f8748bc-c8dc-4db6-a1e2-e24a95e67f52/public?autoplay=false&automute=false"></iframe>
<iframe height="420" width="640" allowfullscreen frameborder=0 src="https://echo360.net.au/media/b77feea5-05e7-486d-a241-14eba9d893d3/public?autoplay=false&automute=false"></iframe>

Here's a video of me, directly addressing the student, giving feedback on an assignment. This seems like a great use of this tech, right? Timely personalised feedback  (whether augmented with GenAI or not) is _fundamental_ to student learning [(Hattie, 2012)](#references), but is this the best way to get it across?

In this instance, I believe that video here is _not_ the better medium for this sort of feedback. While the presentation and tone perhaps could soften some critical feedback, ultimately its just a more time-consuming way to communicate the same feedback to the student. It's not, in my opinion, inherently superior to written feedback, and instead it cost me hard cash and probably increased global temps my a miniscule amount.

## 3: Custom explanations
Imagine you've just watched a micro-lecture, the video was engaging and helpful, but you don't fully understand the concept being taught. You wish you could ask your lecturer, but it's 10pm and no one else is active on the forums. Imagine you could type your question into a form on Canvas, and 5 minutes later your phone pings and there's a short video answering your exact question from your lecturer, that was generated by a LLM while they slept. Is this heaven?

Well, it could be. Here's what happened when I asked ChatGPT to explain a concept and fed its response to my video generator:

<iframe height="420" width="640" allowfullscreen frameborder=0 src="https://echo360.net.au/media/13bca053-6b4d-493f-b6f8-93b05898a565/public?autoplay=false&automute=false"></iframe>

Now, while this might be cool, I'd ask: is it any better than just giving the student the written text? Today, this is just a lossy way to transmit the information, like taking a bad photocopy of a hand-written paragraph. In the future the video presentation might be flawless, but is it actually _adding_ anything? 

You could scale this up to make an agent that answers questions about assessments (due date, extension policies), or timetabling, or other administrivia that often bogs down LICs. But again, today, you have the choice of almost immediately giving them a written response, or making them  wait to see a crappy video giving them the exact same information.


## 4: Translations to other languages
Combining synthetic video with machine translation seems like a great opportunity, students can hear what we have to say in their native tongue. But in actuality it creates two layers of potential errors. While students might benefit from hearing content in their native language, complex domain-specific concepts often lose meaning in translation [(Yu et al., 2024)](#references). This idea has potential, but we're not there yet - try running a complicated domain-specific concept full of unique vocabulary through Google translate, and see what comes out.

Unfortunately, unless I'm willing to cough up "enterprise money", I can't test this with that platform I'm using.

## 5: Demonstrations
Generative video is the cool new thing, building on the work of generative imagery and putting it in motion. While there are certainly some cool things you can do with it, for the purposes of teaching, and specifically demonstrations, I doubt this type of language-prompted tech will _ever_ be good enough to fully replace real demonstrations. My reasoning comes down to the source material these things are trained on. 

Consider an IV canulation, and the specific techniques taught at ACU to student. I've filmed demonstrations of these for both Paramedicine and Nursing degrees, and the details are pretty intricate. Unless a generative model has been trained on these videos in particular, it won't ever be able to understand the concepts of flash-back, or the precise angle required for the needle, etc. While it will excel at producing the generic and the common, it will always struggle with the hyper-specific, and with people's health on the line, it will be a _long_ time before it can confidently be used in this way, if ever.

****

## The cost
To generate the videos above, I used [Synesthesia](http://synthesia.io). To get 10 minutes of generation, I had to 
* upload a three minute video of myself talking, along with a separate video with myself reading a unique 'consent' message
* pay $29 USD (about $50 AUD) each month to get a mere 10 minutes of total video generation, and
* agree to let them use my 'biometric data', though I have the option of requesting it be deleted when I cancel my subscription

So in terms of scalability today it's still pretty expensive, though tomorrow the cost could drop dramatically.

## TL/DR
As of today, I think synthetic video isn't worth the effort in higher-ed. It generally results in a sub-par experience to simply reading the text you fed it in the first place, whether that is hand-crafted text or something from an LLM. That said, the quality is only going to improve, and we may hit an inflection point in the coming years where it is _good enough_ to use in some instances.

****

## References

<ul class="references">
    <li>Hattie, J. (2012). Visible learning for teachers: Maximizing impact on learning. Routledge.</li>
    <li>Li, W., Wang, F., Mayer, R. E., & Liu, H. (2019). Getting the point: Which kinds of gestures by pedagogical agents improve multimedia learning?: Journal of Educational Psychology. Journal of Educational Psychology, 111(8), 1382–1395. <a href="https://doi.org/10.1037/edu0000352">https://doi.org/10.1037/edu0000352</a></li>
    <li>Mayer, R. E. (2024). The Past, Present, and Future of the Cognitive Theory of Multimedia Learning. Educational Psychology Review, 36(1), 8. <a href="https://doi.org/10.1007/s10648-023-09842-1">https://doi.org/10.1007/s10648-023-09842-1</a></li>
    <li>Schneider, S., Krieglstein, F., Beege, M., & Rey, G. D. (2022). The impact of video lecturers’ nonverbal communication on learning – An experiment on gestures and facial expressions of pedagogical agents. Computers & Education, 176, 104350. <a href="https://doi.org/10.1016/j.compedu.2021.104350">https://doi.org/10.1016/j.compedu.2021.104350</a></li>
    <li>Suen, H.-Y., & Hung, K.-E. (2024). Enhancing learner affective engagement: The impact of instructor emotional expressions and vocal charisma in asynchronous video-based online learning. Education and Information Technologies. <a href="https://doi.org/10.1007/s10639-024-12956-w">https://doi.org/10.1007/s10639-024-12956-w</a></li>
    <li>Yu, S., Henderson, M., & Dang, T. K. A. (2024). Challenges for being self-directed in content and language integrated learning with instructional videos. ASCILITE Publications, 147–155. <a href="https://doi.org/10.14742/apubs.2024.1224">https://doi.org/10.14742/apubs.2024.1224</a></li>
</ul>

****

[^1]: This might be seen as a pejorative statement, but for many academic staff teaching is an required component of their job, not something they want to do.

