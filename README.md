# Hotel Yamato Incident — History-Based Educational Game

A story-driven educational game about the **Hotel Yamato incident**, built in **Unity (C#)** as my undergraduate thesis in Informatics at Universitas Pembangunan Nasional "Veteran" Jawa Timur.

On 19 September 1945, Indonesian youths in Surabaya tore the blue stripe off a Dutch flag raised on the Hotel Yamato, turning it into the Indonesian red-and-white. This was one of the events leading up to the Battle of Surabaya. The game lets players live through that story through a branching narrative instead of reading it from a textbook.

<!-- Add 2–3 screenshots or a short GIF: upload them to a /docs folder, then add a line like ![Gameplay screenshot](docs/screenshot-1.png) here -->

## Features

- **Branching story** built with Interactive Digital Narrative (IDN), where player choices shape how events unfold
- **Side quests** alongside the main historical storyline
- **Inventory system** for collecting and using items
- **Historical dialogue** based on the events of the Hotel Yamato incident
- **Mini-games** integrated into the story

## Results

The game was evaluated using the **Game User Experience Satisfaction Scale (GUESS-18)** with **25 respondents**:

| Study | GUESS-18 score |
|---|---|
| Previous study (same project) | 3.80 / 5.00 |
| This version | **4.15 / 5.00** |

The research was published in **Santika**:
*"Pengembangan Game Edukasi Insiden Hotel Yamato menggunakan Interactive Digital Narrative"*
<!-- Add a link to the paper here if it is available online -->

## Bugs Found and Fixed

Both bugs were found during playtesting and fixed before the final evaluation.

### 1. Mini-game could be completed by button-mashing

- **Steps to reproduce:** Start the mini-game and press the action button repeatedly at random.
- **Expected:** The mini-game is only completed when the player performs the correct actions.
- **Actual:** The mini-game completed regardless of what the player did.
- **Severity:** High. Players could skip the challenge and the learning content inside it.
- **Fix:** [Briefly describe what you changed]

### 2. Side-quest progress reset after leaving a building

- **Steps to reproduce:** Complete a side quest inside a building, then exit the building.
- **Expected:** The side quest stays marked as completed.
- **Actual:** The side quest was reset to not completed.
- **Severity:** High. Players lost their progress.
- **Fix:** [Briefly describe what you changed]

## How to Play

**Download:** get the Windows build from the [Releases](../../releases) page, unzip it, and run the `.exe`.

**Controls:**

| Action | Key |
|---|---|
| Move | [e.g. W A S D] |
| Interact / Action | [e.g. E] |
| Inventory | [e.g. I] |
| Pause | [e.g. Esc] |

## Open the Project

1. Install **Unity [version]** using Unity Hub.
2. Clone this repository or download it as a ZIP.
3. In Unity Hub, click **Add** and select the project folder.

## Built With

- Unity [version]
- C#
- Interactive Digital Narrative (IDN)

## Author

**Zata Hashfi Luthfan Tori**
Informatics graduate, Universitas Pembangunan Nasional "Veteran" Jawa Timur (2026)
GitHub: [LordUndying](https://github.com/LordUndying) · Email: zata.tori@gmail.com
