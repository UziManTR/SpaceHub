# SpaceHub

A lightweight all-in-one hub concept for Samsung Smart TVs running Tizen.

## What's in this first prototype?

- TV-friendly, dark space-inspired home screen
- Live local clock and date
- Remote-control navigation with arrow keys, OK/Enter, and Back
- Media, Apps, Weather, Clock, and Settings preview panels
- No frameworks, build step, or external assets required

## Preview

Open `index.html` in a browser, or enable GitHub Pages for a hosted browser preview.

## Build for a Samsung TV

GitHub Pages only hosts the browser preview. It does **not** create an installable Tizen package.

1. Install Samsung's Tizen Studio and the TV extensions for your target TV.
2. Create/import a Tizen TV Web application project.
3. Copy `index.html` and `config.xml` into the project root.
4. Check the package/application ID and required Tizen version against your TV.
5. Sign the project with a certificate created in Tizen Studio.
6. Build the Web application package (`.wgt`) and test it on a compatible TV.

The first version is a UI prototype. Actual launching of installed TV apps and live weather/media integrations are not connected yet.

## Project

Made by [UziManTR](https://github.com/UziManTR).
