The Legend of Heroes: Trails from Zero Assets
=========

The aim of this project is to attempt to upgrade the look of various portraits in the PC version of *The Legend of Heroes: Trails from Zero*. As many of you probably already know, Trails from Zero has been ported from the PSP to PC and released in China by JOYOLAND. Long story short, in 2013 it was localized to Japanese and released with **Windows 8 support**. However, the game didn't come free of bugs and graphical issues, the most common of which was the yellowish shade all portraits features. What I tried to do was to fix this issue by porting the good assets from the *Evolution version* of the game, all the while trying to upscale them to better fit the higher resolution of the PC version. From Evolution, I also ported a few other things, and they'll be included in this package as a separate download. We'll go into details in a bit.

## The method

This isn't by far an original project, and thus some users may already know where I'm going with this. Believe it or not, many of the assets available in the Vita version of the game had the same resolution as the PC version. Heck, there are even assets at higher resolutions. Unfortunately though, the **dialogue portraits (and not only those) aren't part of those lucky assets**. While the PC version features 384p portraits, the Vita version runs them at 256p. In these cases, where possible, I used **Waifu2x**.

For those who don't know what that is, it's a **Convolutional Neural Network** whose primary objective is to upscale pictures and reduce noise. Waifu2x is mainly trained to work with Anime artstyles, but it can handle photos as well. Now, I can't stress this enough, but this isn't a perfect method. While it might work fine with in-game sprites, portraits with defined linearts like in our case suffer from its smoothing filter. The reason why this method work is because portraits are displayed at a lower resolution than what I achieved, *masking* in a way the artifacts.

**NOTE**: I began working on this project quite some time ago. I'll keep researching this subject, and eventually update the assets as I find better methods. I'm also open to suggestions about which Neural Network to test, should anyone of the users know about a better one.

## Preparation

Before we keep talking about the project, you need to prepare your environment to accomodate the assets. So, let's see what you need, shall we?

#### 1. The Japanese PC version of The Legend of Heroes: Trails from Zero

You can purchase the game from Amazon Japan or DLSite, and you can use [this guide](https://www.reddit.com/r/Falcom/comments/7jee3m/how_to_legally_buy_zero_no_kiseki_trails_to_zero/) if you need help with that. Credits to **Luke, the Sexy Irish one** for providing us with this method.

#### 2. The Geofront Patch

This is a patch that fixes A LOOOT of issues with the vanilla version of the game, and it's the only way for my assets to work, as this adds PNG support to it. You can download the patch on [their blog](https://geofront.esterior.net/).

With this out of the way, we can actually talk about the project in detail.

## The core of the project

So, as I said, the main objective is to to bring the portraits up to speed, but I wanna talk a bit more in-depth about what that entails. But first, a comparison for you, so you have an idea about what we're talking about.

![Pic1](doc/res/01.png)