---
title: "Sticker shop Web page - Look around the HTML"
seoTitle: "make the webpage"
seoDescription: "Learn to create a small website using HTML templates and practice basic HTML and CSS for data analysis understanding and communication"
datePublished: Sun Jan 12 2025 02:22:19 GMT+0000 (Coordinated Universal Time)
cuid: cm5szp9fs000009jsgf4a1mej
slug: small-project-create-web-page-look-around-the-html
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1736648915212/83063e81-aedf-4c45-9641-5d37bf17ef7d.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1736648392705/b91a1291-5250-4a49-83ba-95d517626595.png

---

### Hello,

This posting is for reviewing python class and practicing making website.

At lest, in my experience, trying to make a web site is good for understanding when we analysis the data. Because we can understand how the data to stack on the DB and how the developer to work, so maybe we can have a good conversation in the meeting of office.

So, today, I’ll practice to make a small web site. Of course, I’m not a developer, I can’t make very good quality site but it is good for toy project.

### What I want to make the website

I want to experience many things, so I’ll suppose to make a website of company. And I’ll assume to upload my drawing sticker products.

# Look around HTML

Fist of all, I don’t know the HTML and CSS for website, so I’ll look around the HTML templets of free design. You can find many designs of it in the internet.

I used the theme “[astral](https://html5up.net/astral)” in this site.

If you download the file then you can see like this.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736644737955/a1f7076a-9b98-433f-b637-d72046545a32.png align="center")

Maybe Web Developer made folder html file, js folder, css folder, and images folder depends on the developers.

First of all, I’ll open the file of index.html. I open it by two way using web and vs code.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736645284536/0451a2f0-3450-45cb-8350-3c903da2b46b.png align="center")

If you open it on web then you can see the design directly. So after I will change something on the code and check the change something in web.

Let’s start to change it easily.

### change the parts

1. Name : Jane Doe → Vintage Sticker Shop
    
2. Picture : gradation → My drawing picture
    
3. Logo : Twitter → Instargram
    
4. Under : Add My blog
    

## 1 . Name

After earch the letter “Jane Doe” and I change it.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736645598118/1b879d87-a3ec-4d99-b698-e91ece3aec69.png align="center")

```haml
<header>
    <h1>Vintage Sticker</h1>
    <p>Artist SU adds beauty to your records.</p>
</header>
```

I changed like this! Let’s check it!

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736646075295/2e412abf-cf90-4512-87ca-c4f17e65688f.png align="center")

## 2 . Picture

When you look this code, in the Home section, you can find the code “img src= “images/me.jpg” about image.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736646270352/4fa95df1-bd5b-4d55-b99e-da629a8080ea.png align="center")

So, I’ll put my own image at images folder, and change the code little bit.

```http
<img src="images/pict1.jpg" alt="" />
```

I put my picture named “pict1.jpg” in the images folder and change the code.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736646412215/a22bc728-e3fc-421d-ad27-081a55f263b3.png align="center")

The result! Interesting!

## 3 . Logo

When you look at this code, usually we can meet some picture, but in here used something different way. So I found what is the “icon brands fa-twitter”

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736646886498/4515c9c2-fa35-4d71-ad0a-f86e57ffafe6.png align="center")

I can get an answer this [site](https://fontawesome.com/v4/icons/).

So I’ll change it to Instargram icon and I link it to my SNS account.(If you wonder, you can come my account and follow :))

```http
<a href="https://www.instagram.com/swimming.space/" class="icon brands fa-instargram"><span>Twitter</span></a>
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736647253071/7718734a-e0bf-47ce-b7a3-fac6ff329799.png align="center")

Now it is changed it.

## 4 . Add my blog

Find this part, you can see the Untitled, Design ect…

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736647400560/d5631d6f-c43c-44e0-8e57-da8a2085a2b6.png align="center")

Until now, we changed only letter but now we focus on the “&lt;li&gt;”

<div data-node-type="callout">
<div data-node-type="callout-emoji">💡</div>
<div data-node-type="callout-text">&lt; li &gt; : list items</div>
</div>

  
So I add the code like this. (I want to use only my link but I left the existing code as is because I need a source.

```http
<li>&copy; Untitled.</li><li>Design: <a href="http://html5up.net">HTML5 UP</a></li><li>Artist SU <a href="https://swimmingspace.hashnode.dev/"> Blog</a></li>
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736648069220/0798b31b-cff4-4999-a479-26bdc09abc76.png align="center")

Now the item is added and link is also working.

---

Today I changed main page, next time I’ll make it another things.

1. HTML is consist of &lt;head&gt; and &lt;body&gt;
    
2. &lt;div&gt; is exist inside of &lt;body&gt;
    
3. &lt;div&gt; is like a block
    
4. When the block start then write &lt;body&gt;, and end of it, write &lt;/body&gt;