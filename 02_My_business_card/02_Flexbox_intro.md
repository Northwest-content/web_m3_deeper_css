Fiiiinnnaaally its `Flexbox` Tiimmeee!!! 😍

**❓ Question:** 

> What is `Flexbox`?

**🤓 Answer:** 

> It’s an amazing way to control where elements are displayed on the page! 😎
>
> Its the most popular and easy way to make websites responsive 💙

**01_Flexbox_setup**

Before we start with our business card, we will have a simple understanding for the `flexbox` concept.

We will start with the most simplest `body`:

![img](https://lh5.googleusercontent.com/4n81Gw7_k_Pyvq5bOzTBG7FIRjHJGhfdAr46hDdOn-CcK3-nQsnqV-O63Z7mbDctFuMN5FpoviZXKyq09xPx2QwdLa902iL_hQ5tbwHIvOP7Cqac4yXMhtvtggaa3vvF8TALsU24=s0)

With an `HTML`

``````html
<body>
    <div class="container">
        <div class="item-1 item"></div>
        <div class="item-2 item"></div>
        <div class="item-3 item"></div>
    </div>
</body>
``````

And a `CSS`

``````css
html,
body {
  margin: 0;
  padding: 0;
}

.container {
  background-color: #93e5ab;
}

.item {
  height: 50px;
  width: 50px;
}

.item-1 {
  background-color: #9c3848;
}

.item-2 {
  background-color: #1e3888;
}

.item-3 {
  background-color: #f5e663;
}

``````

**📝 Note:**

> The container is colored just to be able to know the background, and the `div` items are colored to represent your future elements.

**Flexbox Steps:**

1. Having a `container` ✔
2. Having `items` inside the `container` ✔
3. Changing the `display` for the container to `display: flex;` 

``````css
display: flex;
``````

**Implementation 👀** 

![img](https://lh4.googleusercontent.com/J3tvBTvdU1ezY8xShwO-GRQb0RhI1pTyDzCAc4jbnJvGbZRgEFXNcSCDwRyUV5l0M0AQyUZ8bAS-RL4kYO8_Cj0JdV47lEQIN7jpHTwjbuhaEEJ1WUUNPVMu-t1I_P_gdFjufDgm=s0)

Play with flex through [link](https://flexbox.help/)

**02_Use_FlexHelp**


![img](https://lh5.googleusercontent.com/3-5CJFr4utb-zohnwojRlAzOVZFOyDIZ_RDjj3cd4EjVien0QFoNnCPSqu7cSuGoqPFfLwwHPIj6qNIP4stf7cI3ocujP96Wvf4yO9uGqXD9LbZrul0-LHx2mGVvFBgPZdE2WpNZ=s0)

Let's play 

We have 3 items that we want to center


![img](https://lh4.googleusercontent.com/pzItD9nXVsQelv6BKTM6vC9DasiafI8L3pQ8x7MTZRGNFhsGMs6skyI6DTeGOYcD3rQB13lNKtDwTaDH-_EW6COrWJKlORUkdPxCI-2VwivS6xeO2jR1UFKoQAloSl2M7TdwE3jc=s0)

``````css
	display: flex;
	flex-direction: row;
	flex-wrap: wrap;
	justify-content: center;
	align-items: center;
	align-content: stretch;
``````

Just by viewing and playing with the rules we can see that our `container` will be getting this, let's test it out


![img](https://lh3.googleusercontent.com/_RaMBFpr1q_KZZTGxpMwu12V4tC0j_RQy__UxEoJtrmMet_yC1pwX5v3GJjtKLIwHciOJw6dJVzuqy5mZ1SMExe0a_m8gAcmcPzVy2IK_sA_Ch6yxO9girjx1R6i3smqjpkoieWA=s0)

**❓ Question:** 

> Even after editing the code to fit, whyyyyyyy didn't it center?

**🤓 Answer:** 

> because the height of the container is not higher to be able to see the centering 

**Fixing:** 


![img](https://lh4.googleusercontent.com/oaJt1LC5xxvzTTbuAI2dytEsH25SLTDVb-jEW-X9fMwhMxAIjLOVe5Oz0rEMRl28tUP_492q_Fh8R3npS-u_9xfAfcqlUqtB5HsMMjIjEjxglytm-QPxVChvbFMpXWOIASFMqKXB=s0)

YEEEEEESSSSSSSS 🔥
