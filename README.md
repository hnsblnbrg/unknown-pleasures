# Unknown Pleasures

A rendition of Joy Division's "Unknown Pleasures" album cover.\
[Live site](https://unknown-pleasures-js.netlify.app/)

## Description

On this project, I generated random lines, inspired by the famous Joy Division album, "Unknown Pleasures".\
To achieve this, I created a canvas and added the lines with their appropriate base values and properties.\
I used two nested loops so each line of the cover could be drawn one right after the other. I added Math.random() in order for the lines to have small edges in random places throughtout.

![Basic lines](/assets/images/img0.png)

Then, I added two functions which generate random values for the line properties. However, this wasn't enough to achieve the effect, so I added the Probability Density Function formula, which made possible for the lines to be randomly curved.

![Probability Density Function](/assets/images/pdf.png)

![Curved lines](/assets/images/img1.png)

Right after, I used the CanvasRenderingContext method to make the lines smoother.

![Curves are smoother](/assets/images/img2.png)

To make the image as similar as the cover, I added some random noise to the canvas, making the lines a lot sharper.\
To wrap up, I added some base values to the nested loop, in order for the edges to be sharper around the middle of the canvas.

![Sharp curves](/assets/images/img3.png)

I commented out the line which added random noise to the canvas, since I hard-coded the values for the lines later on.\
However, you can add the line of code again, since It gives off a glitchy feel to the canvas. Feel free to experiment with the values.

![Glitchy version](/assets/images/img4.png)

After being finished, the final code generates lines which are pretty close to the original album cover.

![Final version](/assets/images/img5.png)

## Installation

- Download the project.
- Open the master folder.
- Initialize the project on the index file.
