# Design Document
## Functional Details 
Using the bubble sort algorithm to sort the pixels of an image.
## Project Structure
1. Class Dislay.java
- Extend class Canvas : to be using to draw stuff to the screen
- Implement Runnable interface: to be using to draw on different threads 
- 
3. Class Picture.java
4. Sorting 
- BubbleSort.java
- MasterSorter.java
- Pixel.java
- SortingMethod.java
## Execution plan
- Write down the path to open the image, which will be sorted
- Boolean variable running turns TRUE, the thread starts.
- Render method draws stuff
- Image class get height and width of image
- Let's take a look to the Bubble sort algorithm
![image](https://user-images.githubusercontent.com/85243027/120709314-5f376780-c4c5-11eb-9d0b-f071c50edfe1.png)

## Result
- Before
 
![image](https://user-images.githubusercontent.com/85243027/120708780-ae30cd00-c4c4-11eb-80e0-162bd35eca19.png)
- After

![image](https://user-images.githubusercontent.com/85243027/120708988-f819b300-c4c4-11eb-8b2c-94b5f29ff37a.png)

