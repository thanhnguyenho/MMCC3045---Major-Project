# Meomeo's Journey Home

**Meomeo's Journey Home** is a one-page interactive web-based visual novel about an abandoned kitten searching for safety, belonging, and the meaning of home.

The project is built with **HTML, CSS, JavaScript, and jQuery**. It uses a single-page structure where different story scenes are loaded dynamically through JavaScript. The project includes branching choices, character stats, interactive challenges, multiple endings, an ending gallery, and an after-credit scene inspired by the real cat who gave the idea for the story.

---

## How to Run the Project

Open `index.html` in a web browser.

No installation, build tools, or server setup are required.

If the project is viewed online, use the published GitHub Pages link.

---

## Controls

- Click on the dialogue box to advance the story.
- Press `Space` or `Enter` to advance dialogue.
- Press `A` to toggle Auto mode.
- Press `S` to toggle Skip mode.
- Press `B` to open the dialogue backlog.
- Press `I` to open the inventory.
- Use the on-screen choice buttons to affect the story route.

---

## Main Features

- One-page interactive visual novel format
- Branching story routes
- Dialogue and narrator system
- Character expression changes
- Multiple NPCs
- Interactive challenges and puzzles
- Character stats: HP, Hunger, Courage, Street Skill, and Kindness
- Inventory system
- 6 possible endings
- Ending gallery
- After-credit scene dedicated to the real cat who inspired Meomeo

---

## Story Overview

The story begins with Meomeo, a small calico kitten abandoned in a cardboard box outside a cafe on a rainy night.

The player decides whether Meomeo should trust a kind human or run into the city. From there, the story can branch into different routes involving home, street survival, other stray cats, danger, freedom, and protection.

The main theme of the project is not only finding a physical home, but discovering what “home” means: a person, a family, a community, freedom, or the act of protecting others.

---

## Important Note for Testing

This section contains spoilers. It is included to help the marker test all story branches and unlock all 6 endings efficiently.

If a puzzle or challenge is failed, use the retry option or replay the route.

---

# How to Unlock All 6 Endings

## Ending 1 — Happy Home Ending

This is the direct warm home route.

### Route

1. Start the story.
2. Choose **Trust her — walk toward the light**.
3. Complete Lily’s Memory Test.
4. At the meeting with Mina, choose **Walk slowly toward Mina — give her a chance**.
5. This unlocks **Happy Home Ending**.

### Story Meaning

Meomeo chooses trust and accepts a new home.

---

## Ending 2 — Second Chance Ending

This route shows Meomeo running away at first, but later accepting a second chance at love.

### Route

1. Choose **Trust her — walk toward the light**.
2. Complete Lily’s Memory Test.
3. At the meeting with Mina, choose **Freeze — panic and run out the door**.
4. Continue through the street route.
5. Complete the street challenges.
6. At the final crossroads, choose **Follow the scent — seek a home**.
7. This unlocks **Second Chance Ending**.

### Story Meaning

Meomeo loses one home, becomes afraid, but eventually chooses to trust again.

---

## Ending 3 — Stray Cat Family Ending

This route focuses on Meomeo joining the street cats.

### Route

1. At the first major choice, choose **Refuse — hiss and flee into the night**.
2. Complete the Street Wisdom Riddle Challenge.
3. When meeting Mochi, choose **Follow Mochi — meet the street cats**.
4. Complete the Cat Survival Test.
5. This unlocks **Stray Cat Family Ending**.

### Cat Survival Test Safe Choices

- Round 1: choose **Cardboard box** or **Bushes near wall**.
- Round 2: choose **Clean bowl** or **Fresh fish scrap**.
- Round 3: choose **Sniff calmly** or **Step back slow**.

### Story Meaning

Meomeo does not return to humans, but finds a different kind of family among other cats.

---

## Ending 4 — Independent Cat Ending

This route is for Meomeo choosing freedom without becoming aggressive or tied to a group.

### Route

1. Choose **Refuse — hiss and flee into the night**.
2. Complete the Street Wisdom Riddle Challenge.
3. When meeting Mochi, choose the route that follows the food smell alone instead of following the cats.
4. Complete the Dog Encounter.
5. Complete the Food Search.
6. At the final crossroads, choose **Stay free — claim the night**.
7. This unlocks **Independent Cat Ending**, as long as Meomeo does not meet the higher stat requirements for the Feral or Guardian routes.

### Recommended Test Approach

- Avoid choosing only the highest-courage options.
- Choose a risky escape option in the dog scene if needed.
- Keep Kindness low and avoid the cat family route.

### Story Meaning

Meomeo decides that belonging to herself is enough.

---

## Ending 5 — Feral King / Queen Ending

This route is for a stronger and more aggressive street-survival version of Meomeo.

### Route

1. Choose **Refuse — hiss and flee into the night**.
2. Complete the Street Wisdom Riddle Challenge.
3. Follow the food smell alone.
4. In the Dog Encounter, use the best timing option to increase Courage and Street Skill.
5. Complete the Food Search.
6. At the final crossroads, choose **Stay free — claim the night**.
7. If Meomeo has high Street Skill and high Courage, the story enters the Feral Path.
8. Complete the Alpha Challenge.
9. This unlocks **Feral King / Queen Ending**.

### Target Stats

- High Street Skill
- High Courage
- Low Kindness compared with the Guardian route

### Story Meaning

Meomeo chooses power, territory, and independence from humans.

---

## Ending 6 — Street Guardian Ending

This route is for Meomeo becoming strong, but still kind enough to protect others.

### Route

1. Choose **Trust her — walk toward the light**.
2. Complete Lily’s Memory Test.
3. At the meeting with Mina, choose **Freeze — panic and run out the door**.
4. Continue into the street route.
5. Complete the Street Wisdom Riddle Challenge.
6. Continue through the later survival route.
7. At the final crossroads, choose **Stay free — claim the night**.
8. If Meomeo has enough Kindness and Street Skill, this unlocks **Street Guardian Ending**.

### Target Stats

- High Kindness
- High Street Skill
- Enough Courage to survive the street route

### Story Meaning

Meomeo learns survival, but does not become cruel. She uses her strength to protect younger and weaker cats.

---

# Puzzle Testing Guide

## Riddle Challenge Answers

These answers can be used for testing:

1. **The night fog**
2. **Observe, then choose carefully**
3. **Fish alone — too good to be true**
4. **Warm spots attract all kinds of trouble**

---

## Food Search Safe Choices

### Safe Food Choices

- **Clean Bowl**
- **Fresh Fish**
- **Fresh Milk**

### Dangerous Choices

- **Rotten Bone**
- **Poison Trash**

---

# Quick Technical Testing

For quick technical testing, the ending screens can also be opened through the browser console:

```js
showEnding('ending_happy')
showEnding('ending_second')
showEnding('ending_cats')
showEnding('ending_independent')
showEnding('ending_feral')
showEnding('ending_guardian')
```

This is only for checking the ending screens, visual layout, ending gallery, and after-credit scene. To test the actual story logic, use the routes listed above.

---

