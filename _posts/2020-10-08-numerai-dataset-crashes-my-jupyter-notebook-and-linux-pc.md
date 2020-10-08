---
title: "Numerai dataset crashes my Jupyter Notebook and Linux PC"
date: 2020-10-08
layout: post
---

<img src="{{site.url}}/images/numerai_20200929.jpg" alt="Numerai Submission Reminder Message" style="display: block; margin: auto;" /> 

So how did I come across [Numerai](https://numer.ai/tournament), the tournament for would-be quants to predict stock market movement?  

It started off with cryptocurrency. Numeraire sits at the very bottom of cryptocurrency stocks running on the [Coinbase](https://www.coinbase.com/price) exchange (or index or what have you) in terms of market cap.  

So yeah... Numerai. It's pretty lousy. It's a hedge fund itself actually (although competitors in the tournament have zero stake in the hedge fund... they just do the grunt work to build it). And since random forests and XGBoost and AutoML have pretty much got machine learning down to a T... er... it's all going nowhere really.  

What most annoys me about Numerai is the size of the dataset. Weekly data must be downloaded and the size of this file unzipped is 3.5GB. That's do-able but running pandas read_csv() on it has thrown a wobbly to break my machine time and time again. Because I don't have enough RAM or grunt power. My machine shouldn't really crash (that's a quite serious problem I am having with Linux right now, I guess) but Jupyter Notebook is going to crash. I maybe have 12GB RAM in this machine (which is not all that tiny really) but it's not going to cut it for analysing this Numerai dataset.  

The way around it is to use [Google Colab](https://colab.research.google.com/) instead of [Jupyter](https://jupyter.org/) notebooks. It worked for me. Oh no... 'Your session crashed after using all available RAM'. At least Google Colab crashes my process but not my whole machine.  

I've managed but been late with my submissions for the first two weeks of my entry into the Numerai tournament. It's a start though. But now I need to learn how to use Google Colab. Quite enjoying it though, mostly fussing about at this stage putting datasets and models into different folders (which is not high-end machine learning). And thinking about it with a bit of perspective too. Thinking: Individual competitors competing on a fairly inane question (predicting the movement of market stocks) by seeing who can throw the fastest, biggest computer force at some pretty large datasets... what's to like?  

My point for readers here is just that if your PC has similar modest specs and your exploratory/analytical notebook (or even computer) is crashing when reading the Numerai dataset it's due to a lack of computer power.  

I watched [The Social Dilemma](https://www.netflix.com/gb/title/81254224) actually, which was quite good (silly in places). I was pleased to see a major film exploring the alarming impact of profit-motivated algorithms on social networking.  

Listening to [Lazy Dog](https://www.discogs.com/Various-Lazy-Dog/master/232788), a 2-CD set of deep house from 2000. Lazy Dog was a club night held in a small basement club in Notting Hill in the late nineties. Deep house, according to Wikipedia, 'rarely reaches a climax, but lingers on as a comfortable, hypnotic and relaxing pulse, perfect for the small, dimly lit nightclub.' I've worn my ears out with it a bit now but it's a very nice couple of mixes.