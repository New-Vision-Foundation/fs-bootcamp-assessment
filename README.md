# New Vision Foundation: Full Stack Coding Bootcamp Technical Assessment
This is a coding assessment for New Vision Foundation: Full Stack Coding Bootcamp Application.

## Instructions:
- Solve the following [Fashion Measurement Conversion project](https://github.com/nu-viz/fs-bootcamp-assessment#fashion-measurement-conversion) on your playcode.io [follow the instructions from the application doc](https://docs.google.com/document/d/1Jin5g7tJCIAKDNbJmjJYGKBQrbCJo8S_j3iCjYScTbI/edit?usp=sharing)
- Once project is complete and you saved your answer, copy link to your application form.


### Fashion Measurement Conversion
We need your help converting a few measurements since we will be moving our Fashion Clothing Line to South Africa and they use the metric system.

Recently, we began publishing our journey geared towards the South African  audience on our website with tips on various measurements for our clothing items. However there’s a problem: All of our measurements are described in the imperial system - inches.
With our knowledge of JavaScript, let’s convert Inches to Centimeters, then Centimeters to Meters.
For example, 50in  converts to 127cm which converts to 1.27m.

If you get stuck during this project refer back to the [CodeAcademy project](https://www.codecademy.com/courses/introduction-to-javascript/projects/kelvin-weather-javascript)

#### Tasks
1. The material I have for the dress is  `108` Inches. To start, create a variable named `inches` and set it equal to `108`. 
> The value saved to inches will stay constant. Choose the variable type with this in mind.

2. Write a comment above that explains this line of code.
3. Use this equation to calculate Centimeters, then store the answer in a variable named `centimeters`.
> `Centimeter = Inches * 2.54`

> In the next step we will round the number saved to `centimeters`. Choose the variable type that allows you to change its value.

4. Write a comment above that explains this line of code.
5. When you convert from Inches to `centimeters`, you often get a decimal number.
Use the `.floor()` method from the built-in Math object to round down the Centimeter measurement. Save the result to the `centimeters` variable.
6. Write a comment above that explains this line of code.
7. Use this equation to calculate Meter, then store the answer in a variable named `meter`
>`Meter = Centimeter/ 100`
8. Use console.log and string interpolation to log the measurement in centimeter to the console as follows:
```
The measurement is MEASUREMENT in CENTIMETERS.
```
> Use string interpolation to replace MEASUREMENT with the value saved to `centimeter`.
9. Use console.log and string interpolation to log the measurement in meter to the console as follows:
```
The measurement is MEASUREMENT in METERS.
````
> Use string interpolation to replace MEASUREMENT with the value saved to `meters`.
10. Run your program to see your results!
11. By using variables, your program should work for any inches measurement — just change the value of `inches` to `876` and run the program again. What’s `876` Inches in Meter? Use console.log and string interpolaton to log:

```
INCHESin  converts to CENTIMETERcm which converts to METERSm.
```
> Use string interpolation to replace INCHES with the value of inches & CENTIMETER with the value saved to `centimeter` & METERS with the value save to `meter`.

Check the console. GREAT WORK!Inches can now publish her fashion items in Centimeters and Meters.

