# Devlog #4

*Published: 2024-08-19*  
*Author: TheHaloDeveloper*

---

Day 4 is here, and things are moving along really well!  

## Caching
Today I added caching to the tower completion info. This minimizes the number of badge check requests and makes the process *instant* for the player (after the initial check). The difference in speed is huge compared to before.

## Stats & Progress
I also wrote code to calculate:
- Positive energy in both Worlds 1 and 2  
- Number of towers completed per difficulty (separated by world)  

With this data, I can now display both **area unlock progress** and **difficulty progress** directly on the site.  

!asset stats.mp4  

## Plans
Tomorrow, I'll work on adding a **Completed Towers** section, along with more stats and sections to give players even more info. Progress is going great, and I think a **beta release could be ready within a week**.