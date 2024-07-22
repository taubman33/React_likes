### SEBR 0429

# React Likes

![like thumb](https://images.fastcompany.net/image/upload/w_596,c_limit,q_auto:best,f_auto/fc/3021307-inline-fb-thumbsup-printpackaging.jpg)

## Overview

In this lab, you will create a likes component in React. Your final product should function similarly to
[this deployed version](https://react-likes.surge.sh/) of the component.

## Getting Started

- Clone this repo and cd into it.
- Create a new react app named `react_likes` in this directory.
- Change into your `react_likes` app and begin your work from there.

## Instructions

Create a new component called **Likes** in the `src` directory and add functionality to it so that when the component renders it records the number of clicks in state and displays the total Likes.

- Use the `useState` hook to add state called `totalLikes` to the component to store the current number of clicks on the component.
- Initialize the `totalLikes` state as `0`.
- Create an increment button with a `+` as its text.
- Render the `totalLikes` to the page in a `p` element.
- Include an `onClick` attribute on the button which increments the value of `totalLikes`.


## Bonus

- Add another button that decrements the `totalLikes` and has a `-` as its text.
- Find a version of the Facebook Likes thumbs up to have as your button, and a Thumbs Down to decrease likes
- Make it so that the `totalLikes` can never display a value less than `0`.
- Once you have the `totalLikes` displaying on the page, move just the display paragraph into its own component called **LikeTotal** and have the Likes component you built render it (hint: use props to pass the value of `totalLikes` to your new LikeTotal component).
