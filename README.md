# CSS-Project

## html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="1.css">
</head>
<body>
    <header>
        <nav>
            <h1>Dribbble</h1>
            <ul>
                <li><a href="#">Shots</a></li>
                <li><a href="#">Designers</a></li>
                <li><a href="#">Teams</a></li>
                <li><a href="#">Community</a></li>
                <li><a href="#">Jobs</a></li>
            </ul>
            <div class="auth">
                <a href="#">Sign up</a>
                <a href="#">Sign in</a>
            </div>
        </nav>
        <div class="header-content">
            <h2>What are you working on?</h2>
            <p>Dribbble is show and tell for designers.</p>
            <button>Learn more</button>
            <button>Sign up</button>
        </div>
    </header>
    <main>
        <section class="gallery">
            <div class="card">
                <img src="vj.jpg" alt="Design 1">
                <div class="details">
                    <h3>Joseph Vijay</h3>
                    <p>320M views • 101M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="dhoni.jpg" alt="Design 1" width="350px">
                <div class="details">
                    <h3>M.S Dhoni</h3>
                    <p>310M views • 99M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="cena.jpg" alt="Design 1" width="350px">
                <div class="details">
                    <h3>John Cena</h3>
                    <p>300M views • 100M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="rohit.jpg" alt="Design 1">
                <div class="details">
                    <h3>Rohit Sharma</h3>
                    <p>80M views • 53M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="musk.jpg" alt="Design 1">
                <div class="details">
                    <h3>Elon Musk</h3>
                    <p>130M views • 121M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="b.jpg" alt="Design 1">
                <div class="details">
                    <h3>Amitabh Bachchan</h3>
                    <p>130M views • 95M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="rossi.jpg" alt="Design 1">
                <div class="details">
                    <h3>valentino rossi</h3>
                    <p>110M views • 102M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="messi.jpg" alt="Design 1">
                <div class="details">
                    <h3>Lionel Messi</h3>
                    <p>860M views • 832M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="ro.jpg" alt="Design 1">
                <div class="details">
                    <h3>CR Ronaldo</h3>
                    <p>930M views • 910M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="deep.jpg" alt="Design 1">
                <div class="details">
                    <h3>Deepika Padukone</h3>
                    <p>200M views • 101M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="jr.jpg" alt="Design 1">
                <div class="details">
                    <h3>Neymar Jr</h3>
                    <p>750M views • 644M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="hsu.jpg" alt="Design 1">
                <div class="details">
                    <h3>Thassapak Hsu</h3>
                    <p>60M views • 54M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="ishu.jpg" alt="Design 1">
                <div class="details">
                    <h3>Aishwarya Rai</h3>
                    <p>140M views • 138M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="stalin.jpg" alt="Design 1">
                <div class="details">
                    <h3>M.K Stalin</h3>
                    <p>145M views • 139M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="pan.jpg" alt="Design 1">
                <div class="details">
                    <h3>Sergio ramos</h3>
                    <p>500M views • 312M likes</p>
                </div>
            </div>
        </section>
    </main>
</body>
</html>
```

## css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #000;
    color: rgb(255, 249, 249);
    padding: 20px;
    text-align: center;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: rgb(255, 0, 0);
    text-decoration: none;
}

.auth a {
    margin: 0 10px;
    color: rgb(255, 0, 0);
    text-decoration: none;
}

.header-content {
    padding: 0;
}

.header-content h2 {
    margin: 0;
}

.header-content button {
    margin: 10px;
    padding: 10px 20px;
    border: none;
    background-color: #31d6ec;
    color: rgb(255, 0, 0);
    cursor: pointer;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.card {
    background: rgb(255, 0, 0);
    border: 1px solid #ff0000;
    border-radius: 5px;
    overflow: hidden;
    text-align: center;
}

.card img {
    max-width: 100%;
    display: block;
}

.card .details {
    padding: 15px;
}

.card h3 {
    margin: 10px 0;
}

.card p {
    margin: 0;
    color: #000000;
}
```

## Output:
![Screenshot 2024-07-06 095252](https://github.com/vijay21500269/CSS-Project/assets/94381788/09e8fe20-4165-4167-b42d-19ca5c988b6b)
