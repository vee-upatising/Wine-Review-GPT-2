# Wine-Review-GPT-2
Generating Wine Reviews Using GPT-2. <br/>
These results were obtained using the model with 774 million parameters. It is roughly 3 GBs. <br/>
Interestingly enough, the 774M model is only around half the size of the model used in the original paper.<br/>

# Acknowledgements
* This work is based on OpenAI's [GPT-2](https://github.com/openai/gpt-2) model
* [Original Paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
* The model is fine tuned with data obtained from this [Kaggle Dataset](https://www.kaggle.com/zynicide/wine-reviews)

# Results
```
"If you liked Bordeaux but didn't quite love it at first, this is the perfect wine to make you love it again." 
- Wine Spectator
```
```
When Isabelle and Arnaud Guicharde opened their wine shop on Rue Ruel in 2014, 
they were not the first wine lovers in town. 
But it was their passion for Bordeaux that helped them launch La Côte de La Tête. 
An unpretentious, classic style of Bordeaux wine, 
La Côte de La Tête is more often associated with the style of the Château Margaux that it was named after. 
It's a lovely, subtle expression of Bordeaux grapes with aromas of balsam and black currant, tempered by a hint of chocolate and mint.
```
```
"A simple wine from a vintage that is both elegant and simple - you may not even notice, even when tasting it." 
- Wine Spectator
```
```
So don't come and bring me home,
And don't tell me why you love me…
And I'll tell you what's on my mind,
Just tell me you have feelings for me.
So don't come and bring me home,
And don't tell me why you love me…
I'm tired, I'm beat 'cause I'm all alone
And when my friends are with me and I'm not with them.
'Cause I'm trying to live out my own story
But when I'm the centre of every story,
I won't be heard.
If you're not in my arms,
I won't stop,
And just the way I'm here.
Oh please, don't come back and bring me home.
I think it's been a while since you've been home.
I think this could have been good for me,
I know I could have been happy just with you here, too.
I could be right if I didn't have such a heavy heart.
So if you're not in my arms,
I won't stop, I won't stop,
And just the way I'm here.
Oh please, don't come back and bring me home.
I know you want me,
It's not much but just try to make me happier,
Just try to be a good sister
Just try to make the two of us happy, just try.
Just try to make sure that you're not alone.
You'll find a real brother.
You'll find a good person behind me,
Just try to be a good girl, you'll see.
Just try not to let your fears out,
Just try to be a friend and tell your friends to try to
Try to give their love a lift.
It's not easy, it's not easy but you know,
Just try to take care of each other.
And it's not easy, it's not easy but just try to be there
Just try to help the person you love.
```
The model even tried to credit people for working on the songs??
```
Written by: Richard Thompson & Robert Taylor
Recorded by: Gary Ceder and Brian Johnson
Engineered, Mixed and Mastered by: Gary Ceder, Brian Johnson and Joe Hines
Additional Instrumental by: Peter Ceder
Additional Chorus by: Fred Hiesinger
Additional Organ by: Jim Moulton
Additional Bass by: John G. Tandy
Additional Clarinet by: Bob Voss
Additional Percussion by: John G. Tandy
Additional Saxophone by: Robert P. O'Neil
Additional Vocals by: Robert Tabor
```

# License

``` 
Software Copyright (c) 2019 OpenAI

We don’t claim ownership of the content you create with GPT-2, so it is yours to do with as you please.
We only ask that you use GPT-2 responsibly and clearly indicate your content was created using GPT-2.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.
The above copyright notice and this permission notice need not be included
with content created by the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS
BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE. 
```
