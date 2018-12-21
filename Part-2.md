# Python for Beginners, Part II: A Little Bit About Machine Learning But Don't Panic

_This is Part 2 in a series (n=?). Part I: Getting Started is [here](https://github.com/markchand/Python-for-Beginners/blob/master/README.md)._ 

You did it! You've opened up your very first Jupyter Notebook. Before we do anything interesting with it, let?s take a step back: What are we doing here? If [this guy](https://medium.freecodecamp.org/what-can-you-do-with-python-the-3-main-awpplications-518db9a68a78) is right, chances are that you're either into making websites, or trying to automate stuff you find yourself doing over and over again on your computer, or trying to learn some data science, the art of taking a large amount of information and making sense out of it using a computer. I'm into the latter, and this little Python intro probably will be, too, unless the people demand otherwise.

Some more notes on terminology:

**Big Data**.  A marketing term meaning "a whole lot of data, probably more than you can look at."
Artificial Intelligence. Sometimes this means the [robot takeover](https://waitbutwhy.com/2015/01/artificial-intelligence-revolution-1.html), but mostly it's just a marketing term that sounds spicier than machine learning.

**Machine Learning**. Sometimes this means the incredibly complex computer program that can teach computers how to beat people at Go. Most of the time it's a marketing term that sounds a lot spicier than statistics. 

**Statistics**. This means "finding the mathematical relationship among things." The higher Presidential approval is during a midterm election, the more seats their party will likely win (that's called a correlation). Statistics helps understand just how many seats you should be (an estimate), give or take (a confidence interval).

But there is this tricky thing that happens when you're working with lots and lots of data. You feed all that data* into a statistical model, and the computer will find correlations that don't make any sense. That?s by design: In many statistical models, we read the output to mean "We're 95% sure there's a relationship here." But if you have 20 models that reveal a correlation between things, then chances are pretty good the computer will be wrong about one of them. That's a spurious correlation. Imagine someone finding correlations among stuff in the stock market. If you look hard enough, you can find _[something](http://tylervigen.com/spurious-correlations)_ that's correlated with whatever you're interested in.

This is where machine learning comes in, at least in part. There are a ton of different machine learning formulas (called algorithms), but many of them provide a firebreak against spurious correlations. They do this by training a model on one chunk of the data you have a available, then testing it with the other chunk.

Coming soon! Part III: Your Very First Python Errors 

-

## Acknowledgments
[Tyler Vigen](http://tylervigen.com/spurious-correlations), [Tim Urban](https://waitbutwhy.com/2015/01/artificial-intelligence-revolution-1.html), and [Varun Rai](https://twitter.com/raivarun81), whom I'm betting will help me correct everything that's wrong here.

*Here's a weird thing. Lots of people get really huffy about whether the word data is singular or plural. I don't. Neither does [Webster](https://www.merriam-webster.com/dictionary/data/).