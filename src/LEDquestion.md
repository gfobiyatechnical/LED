
    You are given a strip of Diwali decoration lights. They are available with LEDs of four colours,
    namely, Red, Green, Blue and White.
    There are also some defective LEDs in the strip. You have been told to find out the defective LEDs
    in the strip. 
>
    Each LED has the following fields
    colourName : String
    working : boolean

>   If you find that in a strip there are more than half of the LEDs defective, you would have to throw away the strip and buy yourself a new one.
    You are required to create the following definition classes - 
    
>   class LED {
	// create fields, getters and setters, constructor and some helper methods for this class
    }

    
    class LEDStrip {
	// create fields, getters and setters, constructor and some helper methods for this class
    }

    and an execution class named `Main`
    class Main {
    }
   
>   
    The signatures for the methods are given below

>
>   public boolean isWorking() // getter for the field : working of class : LED
    private int lengthOfStrip() // to find out the total number of LEDs in a strip
    private int numberOfDefectiveLEDs() // to find out the number of defective LEDs out of the total LEDs
    private boolean isStripDefective() // if more than half of the LEDs are defective then, the strip is considered defective too


    Sample Input
    5
    Red true
    Green false
    Blue true
    White false
    Red true
    This strip is not defective!

4
Red false
Green false
Blue false
White true
This strip is defective!