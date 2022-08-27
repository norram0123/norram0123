### Hi there 👋
**Name**: *Norram*

**Occupation**: *University student* <sub>(Applied Mathematics major)</sub>

**Favorite language**: *Kotlin, Java*

## <img src="https://user-images.githubusercontent.com/102008212/180079714-0d0af206-38c5-4f0a-a91b-32e1396f9f2a.png" width="26px;" /> Recent Activity
I often created android app which can be used offline before. However, I am recently interested in API and learning how to get connection status, images and so on.

My newest app is "Bit", which can get posts in Instagram and open album (Please watch video for details!). The app uses "Instagram Graph API". Instagram has a function called "album posting", which allows you to combine multiple photos into one post. However, the viewer has to scroll over and over, which is troublesome. Therefore, I created an application that displays a list of posts with an expand button by searching for a user name.
<p align="center">
<img src="https://user-images.githubusercontent.com/102008212/186944151-44daae4d-4f45-4ede-8455-642f13c6ecdc.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/186944143-f009bbc1-8ffe-457c-931b-d80cc62d6858.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/186945589-b573a469-54c7-434f-ab42-3f5829be841c.png" width="240dp" />
</p>

[Click here for details!!](https://github.com/norram0123/Bit)
<video controls src="https://user-images.githubusercontent.com/102008212/186937886-35415add-9ae2-4093-9a60-1164450af71b.mp4" muted="false"></video>


## :coffee: Archive (Other apps)
<h3>Personal Note (2020~)</h3>
<p>Notepad app with password function.

It's convenient for people who don't want anyone to see the contents. Too simple!!:laughing:</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/102008212/184160570-b00ca6f3-6f5a-403c-8b00-0d6f5becbe97.jpg" width="120dp" />
<img src="https://user-images.githubusercontent.com/102008212/184160662-de1f06a9-aa87-49b9-a053-54fdd5ca81a0.jpg" width="120dp" />
</p>

<h3>Patienter (2021~)</h3>
<p>Countdown App that can measure not only short time but also very very long time.</p>
<p>Normal timer and countdown Can only be measured for a few days at most. Therefore, I thought it would be interesting to have a countdown app that could measure several years. The app preserve history and judge whether you were able to achieve the countdown.It,s useful for people who want to count days in a long span.</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/102008212/184166314-46c402da-b915-477a-8eeb-045ea87900eb.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/184166332-5d07e71e-1f45-4a64-ba98-f5b657da4413.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/184166338-e6013ae6-ed68-4834-bbd6-da34a6fe1b48.png" width="240dp" />
</p>

## :blue_book: Validated Numerics (My activity on the campus)
Floating-point in C (hereinafter, this is called f) can preserve 16 digits. If my computer calculate "1/3", f preserve not "1/3", but "0.3333....". Therefore, computer can not save value perfectly and small errors can be large error.

Simple example is shown below. If I want to calculate the formula

<p align="center">
<img src="https://latex.codecogs.com/svg.image?x=\frac{-b&space;&plus;&space;\sqrt{b^2&space;-&space;4ac}}{2a}&space;(a=1,&space;b=&space;10^{15},&space;c&space;=&space;10^{14})" />
</p>

This is a well-known formula and most students would have used it.

Its true answer is "x = -0.1". However, standard computers indicate the answer is "x = -0.125".
The cause is that a is almost omitted because b and c is too large. In this case, the solution is to rationalize the molecule. By using below formula,

<p align="center">
<img src="https://latex.codecogs.com/svg.image?x=\frac{2c}{-b&space;-&space;\sqrt{b^2&space;-&space;4ac}" />
</p>

computers indicate "x = -1.0000000000000002". we can calculate accurately by devising.

## :grey_question: Why I learn Validated Numerics
In android app, we will have the opportunity to sort something. 

For example, I want to add the function which can sort something in the order of users interest. If there is a criterion, I only use MySQL. However, if I want to sort by comparing multiple criteria, I need to create the function by myself. At that time, it is a problem if the results are significantly different because of errors and errors may be abused if users notice them. 

Numeric calculations are essential for many algorithms and I think Validated Numerics is useful for many algorithms.
