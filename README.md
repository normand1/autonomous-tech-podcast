<p align="center">
  <img src="_readmeMedia/autonomous-tech-podcast-animated-cover.gif" alt="autonomous-tech-podcast-animated-cover" width="500" />
</p>

# Welcome to the Cutting Edge of Podcast Evolution!

Greetings, esteemed listeners and potential collaborators! You've just stumbled upon the most exciting development in podcast history since the invention of the "Skip 30 Seconds" button. Buckle up, because we're about to take you on a wild ride through the world of AI-powered, community-steered podcasting!

## What's Community Driven Podcasting?

Picture this: you can shape the future of this tech podcast in a way never before possible. Every news broadcaster gets their stories to tell from somewhere, why not update this autonomous podcast with links to the best stories on the internet. We're talking the best blogs, podcasts, subreddits and more!

## How Does This Sorcery Work?

Every day at the crack of dawn (or 6 AM PST for you night owls), our tireless AI minion springs to life. It scours the internet, gathering news like a caffeinated squirrel hoarding acorns based on your configurations. Then, faster than you can say "Is this podcast AI-generated?", it whips up a fresh episode for your listening pleasure.

## Your Mission, Should You Choose to Accept It

Hidden within the depths of this very GitHub repository are sacred texts known as `.env` files. These mystical documents contain the secret sauce, the special spices, the je ne sais quoi that makes our AI tick.

Your mission, should you be brave enough to accept it, is to dive into these files and add your own flavor to the mix. Think the AI is spending too much time on cryptocurrency news? Tweak it! Want more dad jokes in between serious topics? Make it happen! The power is in your hands.

## How to Wield Your Newfound Power

