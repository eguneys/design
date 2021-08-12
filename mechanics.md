# Game Mechanics Advanced Game Design

## Chapter 1 - Designing Game Mechanics

Game mechanics define how play progresses, what happens when, what determine victory or defeat.

Games should be unpredictable.
- Chance, a way of creating unpredictable outcomes, useful in short games, eg: Blackjack
- Choices made by players, eg: Rock, paper, scissors
- Complex rules, The behavior of individual parts might be simple, but complex when combined, eg: Chess

Rules and mechanics are related, but mechanics are more detailed and concrete.

Core mechanics affects many aspects of the game, eg: gravity.

### Five different types of game mechanics:

- Physics, the science of motion and force
- Internal economy, transactions of game elements, that are collected, consumed, and traded
- Progression mechanisms, how a player move through the world
- Tactical maneuvering, what type of advantages, each unit may gain from being in a possible location. eg: chess
- Social interaction, involves online games

### Game genres:

- Action: detailed physics, power-ups, collectibles, levels
- Strategy: Simple physics, unit building, resource harvesting, upgrades, risking units, scenarios to provide challenges, positioning of units for strategic advantages, coordinated actions, alliances
- Role-playing: Simple physics, turn based, Equipment, experience, story-line quests, party tactics, play-acting
- Sports: Detailed simulation, Team managements, Seasons competitions, tournaments
- Management Siulation: Managing of resources, scenarios, managing of resources
- Adventure: Managing player's inventory, Story to drive the game, locks keys
- Puzzle: Simple, discrete physics, short levels increasing challenges
- Social games..

### Discrete vs. Continuous Mechanics

With discrete rules, it is possible to look-ahead, to plan moves, and create strategies. Offer more innovation.

### The Game Design Process

Concept Stage

Decide game's general idea, the target audience, and player's role. Proof of concept prototype

Elaboration Stage

Game mechanics, levels, story, art assets. Short iterative cycles, to produce a playable product that is tested before the design can move on.

Tuning Stage

Feature freeze, focus on polishing, a subtractive phase.


## Prototyping Techniques


A vertical slice is a prototype that includes all the elements that are required to implement one feature of a game. A horizontal slice is a prototype that includes all parts of some aspect of the game but none of the others.

### Prototype Focus

- Tech demos, prototype the workflow of the technology.

- Game economy, is the game balanced, is there a dominant strategy, do players have interesting choices.

- Interface and controls, can players perform the actions you offer them, are there other actions they want or need? Are you giving information to make the right decisions. Do they notice they are taking damage or some state change.

- Tutorials, in later stages of development. Do players understand how to play the game.


## Chapter 2 - Emergence and Progression

Emergence games, have relatively simple rules but much variation. They can be in many different states during play. Eg. a game of chess, with simple rules and many possible positions.

Progression games, offer pre-designed challenges that are ordered sequentially through level design.

Number of rules, low in emergence, high in progression
Number of elements, high in both emergence and progression
Interaction among elements, high in emergence, low in progression
Probability space, large in emergence, small in progression
Replay value, high in emergence, low in progression
Designer control of game sequence, low in emergence, high in progression
Length of game, short in emergence, high in progression
Learning curve, steep in emergence, gentle in progression

## Chapter 3 - Complex Systems and Structure of Emergence

Order: mechanical clock, games of progression
Periodic: Cycle of seasons, Going round in monopoly
Emergent: Daily Weather, Gameplay phases in Civilization
Chaos: Wind Turbulance, Dice rolling


Emergence can occur in complex systems, only after they set in motion. Game design depends on prototypes and testing.

### Structural Qualities of Complex Systems

Simple cells whose rules are defined locally.
Changes in the state of a single part of the system cause changes in distant parts in space or time.
The level of activity is an indicator of complexity.

### Feedback loops

A feedback loop is when the effects of a change in one part of a system affect the same part later in time.

A negative feedback loop maintains a balance within a system. eg: thermostat.
A positive feedback loop will strengthen the effects that caused it. eg: audio feedback. or dominance in chess.


### Categorizing Emergence

Intentional emergence, there is no feedback loops.
Weak emergence, top-down feedback in different levels of the system.
Multiple emergence, short term positive feedback, long term negative feedback.
Strong emergence, such as life as an emergent property of genetic system and culture as an emergent property of language and writing.


## Chapter 4 - Internal Economy

Economy is a flow of resources, such as money, energy, time, units, power-ups etc.
Tangible resources have physical properties in the world. Intangible resources have no physical properties in the world.
Abstract resources do not really exist in the game but are computed from the state of the game. For example strategic advantage in chess.

Specific quantities of a resource is stored in entities. Entities that store one value are called simple entities. Compounds entities are groups of related simple entities.

### Four economic functions

Economies include four functions that affect resources.

- Sources are mechanics that create resource out of nothing.
- Drains take resources out of the game.
- Converters turn resources of one kind to another.
- Traders move a resource from one entity to another.

