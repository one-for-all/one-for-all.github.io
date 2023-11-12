---
title: "Satellite York"
date: "2023-11-12"
---

So I spent some time to create my very first satellite York. "York" comes from
欲 of 食欲, which means appetitie.

It is built fairly straightforwardly. We give it a high-level instruction, namely
picking meals for the user, taking into consideration of budget, nutrition and
variedness. And we provide the names of some restaurants near when I live, all of
which have menu online, so that York can do a web search to find out their menu.

An obvious insufficiency is that the restaurants are limited to the ones we
provide. To tackle this, I had turned to [Google Places
API](https://developers.google.com/maps/documentation/places/web-service/overview),
where it can return places of some type, e.g. restaurant, near a certain
location. However, it does not provide menu information, and no website link.

For now, I will work with the York I have now. 🎉 Happy first, though immature, satellite.
