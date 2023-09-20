# **CLASS NOTES** by Taemour Zaidi

Colors can have an affect on the audience. Different colors communicate different feelings.

## Questions
1. **What is the meaning or impression that you will get when you see different colors? Use the following colors in your answers:**
    - **White:** modern, peace, safe travel, minimalist
    - **Red:** error, wrong, warning, danger, stop, blood
    - **Blue:** calm, deep, ocean
    - **Green:** calm, nature, youth
    - **Yellow:** small warning, sickness, joyful, happiness, school
    - **Purple:** royal, mystery, regal, soothing
    - **Orange:** funky, different
    - **Black:** neutral, void, empty
2. **What are the main Color Models that we could use in computer graphics?**
    - RGB (Red-Green-Blue)
    - CMYK (Cyan-Magenta-Yellow-Black)
    - HSV (Hue-Saturation-Value)
3. **What is the Color Wheel and how is it used in computer graphics applications?**
    - The color wheel is a circular diagram that shows the relationships between the primary, secondary, and tertiary colors. 
    - It is a useful tool for choosing and combining colors that work well together.
4. **Explain the concept of color and its main cahracteristics in computer graphics.**
    - Color is used in computer graphics to help distinguish between different objects, as well as convey types of messages or emotions without the use of words, thus being more universally and easily understood.
    - The main characteristics of a color are:
        - Hue: how most people percieve and name a color, using colors of a rainbow (red, orange, yellow, green, blue, indigo, violet)
        - Chroma: AKA Saturation, it describes the vividness or dullness of a color. High saturation is vivid, low is dull.
        - Value: is the degree of a color's lightness and describes the luminous intensity of a color.

1. **Define Color Theory and its main components from a computer graphics perspective.**
    - Color theory is the study of how colors work together and how they affect our emotions and perceptions. It's like a toolbox for artists, designers, and creators to help them choose the right colors for their projects. Color theory enables you to pick colors that go well together and convey the right mood or message in your work.
    - Color theory was established by Newton when he invented the color wheel in 1666, categorizing colors into:
        - Primary: Red, Blue, Yellow
        - Secondary: Mixes of primary colors
        - Tertiary: mixes of primary and secondary colors
1. **Give a brief introduction about the RGB Color Model and its main use. What is the meaning of additive attribute in this context?**
    - The RGB color model is one of the most widely used color representation method in computer graphics. It use a color coordinate system with three primary colors:

        - ````R(red), G(green), B(blue)````

    - Each primary color can take an intensity value. Mixing these three primary colors at different intensity levels produces a variety of colors.
    - Color specification using the RGB model is an additive process, in that we begin with black and add on the appropriate primary components to yield a desired color.
1. **Give a brief introduction about the CMYK Color Model and its main use. What is the meaning of subtractive attribute in this context?**
    - CMYK colour model is widely used in printers. It stands for Cyan, Magenta, Yellow and Black (key). 
    - 0 represents the primary colour and 1 represents the lightest colour. In this model, point (1, 1, 1) represents black, and (0,0,0) represents white. 
    - It is a subtractive model thus the value is subtracted from 1 to vary from least intense to a most intense colour value.
1. **Give a brief introduction about the HSV Color Model and its main use. Specify the relationship with other color models (RGB and CMYK).**
    - HSV uses Hue, Saturation, and Value channels (the 3 main characteristics of a color).
    - Rather than use primary colors directly, it uses color in the way humans percieve them. Thus HSV color is represented by a cone.
    - In other words, HSV is a cylindrical color model that remaps the RGB and CMYK primary colors into dimensions that are easier for humans to understand.
