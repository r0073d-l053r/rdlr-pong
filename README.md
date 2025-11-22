# 

# **RD/LR Pong**

## **Overview**

RD/LR Pong is a modern, feature-rich implementation of the classic arcade game, built entirely in HTML5 and JavaScript. It expands upon the simple paddle-and-ball concept with three distinct game modes, adjustable AI difficulty (including a challenging 'Impossible' mode), and a chaotic 'r0073dm0d3' mode featuring numerous power-ups and debuffs.

The game is designed to be fully self-contained in a single HTML file, making it easy to host and play in any modern web browser.

## **Game Modes**

1. **Classic Pong**  
   * The standard, traditional game of Pong. First player to 20 points wins.  
   * No special rules, power-ups, or effects. Pure skill.  
2. **Double or Nothing**  
   * A high-stakes mode where two balls are in play simultaneously.  
   * If the balls collide, they both explode, resulting in a score point for the opponent.  
   * Requires high concentration and paddle control.  
3. **r0073dm0d3 (Power-Up Mode)**  
   * A chaotic mode played with two balls, where power-up orbs randomly spawn in the center of the screen.  
   * Hitting a power-up grants you (Player 1\) a temporary buff or inflicts a temporary debuff on your opponent (Player 2/AI).

### **r0073dm0d3 Power-Up Index**

| Color | Type | Effect (Duration: 5s) |
| :---- | :---- | :---- |
| **Green** (\#00FF00) | **PADDLE GROW** | Increases your paddle size by 50%. |
| **Cyan** (\#00FFFF) | **MULTI BALL** | Spawns 1-2 extra balls immediately. |
| **Magenta** (\#FF00FF) | **BALL SUPER GROW** | Makes all balls on the field grow 50% larger everytime they make contact with a paddle for a limited time. |
| **Red** (\#FF0000) | **PADDLE SHRINK** | Shrinks the opponent's paddle by 50%. |
| **Orange** (\#FFA500) | **WEAK SHOT** | Opponent's return shots are dramatically slowed down. |

## **Controls**

| Action | Player 1 (Left) | Player 2 (Right) | Menu/System |
| :---- | :---- | :---- | :---- |
| **Move Up** | W | ArrowUp | (N/A) |
| **Move Down** | S | ArrowDown | (N/A) |
| **Pause/Resume** | (N/A) | (N/A) | Spacebar or ESC |
| **Menu Interaction** | (N/A) | (N/A) | Mouse Click |

***Note:** The "Impossible" AI difficulty has a chance to temporarily "jumble" Player 1's controls.*

## **Setup and Installation**

This game is self-contained in a single HTML file (rdlr_pong-v#.#.#.html) and requires no external libraries or web servers (it uses synthetic audio and native Canvas API).

### **Step-by-Step Instructions**

1. **Save the Code:** Copy the entire content of the game and save it into a plain text file named rdlr_pong-v#.#.#.html. Ensure the file extension is .html.  
2. **Open in Browser:** Locate the saved rdlr_pong-v#.#.#.html file on your computer.  
3. **Launch the Game:** Double-click the file. It will automatically open in your default web browser (Chrome, Firefox, Edge, etc.).  
4. **Start Playing:** Click the canvas area and navigate the main menu using the mouse. Select your desired Game Mode and Opponent (AI or Player 2\) to begin the match.
