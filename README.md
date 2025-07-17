# Hi there! 👋 I'm Swatantra Tiwari

### About Me

I'm a passionate Game Developer with a keen interest in blockchain and Web3 technologies. I enjoy bringing creative ideas to life through code and building engaging user experiences.

Currently, I'm focused on developing a "Color-matching puzzle game where players solve increasingly complex color-based puzzles to progress through levels" color and number prediction game, inspired by titles like Wizcolor and Mantrimall, specifically designed for the **Stake platform using the Stake Engine Math SDK**.

(Note: The demo uses a client-side (JavaScript) randomizer for gameplay simulation. The final version for the Stake platform will integrate with a secure, server-side backend for provably fair results.)

Overview ColorCash Pro is a fast-paced, visually engaging betting game of chance and prediction. Inspired by popular color prediction games, it offers a simple yet deep betting experience. Players predict the outcome of a randomly generated number (0-9) and its associated color (Red, Green, or a rare Violet pair). With multiple betting strategies, from simple color picks to high-stakes number predictions, ColorCash Pro is designed to be intuitive for new players while offering strategic depth for veterans.

### What I'm Working On

* 🎮 **"ColorCash" Game:** Developing a provably fair prediction game with a simple yet addictive concept.
    * **Technology Stack:** Stake Engine Math SDK (Python), React, Web3.js/Ethers.js (for blockchain interaction).
    * **Key Features:** Red/Green color prediction, number betting, clear win/loss conditions, integration with Stake platform's betting mechanics.
    * **Current Progress:** Core game logic (betting, results, multipliers, Firestore records) is complete. UI/UX upgraded with premium design and animations. Next: integrate simulated Stake Engine for provably fair outcomes and explore smart contract interaction.
    * **Repository for the game:** https://github.com/FAI2025/ColorCash.git

* 💡 Always exploring new ideas in decentralized gaming and smart contract development.

**Features**
    * **Dual Betting System:** Players can bet on a color, a number, or a combination of both in a single round.
    * **Dynamic Payouts:** Clear, upfront display of potential multipliers on selection buttons (e.g., 2x, 4x).
    * **Rare High-Multiplier Events:** The appearance of the 'Violet' color on numbers 0 and 5 creates exciting, high-payout opportunities.
    * **Strategic Restrictions:** Betting rules (e.g., Green with even numbers, Red with odd) add a layer of strategy to number selection.
    * **Sleek, Responsive UI:** A modern, Stake-inspired theme that is fully responsive and mobile-friendly.
    * **Persistent History:** A "My Bets" section displays the last 10 results, allowing players to track their performance and identify trends.
    * **Engaging Animations:** A pre-result countdown animation builds anticipation for each round's outcome.
    * **Betting Controls:** Intuitive ½ and 2x buttons for quick bet adjustments.

**How to Play**

**1. Choose Your Bet:**

    * Select a Payout/Color: Click one of the three color buttons.
    * Choose Green or Red for a standard 2x payout.
    * Choose Violet for a higher-risk, higher-reward 4x payout.

**Select a Number (Optional):** Click on a number from 0-9 to add it to your bet for a much higher multiplier. Note that color selections will restrict available numbers and vice-versa.

**Set Your Bet Amount:**

    * Enter your desired bet amount in the input field (minimum ₹0.01).
    * Use the ½ and 2x buttons to quickly adjust the amount.

**Place Your Bet:**

    * Click the "Place Bet" button. The amount will be deducted from your balance.

**Watch the Result:**

    * An animation will play, counting down to the result.
    * The winning number and color(s) will be revealed.
    * Any winnings are automatically calculated and added to your balance.


**Backend (Simulated):** The current demo simulates the backend logic within the client's browser for demonstration purposes.

**Proposed Backend Integration for Stake**
This game is designed to be seamlessly integrated with a secure, server-side backend to meet Stake's standards for fairness and security. A Firebase Cloud Function or a similar serverless solution is recommended.

**The server-side function would be responsible for:**

    * Authenticating the player.
    * Verifying and debiting the bet amount from the player's secure balance.
    * Generating a cryptographically secure random number for the game result.
    * Calculating winnings based on the established payout table.
    * Crediting the player's balance with any winnings.
    * Returning only the final, unalterable result to the client for display.

This architecture ensures that all critical game logic is executed in a trusted environment, preventing any client-side manipulation.

### My Skills

* **Programming Languages:** Python, JavaScript (React), Any other languages you know well, e.g., C++
* **Game Development:** Game Logic Design, UI/UX Development, Interactive Animations, Casino Game Mechanics, Stake Engine Integration (conceptual)
* **Blockchain/Web3:** Decentralized Applications (dApps) Concepts, Smart Contracts (conceptual interaction), Web3.js/Ethers.js (conceptual integration for balance/transactions)
* **Tools & Technologies:** Git, GitHub, Firebase (Firestore), Tailwind CSS

### Connect With Me

* LinkedIn: https://www.linkedin.com/in/swatantra-tiwari-039541202
* Email: swatantratiwari669@gmail.com

Project submitted for consideration by the Stake Engine team.
Thank you for your time and consideration. We are confident that ColorCash Pro would be a valuable and popular addition to the Stake Originals library.

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=FAI2025&show_icons=true&theme=radical)](https://github.com/anuraghazra/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=FAI2025&layout=compact&theme=radical)](https://github.com/anuraghazra/github-readme-stats)


