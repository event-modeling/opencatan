# openKatan

Katan is a very popular board game that's enjoyed by millions around the world. It could be the poster child for (Event Modeling)[https://eventm;odeling.org] like the Bowling game is for Test Driven Development. This project will look at addressing some other goals in addition to showing Event Modeling.

# Setup

You should be able to open the html and supporting files, open the main page in a browser locally and connect to other players doing the same thing on their computers or mobile devices.

# Goals

There are a number of areas that this project will address:

* Use a blueprint in the form of an event model as a replacement for a lot of today's software practices.
* Use event sourcing. The actions of players are recorded on ledger that contains the history of the game.
* Use CQRS. Separate state change parts of the system from the ones that show you any infromation about the state.
* Support polyglot approach by making use of the "by the slice" nature of event modeled projects.
* Address agile concerns in what is done in what priority. First pieces of functionality will be the core of the game that players find most exciting.
* Use free/libre/open-source software (FLOSS) tooling to put no restrictions on who can run it and where.
* Use Github purely as a public mirror. Use a proper host for the project that is owned by individuals.
* Use a an elected leader for the game.
* Use a readily available communication channel with an abstraction to swap to even support sneaker net or manual entry of moves.
* Use the same repo to keep a list of issues. Don't use a separate source of truth for tickets, etc.
* Use a pluggable dice provider.

# Requirements

* LibreOffice Draw for the event model until a suitable markdown-like format becomes available.
* 0-tech JavaScript - no bloat from node_modules or other frameworks or libraries.

# Chat

Currently ussing (gitterIM)[https://gitter.im/Event-Modeling/openkatan]
