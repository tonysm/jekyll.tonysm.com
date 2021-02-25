---
layout: page
title: Hotwire & Laravel
permalink: /courses/hotwire-laravel
---

I've been working on [Turbo Laravel](https://github.com/tonysm/turbo-laravel) - a package that bridges Hotwire with Laravel, and although I have done an [introduction to Hotwire](https://youtu.be/qqLVbd_uGiI?t=171) before, I didn't really dive into using the package itself (lol, right?). And I also didn't cover the [Turbo Native](https://turbo.hotwire.dev/handbook/native) aspect of building applications this way, so... it's time!

## Screencasts

If you enjoy video content, I've recorded 3 videos showing the building blocks of using this technique.

### 01 Hotwire 101

In the first episode, I cover what [Hotwire](https://hotwire.dev/) is, going over the concepts of Turbo Drive, Turbo Frames, and Turbo Streams over HTTP (as responses). The demo application uses a Laravel app. We end up having to do a lot of boilerplate to get things to work (such as request validations).

<div class="embed-responsive">
    <iframe src="https://www.youtube.com/embed/d11HRp-WYC4" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" frameborder="0"></iframe>
</div>

### 02 Turbo Laravel

For the second episode, it's time to introduce the [Turbo Laravel](https://github.com/tonysm/turbo-laravel) package and solve some of the pain-points we saw on the previous video. I also take the opportunity to show how to broadcast Turbo Streams over WebSockets, and for that I go over how to setup the [Laravel WebSockets](https://beyondco.de/docs/laravel-websockets/getting-started/introduction) package with [Laravel Sail](https://laravel.com/docs/8.x/sail) so you can test it all locally.

<div class="embed-responsive">
    <iframe src="https://www.youtube.com/embed/70fCMBNsKvs" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" frameborder="0"></iframe>
</div>

### 03 Turbo Native

For the third and last episode, I go over the [Turbo Native](https://turbo.hotwire.dev/handbook/native) aspect of Hotwire. The Basecamp folks prepared a [demo app](https://github.com/hotwired/turbo-android/tree/main/demo) for us, so I'll use that to show the technique. A little disclaimer here: I'm no mobile developer. I've done an Android development course once, but it was a long time ago. Anyways, I think this is a really powerful way of building hybrid applications and allows you to enhance your mobile apps per page and as much fidelity as you need.

<div class="embed-responsive">
    <iframe src="https://www.youtube.com/embed/RcGgpY6sERo" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" frameborder="0"></iframe>
</div>

## Hotwire & Laravel

The [Turbo Laravel](https://github.com/tonysm/turbo-laravel) package is pretty much done. I haven't tagged v1 yet because I'm waiting on the [Turbo.js](https://turbo.hotwire.dev/) library to get stable as well, although I can't seen anything changing that would force me to change a lot (the integration surface of the backend and Turbo.js is really small).

I thought of writing a longer version of an introduction to the package itself (some kind of Getting Started), but I think that both the [Turbo Handbook](https://turbo.hotwire.dev/handbook/introduction) and the [Turbo Laravel documentation](https://github.com/tonysm/turbo-laravel/tree/main/docs) really covers a lot of what is possible. So, for now, I'll just reference them.

I hope you enjoy the videos and let me know if I said something wrong.
