<p align="center"><img src="https://github.com/coderitual/react-direct/blob/master/media/logo-readme.png"></p>

# React Direct
Modern react application with useful patterns inside. The main purpose of it is to teach how to create real world application by solving real world problems. Other than that I want to learn myself by putting and organizing react knowledge into one application. It covers basic areas such as: __*routing, data fetching, animations & transitions, shared state, themes*__ and a few more UI concepts: __*notifications, modals, navigation*__. All these topics are grouped into applicaion folders in the way which feels right to me. They are not carved in stone though, so they can change their place in the future.

## Introduction

This is an attempt to create fully functional react app using modern approaches. The idea behind is to leverage old and battle tested concepts on the new ground and provide useful UI and code patterns for your application.

## Features
Principles which drive this app are as follows:


##### 🎯 *Direct*
Embraces explicit and co-located code which is easy to delete and move from one place to another. This is an optimization for change as the change is the thing which will eventually happen. The code is direct and specific as it can be. No magic.
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

## Modern libraries

Application uses modern libraries for the core things:
- `Reach Router` Because it's straighforward, composable and does directly what it should. Nothing more.
- `Styled Components` Simply CSS in JS with great documentation. Why not `emotion`? I don't know. If there is a reason I should know about, let me know!
- `React Pose` Animations in react are hard enough. Everything that encourages their use is great. More than that it uses FLIP technique and direct DOM manipulation. We all love 60 fps, right?

## Legal
MIT License Copyright © 2018-present, Mike Skowronek 
