---
layout: post
title:  "Endemic Bird Species Around the World (Exploring BirdMApp Data, Part #1)"
categories: [ BirdMApp ]
tags: [birdmapp, data-analysis]
image: assets/birdmapp/Endemic.png
hidden: false
featured: false
---

There are many curious things that I've uncovered when dealing with bird observation data from GBIF. For example, Estonia has 10 and 8 times as many bird observations as the neighboring Latvia and Lithuania, respectively, despite having a fraction of population. Why so? It turns out that Estonia uses A LOT of cameras for bird identification. I don't know if the stark difference between the countries is because Latvia and Lithuania do not use as many cameras (adding to Estonia's reputation of tech-savviness) or because they do not upload their data to GBIF. It's a curious fact that I'd like to explore in the future.

A thing that crossed my mind as I was working with the data was that I wanted to mark species in country tables that are endemic to that country/area. I was very curious as to whether there are any endemic species in places that I travel to. I could check the data very quickly by simply filtering the data, but I knew that there wasn't any visual representation of this (or even a table) anywhere online, so I decided I'll make one myself and share it with the world, in case there are other curious minds searching for this information. So here it is. The methodology is still the same as it was in [BirdMApp](/birdmapp) as it's the same dataset, so I will not dive into it. Instead, I want to draw your attention to a few curious facts:

1. There are very few endemic species in the colder climates. I specifically chose not to cut off the northern hemisphere to show the stark contrast.

2. Galapagos Islands, despite being the most famous for its unique flora and fauna, is not the one only exceptional island in terms of amount of endemic species. Have you ever heard of unique biodiversity of Sao Tome and Principe, the island to the west of Central Africa, or that of French Polynesia? We need to work on PR of those islands.

3. You will not see Antarctica with any endemic species, e.g. Emperor Penguin. This is because on my map Australian Antarctic Territory is not part of Antarctica; so the aforementioned Emperor Penguins that have been observed on Heard and MacDonald Island do not let Antarctica claim even one bird species.

Which leads me to admit the un-fun thing. This map is not perfect because it does not take into account instances when the species are endemic to a place, but are not constricted by an artificial border. But then, if I start to look at birds that are endemic to 2 countries, 3, 4... where do I draw the line and still keep it a meaningful graphic? There are a few approaches I could take, but I decided against it for now. 

Until then, I will just keep relying on BirdMApp extensively on my travels, and draw the conclusions from rarity, red list category and amount of total observations.
