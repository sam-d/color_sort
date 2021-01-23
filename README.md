Background
==========

I saw an fun little game on a friends mobile phone but could not find any
version of it in the open-source app store F-Droid. Then I thought to myself
that it cannot be too hard to implement. It took a few hours to think through
the concept, half a day to implement and another 2 evening to iron out the
kinks.

I chose plain javascript, because it is the most portable approach. Since I
wanted to play it on my mobile phone, this would also give me the opportunity to
turn it into a progressive web app (PWA). This technology is supposed to give
HTML5+JS content a native feel. It gets you a icon/launcher on you mobile phones
home screen. Using open technologies such as localStorage and web workers (not
required in this simple example) one can ensure content be available when
offline and reload in the background when connectivity is resumed.

Where to try
============

If you have some time to waste you can play
[here](https://services.sam-d.com/color_sort).
