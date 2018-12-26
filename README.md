<p align="center"><img src="https://github.com/coderitual/react-direct/blob/master/media/logo.png"></p>
<p align="center"><em><strong>Ready-to-Use UI Solutions for React Application</strong></em></p>

## Introduction
Set of UI concepts packed into one fully functional react application. The idea behind is to leverage cutting edge ideas to provide useful UI and code patterns for your project. It covers basic areas such as: __*routing, data fetching, animations & transitions, shared state*__ but also more specific UI solutions. All these topics are grouped into folders in the way which helps you find an interesting piece of code.

## Features
Principles which drive this project are as follows:

##### 🎯 *Direct*
Embraces explicit and co-located code which is easy to delete and move from one place to another. This is an optimization for change as the change is the thing which will eventually happen. The code is direct and specific which makes it easy to copy and adapt for your needs.
##### 🍏 *Simple*
Following [The Rise of "Worse is Better"](https://www.jwz.org/doc/worse-is-better.html)
> The design must be simple, both in implementation and interface. It is more important for the interface to be simple than the implementation.

This also means avoiding unnecessary abstractions. 
##### 🍆 *No classes*
Only functional components.
##### ❣️ *Hooks*
Uses hooks all the way (available as of react 16.7.0-alpha).
##### 🖖 *Code splitting*
Uses `React.lazy` along with `import()` and let the webpack do the job.
##### ⏱️ *Suspense*
React suspense for all things except data (code splitting, media loading).
##### 👗 *CSS-in-JS*
It's based on styled components for the look and feel.
##### 🤷 *Promote defaults*
As little configuration as possible. Uses defaults wherever it can.

## Modern Libraries

Application uses modern libraries for the core things:
- `Reach Router` Because it's straighforward, composable and does directly what it should. Nothing more.
- `Styled Components` Simply CSS in JS with great documentation. Why not `emotion`? I don't know. If there is a reason I should know about, let me know!
- `React Pose` Animations in react are hard enough. As they should be the first class citizen in modern UI, everything that encourages using them is great. More than that library itself uses FLIP technique and direct DOM manipulation. We all love 60 fps, right?

## Legal
MIT License Copyright © 2018-present, Mike Skowronek 
