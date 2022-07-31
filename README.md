### simple-navbar-design-3-html-css


---
---
`index.html`
```javascript
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NavBar</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <img class="logo" src="./images/blog.svg" alt="logo">
        <nav>
            <ul class="nav_links">
                <li><a href="#">Services</a></li>
                <li><a href="#">Projects</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
        <a class="contact" href="#"><button>Contact</button></a>
    </header>
</body>

</html>
```

---
---

`style.css`
```javascript
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&family=Playfair+Display:wght@700;900&family=Roboto&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #24252A;
}

li, a, button {
    font-family: "Montserrat", sans-serif;
    font-size: 16px;
    color: #edf0f1;
    text-decoration: none;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 10px;
}

.logo {
    cursor: pointer;
    border-radius: 25px;
}

.nav_links{
    list-style: none;
}

.nav_links li {
    display: inline-block;
    padding: 0px 20px;
    
}

.nav_links li a{
    transition: all 0.3s ease 0s;
}

.nav_links li a:hover{
    color: #0088a9;
}

button {
    padding: 9px 25px;
    background-color: rgba(0,126,169,1);
    border: none;
    border-radius: 50px;
    cursor: pointer;
    transition: all 0.3s ease 0s;
}

button:hover {
    background-color: rgba(0,136,169,0.8);
}


```

---
---


