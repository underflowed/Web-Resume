---
cover : 
title: "Projects."
date: 2022-02-13T14:06:58-05:00
draft: false
cover: "https://i.stack.imgur.com/Hcc35.png"
---

## Text adventure game written in Rust.

https://github.com/underflowed/text-adventure-game-in-rust

This project was done in an attempt to learn Mozillas rust programming language, I also learned some interesting concepts involving storing objects in matrices
```rust
let mut map: Vec<Vec<Option<Box<dyn Room>>>> = vec![
        vec![
            Some(Box::new(EntranceRoom {})),
            ],
        vec![
            Some(Box::new(AxeRoom{})),
            Some(Box::new(BodyRoom {})),
            Some(Box::new(DarkRoom {})),
            ]

    ];
```
Storing room structs in the map as a way of maneuvering in 2D space was interesting concept to implement. (Fun fact! Half of this code was written in Cuba on a trip with 0 internet access and only a copy of Rusts documentation!)

## Visual Novel

https://github.com/underflowed/official_stovoy_VN

Fun project I made in collboration with a friend to make a visual novel in the RenPy game engine, based on a good friend of mine (and also extremely experienced developer and streamer!) Steve Mostovoy

## Discord bot that scrapes Magic The Gathering card info.

https://github.com/underflowed/Coolstuff-Bot

Made in excercize to try and learn HTML parsing by scraping MTG card information off of the coolstuffinc.com website. Also learned something about using web servers by deploying it on Heroku. It was actually used by the company on it's official discord server!



