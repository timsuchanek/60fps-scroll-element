#60fps-scroll-element
This library is 99% what [60fps-scroll](https://github.com/ryanseddon/60fps-scroll)
does. But there were some points to create an own little lib:

  1. In my case the scrolling wasn't happening on the window, because I had an absolute
  positioned element. So I needed to pass in the element to scroll
  2. It was on bower. I'm using webpack, where bower doesn't work great.
  3. I needed it right now. Maybe later we can merge it.

## Credits
100% Credits to [Ryan Seddon](http://www.thecssninja.com/javascript/follow-up-60fps-scroll)

## License
MIT