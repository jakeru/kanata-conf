# Kanata configuration

## Background

I have been using [KMonad](https://github.com/kmonad/kmonad) for a long time
and it have suited me well.

However, in November 2023 I found [Kanata](https://github.com/jtroo/kanata),
and since it was written in Rust I decided to give it a go.

Since I already knew which configuration I wanted to have it was a very quick
exercise to get it working.

## Comparison between KMonad

In my [KMonad configuration](https://github.com/jakeru/kmonad-config) I have
one configuration for each keyboard. Since number of keyboards is always
increasing I decided to simplify things.

In this Kanata configuration the same configuration is used for all keyboards.

## Description

The idea with my `defsrc` layer is to only include (more or less) the keys I
intend to actually use and that are available on all my keyboards.

Caps lock works as escape when tapped and control when pressed. This is
something that is very hard to live without.

I use the left shift as it is.

I do not use the left control at all so that is not included in `defsrc`.

The next key is the left meta key and I use it as super key for my window
manager [i3](https://i3wm.org/). By tapping it I can insert one symbol from my
symbol layer.

Then comes the left alt key. In the applications I use I have noticed that that
key is not very important. In cases I need it I can press the right alt key
instead. When I press the left alt key I reach my navigation layer. In that layer
the vim navigation keys works as arrows and I can access other buttons such as
home, end, delete, backspace and enter. I can also copy and paste.

The next key is the space key. I use it for space. And as enter if left alt is
pressed.

After that comes the right alt key. This key works as enter when tapped and as
right alt when pressed.

## To Do list

- Move tab to a more easy accessible location.
