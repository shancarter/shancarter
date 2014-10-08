
1
I first fell in love with electoral calculators in 2004. I was working in a newsroom in San Jose laying out news pages for The Mercury News. My and my boss Kevin Wendt were waiting for our sections to close and we were dicking around on other news sites. I can still remember him turning around his 19-inch CRT monitor -- it was craned up on a huge metal arm -- and saying "check this out." Looking back I sort of think of it as a turning point, but really at the time I didn't really feel anything special. Anyway, what he showed me was the nytimes.com electoral calculator. Looking at it now, it looks pretty simple, but at that moment, in that newsrooom, spending my time designing static documents, it was new, shiny, and exciting. I think at that moment I fell out of love with print and in love with interaction.

2
A few years later I was lucky enough to get a job at this newspaper doing exactly the sort of thing that has been so exciting to me. And a few years after that, I was assigned to make the calculator in 2008. And it sucked.

3
2012 results as it is on our website right now.
While the form is easy to understand. it is very old

4
William McKinley (R-shaded white) defeats William Jennings Bryan (D-shaded black). Page 1 of The New York Times on Wednesday, November 4, 1896. (Virginia, North Carolina and a handful of other states in the West were shaded incorrectly.)

So why do I now dislike those electoral scenario maps so much? Because the root visualization, the electoral college choropleth map, is flawed.

After much hand wringing, i realized it's flawed in 4 ways.

5
Area problem

6
Can be solved with cartogram

7
But something there is something else that is harder to fix.
Here are 4 very different elections, and they look basically the same.
It's not very good at showing what's unique about each year.

8
Interaction problem
Painting the map
The problem is

9
When you paint the map you lose information. We're using color to encode both OUR choices and the INITIAL choices. So as you interact with it there is information lost.

10
At the end of 2008 I had this idea of putting bubbles into bins. Mostly I thought it would be fun, and nothing more, and sort of shelved the idea. But in 2012, when I begin redesigning the calculator I realized that this could solve all of my problems.

size is fixed and you could use color to encode original choices and position to encode YOUR choices.

12
Not only that but different scenarios actually looked different

13
Glenn Beck even liked it!
But after we launched this and I had been playing with it for a few months, I became increasingly frustrated with it though. It just felt like too much work. I felt lost using it.

14
So I decided to code up something for myself that just focused on the tossup states, because that's all I ever moved around.

15
I came upon what the problem was: I was feeling lost, exploring a world of possibilities, mining it for information or interesting scenarios.

Now, this is not bad. This can be a great way to learn and some people actually prefer this form of exploration / interaction.

16
But other people prefer being given a map.

17
So I decided to look at all the options.

18
And filter that down to all the options that made a difference.



Recently Mike Bostock joined our team.

In print you can't hide anything, it has to be good at face value.

Most people in our department come from a print background.


With all these calculators, you're exploring the universe of possibilities, but exploring it one path at a time. If instead of exploring this forest by walking all the trails, couldn't we just show people the map of the area?








I want to end with a little postscript about how to do good work. I get question how do you come up with your ideas, or what's your process. Basically, the only thing I know for sure is that everything I've done, even if my name is the only byline, is made better by all my talented coworkers. Whether it's getting someones. My work has been made so much better by being surrounded by super talented, nice people. SO the only advice I have is try to find other like minded people smarter than yourself and convince them to be friends with you.