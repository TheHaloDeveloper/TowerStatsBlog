# Devlog #2

*Published: 2024-08-17*  
*Author: TheHaloDeveloper*

---

After yesterday being a success, today I continued developing my brand new JToH tower tracker.

## Badges 
I started the day by gathering a list of all the badges in the game. After that, I was able to get rid of the ones that weren't related to completing towers. I also had badges for mini towers, something that [jtoh.info](https://jtoh.info/) doesn't have.

I wrote the main backend logic to check which of these badges a player has, but there's currently some issues with ratelimits. I'll need to figure out how to get around this before releasing this website. Maybe I could use a rotating IP address system?

!asset parsed.png

## Plans
Tommorow, I'll continue the badge logic and try to figure out a solution for the ratelimit issues. It would also be nice if I could setup some UI so the code is actually viewable, rather than in the console like it is today. Some research on caching completions or using a database could help in the future as well.