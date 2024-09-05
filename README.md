The Box-model: 4.1.2

In HTML-Broders:
  /* broder: */ is a CSS property that adds a border to any web page element. The border has three parts: width, style, and color. The width determines how thick the border is, the style determines how it looks, and the color determines its color.

Box-Sizing Comparison:
A lesson over standarizing styling by setting ALL HTML elements with border-box sizing
Assigning margins and padding
There are a few different ways to assign values to margins and padding. And with a little practice, you'll find this pretty easy.

Assigning a single value
When a single value is applied to the margin or padding of a box, the code will apply that value (measured in px) to all four sides of the HTML element: the top, right, bottom, and left sides. Here are some example values:

margin: 25px;

padding: 25px;

Assigning specific values
But you don't have to set just one value. You can also apply a specific value to each side. When you want to set a specific value to a specific side, you can do so like this:

margin-top: 25px;

margin-right: 15px;

margin-bottom: 20px;

margin-left: 12px;

padding-top: 25px;

padding-right: 15px;

padding-bottom: 20px;

padding-left: 12px;

Assigning two values
Or maybe you've provided only two values. In this case, the code will apply the values to the two pairs of sides as follows: The first value will apply to the top and bottom sides. And the second value will apply to the left and right sides.

margin: 25px 15px;

padding: 25px 15px;

Assigning four values
And finally, when four values are provided, they will always apply to each side of the box in this specific order: The first value will apply to the top side. The second value will apply to the right side. The third value will apply to the bottom side. And the fourth value will apply to the left side.

margin: 25px 15px 20px 12px;

padding: 25px 15px 20px 12px;

Browser defaults versus normalize.css
And there you have it—you've learned several challenging CSS concepts already in this module. The final point that's worth reiterating here is the issue of browser style defaults. Not all web browsers have the exact same settings for the default styles of CSS. But there is a popular and easy-to-implement solution: normalize.css. With this small CSS file, you can guarantee cross-browser consistency for default styles