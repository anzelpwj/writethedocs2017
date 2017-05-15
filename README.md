# The Science(?) of Documentation

## WriteTheDocs, Portland, 2017

## Paul Anzel, Data Scientist, Metromile Inc.

# Script

### Slide 1

Hello everyone, my name is Paul Anzel, and I’m NOT a documentarian. Instead, I’m a data scientist, though one who has had to use enough ill-documented code to want to try and do better. Hence why I’m here to hang out with y’all today.

### Slide 2

Like most data-scientists, I went through the academic pipeline until I realized that was a mug’s game, but old habits die hard and I thought a good way to try and learn how to do documentation right would be to see what sort of research there was. So, I went to Google Scholar, entered in “software documentation” and looked to see what I would get.

### Slide 3

First off the bat, what I found were surveys with people complaining about the state of documentation: things are obsolete and incomplete, and programmers are going right to the source code because they don’t even know if they can trust what docs they get.

### Slide 4

So, yeah...

### Slide 5

But wait, it gets worse!

There’s not really that much more peer-reviewed research beyond that! We all know things aren’t where we want them to be, but what changes should we make to improve matters? If all I get is a Friday afternoon to document our API, should I write a tutorial or try and just do a general reference?

For the most part, people have written books and blog-posts about what’s worked for them, which in science we call a “case study”. And case studies are important! We see them all the time in medical journals. But alone, they’re not sufficient.

### Slide 6

Now, I realize that this is pretty much what I sound like right now...

### Slide 7

...and this is not my intention! And, in all fairness, it’s not like my corner of the office does much better.

### Slide 8

One of my favorite authors in the tech industry is a fellow named Greg Wilson. One trenchant thing he’s said is that the field probably isn’t ready to be called “Computer Science”, but rather “Computer Two Beers and Here’s My Opinion”. There is some research, much of which he collected in this book, but it hasn’t filtered down.

Here’s one recent example--this fellow named Andreas Stefik has been doing research into how people, especially beginners, learn programming languages. For a basis of comparison, he and his grad students designed Randomo, a language where the syntax was randomly generated. He then had beginners try and learn a number of different languages to see how well they could pick them up. Turns out, the C-family languages--Java, C, and Perl--were all as hard to learn as Randomo.

The programming community--trained, experienced professionals--took this information in with measured consideration...

### Slide 9

[pause]

### Slide 10

But, my main point here is not to scold, but to say that I think we have some real opportunities to do some good science here! Let’s methodically test our assumptions! If you’ve got a number of coders who might be game to try things, let’s see how they consume your internal API, and try and couple of different methods to see how they work. And then share your results with the rest of us!

### Slide 11

Now, there is a fair amount of educational psychology literature you can draw on, though I haven’t seen it filter into the books or blog-posts I’ve seen. I’m not actually going to go over these, but I recommend going to the links and reading this book for more details.

### Slide 12

And social science is difficult! Humans are unpredictable beings and we’re often looking for subtle effects. But there are some good things I’d recommend as rules of thumb.

First, be very careful when you read a study that it’s not looking at a very small sample size. So many of the headlines you see along the lines of “Chocolate causes cancer! No wait, it cures it! No wait...” are dealing with looking at too few people to really make a strong assessment.

Second, if no-one shows you how uncertain they are, be careful. There’s going to be a lot of noise.

Third, look to see how important the effect is. “Statistically significant” and practically significant are two very different things.

Finally, there are different types of studies, and I have a heirarchy of how much trust I should give to each. Case studies - “I did this” are a start, but I’d like to see us doing more surveys and randomized controlled trials! And, once we get those, we can start doing meta-analyses, which are when we look at multiple studies on a particular subject, try and assess their strengths and shortcomings, and then try and really get a good handle on what we’re seeing.

### Slide 13

One final thing--while I wasn’t able to find a good cost-benefit article on software documentation, I did find an interesting article in science popularization. At one point, I believe in the 80s, the writers of the New York Times went on strike and while they wrote the articles, they did not publish anything. This included the science section of the Times.

As it turns out, this ended up being a nice natural control-study on whether or not having scientific work written up in the lay press did anything for whether or not these studies got extra citations. Since the Times writers were still selecting papers to write up, the authors of this study were able to compare citation rates for the ones written up and published versus the ones merely written up. As it turns out, being published in the Times led to an over 70% improvement in citation rates.

### Slide 14

So, even though it’s by analogy, I think I can have some real confidence in saying what we’re doing here has some real value. And the experiences people will be sharing here are definitely useful for us to learn from as case studies.

But I think, if we try a more methodological approach to demonstrating why we believe what we believe, we will be even better.

### Bonus slide

So, here’s a bad example I saw going across Facebook a month or two ago. A survey came out a bit ago saying that millennials are much more likely to want people to be in traditional gender roles in families (that dip right around 2014 on the left), which many media articles made great hay out of.

But many folks found some real problems in the study--this dip reflects only 66 men, and if they had bothered to plot error bars they would be bigger than the observed dip. Some folks reran the numbers with larger bins (young Americans being 18-34 instead of 18-25) and the effect pretty much disappears.

So, hashtag-millennials, amirite?
