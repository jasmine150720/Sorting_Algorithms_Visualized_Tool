# Design Document
## Functional Details 
Using the bubble sort algorithm to sort the pixels of an image.
## Project Structure
1. Class Dislay.java:
- Import Java Packages & API:
  - import java.awt.Canvas;
  - import java.awt.Dimension;
  - import java.awt.Graphics;
  - import java.awt.image.BufferStrategy;
  - import java.awt.image.BufferedImage;
  - import java.awt.image.DataBufferInt;
  - import java.util.ArrayList;
  - import java.util.Collections;
  - import javax.swing.JFrame;
  - import sorting.visualizer.graphics.Picture;
  - import sorting.visualizer.sorting.MasterSorter;
  - import sorting.visualizer.sorting.Pixel;
  - import sorting.visualizer.sorting.SortingMethod;
- Created method:
  - Display()
  - initPixels()
  - randomizePixels()
  - start() and stop(): run the threads
  - Override public void run()

2. Class Picture.java
- Import Java Packages & API:
  - import java.awt.image.BufferedImage;
  - import java.io.IOException;
  - import javax.imageio.ImageIO;
- Created method:
  - load(): load the picture from Resource;
  - getWidth(),getPixels() and getHeight(): pixels = new int[w * h];
3. Sorting: Those classes for storing the pixels of picture 
- BubbleSort.java 
- MasterSorter.java
- Pixel.java
- SortingMethod.java
## Execution plan
- Write down the path to open the image, which will be sorted
- Boolean variable running turns TRUE, the thread starts.
- Render method draws stuff to the windown
- Image class get height and width of image
- Create a rectangular area with the height and the width of the picture
- Randomize the pixels
- Use the algorithm to sort the picture
  - Let's take a look how the Bubble sort algorithm works:
![image](https://user-images.githubusercontent.com/85243027/120709314-5f376780-c4c5-11eb-9d0b-f071c50edfe1.png)
- End program until the Boolean variable running is false, thread stops.

## Result
- Before
 
![image](https://user-images.githubusercontent.com/85243027/120708780-ae30cd00-c4c4-11eb-80e0-162bd35eca19.png)
- After

![image](https://user-images.githubusercontent.com/85243027/120708988-f819b300-c4c4-11eb-8b2c-94b5f29ff37a.png)

