+++
date = '2026-04-07T20:36:40-07:00'
draft = false
title = "A radical's take on radicals: Square Root without using a calculator"
+++

You walk into class and realize today is the day of your square roots test. You sit down and grab your calculator. You put in the question and the calculator gives you the answer. Seems simple, right? But for over two thousand years, how did people find square roots? It wasn't as simple as just asking AI. Luckily, an abundance of different ways were discovered. Some of them are:

    1. Babylonian/Heron's method
    2. Approximation method
    3. Bakhshali's method
    
and many more.Today, I want to share what I learned about the Babylonian method.

## Babylonian/Heron's method

First, let's examine some perfect squares:

√4: 2

√9: 3

√16: 4

√25: 5

√36: 6

Why? 

√4 => √2² => (2²)^1/2 => 2^(2 * 1/2) => 2

But, what about the numbers which are not perfect squares. Let us take this as an example: √27

Since 27 is between 25 and 36, the √27 should be between 5 and 6. To find the answer, we will have to use the equation shown below

xₙ₊₁ = ½ (xₙ + S / xₙ)

Now, we need to pick a starting value for xₙ. We need to start out by overshooting the value, so we can use 6. Once we substitute 6 into the equation, you will get this:

```
1/2(6 + 27/6)
```

The result will be: 5.25

Now we need to use the equation again, but this time we use the *previous* answer. Now the equation will look like this:

```
1/2(5.25 + 27/5.25)
```

Once we round the answer, we will get: 5.196

Now the equation will be:

```
1/2(5.196 + 27/5.196)
```

The answer is 5.196

Since 5.196 appears again, the value has stabilized, so we can take it as the answer. But why? Why is 5.196 repeating? This is because, every time you use the equation, the range for the answer is getting smaller and smaller until it can no longer push. So, the number will stay the same. Of course, the √27 will never be exact, but 5.196 is extremely close.

Now, you might be wondering, why does this method work? This method works because the equation we are using is actually the equation for finding the average of two numbers - one by overshooting the estimate and one by undershooting it. Since we keep substituting numbers into the equation, the average keeps getting closer and closer and converges to the answer. This is the method that Babylonians used. Nobody knows how they discovered this equation, but this proves how intelligent mathematicians were two thousand years ago.

We carry calculators in our pockets every day… and still panic during a square roots test. Meanwhile, the Babylonians were out here solving this without even electricity. Cool... 

Now I just need to find a map and figure out where Babylonia actually is… 😄


P.S.
1. In mathematics, a “radical” refers to the √ symbol.
2. In 80s slang, “radical” means “extremely cool.”

So technically… this post is both 😄
