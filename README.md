# Swipeable Card Interface

This project implements a swipeable card interface using HTML, CSS, and JavaScript (with jQuery). Users can swipe cards left or right, simulating interactions similar to mobile applications like Tinder. The card swiping triggers a transform animation, and based on the direction of the swipe, cards either "like" or "reject."

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [System Requirements](#system-requirements)
- [License](#license)

## Installation

To use this project, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/akshatjaiin/scroll_slide.git
   cd scroll_slide
```

Open the Project: Open index.html in your web browser. Ensure that you have an internet connection to load the jQuery library, as it's loaded from a CDN.

If working locally, ensure the external .js and .css files are correctly linked to index.html.

(Optional) Install Dependencies: If you're modifying the JavaScript or using an environment without internet access, download jQuery locally or use a local version of something.js.

Features
Swipe Interaction:

Users can swipe cards left to reject and right to like.
The cards rotate and move based on user input.
Transform Animations:

The swipe gestures translate the cards horizontally and rotate them slightly.
Opacity of the like/reject indicators changes as the user swipes the card.
Reset and Recycle Cards:

Cards are reset and recycled back to the deck once all cards are swiped.
Mobile Touch Support:

The swiping functionality works for both mouse input (on desktops) and touch input (on mobile devices).
Usage
Card Swiping:

The user can click and drag a card left or right to simulate a swipe gesture.
Cards will animate based on the swipe direction.
Interaction:

The system keeps track of how many cards have been swiped, and once all cards are swiped, the deck resets.
Project Structure

Contains the card container with several cards stacked on top of each other, each with a name and description.
CSS (maybe.css):

Styles the card elements and defines colors, fonts, and animation effects for the cards.
JavaScript (something.js):

Handles the swipe functionality, including the detection of mouse or touch gestures, animation of card movements, and resetting the deck after all cards are swiped.
System Requirements
Web Browser: A modern web browser that supports JavaScript and CSS animations (Chrome, Firefox, Safari, Edge).
JavaScript Libraries:
jQuery (included via CDN).
