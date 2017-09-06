# AnimeJS-App

I really like Frontend Web Development and especially different visual effects based on the jQuery. I like to know something new every day, so I created this simple app to be more familiar with AnimeJS.

**AnimeJS** is a lightweight JavaScript animation library. It works with any CSS Properties, individual CSS transforms, SVG or any DOM attributes, and JavaScript Objects.

![1](https://user-images.githubusercontent.com/28790452/30134682-9469ad7e-931d-11e7-95f5-e733b73e5a8c.gif)

## Function based values

Get different values for every target of the animation.
The function accepts 3 arguments: `target`, `index`, `targetsLength`.
```
anime({
  targets: 'div.box.red',
  translateY: [
    { value: 200, duration: 500 },
    { value: 0, duration: 800 }
  ],
  rotate:{
    value: '1turn',
    easing: 'easeInOutSine'
  }
});
```