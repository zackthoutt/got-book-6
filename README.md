# GOT Book 6 Generator

Are you tired of waiting for the next GOT book to come out? I know that I am, which is why I decided to train a RNN on the first five GOT books and use predictions from the network to create the sixth book in the series. The first five chapters of the generated sixth book are now available and are packed with as many twists and turns as the books we've all come to know and love. Here's the sparknotes summary:

Sansa is actualy a Baratheon and Jaime fears her because she is one of the second sons of the onion concubine...
> “I feared Master Sansa, Ser,” Ser Jaime reminded her. “She Baratheon is one of the crossing. The second sons of your onion concubine.”

Reek is still annoying people...
> “Some must, for you,” a woman’s voiced up lazily. “Gods, Reek.”

A new protagonist named Greenbeard is intorduced to the plot...
> “Aye, Pate.” the tall man raised a sword and beckoned him back and pushed the big steel throne to where the girl came forward. Greenbeard was waiting toward the gates, big blind bearded pimple with his fallen body scraped his finger from a ring of white apple. It was half-buried mad on honey of a dried brain, of two rangers, a heavy frey.

Hodor comes back and can say something other than "Hodor!"
> Hodor looked at them bellowing, “which road you should be home.”

Ned is still alive and Jon is a Lannister!
> At once they were back there and they realize the way they wanted him to answer. When Jon Lannister staggered backward, Ned saw his axe and left hand in his head.

Varys poisons Daenerys and a dead man.
> Varys poisoned Daenerys and another of the dead men. As he woke, it was a peaceful song, and now the low and the dawn was breaking up and there no smaller, robar the broken bones.

Jon rides a dragon and starts to get a little perverted...
> Jon rode the dragons in a steep circle, buried fingers in the sand and there a burnt slope. “With a man should leave us clean, wench,” he said. “Stop him. Is that much? Until you’re at Winterfell simply get inside ’em o’ wildlings, or on the sound of a bastard dies.”

Lord Friendzone is off eating stew with chunks of butter...
> Ser Jorah lingered to where the banners wending their descent down a long ways of rain. The marsh was ladling out beef-and-barley stew, cold as shy of three colors, chunks of butter.

Jaime kills Cersei and Jon becomes the wolf...
> Jaime killed Cersei and was cold and full of words, and Jon thought he was the wolf now, and white harbor... Something about the day made the butt of her grow from the hem, half the white dogs running between two of Hizdahr’s arms.

They decide to let the dogs make decisions...
> “Ask the dogs.”

It ends on a weird note during a winter storm with Jon's Targaryen side coming out in full color...
> Once, she thought, it was wrong, climbing through the cloudless terrible light noise that was no last snow. Jon did not need to share a cup or part of it, but maybe this, a fat little blind girl.

# Posted Elsewhere

- [Hacker News](https://news.ycombinator.com/submitted?id=zthoutt)
- [ASOIAF subreddit](https://www.reddit.com/r/asoiaf/comments/6vhqyr/spoilers_extended_somebody_is_training_a_neural/)
- [Vice Interview](https://motherboard.vice.com/en_us/article/evvq3n/game-of-thrones-winds-of-winter-neural-network)
- [Motherboard Article](https://motherboard.vice.com/en_us/article/bjjp4a/winds-of-winter-neural-network)
- [Udacity Blog](http://blog.udacity.com/2017/08/neural-network-game-of-thrones.html)
- [New York Post](http://nypost.com/2017/08/29/artificial-intelligence-is-writing-the-next-game-of-thrones-book/)
- [Huffington Post](http://www.huffingtonpost.co.uk/entry/ai-plot-game-of-thrones_uk_59a6a59ce4b063ae34da24bb)
- [Business Insider](http://www.businessinsider.com/ai-just-wrote-the-next-book-of-game-of-thrones-for-us-2017-8)
- [Observer](http://observer.com/2017/08/game-of-thrones-next-book-artificial-intelligence/)
- [I Fucking Love Science](http://www.iflscience.com/technology/artificial-intelligence-is-attempting-to-write-the-next-game-of-thrones-book/)
- [Futurism](https://futurism.com/the-next-five-game-of-thrones-chapters-have-been-leaked-by-an-ai/)
- [Science Alert](https://www.sciencealert.com/everyone-s-so-sick-of-waiting-for-the-next-game-of-thrones-book-an-ai-just-wrote-it-for-us)
- [Gizmodo](http://io9.gizmodo.com/rest-easy-george-r-r-martin-a-computer-program-has-w-1798541924)
- [Le Monde](http://www.lemonde.fr/pixels/article/2017/09/01/on-a-lu-une-suite-de-game-of-thrones-ecrite-par-une-intelligence-artificielle_5179449_4408996.html)

And many other places on [Google](https://www.google.com/search?q=zack+thoutt+game+of+thrones&oq=zack+thoutt+g&aqs=chrome.0.69i59j69i60l3j69i57.1918j0j4&sourceid=chrome&ie=UTF-8)

# Training the Model

If you would like to train this model, you will need to use a GPU and Tensorflow 1.0. I used FloydHub with the following command:
```
floyd run <your-project-id> --gpu --env tensorflow-1.0 --mode jupyter
```

The text data can be found many places online.

# Contributing

There are still so many unanswered questions. Is Jon actually a Lannister-Targaryen? How will the dogs rule the seven kingdoms? Why did Varys poison Daenerys? Who are the seconds sons of the onion concubine?

If you would like to help sing the song of fire and ice, feel free to use this repository and offer advice on how to improve the model. I'm still fairly new to neural networks, so any help would be greatly appreciated. I will consider merging pull requests if they make significant changes and improvements to the model.
