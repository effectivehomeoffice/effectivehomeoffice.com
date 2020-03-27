# Effective Home Office

An opinionated guide to effectively work from home.

![Effective Home Office](images/header.jpeg)

We've written this guide because we got asked the same questions (e.g., [which microphone should I get?](#microphone) or [which software should I use for video conferencing?](#video-conferences)) over and over again, and we wanted to have a place where we could direct all those people to.

Instead of providing yet another long list of tools, this guide contains a short, curated selection of things that worked well for [us](#authors) working from home.
Everything is our own and honest opinion, and reflects our preferences, dislikes, and priorities.
But as we all know, everybody is different. 
So follow this guide with caution. 
Still, we do hope you can find one or two things that improves your work from home experience!

Feel free to reach out to us on Twitter with hashtag [#effectivehomeoffice](https://twitter.com/hashtag/effectivehomeoffice) or via email at [hello@effectivehomeoffice.com](mailto:hello@effectivehomeoffice.com) for questions, comments, praise, or critique.

## Microphone

Nobody wants to wear a headset all day.
Sadly, common integrated headset-free solutions in phones and notebooks let every listener suffer from bad audio and lots of noise.
To have happy listeners instead, get a podcaster microphone with directed antenna and noise-cancelling capabilities.
We recommend the [Blue Yeti](https://www.bluedesigns.com/products/yeti/) ($129). Set it to cardioid mode.

## Headset

Don't use a headset. 
If you really have to, get the [Jabra Evolve 65](https://www.jabra.com/business/office-headsets/jabra-evolve/jabra-evolve-65) ($180), or any other of the [Jabra Evolve](https://www.jabra.com/business/office-headsets/jabra-evolve) family that fits your wearing preferences. 
For occasional calls the [Apple AirPods](https://www.apple.com/airpods/) are just fine.

## Webcam
Make sure to activate your webcam and look directly to each other in video conferences.
For that, [the webcam must be on eye-level](https://effectivehomeoffice.com/webcam-position/) (or slightly above).
This rules out your laptop's built-in camera as it's mounted too low.
Instead, get an external webcam and mount in on top of your primary screen.
We use a [Logitech C920](https://www.logitech.com/en-us/product/hd-pro-webcam-c920) ($79).

_Corona-Update: As the Logitech C920 and C922 webcams are currently out-of-stock everywhere: 
The camera model itself is not super important. 
Any webcam should work. 
And in the meantime it is totally fine to use your laptop's built-in camera.
Anyway, try to look directyl to each other in video conferences._

## Monitor

Don't work primarily on your notebook monitor for ergonomic reasons and because of [issues with the webcam position](#webcam). 
Get an external 27" 4K display. 
4K resolution is required to display others shared screens sharply, especially when scaled.
No ultra-wide or 5K -- it's not worth it because it makes displaying your shared screen hard!
We would love to see a monitor with a webcam built-in, good speakers, and Thunderbolt 3 in a beautiful design.
Unfortunately none of currently available monitors matches these requirements. 
So, we bought the [EIZO EV2785](https://www.eizoglobal.com/products/flexscan/ev2785/index.html) ($1000), a good 4K IPS display to get at least a beautiful design, and we're quite happy with it.

## Wi-Fi

A flaky connection is annoying for everyone.
For a reliable and fast connection, use a [Cat 7 ethernet cable](https://www.amazon.com/AmazonBasics-Network-Ethernet-Patch-Cable/dp/B013PUMX8I) to connect your computer to your router.
If you have to resort to Wi-Fi, invest, for the sake of your team, in high quality access points.
We recommend Ubiquiti [Unifi](https://www.ui.com/unifi/unifi-ap-ac-pro/) and [Amplifi](https://amplifi.com/amplifi-hd).

## Video Conferences

Use [zoom.us](https://zoom.us/) for video conferences and screen sharing. 
It's the most mature, stable, and less CPU-intense video conferencing software that we know -- and is fast on Linux and mobile devices as well.
We can't live without the moveable video stream gallery overlay anymore, especially while screen sharing.
Make sure to [enable global shortcuts for mute and start/stop screen sharing](/setup-zoom-for-effective-screen-sharing).

## Virtual Team Room

A *virtual team room* is a video conference that's always available -- you can come and go anytime.
Zoom doesn't support the concept of a virtual team room directly, [but you can get close by configuring your personal meetings in a specific way](/setup-zoom-as-virtual-team-room).
We use such a virtual team room all the time to work together, for plannings and meetings, and for small talk.
Make sure that your team room is for your team only, and any meetings with other teams happen in separate, dedicated *virtual meeting rooms*.

## Team API

More and more companies introduce some form of channel-based chat system like [Slack](https://slack.com/) or [Microsoft Teams](https://products.office.com/en-US/microsoft-teams/group-chat-software/).
It makes it easy for people to get in touch with each other.
We recommend getting a public team channel to make it easy for other teams to get in touch with you.
Think of this channel as a public API for questions and requests to your team.
Have a private team channel as well, and keep it private so it can become a safe space to discuss sensitive subjects.
Topic-specific channels such as #kubernetes, #frontend, or #marketing allow communication and knowledge sharing across teams.

## Team Insights

A big problem when working from home is that managers no longer see their teams working. Doubts on their productivity may arise, regardless of whether these doubts are justified or are merely the result of a gut feeling. The problem lies in the inherent feeling of loosing control. One way to counteract is to keep your manager up to date through regular insights, similiar to [Basecamp Check-Ins](https://basecamp.com/features/checkins). We highly recommend doing this in a written form asynchronously at the end of the business day -- and make them publicly available within the company. We basically do exactly this: before shutting our computers down at the end of the day, we write a short post about what is newsworthy in a [public team insights channel](#team-api). This insight can be about a finished feature, about yesterday’s refactoring that paid off, or about a complaint about a pointless meeting ([example](https://www.innoq.com/de/articles/2020/03/effectively-working-from-home/#trustthroughtransparency)).

## Full-Team Collaboration

We love [Remote Mob Programming](https://www.remotemobprogramming.org/).
The whole team works together on the same thing, at the same time, in the same virtual space.
Regardless of the term *programming*, these methods are suitable for any kind of knowledge work.
By collaborating so intensely in our [virtual team room](#virtual-team-room) we solve the typical home office issue of social isolation for us. 
And with mob programming, we're being super productive in terms of time-to-market.
One thing that we happily use everyday is the tool [mob](https://github.com/remotemobprogramming/mob), which enables us to make smooth handovers via git.

## Pairing

[Tuple](https://tuple.app/) (macOS only) seems very promising for remote pairing. 
It's the self-declared successor of the late screenhero. 
However, [screen](https://screen.so), being developed by the original developer of screenhero, has made it clear that it wants to become the successor of screenhero as well.
We'll try both, and report to you who'll win the game of the screenhero throne afterall.

## Breaks

Have breaks away from keyboard! 
It's tempting to check emails or read stuff online during a short break, but we recommend to take your breaks seriously and walk away from your home office, get a cup of coffee or go for a short walk. 
It really makes a difference!
And for lunch, take your time to cook a good meal. 
Don't rush it to get back to work faster -- it's not worth it in the long run.

## Desk and Chair

Advices on good desks and office chairs are quite rare, and probably subject to individual preferences and budget. 
However, we would like to give some tips here, as well:
We like the height-adjustable timeless and robust [USM Haller Desk](https://www.usm.com/en/residential/products/usm-haller-collection/usm-haller-tables-and-desks/) ($1000), and can recommend it.
But more important for your long-term health is your chair -- you'll sit on it 8 hours every working day.
We recommend the ergonomic, fully customizable, and very beautiful [Vitra Pacific Chair](https://www.vitra.com/en-ch/office/product/details/pacific-chair) ($900).

## CO2 meter

You'd be suprised how quickly the oxygen in a small room runs low, affecting your mental capacity.
The solution is simple: open your windows.
Thing is, your body realizes bad air quality too late -- your mental capacity is already reduced at that point.
So be proactive, and measure the co2 levels in your room to know when to open your windows so your brain stays happy.
We recommend a simple [co2 sensor with a warning light when to open your windows](https://www.amazon.de/dp/B00TH3OW4Q/).

## Whiteboard

We miss to scribble and discuss together on a physical whiteboard.
There is no good alternative for distributed teams.
What comes next is [Miro](https://miro.com/) on an [iPad](https://www.apple.com/ipad-pro/) with an [Apple Pencil](https://www.apple.com/apple-pencil/) to draw. 
One shares the Miro board in a [video conference](#video-conferences), so that everyone puts their focus on the same section of the board.

## Lighting and Green Screen

Our colleagues at INNOQ who give [remote trainings](https://www.innoq.com/en/trainings/) and online workshops use a green screen to have a clean background and soft lights for perfect illumination.
This comes from professional video game streaming, a pair of [Elgato Key Light Air](https://www.elgato.com/en/gaming/key-light-air) and the [Elgato Green Screen](https://www.elgato.com/en/gaming/green-screen) is the way to go. 
We already ordered them to evaluate and will give feedback here. 
Stay tuned!

## Further Guides

[Remote: Office Not Required, by David Heinemeier Hansson and Jason Fried](https://basecamp.com/books/remote) is a great starting point for ideas on making the switch to remote. It covers a wide range of topics, including recruiting and managing remote teams.

[Remote Guide, by Gitlab](https://about.gitlab.com/company/culture/all-remote/) is a complete and very extensive collection on how to build a fully remote company, touching every aspect of that. It's basically the playbook of Gitlab itself, and is constantly improved from their own learnings.

Both guides strongly promote an asynchronous way of distributed work, while we prefer a synchronous whole team approach.
So, find out what works best for you and your team.

## Authors

<img src="images/simon-avatar.png" alt="Simon" width="80" style="float:left; padding: 12px">
[Simon Harrer](https://twitter.com/simonharrer) is a senior consultant at [INNOQ](https://www.innoq.com). Sharing knowledge is his passion, be it through books, articles, talks, or even tweets. From his experience as a lecturer at the University of Bamberg, Harrer has co-authored the best-selling book [Java by Comparison](https://java.by-comparison.com) that helps Java beginners to write cleaner code through before/after comparisons. When he is not building microservices on Kubernetes, you might see him moderating event storming workshops or helping young PhD students to document their research prototypes with arc42.

<img src="images/jochen-avatar.png" alt="Jochen" width="80" style="float:left; padding: 12px">
[Jochen Christ](https://twitter.com/jochen_christ) is a senior consultant at [INNOQ](https://www.innoq.com). He is an expert for Java technologies and cloud architectures. He is interested in technical leadership, remote working methods, and badminton. Jochen is a speaker at international conferences and enjoys participating in local meetups.

<div style="clear:both"/>

[Legal Notice and Privacy Policy](/legal)

<script async defer src="https://cdn.simpleanalytics.io/hello.js"></script>
<noscript><img src="https://api.simpleanalytics.io/hello.gif" alt=""></noscript>
