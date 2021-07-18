# Stats Preview Card Component Solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 💪

## Overview

### The challenge

Your challenge is to build out this card component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Users should be able to:

- View the optimal layout depending on their device's screen size

### My solution

- [https://genuinestalwart.github.io/Stats-Preview-Card-Component](https://genuinestalwart.github.io/Stats-Preview-Card-Component)

## My process

### Built with

- Semantic HTML5 markup
- CSS media queries
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to apply graphical effects to an image while figuring out how to set the color of **image header** to violet. 😳

```css
img {
    filter: hue-rotate(300deg);
}
```

But you won't see this in the code tbh. Because I used something else and easier than that. 😎

```css
img {
    opacity: 0.4;
}
```

### Continued development

As it was my first encounter with `filter` property, so I'm not done yet. I want to continue using this in the future because it seems quite interesting. 🤔

### Useful resources

- [Apply a hue-rotate filter to a greyscale image](https://stackoverflow.com/questions/23520159/apply-a-css-hue-rotate-filter-to-a-greyscale-image) - The answer to this question solved my problem too. I was wondering why the color of the image isn't changing. When I knew that `hue-rotate` doesn't work directly on a grayscale image because it must have a color to be rotated. Using `sepia` was the only way to do that. But unfortunately, I couldn't find the color I was looking for. 😅

## Author

- Frontend Mentor - [@genuinestalwart](https://www.frontendmentor.io/profile/genuinestalwart)
- Twitter - [@genuinestalwart](https://www.twitter.com/genuinestalwart)

## Acknowledgments

Thanks to [Prasant](https://github.com/prasantdev) for reminding me about `opacity`. I mean, yeah. I knew about this property. But it didn't come to my mind that changing the opacity of an image can make the color under it visible. 😋
