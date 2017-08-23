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

John rides a dragon and starts to get a little preverted...
> Jon rode the dragons in a steep circle, buried fingers in the sand and there a burnt slope. “With a man should leave us clean, wench,” he said. “Stop him. Is that much? Until you’re at Winterfell simply get inside ’em o’ wildlings, or on the sound of a bastard dies.”

Lord Friendzone is off eating stew with chunks of butter...
> Ser Jorah lingered to where the banners wending their descent down a long ways of rain. The marsh was ladling out beef-and-barley stew, cold as shy of three colors, chunks of butter.

Jaime kills Cersei and Jon becomes the wolf...
> Jaime killed Cersei and was cold and full of words, and Jon thought he was the wolf now, and white harbor... Something about the day made the butt of her grow from the hem, half the white dogs running between two of Hizdahr’s arms.

They decide to let the dogs make decisions...
> “Ask the dogs.”

It ends on a weird note during a winter storm with Jon's Targaryen side coming out in full color... 
> Once, she thought, it was wrong, climbing through the cloudless terrible light noise that was no last snow. Jon did not need to share a cup or part of it, but maybe this, a fat little blind girl.

# Training the Model

If you would like to reproduce my work, you'll need to train the network on a GPU with Tensorflow 1.0.0. I used FloydHub to train my network with the following command:

```
floyd run <your-project-id> --gpu --env tensorflow-1.0 --mode jupyter
```

# Contributing

There are still so many unanswered questions. Is Jon actually a Lannister-Targaryen? How will the dogs rule the seven kingdoms? Why did Varys poison Daenerys? Who are the seconds sons of the onion concubine? 

If you would like to help sing the song of fire and ice, feel free to use this repository, put up pull requests, and offer advice on how to improve the model. I'm still fairly new to neural networks, so any help would be greatly appreciated.
