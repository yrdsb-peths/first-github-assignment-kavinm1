# Welcome to our GitHub classroom!

Do the following to Complete this assignment:

1. Begin editing this file by clicking the 'pen' symbol above.

2. Enter your First Name: Kavin

3. Enter your favourite animal: Dog

4. Now click the green 'commit changes' button at the bottom.

5. Done!

public class Rectangle
{
    private int width;
    private int height;
    
    public Rectangle(int rectWidth, int rectHeight)
    {
        width = rectWidth;
        height = rectHeight;
    }
    
    public int getArea()
    {
        return width * height;
    }
    
    public int getHeight()
    {
        return height;
    }
    
    public int getWidth()
    {
        return width;
    }
    
    public String toString()
    {
        return "Rectangle with width: " + width + " and height: " + height;
    }
}

public void run()
    {
        Rectangle rect = new Rectangle(20, 30);
        System.out.println(rect);
    }
