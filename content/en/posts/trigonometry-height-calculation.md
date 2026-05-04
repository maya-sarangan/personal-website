+++
date = '2026-05-03T12:53:37-07:00'
draft = false
title = 'How to Measure a Building Without Touching It'
tags = ["math", "geometry", "trigonometry", "sin", "cos", "tan", "eratosthenes", "circumference"]
+++
I have this big hole on my face called my mouth… and I probably should have kept it shut. One day, I peeked ahead in my math book and saw a chapter on trigonometry. Out of curiosity, I asked my dad what it meant… and that’s when things got interesting. My dad explained the basics and asked me a question. How would you try and find the height of the building?

My first answer was to try and count the windows. I would find the height of one window and multiply it by the number of windows on one side. Seems simple enough right? But what if I'm trying to find the height of a windowless building? This method wouldn't work. I tried a few more times with answers like "Measure from the inside!" but no. No measuring tools, no estimating, no approximations, just trigonometry. Let's go...

So what exactly is trigonometry? Trigonometry is the study of triangles. Specifically, the relation between their sides and angles. Let me introduce you to three terms in trigonometry: `sine`, `cosine`, and `tangent`. Also known as `sin`, `cos`, and `tan`. Keep this in mind.

Now let's go to right triangles. What exactly do you call the three sides? Try and hazard a guess! Many people usually call them leg, leg, and hypotenuse. But in trigonometry, the leg next to θ is called the adjacent side, and the one across from θ is the opposite side. Here is a visual display of this:

![5](/personal-website/images/trigonometry_5.png)

'θ' is the angle ∠ABC and in trigonometry, 'θ' is the variable for all angles. AC is called opposite because it is opposite to 'θ', and CB is called adjacent. Let's now go back to `sin`, `cos`, and `tan`. The equations for these are:

```
sin(θ) = opposite/hypotenuse
cos(θ) = adjacent/hypotenuse
tan(θ) = opposite/adjacent
```

These are the basics for trigonometry, and we can use this knowledge to find the height of buildings.

To measure the height of a building, you must start by standing away from the building. You have to be able to see the top of the building when you look up/straight. Now you must measure how far back you are from the building. From here, you can use an inclinometer (an enlarged protractor) and find the angle from your eye level to the top of the building. Here is an image that shows this:

![4](/personal-website/images/trigonometry_4.png)

As you can see, the person and the building form a right angle triangle. Now you must measure 'θ' and use the equation:

tan(θ) = opposite/adjacent

Since our goal is to find the opposite, not tan(θ), we can modify this equation a little bit and turn it into this:

tan(θ) x adjacent = opposite

We can input 'θ' and the adjacent(the distance from you to the building) to solve the problem. And of course, you need to add your own height to get the full height.

I actually simulated this problem by doing an experiment at home(I used a bookshelf though, not a building...). Here is an image of the bookshelf I used:

![0](/personal-website/images/trigonometry_0.jpeg)

Then, I marked the adjacent, and 'θ'. Here is a diagram showing this:

![1](/personal-website/images/trigonometry_1.jpeg)

When I put these values into the equation, I got **42.000406654426420834172749171547 inches** which is approximately **42 inches** using the following calculations:

```
tan (39.75°) = height / 50.5 inches
height = tan (39.75°) * 50.5 inches
       = 0.83169122087973110562718315191182 * 50.5 inches
       = 42.000406654426420834172749171547 inches
       ~ 42 inches
```

But, how do we verify if this value is correct?  We can verify the answer by standing somewhere else and doing the same thing! The angle and the adjacent distance will change. But, the height should be the same. Here is a diagram showing this:

![2](/personal-website/images/trigonometry_2.jpeg)

When I substituted the new values for 'θ' and the adjacent into the equation, I got **41.992791007866674237601590888427 inches** which is approximately **42 inches** using the following calculations:

```
tan (36.5°) = height / 56.75 inches
height = tan (36.5°) * 56.75 inches
       = 0.73996107502848765176390468525863 * 56.75 inches
       = 41.992791007866674237601590888427 inches
       ~ 42 inches
```

This answer is extremely close to the actual height, so I know it is correct.

Also, I can actually use a measuring tape (of course you cannot do it with a real building). When I measured my book shelf's height, I got exactly 42 inches!

A more interesting piece of information is that you can use the same method to measure the circumference of the Earth. It had been done by a Greek Mathematician named Eratosthenes. He measured the circumference of the earth using the shadow of a pole in the city of Alexandria. Sounds unbelievable right? But he found the circumference of the earth using it! He actually used a method very similar to the method we use to find the height of buildings.

It was summer solstice at noon and the sun was directly over the earth and there were two cities, Alexandria, and Syene. There was a pole in Alexandria that had a shadow thanks to the sun. Eratosthenes noticed this pole and used θ. θ was **7.2**. By the logic of a line cutting two parallel lines, the angle between the two cities and a portion of the center of the earth is 7.2 degrees. Eratosthenes then measured the distance from Syene to Alexandria: **800 km**.

Using the Proportional table method (Refer [`Ratios, Tables, and One Very Proud 90’s Kid`](/personal-website/posts/table-method/) to learn more about the table method), Eratosthenes found that the circumference of the earth is **40,000 km**. his answer is extremely close to the actual circumference: **40,075 km**.

The following image (Courtesy of Google Nano Banana) explains this experiment more clearly.

![3](/personal-website/images/trigonometry_3.jpeg)

So, Moral of the story: curiosity is great… but it comes with homework... 