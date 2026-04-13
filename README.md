# 3D Landscape CSS

A stunning 3D landscape created entirely with CSS, featuring mountains, trees, and a house in a layered parallax effect. Hover over different areas of the screen to rotate the scene in 3D space.

## Demo

Open `index.html` in your web browser to view the interactive landscape.

## Features

- **Pure CSS 3D Rendering**: No JavaScript or images required – everything is built with CSS transforms and clip-paths.
- **Interactive Rotation**: Hover over a 3x3 grid overlay to rotate the landscape in various directions.
- **Parallax Layers**: Multiple depth layers create a realistic 3D effect using `translate3d`.
- **Responsive Design**: Scales with viewport units for any screen size.

## How It Works

The scene is composed of several layers positioned at different z-depths:
- Background mountains
- Tree layers at varying distances
- A central house
- Foreground trees

Hovering over invisible grid sections applies `rotate3d` transforms to the entire cartoon container, simulating camera movement.

## Screenshots

![3D Landscape Screenshot](Screenshot%202026-04-13%20132757.png)

## Inspiration

Inspired by [this Dribbble shot](https://dribbble.com/shots/7981891-Landscape).

## Technologies

- HTML5
- CSS3 (Transforms, Clip-path, Perspective)

## License

Feel free to use and modify this project as you wish.