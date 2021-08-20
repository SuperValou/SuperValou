
# SuperValou
Welcome to my profile! 

I like C# and Unity, and here is an overview of some of the personnal projects I've done so far.




##  SceneLoading (2021)

[thumbnail]

#### What's this?
SceneLoading is a Unity package to handle transitioning between different rooms. To illustrate what it does and ensure it works as expected, I built a mini-game with it!

[screenshot]

This demo shows that you can split rooms into individual scenes and still have your player moving freely between them like they were all part of the same area. Information can also be "remembered" by a room once it is unloaded/reloaded, and communication can also occur accros different rooms. 

You can either:
- [Play the demo](https://supervalou.itch.io/sceneloading-demo) on itch.io
- Watch the video below (**coming soon**)
- Check out the [Documentation](https://supervalou.github.io/SceneLoading/manual/Concepts.html) 


**Repository:** https://github.com/SuperValou/SceneLoading






## TypewriterEffect (2021)

#### What's this?
A Unity package to display text progressively like a typewriter would do. It also supports few commands to configure how letters are appearing on screen.

Click on the video below to see a demo of it.

https://user-images.githubusercontent.com/6672340/128429432-2a1bfc00-25c0-4d33-aa97-9b2c343aad2f.mp4


#### Context
I wanted to replicate how text gets displayed while [scanning items in this 20-years-old game](https://www.youtube.com/watch?v=1NdGr0vrbeg&t=206s). I took inspiration from [this video](https://youtu.be/So8DpNh3XOE) on how to achieve this effect, and implemented everything myself. 

It parses the input string to create the corresponding tokens and generate the resulting characters along with their animation data.

Note that such "typewriter effects" in Unity are already available in the Asset Store, but the underlying idea was more about learning and building a package with a clear and extensible architecture rather than reinventing the wheel to "just make it work".

**Source code:** https://github.com/SuperValou/TypewriterEffect







## Super Light Shoot (2020)

![2020-04-15 00_38_35-](https://user-images.githubusercontent.com/6672340/128428608-83c71e84-ec03-4542-b021-3a6f6f9d3db4.png)


#### What's this?

A little 3D wave-defense game where you have to shoot incoming ennemies to keep them away. If they get too close, they'll destroy the tower you're standing on, and once you end up on the floor, well... it's up to you to survive!

You can **try it out** by downloading and lauching it from the [Super Light Shoot itch.io page](https://supervalou.itch.io/superlightshoot)! 

Here are some nice comments that were left on the game page:
> Hey, it's a super cool game!

> Great game!

> I LOVED this game, even though it made me scream at one point

It was even mentionned in a [video](https://youtu.be/tZ1buaQJlqk?t=273), and also [another one](https://youtu.be/QTvqWMv6s6s?t=321).


![Cover](https://user-images.githubusercontent.com/6672340/128428668-e925bb2e-ffb4-4bb3-b749-01ff59cc7f3c.png)


 #### Context
It was done during the [Weekly Game Jam - Week 144](https://itch.io/jam/weekly-game-jam-144/rate/611688). The theme was **In the Dark**, and I did everything all by myself.

**Source code:** https://github.com/SuperValou/WGJ144-InTheDark






## Super Tomb Hunter (2018)

![Super Tomb Hunter Gameplay](https://github.com/SuperValou/SuperValou/blob/master/Resources/SuperTombHunter/STH_gameplay.png)

#### What's this?
A four-players game, basically a **2v2 Connect Four**. You and your partner have to fill a row/column/diagonal with four of the same tile in order to score for your team. Be careful, your opponents can steal the rows you're building up... but you can steal theirs too!

![Super Tomb Hunter Main Menu](https://github.com/SuperValou/SuperValou/blob/master/Resources/SuperTombHunter/STH_main_menu.png)

 #### Context
It was done during a three days game jam that took place during **December 2018**. The theme was **Party Game**, and we were a team of **four people**: a producer, a 2D artist and two programmers (another guy and me).


**Source code:** https://github.com/SuperValou/SuperTombHunter

**Try it out:** You can [download the game for Windows](https://github.com/SuperValou/SuperValou/blob/master/Resources/SuperTombHunter/SuperTombHunter.zip) but you will need some XBox Controllers in order to play. Please note that you will be stuck to the main menu if you don't have a controller connected to your computer.







## Dab Dashers (2017)

![Dab Dashers Gameplay](https://github.com/SuperValou/SuperValou/blob/master/Resources/DabDashers/DD_gameplay.png)

#### What's this?
A 2D-rythme-game where you have to dab on the beat to win against the other player. Keep the pace or loose the race!

![Dab Dashers Main Menu](https://github.com/SuperValou/SuperValou/blob/master/Resources/DabDashers/DD_main_menu.png)

#### Context
It was done during a three days game jam that took place during **September 2017**. The theme was **Battle Aracde**, and we were a team of **five people**: two game designers, a level designer, a sound desginer, and a programmer (me).

**Source code:** https://github.com/SuperValou/DabDashers
