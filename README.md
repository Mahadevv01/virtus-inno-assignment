# Vehicle Survival Game

## Overview
Build a game using React-three libraries like Fiber, Drei, Rapier, or any other react-three library. The game features a vehicle with the following characteristics and mechanics:

## Vehicle Features
1. **Wheels and Joints:**
   - The vehicle should have 3 wheels and joints.
   - The front wheel should be a sphere.
   - The back wheels should be small cylinders.
   - The body of the vehicle should be rectangular.

## Game Mechanics
1. **Movement:**
   - The car should move in the direction you point the cursor when you press "W".
   - The car should move backward when you press "S".
   - The cursor should help you take turns.

2. **Falling Shapes:**
   - Randomly drop different shapes (cubes, spheres, pyramids) from the sky.
   - The shapes should have different masses and sizes.
   - The falling shapes should exhibit physics properties when they hit the ground.
   - Your goal is to escape the falling shapes to survive. If you touch any of the shapes, the game will be over.

## Bonus Features
1. **Score Storage:**
   - Store the score in a Supabase database at the end of the game.

2. **Responsive Design:**
   - Use Tailwind CSS to make the game adaptable to mobile and tablets.

## Tech Stack
- **Front-end & Back-end:** Next.js
- **3D Graphics:** React-three libraries (Fiber, Drei, Rapier, etc.)
- **Database:** Supabase
- **Styling:** Tailwind CSS
