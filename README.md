# LongLong Arcade

## A Handmade Game Collection

This is not a big company product. It is not backed by a team of hundreds. It is just one person, sitting in a small room in China, tapping away at a keyboard late at night. The project is called LongLong Arcade. It is a collection of seven small games that run in a web browser. No downloads, no installs. You open the page, you play.

I built this because I wanted something simple. Something that loads fast, works on a phone, and does not ask for your email or your money. Just games. Pure and simple.

But let me tell you, making this was not easy. Not even close.

## The Beginning

It started with one game. A color matching game. You know the type: a grid of squares, one of them has a slightly different color, you have to tap it. Simple, right? I thought so too. I built it in a few hours. Then I played it. And I realized it was boring. Too easy. The colors were too different. So I spent the next three days tweaking the color difference. Making it harder. Making it smoother. Adding a timer. Adding combo scoring. Adding star ratings. Suddenly it was not a quick throwaway. It was a real game.

Then I thought, why stop there? Let me add a maze. A simple maze where you move from start to finish. That took another week. Because generating a random maze that is actually solvable, and not too easy, and not too hard, is a pain. I wrote the algorithm, tested it, found bugs, rewrote it. Then I added swipe controls. Then I added keyboard controls. Then I made the maze bigger as you level up. By the time I was done, I had 120 maze levels.

Then I added Sokoban. Push the boxes onto the targets. Classic. But making sure the boxes never start on the targets? That was a nightmare. I had to write a reverse solver. I had to pull the boxes away from the goals, step by step, to make sure the puzzle was solvable but not already solved. I spent two full days on that one function. Two days. Just to make sure the boxes were in the right place.

Then came Match 3. The candy crush style game. 300 levels. No time limit. Just moves. I thought it would be easy. I was wrong. Balancing 300 levels is hard. You need a difficulty curve. You need to make sure the player does not get stuck. You need to make sure there are always possible moves. I wrote a shuffle function. I wrote a match finder. I wrote a gravity system. I tested level after level after level. Some levels were too easy. Some were impossible. I had to adjust the target scores. I had to adjust the move counts. I had to adjust the board sizes. It was endless. But I did it. 300 levels. All hand-tuned.

Then I added Snake. Classic snake. But I added three modes. Endless. Survival. And Immortal. The immortal mode was tricky. Because in immortal mode, you can wrap around the walls. You can go through yourself. You cannot die. But you still need to eat food. And you still need to grow. And you still need to avoid getting stuck. I had to change the collision logic. I had to change the movement logic. I had to make sure the snake did not get trapped in a corner with no way out. It took a while. But it works.

Then I added Pinball. A canvas based pinball game. Bumpers. Physics. Particles. Score floating text. That one was all about performance. Because pinball is fast. You have balls bouncing around. You have particles flying everywhere. You have bumpers lighting up. If you are not careful, the frame rate drops. So I learned about offscreen canvas caching. I learned about limiting the number of particles. I learned about using requestAnimationFrame properly. I spent hours profiling. I spent hours optimizing. And now it runs smooth. Even on older phones.

Then I added the Relax Zone. A place with no score, no timer, no pressure. Just bubbles to pop. Just sounds to play. Animal noises. Voices saying hello in different languages. That one was fun. But also tricky. Because making realistic animal sounds with code is hard. I used oscillators and filters and noise bursts. I tweaked the frequencies. I tweaked the envelopes. I made a cat that sounds like a cat. A dog that sounds like a dog. A bird that sounds like a bird. It is not perfect. But it is close.

## The Ad

I know. Nobody likes ads. But I put a 15 second ad at the start. Why? Because I wanted to see if I could. Because I wanted to build a skip button. Because I wanted to make something that felt like a real product, even if it is just a hobby. The ad is fake. It is just a splash screen. But it has a skip button. You can skip it any time. No waiting. No forced views. Just a little thing to make the start feel special.

## The Languages

I speak Chinese. I speak some English. But I wanted this to be for everyone. So I added four languages. Chinese, English, Japanese, Korean. I translated everything myself. Every button. Every label. Every message. I used online dictionaries. I asked friends. I checked and double checked. I wanted the translations to feel natural. Not robotic. Not like a machine did it. I think I did okay. But if you find a mistake, tell me. I will fix it.

## The Little Things

I added sounds. Little beeps and boops. I added vibrations. Little haptic feedback. I added animations. Little pops and slides. I added a dark theme. Because dark themes are easier on the eyes. I added a reset button. Because sometimes you want to start over. I added a language switcher. Because sometimes you want to read in your own language. I added a sound toggle. Because sometimes you want silence.

These little things took time. Each one was a small project. Each one had its own bugs. But they make the whole thing feel polished. They make it feel like someone cared.

## The Testing

I tested this on my phone. I tested it on my laptop. I tested it on my tablet. I tested it on my friend's phone. I tested it on my old phone that barely runs anything. I found bugs. I fixed bugs. I found more bugs. I fixed more bugs. I spent a whole weekend just tapping on buttons to make sure they worked. I spent another weekend just playing through levels to make sure they were beatable. I spent another weekend just checking the translations.

It was not glamorous. It was not fun. But it was necessary.

## Made in China

I am a developer in China. I built this in my spare time. After work. On weekends. Late at night. I did not have a big team. I did not have a big budget. I just had my computer and my ideas.

China has a huge developer community. We build things. We ship things. We learn things. This is my small contribution. A little arcade. A little piece of joy. Made with care. Made with patience. Made in China.

I am proud of that.

## The Code

The code is not perfect. It is not the cleanest. It is not the most elegant. But it works. It runs. It plays. And it is all here. For you to look at. For you to learn from. For you to improve. If you want to use it, use it. If you want to change it, change it. If you want to sell it, go ahead. I do not mind. I just want people to play.

## Final Words

This project took me months. Months of late nights. Months of frustration. Months of small victories. It was not easy. It was not quick. But it was worth it.

If you like it, play it. If you love it, star it. If you hate it, tell me why. I am always learning. I am always building.

Thank you for reading. Thank you for playing.

LongLong Arcade. Made in China. Made with love.
