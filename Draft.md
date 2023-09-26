---
marp: true
theme: umbraco-theme
transition: fade .3s
---

<style>
    h1 strong {
        color: inherit;
        text-shadow: -4em -4em 0px rgba(255,255,255,0.1),
                     -3em -3em 0px rgba(255,255,255,0.2),
                     -2em -2em 0px rgba(255,255,255,0.3),
                     -1em -1em 0px rgba(255,255,255,0.4)
                     ;
    }
</style>

# How to **Copy & Paste**
Effectively working with strangers on the internet

![bg](images/52993360181_f7bded0189_k.jpg)

<!-- Awkwardly highlight the "copy & paste" joke -->

---
<!-- _class: invert -->

![bg left Joe](images/me.jpg)

## <small>Hello, my name is</small> Joe Glombek
Umbraco Developer at Bump
Umbraco MVP

- <i class="fab fa-fw fa-mastodon"></i>[umbracocommunity.social/**@joe**](https://umbracocommunity.social/@joe)
- <i class="fab fa-fw fa-discord"></i>glombek
- <i class="fad fa-fw fa-globe"></i>[www.**joe.gl**](https://joe.gl/ombek)

<!-- ## CFP

Since the dawn of Forums, CodeProject and Stack Overflow - and more recently with Our Umbraco, Github, Discord, Youtube and blog posts - we've been building applications with strangers on the internet, copying and pasting other developers' code. And now with the advent of ChatGPT, GitHub CoPilot and other AI solutions, it's easier than ever to use code somebody (or something) else wrote... without necessarily understanding the code completely. We all copy and paste code, but a senior developer will often approach the task in different way to someone more junior. We'll look at how to level-up our Ctrl+V game through understanding the problem, assessing suitability and adapting code samples to meet our needs. Together, we can build something better and quicker... so long as we know what we're building. -->

---

## Professional googling

We've all heard that software developers are just "professional Googlers" - the more senior you are is mostly a product of how good you are at Googling.

It's a great joke... but have you tried being a developer _without_ internet access? It doesn't feel like much of a joke then, does it?

But I don't see this as a negative. When we're isolated we might feel weak and hopeless but as a team - a community - we're quick and efficient problem solvers. And that's where the idea for this talk came from: how can we work together more effectively as a worldwide developer community without getting stung along the way?

---
<!--
_class: invert
_footer: Emma Burstow on Umbraco collaboration: [go.joe.gl/yt-collab-joe-paul](https://go.joe.gl/yt-collab-joe-paul)
-->

## We're not **competitors**, we're a **community**

![bg right:45%](/images/joe-and-paul.jpg)

<!-- 
This photo is from after a Umbraco festival in the UK, when me and Paul (from Codeshare, creater of the Clean Starter Kit) went back to our hotel.
The aim was to grab a snack and get some sleep, but we accidentally ended up fixing some bugs in the Clean Starter Kit together!

In an open source world, we're much stronger together.

So we shouldn't be afraid to ask for help, and to offer our expertise to others.
 -->

---

## Where to get help

<!-- Before we start with how and what to copy and paste, let's first start with some places we might find answers -  -->

### Google it first!

* <i class="fa-fw fad fa-books"></i>Documentation
* <i class="fa-fw fab fa-youtube"></i>YouTube
  **CodeSharePaul**, talk recordings, etc
* <i class="fa-fw fad fa-blog"></i>Blog posts
  Personal blog, **Skrift**, etc
* <i class="fa-fw fad fa-code"></i>Source code



![bg right:41%](https://assets-global.website-files.com/5f3c19f18169b62a0d0bf387/60d33bee9c10a5689cd5e64a_qPOubJQVFNBuF_cDqEwbRTw1cI-9dKzoZ8o18D2XtiOgi4pmoMudEBbHcICtDhwBZSY71CKKqOaaWPnkycOU-w24UtOo5M-z-lul9v78JvvUrHKbaKRHHIpE6Tx5WkALe5tIYnaK.png)

<!-- _footer: "[Image source: @VishalMalvi_@x.com (probably)](https://twitter.com/VishalMalvi_/status/1520026885626814464)" -->

---

### So you need to ask for help?

* <i class="fa-fw fab fa-stack-overflow"></i>StackOverflow - good for more generic development questions
* <i class="fa-fw fab fa-github"></i>Github? - some repositories have discussions or issues may be appropriate
* <i class="fa-fw fab fa-umbraco"></i>Umbraco Forum - specific to Umbraco
* <i class="fa-fw fab fa-discord"></i>Discord - specific to Umbraco
* <i class="fa-fw fab fa-mastodon"></i>Mastodon/X/Facebook
<!-- * <i class="fa-fw fad fa-robot"></i>AI -->

---

## *How* to ask for help

How can we ask for help in a way that's most likely to get the best possible answer?

* <i class="fa-fw fad fa-search"></i>Do your research *first*
* <i class="fa-fw fad fa-head-side-brain"></i>Comprehend the problem
* <i class="fa-fw fad fa-hands-heart"></i>Be polite and patient - nobody _has_ to help you
* <i class="fa-fw fad fa-tags"></i>On-topic and suitable (including tags, categories, etc)
* <i class="fa-fw fad fa-clipboard-list"></i>Summarize your problem
* <i class="fa-fw fad fa-code"></i>[Include a reproducible example](https://stackoverflow.com/help/minimal-reproducible-example)

<!-- We know this is good advice, because it's from StackOverflow. And if anybody is fussy about how you ask a question, it's them! -->

<!-- _footer: https://stackoverflow.com/help/how-to-ask -->

---
<!-- _footer: https://discord-chats.umbraco.com/t/15854045/solved-backoffice-in-block-list-show-image-name-in-label -->
### Let's look at an example

<iframe src="https://discord-chats.umbraco.com/t/15854045/solved-backoffice-in-block-list-show-image-name-in-label"></iframe>

<!--

Do your research: Read my blog post
Understand the problem:
Be polite: Flattery will get you everywhere! Friendly, sociable, "TIA"
On topic & suitable: Umbraco Discord, help-with-umbraco channel
Summarize your problem: Pictures! "I would like to..."
Reproducible example: Provided Umbraco version, media picker version, exact setup - I could do this!
-->

<!-- ---

> Happy Monday!
> In the backoffice (v10) I have a block list editor with image rows. That image row has an Image Media Picker, with the alias "image". I would like to show the name of that image in the block list editor's label for that row.
> 
> I have tried label values such as Image: `{{ image.name }}` and `Image: {{ image }}` but to no joy. Fields such as "caption" can be accessed happily though `{{ caption }}`, the problem arises because image is an Umbraco.MediaPicker3 and I'm trying to access the name of that specific piece of picked media (3).
> 
> I have scoured @Joe Glombek's EXCELLENT [blog post](https://joe.gl/ombek/blog/umbraco-angularjs-filter-cheat-sheet) but alas I am without results.
> 
> Please do consider helping a boy out on a cold, autumnal Monday morning.
> 
> TIA! -->

---

## Improvable question

This is someone's first StackOverflow question - it's not necessarily a **bad** question, but we could improve it.

![Title: "Implement SSO in ASP.NET MVC" Question: "How to implement a website with a list of application content, you can log in once on the first website and when you want to go to the second website, you don't need to log in again using ASP.NET MVC 5. I tried throwing params into the database and with this I was able to log in to other websites with just 1 login."](/images/question.png)

---

![Title: "Implement SSO in ASP.NET MVC" Question: "How to implement a website with a list of application content, you can log in once on the first website and when you want to go to the second website, you don't need to log in again using ASP.NET MVC 5. I tried throwing params into the database and with this I was able to log in to other websites with just 1 login."](/images/question.png)

* <i class="fa-fw fad fa-search"></i>**Research:** None clear. Did they already search for solutions? Why was this not suitable?
* <i class="fa-fw fad fa-head-side-brain"></i>**Comprehend:** Doesn't grasp key concepts of SSO
* <i class="fa-fw fad fa-tags"></i>**On-topic:** Is `navicat` an appropriate tag?
* <i class="fa-fw fad fa-clipboard-list"></i>**Summarize:** Unclear what the problem is and what solution they want.
* <i class="fa-fw fad fa-code"></i>**Reproducible:** Not enough information for me to build this myself and see how they're stuck.

---

How might we fix this?

> ### Using a self-hosted OAuth server with ASP.NET MVC
> I have an OAuth server configured ([using the AuthU Package with an Umbraco install](https://github.com/mattbrailsford/umbraco-authu)) and I'm having issues connecting with it from an ASP.NET MVC website.
> 
> I've tried registering the OAuth server in `Startup.cs`:
> ```
> services.AddAuthentication(...)
> ```
>
> But I get the following error:
> ```
> An Exception of type MadeUpAsAnExampleException was thrown...
> ```
>
> <i class="fa-fw fad fa-tags"></i> `asp.net` `asp.net-mvc` `oauth` `asp.net-identity`

---

## What about **AI**?

* <i class="fa-fw fad fa-mind-share"></i>**Our** programs and **our** code samples
* <i class="fa-fw fad fa-people-carry"></i>Effectively **built by the community**
* <i class="fa-fw fad fa-medal"></i>You need **the same skills** to effectively use AI as for human-generated answers


![bg right:30% 90% Animation of The Simpsons newsreader Kent Brockman on TV captioned "I, for one, welcome our new robot overlords.". The word "robot" is clearly superimposed.](/images/robot-overlords.gif)

<!-- We've been talking a lot about community and collaboration - so why am I brining up artificial intelligence? Is it because I want this talk to sound topical and modern? Well... yes. But only in part!

AI has been scouring the internet looking at _our_ programs and _our_ code samples. As I see it, AI is a tool built by the community. And it takes a lot of the same skills to effectively use AI generated code as it does to pick the right Stack Overflow answer. -->


<!-- **Introduce AI-powered code assistance tools like GitHub CoPilot and ChatGPT, highlighting their role in code creation and adaptation.** -->

---

### AI tooling

- <i class="fa-fw fad fa-bolt"></i>OpenAI ChatGPT
- <i class="fa-fw fab fa-github"></i>Github Copilot <small><i class="fad fa-badge-dollar"></i></small>

---

### What can I ask AI to do?

* <i class="fa-fw fad fa-play"></i>A **starting point** for:
  * <i class="fa-fw fad fa-comment-alt-dollar"></i>Regular expressions
    > Write me a regular expression for UK phone numbers
  * <i class="fa-fw fad fa-code"></i>Generic coding questions
* <i class="fa-fw fad fa-magic"></i>**Autocomplete** of common structures and repeating patterns
* <i class="fa-fw fad fa-chalkboard"></i>**Explaining** code samples and error messages
* <i class="fa-fw fad fa-transporter-2"></i>**Converting** from one format to another
  > Convert the following XML file into JSON

---

### When might I want to ask elsewhere?

* <i class="fa-fw fad fa-tachometer-alt-slowest"></i>Poor understanding of performance
* <i class="fa-fw fad fa-sparkles"></i>Understanding versions
  - Old Umbraco vs Umbraco 9+
  - `WebClient` vs `HttpClient`
  - Which type of controller you're using 
* <i class="fa-fw fad fa-sync-alt"></i>Often inverts boolean logic?!
* <i class="fa-fw fad fa-edit"></i>Can struggle with modifications
  > Write me a regular expression for international phone numbers
  > Don't people in the US often hyphenate their phone numbers?
* <i class="fa-fw fad fa-hand-holding-magic"></i>Makes things up

<!--

Makes things up: AI will rarely tell you that you can't do something. It will generally make up ways you can... even if those ways are not possible and use API methods that simply don't exist.
-->

---

TODO: AI examples

---

So, you've asked a question and got an answer. Now we need to know...
## How to Copy & Paste

<!-- _footer: "🎉 *(Roll credits...)*" -->

---

<!-- _class: invert -->
We've established AI can be wrong.

## AI learns from **people**,<br> People are **wrong too**.

---

## Copy-Pasting vs. Understanding

* Computer or robot, we need to **understand** what we're copying into our projects.
* We don't need to understand every intricacy of the code, but we should have an idea line-by-line what it's doing

<!-- **Discuss the importance of understanding copied code versus blindly pasting it, emphasizing the role of comprehension in building better applications.**

**Explore how junior and senior developers approach code copying and adaptation differently, showcasing the importance of experience and expertise.**

**Discuss the goal of building better applications by improving the way we utilize copied code, emphasizing comprehension and adaptation.** -->

---

TODO Example of complex code sample

---

## Assessing Suitability of Code

<!-- - **Discuss the importance of evaluating the suitability of copied code for your specific application.** -->

---

## Adapting Code to Meet Needs

<!-- Explain how to effectively modify and tailor copied code to meet your application's requirements -->

---

## Considering Performance in Context

- Title: "Performance Matters: Code Context and Frequency"
- Discuss the importance of considering performance based on the context and frequency of code execution, highlighting the difference between code running once a day versus code running 100 times per second. 

-  apply these strategies for more effective code usage and application development.