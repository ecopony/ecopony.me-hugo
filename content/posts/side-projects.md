+++
date = "2015-09-03T15:52:20-07:00"
draft = true
title = "side projects"
weight = 2
type = "post"
+++

### Velofight!
#### Online fantasy cycling game and community

Velofight! started when my friend and colleague Mike Westover came down from Seattle to visit me in Portland. We met at a coffee shop and he pitched his idea. He knew someone in Seattle who had been running a fantasy cycling game for his friends out of an Excel spreadsheet for a number of years. Mike's idea: Take the game out of the spreadsheet, put it online in time for the Tour de France, do a little advertising for it, slap ads on it, and see what happens. And, as Mike is skilled at doing, he made it sound really simple. It would have to be, since we had about two weeks before the Tour de France started.

We had about a week to get user account creation and roster creation built and the app deployed. This would allow people to get signed up and make their teams. Then, we had about a week until the first stage, so we had that long to get individual stage scoring built. From there, no problem! We had three weeks to finish the final scoring. The application also emailed participants about daily results, so there was that piece, and we gave away killer Velofight! socks and t-shirts for top performers.

Velofight! was a blast. We used Rails for the app, we deployed to AWS, we managed the work with Pivotal Tracker. I was the main developer, Mike handled deployment, operations, and some light development. We got all parts of the site up in time, working after hours when we were done with our day jobs. Despite the mad dash, we did test-driven development, had great test coverage, and only a couple, very minor defects make it to production. The users had a blast, and we made improvements for the Tour of Spain, which was about a month later.

Over the next winter we added support for single-day races and added series support for multiple competitions throughout the year. Users could invite their friends to Velofight!, and many did. We had users all over the world.

We ran the site for four years, before time constraints on both of us led us to, sadly, shut it down. Our users thanked us -- some even said they would pay to play! Someday we might decide to bring back Velofight! on a different platform.

### MLB Gameday API (Go version)

After using my Scala version of the API for a couple years (see the next side project below), I wanted an easier way to play with command-line apps. This led me to Go. I learned Go and had an alternate version of the API working in short order. Building with Go was a much simpler experience than Scala. It's a great option for solving a lot of different kinds of problems.

[MLB Gameday API (in Go)](https://github.com/ecopony/gamedayapi)

### MLB Gameday API (Scala version)

Wanting to learn Scala, and wanting to play with the free data that MLB makes available for fans to use, I developed an API to MLB Gameday using Scala. Scala has some cool features, the ability to do OO and more functional programming is nice. The language and the ecosystem is pretty complex, though. It takes a lot of room in your head, and can make some simple things harder than they need to be. 

[MLB Gameday API (in Scala)](https://github.com/ecopony/scala-gameday-api)
