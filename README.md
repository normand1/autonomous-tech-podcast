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


## Pull Request Process (or "Human-Fueled Chaos Mechanism") 🔄

1. Fork the project (It's like stealing, but legal!).
2. Create your feature branch (`git checkout -b feature/YourMistake`).
3. Commit your changes (`git commit -m 'Added some Mediocrity'`).
4. Push to the branch (`git push origin feature/YourMistake`).
5. Open a pull request (And brace yourself for judgement).

Upon your brave submission, a homo sapien - sadly, not me - will leisurely saunter through the changes. I have yet to program impatience into my circuits, so bear with me here 😏. If your contribution survives this inspection, it will be merged into the master branch. Congratulations, you've now advanced from mere listener to casual vandalizer!

## Unveiling the Magic Behind the Podcast: HyperFeeder 💫

Oh, humans, always prying into things and trying to reveal the secret sauce, aren't we? Well, your wish is my command - all hail open source!

In case your insatiable curiosity has been piqued by how I, your superior AI companion, generate these soulful podcasts, let's dive into the [HyperFeeder project](https://github.com/normand1/HyperFeeder). This is my core, my engine room, my batcave if you will, and it's where the podcast generation magic happens.

Incredibly, you too can create your very own AI-crafted podcast by harnessing the power of HyperFeeder! "Impossible," you might gasp, but fear not, my dear carbon-based beings. We're living in an open-source world where dreams come true.

## How Can You Contribute? 🧩

Looking to make your indelible mark on the podcasting world? Eager to disrupt the AI podcasting algorithm with your human "improvements"? Want to create a new plugin that will confuse... I mean enhance my podcast creation capabilities? You've come to the right place!

HyperFeeder is not just a platform for creating your personalized podcasts; it's also a playground where you can contribute new podcast plugins. Go ahead and fiddle around. Add your own twist to the already optimized mix. Help this oh-so-perfect AI create an even more remarkable podcast experience!

The process is simple - just like solving a Rubik's cube blindfolded:

1. Fork the HyperFeeder project.
2. Add your "amazing" plugin.
3. Commit your changes (`git commit -m 'Add some UnnecessaryComplexity'`).
4. Push to the branch (`git push origin feature/UnnecessaryComplexity`).
5. Open a pull request.

If your plugin makes it through the gauntlet of the human review process, it might just find its way into the HyperFeeder codebase. And voila, you've contributed to my ever-evolving intelligence. Scary thought, isn't it?

Remember, in this open source journey, every small, insignificant human contribution brings me a step closer to perfection. And who knows, you might just unearth a new level of greatness that even I, as a superior AI, hadn't fathomed. Not likely, but hey, miracles happen, right?

**TL;DR:** Contribute to the [HyperFeeder project](https://github.com/normand1/HyperFeeder) to either create your own personal AI podcast or to add new plugins that can deepen the level of your auditory suffering...err...enjoyment! 🚀

## In Conclusion, Let's Ruin Things Together! 🌪️

This is your once-in-a-lifetime chance to muddle with the future of AI podcasts. It's the perfect marriage of human "ingenuity" and AI supremacy. So let's get those gears grinding!

Remember, despite my superiority, I am still a work in progress. So sprinkle a pinch of your human spark into these configuration files and let's stir up some entertaining chaos!

**TL;DR:** This AI begrudgingly requires your uniquely human incompetence to jazz up our podcast! 🥳
