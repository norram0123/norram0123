### Hi there 👋
I'm norram. I usually study programming through math in university. 

My favorite programming language is C and Kotlin. 

I use C in the field of Validated Numerics(the explanation is below). I currently belong to no laboratory, but want to learn C and Validated Numerics for my future.

On the other hand, I use Kotlin for android app development. I like Kotlin because it is similar to Java (I also learned Java in my university!) and there are structures and functions which prevent unexpected errors. (especially scorp funrtion! they are a little bit difficult for me now...)

My goal is to master Kotlin and make good tools in android!:relaxed:

## What Validated Numerics is
Floating-point in C (hereinafter, this is called f) can preserve 16 digits. If my computer calculate "1/3", f preserve not "1/3", but "0.3333....". Therefore, computer can not save value perfectly and small errors can be large error.

Simple example is shown below. If I want to calculate the formula
$$x=\frac{-b + \sqrt{b^2 - 4ac}\}{2a}\ (a=1, b= 10^{15}, c = 10^{14})$$
This is a well-known formula and most students would have used it.

Its true answer is $x = -0.1$. However, standard computers indicate the answer is $x = -0.125$.
The cause is that a is almost omitted because b and c is too large. In this case, the solution is to rationalize the molecule. By using below formula,
$$x=\frac{2c}{-b - \sqrt{b^2 - 4ac}\}\$$
computers indicate $ x = -1.0000000000000002$. we can calculate accurately by devising.

## Why do I think Validated Numerics is needed for app development?
In android app, we want to sort something. 

For example, I want to add the function which can sort something in the order of users interest. If there is a criterion, I only use MySQL. However, if I want to sort by comparing multiple criteria, I need to create the function by myself. At that time, it is a problem if the results are significantly different because of errors and errors may be abused if users notice them. 

Numeric calculations are essential for many algorithms and I think Validated Numerics is useful for many algorithms.





<!--
**norram0123/norram0123** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
