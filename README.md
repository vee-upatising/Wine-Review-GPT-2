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
When Isabelle and Arnaud Guicharde opened their wine shop on Rue Ruel in 2014, they were not the first wine lovers in town. 
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
 The finish is long, dry and resinous, with a long-lasting floral note lingering. 
 The body is medium-long, so it's one to sip on to finish up.
```
The model even put a disclaimer about its review at the bottom. I am floored at the complexity of GPT-2.
```
The Chardonnay's delicate character comes through on this sparkling wine. 
Chardonnay is a fruit-forward wine that has a rich, round flavor profile. 
It is balanced, refreshing and offers enough complexity to keep one interested. 
Chardonnay comes in all different shapes and sizes, and so if choosing a particular size will offer the right balance between acidity and sweetness, choose the one that fits. 
A bottle of Sauvignon Blanc or Merlot with a bit of Chardonnay is excellent.

*These are wine descriptions or opinion only. No guarantees whatsoever. 
Be sure you are familiar with the style of wine you intend to purchase before committing to a purchase or wine making process.
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
