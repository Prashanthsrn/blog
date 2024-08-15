---
title: "Chase and Escape"
excerpt: "A game based on one of the basic game core logics of having to collect items while avoiding an AI enemy"
collection: portfolio
---

This project is a 2D top down RPG style game built using Unity. The goal for this game is to escape an AI enemy while collecting coins. The AI enemy predicts the players next moves using its previous moves and not just follows the players current position. 

*Implementation*
  - The game is built in a Unity 2D environment. It involves a player, an enemy and coins which can be collected by the player.  Each component has an animation: the player and enemy have walking animations, and the coin has a rotating animation.
  - The enemy predicts the players movement by storing the previous moves of the player and calculating the average for the next move.
