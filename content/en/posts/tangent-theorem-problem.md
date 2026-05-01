+++
date = '2026-04-12T12:29:46-07:00'
draft = false
title = 'When Lines Just Touch: The Secret of Tangents'
tags = ["math", "puzzles", "geometry", "algebra", "tangent", "tangent tangent theorem"]
+++

I was watching the movie Aladdin when my dad walked in and said "Let's do something tangential to watching the movie!". I asked, "what is a tangent?". After a short session on tangents I ended up with this problem.

Here is the problem:

![1](/personal-website/images/tangent_1.png)

AB = 9, BC = 12, and triangle ABC is a right-angled triangle. The two circles have the same area. Find the combined area of the 2 circles. 

To find the area of the circle we need to find the radius. First, let's start off by marking the radius. The radius is the distance from the midpoint of a circle, to the perimeter. In the diagram, the radii (plural for radius) are marked with the letter `r`. We have also marked the midpoints of the two circles with the letters `M` and `N`. Also, we can mark everything that we can deduce from the image.

![2](/personal-website/images/tangent_2.png)

Now, you might be wondering, why are some 'r' outside of the circle? That is because, these lines are of equal length to the radius, so we can mark them as such. 

Now, can we find the length of `AC`. Yes. Of course. But how? The missing sidelength can be determined with a **Pythagorean triplet**. One example of a Pythagorean triplet is **3:4:5**. Basically, if two of the sides in a right triangle(this only works for right triangles) are any of these three numbers, we know what the third one is. Now, if we multiply the numbers in this ratio by 3, we will get **9:12:15**. This matches `AC` of our right triangle, so we know that the missing length is 15. 

And, we can split the side lengths 9 and 12! We can split 9 into r and 9 - r. And we can split 12 into 3r and 12 - 3r.

For this next part, I must explain to you what tangent lines are. If you took a circle and drew a line right on top of it so that the tangent line is touching the top of the circle, you just created a tangent line. This tangent will form a 90° right angle with the radius. So, Now the picture looks like this:

![3](/personal-website/images/tangent_3.png)

During our earlier session, my dad taught me the Tangent Tangent theorem. So, knowing him, I had a gut feeling that he would have found a way to include that here. First, we can discuss about the theorem called the **Tangent Tangent theorem**. The Tangent–Tangent Theorem states that if two tangent segments are drawn from the same external point to a circle, then their lengths are equal. If you look closely at the diagram you will actually see this! This is the property we use to find the length of PC and QC. Since we already found `12 - 3r`, we can subtract that from `15` to find the other side, `3 + 3r`. Here is the diagram that shows this:

![4](/personal-website/images/tangent_4.png)

When I got to this step of the problem I got stuck. What should I do next? So I asked my dad for some assistance (Hey... I am 11...) and he gave me this hint. He pointed me to the two right angles at `Q` and `S` . After a little bit of thinking and pondering I was able to do it. This is what I got:

![5](/personal-website/images/tangent_5.png)

Draw a line between `AN` and make 2 right triangle which share the hypotenuse `AN`. Then, We can use that to solve for `r`.Now, solving the problem is simple! You just need to write the equation. Ahh... my friend Algebra is back.  Its interesting to note that what started as a geometry problem is becoming a problem in algebra. Since the two triangles share a hypotenuse, the equation will be:

For triangle ASN:
    (9 - r)² + (3r)² = AN²   (by the Pythagorean Theorem: a² + b² = c²)

For Triangle ANQ:
    r² + (3 + 3r)² = AN²     (by the Pythagorean Theorem)

By the transitive property of equality:

    (9 - r)² + (3r)² = r² + (3 + 3r)²

Using the following formulae:

    (a + b)² = a² + 2ab + b²
    (a - b)² = a² - 2ab + b²
    (ab)ⁿ = aⁿ bⁿ

which will give:

    81 - 18r + r² + 9r² = r² + 9 + 18r + 9r²
    81 - 18r = 9 + 18r
    72 = 36r
    r = 2

Since we found the radius, we can use the formula πr² for finding the area of a circle.

So the combined area of the two circles = 2(πr²) = 2(4π) = 8π

Now, let me take another tangential turn from tangents and go back to Aladdin and his magic carpet 😄
 