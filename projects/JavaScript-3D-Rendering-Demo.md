# JavaScript 3D Rendering Demo

This was a final project for my Intro to Computer Graphics class. It demonstrates some of the concepts of 3D rendering. It was written in JavaScript, using WebGL, GLSL, and the gl-matrix library.

![A screenshot from the rendering demo, depicting a scene from Hollow Knight: The Knight sitting on a bench in the City of Tears with rain crossing in front of the viewer](/assets/img/js3drd_screenshot.png)

[Check out the full rendering demo here!](https://people.rit.edu/pps3941/GraphicsFinal/cityoftears.html) I wrote a lot more about the technical details over there.

## About the Assignment

The class was a sort of very basic intro and crash course to how 3D graphics stacks work. We spent a little time implementing the same algorithms that provide the fundamentals of 3D rendering (line drawing, shape drawing, transforming coordinates, etc.) until we moved on to implementing basic operations in JavaScript and WebGL. The assignment was to create something that expands on what we were doing in class, so I decided to recreate one of my favorite scenes from one of my favorite video games. I took a previous assignment and added textures, transparency, and refresh-rate-independent animation (i.e. if your computer renders at double the speed of mine, the animations will sill appear to be running the same speed) to the backend, and then created the models that were used in the scene.

## Usage

For now, the demo is [up and running on a web server at RIT, please feel free to check it out there](https://people.rit.edu/pps3941/GraphicsFinal/cityoftears.html).

## About the Project

I am very proud of this project. I learned about a lot of new technologies in a very short time frame in order to build it, in addition to a few new skills (3D modeling, framerate-independent animation, etc.). Making an homage to my favorite video game was a blast. Apologies for the flat file structure, I wasn't focusing on making it look pretty. In addition, we were encouraged to use a program to convert our 3D models into JS files that listed all of the vertices, so portability into other frameworks isn't very easy, and the source files are frankly rather ugly, haha. But it was necessary to ship the project in time, and it made importing the models very easy: simply load the JS file and use the same object-building structure we'd been using for the entire class so far.

It's not the prettiest project, but it made me very happy, and I'm glad to have pushed myself to do it.
