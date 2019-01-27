# Slime
Slime

This IS NOT my code. 
Source: https://cdn.rawgit.com/marler8997/SlimeJavascript/master/SlimeVolleyballLegacy.html
Used to HTTrack to and WebHTTrack to download.

Intention of this repo is to learn how the JS works and potentially create a JS game dev activity.

The JS is pretty complex and would take significant time to gain an understanding to replicate an example of it.

---

Notes:

I'm guessing this was a clone or manual emulation of the Java Version. It's pretty spot on with a couple bugs, seems like the Slime Volleyball I played back in highschool.

The JS seems somewhat similar to the JS game build in [Eloquent JavaScript](https://eloquentjavascript.net/16_game.html).

The AI slimes actually have a miss-jump percentage chance which I think is responsbile for when they miss on a serve.
Ball speed is determined by x and y velocity values between small range (ex: 15-22).
It seems that each single AnimationFrame is based on the previous AnimationFrame.
Similarly, the ball velocity x,y values are dependent on the previous AnimationFrame's ball velocity x,y values.

Activating the slow motion cheat seems to trigger a return false for 50% of the AnimationFrame updates.
Essentially updating the AnimationFrames at 50% of the speed at which they are processed, giving the human player ~twice as long to anticipate and react.

---

Ideas:

Would be fun challenge to add some sort of mobile controls.