Negative feedback creates an equilibrium
Positive feedback creates a race, and can create deadlocks and mutual dependencies.

Use an internal economy to:
- complement physics.
- influence progression. Access can be used to progress through the game.
- add strategic game play.
- create large probability space.

- Don't introduce all building blocks at once.
- Be aware of the meta-economic structure. Like certain structures are better than others.
- Use maps to produce variety and constrain the probability space.  


## Chapter 10 - Integrating Level Design and Mechanics

- Progress through completing tasks.
* The aesthetics of shifting perspectives, it is a good idea to have different landscapes and backgrounds.

- Progress as distance to target.

- Progress as character growth.

- Progress as player growth.

Focusing on different structures in your mechanics.

### Missions and Game Spaces

When designing levels, one focus is on the challenges to overcome to complete the level.
Other is on layout of the world.

Mapping mechanics to missions, make sure the tasks are not too trivial or repetitive. Eg: by adding subtasks.

Mapping mechanics to game spaces...

### Martial arts learning principles

- Kihon, learn to perform an individual technique
- Kihon-kata, repeats the same technique to master it
- Kata, combine different techniques in a fixed, sequence of moves.
- Kumite, fight the master in a free fight.


## Chapter 11 - Progression Mechanisms

Lock and key mechanism, is any mechanism that controls access to parts of a level.
Invent locks and keys that are based upon the game's core mechanics.
To involve more feedback, treat the keys as a resource.

Framing progress as a relationship to a particular game state allows us to think about creating dynamic forms of progress from new angles.

The best way to create progression is to set them up so different gameplay phases emerge naturally from the mechanics rather than arbitrary rules. 

To measure progress in terms of game's state it's best to treat the progress as a resource. Such as experience points or character levels.

Characterizing progress as a journey is still useful when the game tells a quality story.
Good stories have certain qualities:

- The events of a story must be coherent. Not arbitrary mechanistic or random.
- The story must not be repetitious. Every event in a story must have a purpose.
- Stories must not move backward in time. Novelty and momentum.
- Stories are about characters.

Storytelling games usually map the game's progres and the story onto a space.

Emergent storytelling, would use emergent mechanics to create gameplay and an emergent progression system to generate dynamically interesting plot events.

Producing the progress indirectly, involves multiple steps and multiple resources. Such as open ended simulation games, The Settlers of Catan, The Sims.

In games of emergence, variation and pacing have to come from different phases the game goes through. You can try to have all different phases emerge naturally from playing the game, or force a few changes through scripts.

- Slow cycle,
- Static friction
- Escalating complexity
- Stopping mechanism/multiple feedback.

## Chapter 12 - Meaningful Mechanics

Semiotics examines the relationship between signals and their meaning. An icon is a sign where it's signal resembles it's meaning. An index is a sign where the signal is causally related to its meaning. A symbol is a sign where the signal is related to its meaning by convention.

Games are often stylized simulations; for aesthetic purposes.
Analogous simulations are based on relationship between their source system and the simulation mechanics. Symbolic simulation, is where relationship between the source system and the simulation mechanics is not causal but arbitrary. eg: use of dice.


Abstracting features to produce analogous and symbolic simulation is better without affecting the structural complexity.

Systems do not have to have many parts to create many different meanings. To create discrete infinity, the number of elements is not as important as the number of possible connections between the elements.

Things can have different layers of meaning that appeal to different audiences. Inter-textual irony is created when a game's style refers to well-known genres or settings outside the game, while contrasting the message with an opposed meaning on a different layer.

## Appendix Design Pattern Library

- Static Engine, produces steady flow of resources over time that never dries up.
- Dynamic Engine, produces adjustable flow of resources, players can invest resources to improve the flow.
- Converter Engine, two resources, a converter changes energy into fuel or vice versa. Introduces possible deadlocks.
- Engine Building, game-play is dedicated to building and tuning an engine to create steady flow of resources.
- Static friction, A drain consumes resources
- Dynamic friction, A drain consumes resources, consumption rate is affected by state of other elements.
- Stopping Mechanism, Reduce the effectiveness of a mechanism every time it is activated.
- Attrition, Players steal or destroy resources of other players they need for other actions.
- Escalating Challenge, Progress towards a goal increases the difficulty of further progression.
- Escalating Complexity, Players act against growing complexity.
- Arms Race, Players can invest resources to improve their offensive and defensive capabilities against other players.
- Playing style reinforcement, is applying slow, positive, feedback on player actions, encourages specialization and adapts to playing style.
- Multiple Feedback, A single gameplay mechanism feeds into multiple feedback mechanisms.
- Trade, Allow trade between players, to introduce negative feedback
- Worker Placement, The player controls a limited resource, that she must commit to activate or improve different mechanisms.
- Slow Cycle, A mechanism that cycles through different states slowly, creating periodic changes to game mechanics.
