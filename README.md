# Bellow

Status: In Development; 
Team: Matas Mulevicius - Gameplay Systems Programmer , Ignas Barauskas - 3D artist 

Bellow is a first-person horror where the player spawns at the bottom of a very large pit with one objective - climbing out alive. The player faces various obstacles, the main one being "The Warden", who constantly hunts, ambushes and sets small bell traps to detect the player. 

This game is being developed as a two-person project, by using Unreal Engine 5.7, a combination of C++ and blueprints, for version control Perforce is being used.

## Features

- **Climbing and vertical traversal** — climb through the environment and work your way upward.
- **Stamina** — manage stamina while moving and climbing.
- **Items and props** — interact with items, manage them in inventory, and throw props.
- **Checkpoints** — support progression through the level.
- **Sound-reactive threat** — noise can draw the enemy's attention.

## My Contribution

I work on the core gameplay programming in C++, including player traversal, stamina, item interaction, throwing, inventory, and checkpoint systems. I also contribute to the design and implementation of the game's underlying gameplay systems.

## Technical Highlights

- **Modular gameplay systems** — player features are organised into separate components and systems.
- **Vertical level flow** — the game is designed around progressing upward through a sequence of spaces.
- **Gameplay events and sound** — player actions can feed into systems that control how the threat responds.
- **Smart Enemy AI** - enemy AI has a complex behavioural state system.

# Mechanics Clips

## Death efffect
https://github.com/user-attachments/assets/59874f32-eff7-4bf4-bdae-43cb56c1cbb4

## Climbing
https://github.com/user-attachments/assets/57ab9aae-a6f4-4752-a81e-fa686da5e1be

## Damage Feedback
https://github.com/user-attachments/assets/a7547502-5095-47c2-a66d-9bc24a077abc

## Bandage Healing
https://github.com/user-attachments/assets/9ad70261-c6b2-4916-bf1c-c87787ef5607

## Bandage Item Consumed
https://github.com/user-attachments/assets/57a3190d-f388-4dfa-bfa1-5475b3b0c30e

## Bandage Item Stayed (0 durability)
https://github.com/user-attachments/assets/49b33602-03da-49ff-8739-6364867f3663

## Prop Inspecting
https://github.com/user-attachments/assets/df5abba7-9f62-4c84-984c-96e3552e9e65

## Module Generation
https://github.com/user-attachments/assets/cec7fcf6-5cd3-4c73-a7b2-3f1dd1380137

## Stackable Items and Infinite Use Items
https://github.com/user-attachments/assets/19a77daa-0f1e-4a39-870e-3452bc8216f7

## First Version Of Throw Mechanic
https://github.com/user-attachments/assets/613e46cf-d22b-4124-a682-3e405c42eca9

## Current Version Of Throw Mechanic 
https://github.com/user-attachments/assets/91e03010-4824-40e2-b8ac-8a9d7d89df88


## Project status 

Bellow is currently in active development. Each gameplay mechanic is being refined and tested to make sure they meet the defined requirements. However, currently the systems haven't been brought together so there is no working gameplay loop yet. The clips above show examples of some of the mechanics currently in place. Currently the development is focused on the enemy AI and sound system implementation, which is one of the most important aspects of the game. In the future there will be a development milestone map revealed but for now, any updates on this game will be revealed here.

## Next Steps

- Refine climbing, traversal, and stamina mechanics.
- Connect the player mechanics to level progression and checkpoints.
- Develop the sound-reactive threat and connect it to player actions.
- Implement prototype version of enemy AI.
- Bring these systems together in a cohesive playable level.



