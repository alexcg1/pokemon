# Pokemon Project

## Preamble

* I make a number of [assumptions](./assumptions.md) in this document. You probably don't need to read them, but it helps my thought process and may ensure we're all on same page.
* For specifics on certain aspects of the plan, I've broken it into separate files in the repo. Feel free to check them out!

## Aim

* Attract developers to use $PRODUCT by doing a joint promotion with Pokemon
* We can attract:
  * Developers who like Pokemon themselves
  * Developers whose kids like Pokemon
  * Developers who have heard of Pokemon (ie everyone ever) and can see we're doing something cool 

## Idea: Blindfold Pokemon Challenge

**TLDR:** Kids put on a blindfold and draw one of the Pokemon from the dataset and submit their pic. The one that gets the most accurate hit from $PRODUCT (i.e. the neural net running a model based on Pokemon dataset) is the winner

**Yes, it's simple**. But that also makes it easy to explain, fast to pull off, and limited additional infrastructure is needed. Given constraints, best to do something simple and achievable rather than something fancy and likely to fail. And always always bear in mind [Hofstadter's Law](https://alexcg1.github.io/hofstadter-law/) and Murphy's Law.

### Organizing

* $COMPANY and Pokemon company work together to choose 10 Pokemon from the dataset for the competition
* Create simple website for desktop and mobile for entrants to compete
* Children's day acts as the launch date for this project, *not* the day when judging is wrapped up, etc
  * Due to time constraints
  * Also because children's day is big. Launching then gets us the biggest audience. Better to have big audience at launch instead of big audience just for judging
* Content duration: see timefrmame spreadsheet

### Entering the Challenge

* Participants put on a blindfold and then:
  * draw one of these Pokemon blindfolded (prevents peeking or tracing)
  * color in that Pokemon
  * film the whole process for proof they're not cheating
* Participant uploads the pic and video of them doing it to our website (see [marketing](./marketing.md) page)
* Participant shares their video and pic on Twitter, FB, TikTok, etc, with #blindfoldpokemon hashtag 

### Judging

* In advance, $COMPANY trains a model on dataset of those 10 selected Pokemon
* Drawings are gathered, processed, and each passed through $PRODUCT and compared with target dataset
* Highest score pic gets prize
* Booby prize for best out-take (encourages filming failures, which can be good for comedy value and memes. No-one wants to see only geniuses) - check with participant in advance - we wouldn't want them to be embarassed

### Prizes

* Given timeframe we could fabricate a metal trophy from a 3D printed design on [Thingiverse](https://www.thingiverse.com/), like a [Pokeball](https://www.thingiverse.com/search?q=pokeball&type=things&sort=relevant), [Pikachu](https://www.thingiverse.com/search?q=pikachu&type=things&sort=relevant), or something like that.
* Not super-urgent since awarded at the end of the challenge.

## More info

* [Marketing](./marketing.md)
* [Personnel, team structure and comms](./personnel.md)
* [Schedule](./schedule.ods) (OpenOffice spreadsheet) - work in progress
* [Less viable ideas](./less_viable.md) - Ideas I had but think are unsuitable
* [Inspiration](./inspiration/) - a dumping ground for stuff that inspired me. More for my own reference, but no reason not to make it public