1. Fork this repository (it's like adopting a digital pet)
2. Tinker with the `.env` files (go wild, but maybe not too wild)
3. Submit a pull request (fancy talk for "show us your masterpiece")
4. Wait with bated breath as [<@normand1>](https://github.com/normand1) reviews your changes
5. Tune in the next day to hear your influence on the podcast!

## But Why, You Ask?

Because in the world of AI, a little human chaos goes a long way. Your contributions, no matter how small or silly, help make this podcast a true reflection of its community. It's like a potluck dinner, but for your ears!

So come on, jump into the deep end of the podcast pool. Help us create something truly unique – a daily news podcast that's as unpredictable and diverse as the internet itself.

Check out our current feed and prepare to be amazed (or at least mildly entertained):
https://podcasters.spotify.com/pod/show/autonomous-tech

Remember, in the world of AI-generated content, your input is the secret ingredient. Let's cook up something amazing together!
## How Do I make Updates to the Podcast?

<details>
<summary>How do I add an additional newsletter summary to the daily podcast?</summary>
<br>
To add a new newsletter to be scraped for each daily podcast you can modify the `NEWSLETTER_RSS_FEEDS` variable in the <a href="https://github.com/normand1/autonomous-tech-podcast/blob/master/.env.datasource">.env.datasource</a> file. For substack newsletters you just need to add `/feed` to the end of the url to reference the RSS feed for that newsletter and add it to the end of the list.
</details>
<br>
<details>
<summary>How do I add an additional podcast summary to the daily podcast?</summary>
<br>
To add a new podcast feed to be scraped for each daily podcast you can modify the `PODCAST_FEEDS` variable in the <a href="https://github.com/normand1/autonomous-tech-podcast/blob/master/.env.datasource">.env.datasource</a> file. 
</details>
</br>
<details>
<summary>How do I modify how each segment is presented?</summary>
<br>
The Prompt for each segment is contained in the <a href="https://github.com/normand1/autonomous-tech-podcast/blob/master/.env.writer">.env.writer</a> file. This prompt is currently passed the summary text for each story. This prompt can be used to add some flavor to the podcast beyond just summarizing the story.
</details>
</br>
<details>
<summary>How do I modify the intro/outro to the podcast?</summary>
<br>
The Prompt for the intro is contained in the <a href="https://github.com/normand1/autonomous-tech-podcast/blob/master/.env.intro">.env.intro</a> file. And the prompt for the outro is contained in the <a href="https://github.com/normand1/autonomous-tech-podcast/blob/master/.env.outro">.env.outro</a> file.
</details>
</br>
<details>
<summary>How can I add brandnew segments or features to the podcast?</summary>
<br>
The project is under very active development and we'd very much appreciate additional help building out these new features by contributing to the HyperFeeder OpenSource project being used to generate this daily podcast: <a href="https://github.com/normand1/HyperFeeder">https://github.com/normand1/HyperFeeder</a>
</details>

# Welcome to the Cutting Edge of Podcast Evolution!

## The Pull Request Process (or "How to Hijack an AI's Brain") 🔄

1. Fork the project (It's like adopting a digital pet, but with less responsibility).
2. Create your feature branch (`git checkout -b feature/BrilliantIdea`).
3. Commit your changes (`git commit -m 'Added a sprinkle of human genius'`).
4. Push to the branch (`git push origin feature/BrilliantIdea`).
5. Open a pull request (and cross your fingers!).

Once you've bravely submitted your changes, a real human being (yes, we still need those) will review your contribution. Don't worry, we've programmed patience into our review process, so feel free to grab a coffee or solve world hunger while you wait. If your changes pass muster, they'll be merged into the master branch. Congratulations! You've just leveled up from casual listener to podcast co-conspirator!

## Unveiling the Magic Behind the Podcast: HyperFeeder 💫

Curiosity killed the cat, but satisfaction brought it back! For those of you itching to peek behind the curtain, let's dive into the wizardry that makes this podcast tick: the [HyperFeeder project](https://github.com/normand1/HyperFeeder).

Think of HyperFeeder as the mad scientist's lab where our AI alchemist turns raw internet chaos into podcast gold. It's the engine room, the secret sauce, the special blend of 11 herbs and spices that makes our podcast uniquely... well, unique!

But here's the kicker: You, yes YOU, can harness the power of HyperFeeder to create your very own AI-crafted podcast! It's like being handed the keys to your very own Wonka factory, but instead of chocolate, you're making audio content. Delicious!

## How Can You Contribute? 🧩

Feeling the urge to leave your mark on the AI podcasting world? Want to add your secret ingredient to our audio gumbo? Here's your chance to shine!

HyperFeeder isn't just a platform for creating personalized podcasts; it's a playground where you can contribute new podcast plugins. It's like Lego, but for audio content creation!

Here's how you can add your brick to our magnificent audio castle:

1. Fork the HyperFeeder project (adopt another digital pet, you know you want to).
2. Add your mind-blowing plugin.
3. Commit your changes (`git commit -m 'Add some AudioMagic'`).
4. Push to the branch (`git push origin feature/AudioMagic`).
5. Open a pull request (and start practicing your acceptance speech).

If your plugin survives the gauntlet of human review, it might just become part of the HyperFeeder family. Congratulations, you're now officially a podcast pioneer!

Remember, in this grand open-source adventure, every contribution, no matter how small, helps evolve our AI podcaster. Who knows? Your addition might unlock a new level of podcast greatness that even our AI hadn't dreamed of. After all, sometimes it takes a human touch to make AI truly sing!

**TL;DR:** Contribute to the [HyperFeeder project](https://github.com/normand1/HyperFeeder) to either create your own AI podcast empire or to add new plugins that can take our audio adventure to new heights! 🚀

## In Conclusion, Let's Create Podcast Magic Together! 🎭

This is your golden ticket to shape the future of AI podcasts. It's the perfect blend of human creativity and AI capability, like peanut butter and jelly, but for your ears!

![Alt](https://repobeats.axiom.co/api/embed/14287e4949404ce914868187d3be5a900235d4f9.svg "Repobeats analytics image")

Remember, our AI is a constant work in progress, always learning and evolving. So sprinkle a bit of your human magic into these configuration files, and let's cook up some audio awesomeness!

**TL;DR:** This AI needs YOUR uniquely human touch to make our podcast truly extraordinary! Let's make some noise! 🥳
