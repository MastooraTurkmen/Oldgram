# Oldgram

> Three popular persons whose paintings sold thousands of dollars 🙀

https://oldgram-project.netlify.app/

This is an amazing CSS and HTML project. In these images, you can see a lot of **_Oldgram_** photos.
There are also wonderful icons.

![oldgram-1](https://github.com/MastooraTurkmen/Oldgram/assets/132576850/e0b0f0a4-aed3-4137-b8d0-35a711b73a2d)

![oldgram-2](https://github.com/MastooraTurkmen/Oldgram/assets/132576850/8965c339-a6ec-444a-921e-f50f2c90cf6f)

![oldgram-3](https://github.com/MastooraTurkmen/Oldgram/assets/132576850/227c4a81-3bf0-4e12-852c-9cc33a253706)


-----


## Cloning the project 🪛🔨

```bash
# Clone this repository
$ git clone https://github.com/MastooraTurkmen/Oldgram.git

# Go inside the repository 
$ cd Oldgram
```

-----

## Languages and Tools are used 🗣️🔧

1. **Languages** 🗣️

    + [HTML](https://github.com/topics/html)
    + [HTML5](https://github.com/topics/html5)
    + [CSS](https://github.com/topics/css)
    + [CSS3](https://github.com/topics/css3)
    + [JavaScript](https://github.com/topics/javascript)

2. **Tools** 🔧

    + [Chrome](https://github.com/topics/chrome)
    + [Figma](https://github.com/topics/figma)
    + [VSCode](https://github.com/topics/vscode)
    + [Netlify](https://github.com/topics/netlify)


------


## Deployment 📥

1. How to deploy our project to the ***Netlify*** site?
2. I use [Netlify App](https://app.netlify.com/) for deploying my projects.
3. Go to the Netlify site and select Add a new site.
4. From there select **_Deploy with Github_**.
   ![Oldgram](./netlify-screenshots/netlify.png)
5. Then write your project name and select it.
   ![Oldgram](./netlify-screenshots/netlify-1.png)
6. After selecting here you can see that the project **_Review configuration for Oldgram_** and then select the **_Deploy Oldgram_** Button.
   ![Oldgram](./netlify-screenshots/netlify-2.png)
   ![Oldgram](./netlify-screenshots/netlify-3.png)
7. Now your project is Live.
   ![Oldgram](./netlify-screenshots/netlify-4.png)



------


## Author 👩🏻‍💻

**Mastoora Turkmen**

[LinkedIn](https://www.linkedin.com/in/mastoora-turkmen/) 
<br>
[Github](https://github.com/MastooraTurkmen/) 
<br>
[Twitter](https://twitter.com/MastooraJ22)


------


# Codes are used 

1. ***Index HTML***
2. ***Index CSS***
3. ***Index JS***


## ***Index HTML***

```html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.css">
    <link rel="stylesheet" href="index.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300;900&display=swap" rel="stylesheet">
    <title>Oldgram</title>
</head>
<body>      
    <header>
        <img class="logo-img" src="images/logo.png">
        <img class="user-avatar-img" src="images/user-avatar.png">
    </header>
    <section>
        <div class="section-one">
              <img class="avatar-vangogh-img" src="images/avatar-vangogh.jpg">
              <h3>Vincent van Gogh<p>Zudert, Netherlands</p></h3>
            </div>
            <img class="post-vangogh-img" src="images/post-vangogh.jpg">
            <img class="icons" src="images/icon-heart.png">
            <img class="icons" src="images/icon-comment.png">
            <img class="icons" src="images/icon-dm.png">
            <h4>21,492 likes</h4>
            <p class="user-name-caption"><span>vincey1853</span>  just took a few mushrooms lol</p>
            <div class="line-img"></div>
    </section>
    <section>
        <div class="section-one">
            <img class="avatar-courbet-img" src="images/avatar-courbet.jpg">
            <h3>Gustave Courbet<p>Ornans, France</p></h3>
        </div>
        <img class="post-courbet-img" src="images/post-courbet.jpg">
        <img class="icons" src="images/icon-heart.png">
        <img class="icons" src="images/icon-comment.png">
        <img class="icons" src="images/icon-dm.png">
        <h4>12,502 likes</h4>
        <p class="user-name-caption"><span>gus1819</span> i'm feelin a bit stressed tbh</p>
        <div class="line-img"></div>
    </section>
    <section>
        <div class="section-one">
            <img class="avatar-durcreux-img" src="images/avatar-ducreux.jpg">
            <h3>Joseph Ducreux<p>Paris, France</p></h3>
        </div>
        <img class="post-ducreux-img" src="images/post-ducreux.jpg">
        <img class="icons" src="images/icon-heart.png">
        <img class="icons" src="images/icon-comment.png">
        <img class="icons" src="images/icon-dm.png">
        <h4>15,137 likes</h4>
        <p class="user-name-caption"><span>jd1735</span> gm friends! which coin are YOU stacking up today?? post below and WAGMI!</p>
    </section>  
    <script src="index.js"></script>
</body>
</html>

```

## ***Index CSS***

```css

html, 
body {
    padding: 0;
    margin: 0 auto;
    width: 375px;
    background: #FFFFFF;
    font-family: 'Source Sans Pro', sans-serif;
    line-height: 16px;

}

/* typography */

header{
    display: flex;
    justify-content: space-between;
    box-sizing: border-box;
    border-bottom: 1px solid #C6C6C6;
    padding: 16px 8px;
    width: 375px;
    margin: 0 auto;
}

.logo-img{
    width: 127px;
}

.user-avatar-img, 
.avatar-vangogh-img, 
.avatar-durcreux-img, 
.avatar-courbet-img{
    width: 34px;
    height: 34px;
    border-radius: 50%;
    margin-top: 10px;
}

.post-vangogh-img, 
.post-courbet-img, 
.post-ducreux-img{
    height: 375px;
    width: 375px;
}

.section-one{
    display: flex;
    margin-left: 10px;
}

h3{
    margin-left: 7px;
    font-weight: 700;
    font-size: 13px;
    margin-bottom: 0;
}

h4{
    font-weight: 700;
    font-size: 13px;
    margin-left: 10px;
    margin-top: 0px;
}

p{
    font-weight: 500;
    margin-top: 0;
}

.line-img{
    padding: 15px 0;
    background: #EDEDED;
}

.icons{
    margin: 15px 4px;
    margin-bottom: 10px;
    width: 28px;
    height: 28px;
}

.user-name-caption{
    font-size: 13px;
    margin-left: 10px;
    line-height: 16px;
}

span{
    font-weight: 700;
}
```


## ***Index JS***   

```js
const posts = [
    {
        name: "Vincent van Gogh",
        username: "vincey1853",
        location: "Zundert, Netherlands",
        avatar: "images/avatar-vangogh.jpg",
        post: "images/post-vangogh.jpg",
        comment: "just took a few mushrooms lol",
        likes: 21
    },
    {
        name: "Gustave Courbet",
        username: "gus1819",
        location: "Ornans, France",
        avatar: "images/avatar-courbet.jpg",
        post: "images/post-courbet.jpg",
        comment: "i'm feelin a bit stressed tbh",
        likes: 4
    },

]


```