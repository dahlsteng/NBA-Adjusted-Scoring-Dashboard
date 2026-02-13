This project adjusts the scoring for the top 50 scorers of each season since 1979 using the following formula. 
  FTs: .67 pts
  2pt: 2 pts
  3pt: 2.67 pts
You can stop reading here if you want. Everything that follows is how/why i did this. 

**Why:**
I started this project because I was interested in a systemic way to realign scoring incentives in the NBA that didn't involve officiating. I'm not an oldhead who misses the days of isos from the midrange. The modern NBA is *mostly* quite fun to watch in my opinion. But the influence figures like Steph, James Harden, and Daryl Morey have had on the way the game is played is undeniable. The NBA shoots more 3s than ever before and as an OKC fan, I can't go into any comment section without (correct but annoying) accusations of foul baiting. 

Part of the analytics movement in the NBA came from teams recognizing that a 3 is worth 150% of a 2. A 40% 3pt shooter provides the same expected value as a 60% 2pt shooter. You can do similar math with free throw shooting. The best shots in basketball are layups, free throws, and 3s **because of the math**. 

So what if I changed the math? What if we changed how much shots are worth? 
  FTs: 2
  2pt: 3
  3pt: 4

That changes the math so a 3-pointer is worth 133% of a 2-pointer while a free throw is worth 33%. 

Let's do a quick list of pros and cons for this idea:
  Cons:
    - it goes against the sanctity of basketball
    - it's ugly
    - it makes historical comparisons more complex
    - it would likly devalue Steph Curry's career
    - it would likely memorialize James Harden as a Wilt or Shaq-esque figure who caused the rules of basketball to fundamentally change

  Pros:
    - it makes free throws and threes less valuable
    - we have box score stats to do historical conversions if needed
    - it would likely devalue James Harden's career 
    - it would likely memorialize Steph as a Wilt or Shaq-esque figure who caused the rules of basketball to fundamentally change

**How**
1. I used box scores for every player season since the 3pt line was introduced (1979). Right now it is just Top 50 scorers per season but I may expand to every player season in the future.
2. Re-weight scoring using a 1/3/4 system (FT=1, 2PT=3, 3PT=4)
3. Rescaled scoring back to the 1/2/3 format while preserving the new ratios (FTs worth ~0.67, twos worth 2, threes worth ~2.67)
4. Started messing around as I explored the changes that occured
