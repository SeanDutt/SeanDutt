# Hello, I'm Sean 👋

Welcome to my GitHub profile! I'm a passionate software engineer with a diverse skill set and a love for creating innovative solutions. Below, you'll find my 2023 and 2024 year-in-review.

## 2024 Year in review:


### Participated in the PIGSquad Summer Slow Jam, July
After joining up with a couple of teammates from past jams, we found another couple artists, and put together this short game for a Portland-based jam hosting and game dev community.
A little bit of scope creep, and some unavoidable circumstances led to us only having one level, but the game was still received well, and was great practice for creating gameplay loops, and data structuring.

![image](https://github.com/user-attachments/assets/1edc7104-6561-49cc-a9fe-bffa28793593)

Play our game here (requires download):

https://dutt1ez.itch.io/cryptid-chaos


### Participated in the Buddy Up Game Jam: Winter 2024
My second time participating in this jam. This time around I was not assigned a team, and was left to go and find one. After getting a good idea of a few team options, I joined a team with 6 others as the primary developer.
I led the team in their first Godot project, and we quickly got to work on brainstorming our game idea for the theme: "Renewal". We came up with a solid game loop, started work on our game design document, and I got to work setting up a basic scene.
The planning phase with the team gave me a very good idea of the "events" that would need to occur in the game, so that took a lot of the work out of the code writing process, leaving me with more time to polish the game.

At the end of the jam, and the community ranking phase, we were told we got 2nd place (out of 61 entries)!
This was an incredibly proud moment for me, and it really proved to myself that this is something that could be taken on as more than a hobby, should the opportunity come along.

![image](https://github.com/SeanDutt/SeanDutt/assets/80294286/659ce608-3b3b-4c74-8137-8a7df59b7e6d)

Play our game here (requires download):

https://d3nji.itch.io/helfys-cure-corner


## 2023 Year in review:

## Professional accomplishments:

- Wrote over 500 test cases using the Jasmine, Karma, and Playwright libraries.
- Helped design the QA process for a product's development team.
- Developed, and maintained, a culture of writing automated tests for your code before you merge it.

### Untested Code Release
Encountered a critical issue where untested changes were inadvertently released into the live product environment.
Arranged a team meeting to analyze the situation and devise preventive measures.
Established a new release protocol mandating three-person approval to prevent future occurrences of untested code deployment.


### Code Rollback
Had a scenario where recent changes made to the product were beneficial for its future trajectory, but were incompatible with the current use-case, resulting in a meeting being called by product stakeholders asking to rollback the changes.
Facilitated a de-briefing discussion with the development team to talk about the rationale for the recent changes, emphasizing the importance of our changes towards the long-term vision and future requirements of the product.
Concluded that while the implemented changes were strategically sound for the product's trajectory, they were unsuitable for now, and should be kept in mind for when the current use-case of the product is ready to change.

## Personal accomplishments:

### Participated in the Buddy Up Game Jam: Winter 2023
After being assigned the role of "Production Manager", I put my effort into developing relationships with the rest of the team, and figuring out how I could play a supporting role in the development of our game.
I quickly realized that we had a great team, but no organization, so I put together a scrum board for the team to document features that needed to be developed, art and audio that needed to be created, as well as writing that needed to be done. I also created separate channels in our group chat so that the development chatter could be contained to various aspects of the game, such as code, art, audio, and storyline/writing.

Having spent a good portion of my professional time fighting with, and taking these tools for granted, this game jam experience really drove home the utility that these tools provide a team.

The need for a mediator and manager was also quickly realized, as people don't always figure out healthy and supportive ways of communicating and working with each other right away. My background in management was extremely helpful in these times, as I was able to recognize the need, and bring the skills needed to the table to navigate difficult emotions from multiple people, and align everyone towards the same goal, in ways that give everyone the opportunity to do their best work.

At the end of the 3 weeks, we had created a finished, (mostly-working) game, that we were proud to present, which was all we could ask for as a team of ~10 first-time game jammers.

![image](https://github.com/SeanDutt/SeanDutt/assets/80294286/0b736071-6346-495a-a32e-da9594b2138b)

Play our game here:

https://fakehiking.itch.io/plushiepanic


### Released my own game
In an effort to better learn hosting, authentication, and database management, I decided to create a game.
Using Typescript, Firebase hosting/authentication, and Firebase's database (Firestore), I released a web game, playable by anyone.

In the process of developing items, characters, and locations for the game, all of which needed their own icons, I made the VERY CONTROVERSIAL decision to utilize an AI art tool.
I learned how, and why, to self-host an instance of Stable Diffusion. I learned what models are, and how to use/train different models. I spent many hours practicing my prompts, both image-to-image prompts, as well as text-to-image prompts. Using this, I created many icons for the game's items, characters, and locations.

![image](https://github.com/SeanDutt/SeanDutt/assets/80294286/0b4d273c-3512-4a96-9bf9-e50293a43d53)

Take a look at the code here:

https://github.com/SeanDutt/metal-forge-tycoon

Play the game here:

https://metalty-da486.web.app/

This exercise taught me a lot about hosting, version control, database manipulation, UI/UX, gameplay loops, and AI art.


### Created a Spotify Playlist web app
I listen to music a lot. I'm typically listening to music while I work, while I cook, while I garden, etc.
A problem I found myself facing quite frequently was what to listen to. Spotify gives you daily mixes that list four or five artists they include, which sometimes got me excited to listen to those artists, only to find a song or two by each of them.
In an effort to solve this problem, I created an app that searches Spotify for artists, and allows you to select up to five. Once you have your artists selected, you can generate a playlist.
Using an algorithm I created, the app will select a number of songs by, or including, each artist you provided, I call them "seed artists", and will create a playlist in your library that is 80% "seed artist" songs, and 20% recommendations based off of those selected artists.

![image](https://github.com/SeanDutt/SeanDutt/assets/80294286/28452562-02f4-4514-a72b-d31871171366)

This app has allowed my partner, a handful of friends, and I, the ability to select a handful of artists we're feeling like listening to that day, and create a very quick, on the fly, playlist that has a "vibe" we were going for.
The app, Blendify, is currently in Spotify's app review process, and has the possibility of being a publicly available app.
As of writing this Jan 24th, 2024, the app is not yet approved, and so it only allows 25 users I approve.

If the app has been approved, you will be able to use it here:
https://blendify-f4047.web.app/


### Tailored Workout Web App
After moving to a different home, I was left without a personal trainer, so I decided to replace them with an app of my own (nothing could ever really replace them).

Using vanilla javascript I created a web app that will randomly select a set of HIIT workouts, show me the set, and then walk me through them, one hy one, with the option of seeing a description of an exercise if I need it.

### Shopify Digital Storefront
It happened. A family member asked if I could make a website for them.

After meeting with them to talk about what they needed in their site, I decided that since their intent was to sell products, we should go with Shopify.

I learned how to use themes, customize themes, and how to apply custom code and styling. I also learned, and taught, how to list products, set up simple automation, manage the digital storefront, and search engine optimization.
