---
title: "Global game jam"
layout: single
permalink: /projects-global-game-jam/
sidebar:
  title: "Projects"
  nav:
    - projects

gallery_gameplay:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 1"
    title: "GGJ"
    caption: "Core loop"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 2"
    title: "Challenge"
    caption: "Challenge"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 3"
    title: "Power-ups"

---

1. [Overview](#overview)
2. [Development](#development)
3. [Link](#link)

## 1. Overview {#overview}
Guns n' Growth is a 2D horde survival where you must revitalise a desolate wasteland while fighting off mutated hordes of monsters approaching you. The game was made for the Global Game Jam 2026 under the theme of "mask". The project was made within a week using Godot.

## 2. Development {#development}
I decided before the game jam had started that I would work alone. This led me to make a rough plan for the week ahead to keep myself on track, where I would spend the first day brainstorming, the next four developing, and the final two for art, audio and polish.

Once the theme of "mask" was revealed, I began brainstorming. One of the ideas I got was relating the word mask to masking, as in making objects transparent through digital tools. I thought it would be an interesting puzzle or stealth game to make objects visible or invisible to evade the sight of enemies. Another idea I had was to use the definition of masking that detailed using something to protect yourself from inhaling toxic fumes. This led me to the idea of having to use your mask to aviod inhaling fumes while fighting enemies, but you could take the mask off to improve fighting capabilities but lose survivability. Between these two ideas I decided to stick with the last one for its simplicity, as I didn't want to waste time working on mechanics that were at the time outside my skillset. Once I had the idea, I started development on the basic mechanics. I decided that making a horde survival would be the easiest genre to work with, as it would allow to to reuse enemies and art easily, giving me more time to focus on mechanics. 

For the player controls I made their method of attacking enemies in the form of a simple twin stick shooter, as it would be an easy control scheme to give to the player while allowing for engaging gameplay. I also created the main gimmick surrounding the theme, which was using the mask. I wanted this system to use the fundamentals of risk and reward gameplay, so I decided that when the player had their mask off, it would increase a toxin meter, which would affect different things surrounding the player. A higher meter would increase firerate and damage, but would also increase how much damage was taken from enemies as well as decreasing health regeneration. I did find while playtesting that it became too easy to kill enemies and stay on a high bar with little downside. To counter this, I made it so the player could run faster while the mask was off, but only while their toxin meter was below 100%. This combined with some more rampant enemy spawning would turn this system into a resource the player would have to manage while also accentuating the risk and reward in the system, as to play with higher damage would leave you with less time to be able to run away from enemies if you were to get overwhelmed.

Next was working on the enemies. I decided to make a small variety of them that would mostly include changing some values to make them feel unique from one another. They would all simply make their way to the player's position and didn't need any pathfinding since gameplay would take place in a mostly empty arena. I also added incremental difficulty as the game progressed, where the number and difficulty of the enemies spawning would both increase over time. To add some variety to the game, I also added one special enemy with its own effect, which would be to explode upon being killed. This would kill surrounding enemies and massively damage the player if they got hit. This added some variety to the gameplay, as it would give the player an option for crowd control.

I then wanted to make an end goal for the game. 

## 3. Link {#link}
{% include video id="dQw4w9WgXcQ" provider="youtube" %}
