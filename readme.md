A piece of interactive fiction written using [twee2](https://dan-q.github.io/twee2/) and [snowman](https://github.com/klembot/snowman).

The premise: a nation caught in civil war and famine as powerful religious blocs vie for control. A conflict that has dragged on for years. The towns are starving, the harvests failing, and mercenary companies roam and pillage the land.

Every army is accompanied by a vast train of camp followers: sex workers, washerwomen, looters, all kinds of people who seek their survival through meeting the soldiers' needs. Most of them, women.

In the misery of war, they form a rebellion.

> The sword meets your husband's neck with an abrupt jolt, the force almost wrenching it from your grip.

## Content warnings
This story deals with some pretty heavy themes. In the present draft, specific content warnings for individual passages have not yet been implemented. Please be aware this story contains:
- graphic violence
- implied sexual violence (not shown onscreen)
- transmisogyny (enacted and internalised by the protagonist)
- religiously backed bigotry
- sex work
- sex scenes, with explicit reference to genitals

## Installation

To compile, ensure you have a version of [Ruby](https://www.ruby-lang.org/en/downloads/) later than 2.1.6 (e.g. `apt-get install ruby ruby-dev` on Ubuntu).

Then, to install Twee2, run 

```
gem install twee2
```

To build the story run

```
twee2 build 30yrs-intro.tw2 index.html
```

and for live recompilation run

```
twee2 watch 30yrs-intro.tw2 index.html
```
