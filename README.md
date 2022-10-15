### Hi there 👋
**Name**: *Norram*

**Occupation**: *University student* <sub>(Applied Mathematics major)</sub>

**Favorite language**: *Kotlin, Java*

## <img src="https://user-images.githubusercontent.com/102008212/180079714-0d0af206-38c5-4f0a-a91b-32e1396f9f2a.png" width="26px;" /> Recent Activity
I often created android app which can be used offline before. However, I am recently interested in API and learning how to get connection status, images and so on.

My newest app is "Bit", which can get posts in Instagram and open album (Please watch video for details!). The app uses "Instagram Graph API". Instagram has a function called "album posting", which allows you to combine multiple photos into one post. However, the viewer has to scroll over and over, which is troublesome. Therefore, I created an application that displays a list of posts with an expand button by searching for a username.
<p align="center">
<img src="https://user-images.githubusercontent.com/102008212/193114217-7fb93a68-62c8-401a-8e37-d379a08c1f60.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/193114222-32e045eb-ff49-4742-bed1-4aab5096b93b.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/193114227-806268e5-7c2c-4ca6-a759-170d2d7aeba1.png" width="240dp" />
</p>

[Click here for details!!](https://github.com/norram0123/InstagramViewer-Java)
<video controls src="https://user-images.githubusercontent.com/102008212/193116527-44b1b11a-be51-45b2-adf4-c1694433222e.mp4" muted="false"></video>


## :coffee: Archive (Other apps)
<h3>Personal Note (2020~)</h3>
<p>Notepad app with password function.

It's convenient for people who don't want anyone to see the contents. Too simple!!:laughing:</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/102008212/184160570-b00ca6f3-6f5a-403c-8b00-0d6f5becbe97.jpg" width="120dp" />
<img src="https://user-images.githubusercontent.com/102008212/184160662-de1f06a9-aa87-49b9-a053-54fdd5ca81a0.jpg" width="120dp" />
</p>

<h3>Andante (2021~)</h3>
<p>Countdown App that can measure not only short time but also very very long time.</p>
<p>Normal timer and countdown Can only be measured for a few days at most. Therefore, I thought it would be interesting to have a countdown app that could measure several years. The app preserve history and judge whether you were able to achieve the countdown.It,s useful for people who want to count days in a long span.</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/102008212/196005308-b1b9c8e4-440f-4800-a654-9df90277bd8e.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/196005313-4c534958-4ca4-43d0-a929-ef22ababc155.png" width="240dp" />
<img src="https://user-images.githubusercontent.com/102008212/196005316-21fcb6f1-f0f4-49d9-a3b9-543aea13cffd.png" width="240dp" />
</p>

## :blue_book: Validated Numerics
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

## :lock: Cryptography and Information Security <sub>(Coming Soon!)</sub>
