# Adopt & Learn: Play with Your Buddy!
Welcome to Adopt & Learn — an interactive web experience designed to educate and entertain users about pet care and animal adoption, featuring a fun mini-game where you can play with your virtual buddy!

About the Project
"Saving lives (and having fun) is just a click away!"

This web app simulates a heartwarming world where users can:

Discover & Adopt: Learn about various pets and simulate the adoption process.

Track Coins: Earn virtual coins from adopting pets and playing games.

Customize Pets: Use earned coins to buy items for their adopted companions.

Play Mini-Games: Engage in interactive games, like "Cat-ch Me If You Can," to bond with their virtual pet and earn rewards.

Interact with a Bot: Get quick answers and announcements to enhance the learning and playing experience.

Experience a 3D Play Area: Dive into an immersive environment for the mini-game.

Inspired by the joy of pet ownership and the importance of responsible care, we aim to make people more aware of animals in need and the fun of interacting with them, all within an engaging and playful setting.

## Core Functionality
To stimulate continuous engagement and learning, "Adopt & Learn" features a unique gameplay loop:

Timed Adoption System: Every 2 hours (set to 2 minutes in development for quick demonstration), users are eligible to adopt a new animal companion from the available selection. This encourages regular visits and interaction.

Coin Economy:

With each adopted animal, you receive 5 cash coins.

These cash coins can then be used to purchase various items for any of your adopted animals, allowing for personalization and enhanced care.

Interactive Bot Integration: An AI-powered bot is integrated into the site to provide instant answers to user questions and deliver important announcements, making the experience more interactive and informative.

Post-Adoption Actions: After successfully adopting an animal, two key options become available:

"Learn More" Button: Send a direct message to the integrated bot to receive detailed information about your newly adopted pet.

"Play Game" Button: Dive into the exciting 3D mini-game "Cat-ch Me If You Can" with your buddy.

# Features
Games
"Cat-ch Me If You Can"

Goal: Control a cat, collect mice, and evade a mischievous dog.

Mice Collection: Your mission is to collect a total of 30 mice to win the game.

Coin Rewards: For every 10 mice collected, you receive 1 cash coin.

Obstacle: You must skillfully avoid the dog that chases you around the play area, as getting caught results in a game over.

3D Environment: An immersive 3D scene with ground, obstacles, and dynamic lighting.

Controls: W/A/S/D for movement, Spacebar for jumping, Mouse for camera rotation.

Scoring: Tracks collected mice and evasion time from the dog.

Dynamic Danger Overlay: Visual feedback when the dog is near.

Restart/Back to Site: Options at game over/win.

Cash Award Popups: Notifies you of earned coins post-game.

# User Interface & Experience
Loading & Error Handling: Provides feedback during 3D model loading.

Instructions Display: Clear in-game controls and objectives.

Audio Controls: Toggle music and adjust volume for an immersive experience.

Personalization: Display your chosen buddy's name and image.
# Technologies Used
HTML5 / CSS3: For the structure and styling of the web pages, including responsive design.

JavaScript (Vanilla): For all interactive elements, game logic, dynamic content, bot integration, and the timed adoption system.

Three.js (r128): A powerful 3D JavaScript library for rendering the "Cat-ch Me If You Can" game.

GLTFLoader.js: Used to load complex 3D models in GLTF/GLB format into the Three.js scene.

Web Storage (LocalStorage): For persistently storing user progress, adopted pets, and coin balances.

Sound Assets: For background music and in-game sound effects.

Image Assets: For backgrounds, textures, and UI elements.

Google Fonts (Quicksand): For consistent and friendly typography.

# Assets & Media
3D Models:

./models/scene.gltf (Player Cat Model)

./models/Muchkin2_baseColor.png (Cat Texture)

./models/mouse.glb (Collectible Mouse Model)

./models/dog.glb (Enemy Dog Model)

./models/desktop_design_cute.glb (In-game obstacle/decoration)

./models/rat_plushy.glb (In-game obstacle/decoration)

./models/slide_playground.glb (In-game walkable obstacle/decoration)

./models/pink_house.glb (In-game obstacle/decoration)

./models/paper_box.glb (In-game obstacle/decoration)

./models/japanese_cherry_tree_low-poly.glb (In-game obstacle/decoration)

# Textures & Backgrounds:

grass.jpeg (Ground and Scene Background Texture for the game)

background-chase.jpg (Background image for the game's start screen)

# Audio Files:

comedy.mp3 (Background music for the game)

win.mp3 (Sound effect for game win)

loose.mp3 (Sound effect for game over)

kitz.mp3 (Sound effect for collecting a mouse)
