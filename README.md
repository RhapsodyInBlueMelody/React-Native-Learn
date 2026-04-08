# Learning React Native — A Journey Through Pain and Suffering

I built this. It nearly killed me. You're welcome.

## What is this?

A responsive grid layout in React Native with React Native Paper. Cards are square,
they reflow based on screen size, and they have ripple touch feedback.

It's maybe 60 lines of code. It took an unreasonable amount of my life force to complete.

## The Suffering, Documented

- `aspectRatio: 1` looked me dead in the eyes and lied to me
- `flex: 1` did absolutely nothing. Just sat there. Useless.
- Text was rendering. Then it wasn't. Nobody knows why.
- `StyleSheet.absoluteFillObject` — doesn't exist. Found out the hard way.
- Cards were squares. Then rectangles. Then squares again. Then rectangles.
- At some point my mouse was in danger. I won't say more.
- The keyboard survived. Barely.

## What I Actually Learned

- Explicit `width` and `height` on **every single layer**. Every. Single. One.
- Margins and gaps must be subtracted before dividing. React Native will not remind you.
- Front-end development is a form of psychological warfare
- I do not like front-end development
- I will never like front-end development
- Please do not ask me to do front-end development

## Tech Stack

- React Native
- React Native Paper
- Rage
- Determination
- More rage

## Running It

```bash
npm install
npm start
```

Pray it works on your machine too.

## Final Thoughts

It works. The cards are square. The text is visible. The grid is responsive.

I am not okay.
