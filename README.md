# Compute, Storage, and Network Core

This repository contains my notes and research on the three foundational pillars of computer systems. 

To make sense of how these three interact, I like to use a restaurant analogy:

### 1. Compute (The Chef)
Compute is the processing power (CPU/GPU). In a restaurant, this is the chef. The chef takes raw ingredients, processes them, and creates a meal. The faster the chef, the faster the work gets done. It doesn't store things long-term; it just does the immediate work.

### 2. Storage (The Pantry and Fridge)
Storage is where data lives (RAM, Hard Drives, SSDs, Databases). This is the restaurant's pantry. When the chef needs ingredients, they pull them from storage. 
* RAM is like the counter-top (fast, short-term).
* Hard drives are like the deep freezer (slower, but holds a lot long-term).

### 3. Network (The Waiter)
The network is how data travels (Routers, Cables, Wi-Fi). This is the waiter carrying the food from the kitchen to the customer. Even if you have a fast chef (Compute) and lots of food (Storage), if your waiter is slow, the customer has a bad experience (high latency/lag).

---
**To-do list for this repo:**
- [x] Define the big three concepts
- [ ] Add a diagram of how they connect 
- [ ] Look up how AWS handles these three things
