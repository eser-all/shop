<main>
    <section class="banner">
        <h1>সেরা অফার!</h1>
        <p>আমাদের নতুন কালেকশন দেখুন।</p>
    </section>
    
    <section class="products">
        <h2>আমাদের প্রোডাক্টস</h2>
        <div class="product-grid">
            <div class="product-item">
                <img src="router-image.jpg" alt="রাউটার">
                <h3>রাউটার মডেল ১</h3>
                <p>দাম: ১৫০০ টাকা</p>
                <button>কিনুন</button>
            </div>
            <!-- আরও প্রোডাক্টস এখানে যোগ করা যাবে -->
        </div>
    </section>
</main>

<footer>
    <p>© স্বত্বাধিকার সংরক্ষিত</p>
</footer>
```css
body {
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
box-sizing: border-box;
}

header {
background-color: #f8f8f8;
padding: 15px;
display: flex;
justify-content: space-between;
align-items: center;
border-bottom: 1px solid #ddd;
}

nav ul {
list-style: none;
margin: 0;
padding: 0;
display: flex;
}

nav ul li {
margin-left: 20px;
}

nav ul li a {
text-decoration: none;
color: #333;
}

.banner {
background-color: #ff9900;
color: #fff;
text-align: center;
padding: 50px 0;
}

.products {
padding: 20px;
}

.product-grid {
display: flex;
flex-wrap: wrap;
gap: 20px;
}

.product-item {
border: 1px solid #ddd;
padding: 15px;
width: 200px;
text-align: center;
}

.product-item img {
max-width: 100%;
}

footer {
background-color: #333;
color: #fff;
text-align: center;
padding: 10px;
position: fixed;
bottom: 0;
width: 100%;
}
```
