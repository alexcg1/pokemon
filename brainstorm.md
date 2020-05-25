# Pokemon Project

## Assumptions

* That we have 7 days to plan and execute, with launch on children's day (1 June 2020)
* That we have full resources of the $COMPANY team and organization as it stands on 25 May 2020 (i.e. like 4 people)
* That we're working in the world of 2020 - i.e. coronavirus lockdown, no travel or in-person events
* That we've already arranged a licensing agreement with rights-holders

### Dataset

* Dataset is [G1 Pokemon only](https://www.kaggle.com/thedagger/pokemon-generation-one)
* Since these are just simple drawings (like fashion-mnist), we have to keep activities simple

## Aim

* Attract developers to use $PRODUCT by doing a joint promotion with Pokemon
* We can attract:
  * Developers who like Pokemon themselves
  * Developers whose kids like Pokemon
  * Developers who have heard of Pokemon (ie everyone ever) and can see we're doing something cool 

## Plan

We organize an event to promote $PRODUCT in association with Pokemon. This event:

1. Is highly promotional in itself, by doing **Something Cool**(TM)
2. Leads to longer term promotion by acting as launch event for a larger venture

This gives us two avenues:

1. Something cool, which we need to plan and execute fast
2. Larger venture, which we need a rough plan and launch date for, but will need marketing materials to launch at end of Something Cool event

## Ideas

Our idea has to be cool for developers and kids, and be able to pull it off within a week. This limits our options!

### Viable

#### Blindfold Pokemon Challenge

a.k.a. Don't peek-a-chu!
a.k.a. Draw-a-pic-a-chu!

* Draw a G1 Pokemon blindfolded (prevents peeking or tracing)
* Share video and final pic on tiktok, Facebook, Twitter, etc with hashtag #blindfoldpokemon
* Results in video (proof of effort by user) and line drawing (simple enough to pass to neural net with given dataset)
* Drawings are gathered and each passed through $PRODUCT and compared with pokemon dataset
* Highest K-score pic gets prize
* Potential for prizes for top 10 entrants in different age brackets (kids of all ages love pokemon, but if we allow entrants between 8 and 16, obviously 16 year olds will kick ass). Could also have adult category to engage older Pokelovers
* Booby prize for best out-take (encourages filming failures, which can be good for comedy value and memes. No-one wants to see only geniuses)
* Need interesting animation for showing $PRODUCT working out which Pokemon it is. Fake something up showing $PRODUCT logo with a thought bubble that flashes between different pokemon like a slot machine, before landing on correct one with ding ding ding
* Simplify: Draw the closest Pikachu

##### Improvements

These are just thoughts, but don't have timeframe to implement

* Release an app for iOS and Android to allow blind drawing and instant compare to pokemon database so entrants can practice and submit drawings

### Semi Viable

Would need to either:

* train model on less restricted dataset (e.g. Pokemon in more poses, positions, backgrounds), or
* pre-process input data for search (this one seems easier, especially with pretrained models that already turn ppl into anime characters or remove backgrounds)

For below ideas, winner is determined by feeding each image in turn to $PRODUCT and seeing which gets hit with highest probability

#### Pokecosplay

* Prize for user who can create and model best [shitty cosplay] that resembles a still from the Pokemon cartoon.
* Requires input image preprocessing

#### Real Life Pokemon

* Take pictures of things in real life that look like Pokemon
* Requires input image preprocessing

#### Which Pokemon are you?

* Take a pic of yourself
* Match that via neural search to closest Pokemon look-alike
* Requires input image preprocessing

### Not Viable

Given timeframe, company size, pandemic, dataset limitations, we can't really pull these off within a week

#### Pokehack

Hackathon. Impossible to pull off with just a week notice, but could be a follow-up event

### Not thought out yet

These are more concepts and brainstorming, rather than actual ideas

* Pokemon Go integration
* Pokemon cards

### Prizes

#### Trophy

Given timeframe we could fabricate one from sintered metal from a 3D printed design on [Thingiverse], like a [Pokeball], [Pikachu] or something like that.

#### Real Life Pokedex

Not viable in short term!

* $PRODUCT running on a Rasp Pi in a custom shell
* Can do search for Pokemon via text or sketched neural search and display wikipedia style entry and matching pics

#### Create your own pokemon

Winner gets to design Pokemon for next game. This seems like a huge ask and not sure we could get agreement from stakeholders

### Timeframe

Assuming already have agreement from key stakeholders that this is a good idea. Otherwise back-and-forward over zoom and dealing with legal dept would take more time than we have.

Launch of the contest is children's day. Judging comes a month later (for example)

I'm taking full account of Murphy's and Hofstadter's Laws, and being deliberately pessimistic. Things will go wrong!

#### Day 1

* Confirm marketing with team and stakeholders - video script, visuals
* Meeting with Pokemon company marketing team - what existing efforts can we leverage for promotion?
* Contact large existing children's day events and media - find out sponsorship costs and arrange shout outs and coverage for launch
* Brief video creator on what we need - they should give us quote by end of day and start brainstorming visuals
* Get quotes from voice-over talent for relevant languages for 2 minute video (assume English and Chinese only for now, bc constraints)
* Check stock footage we can use for video - someone being blindfolded, a hand drawing. No time to film new footage
* Finalize 2 minute video script that demonstrates and explains the challenge
* Agree quotes, send script to video producer, voiceover talent

#### Day 2

* Work with graphic designer on visuals and relay to video creator
* Finesse script with voiceover team

## Misc

### Video Visuals

Frankly impossible given time constraints. Turnaround for animation companies isn't that quick. Unless pre-existing footage??

* Pokemon trying to draw each other blindfolded, but $UNTRUSTWORTHY_POKEMON is peeking. Pikachu electrocutes them. Don't PIK-A-CHU!
* Can we integrate with "shocked pikachu" meme?
