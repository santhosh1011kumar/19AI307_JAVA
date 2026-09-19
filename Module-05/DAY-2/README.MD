# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS
class Cylinder
{
    private int radius;
    private int height;

    public void setRadius(int r)
    {
        radius = r;
    }

    public void setHeight(int h)
    {
        height = h;
    }

    public void getVolume()
    {
        double volume = Math.PI * radius * radius * height;

        System.out.println("Volume of Cylinder = " + volume);
    }

    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        int radius = sc.nextInt();
        int height = sc.nextInt();

        Cylinder c = new Cylinder();

        c.setRadius(radius);
        c.setHeight(height);
        c.getVolume();

        sc.close();
    }
}
```



## OUTPUT:
![Image](https://github.com/aswin0603/19AI307_JAVA/blob/main/Module-05/DAY-2/Screenshot%202026-08-25%20212943.png)


## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.


