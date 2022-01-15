
>Html code

```html

<div class="products">
        <!--Card-->
        <div class="product">
            <img src="assets/images/macbookpro.jpg" alt="products main image">
            <div class="product-details">
                <h1 class="product-title">Apple macbook pro</h1>
                <div class="product-price">
                    <p>MRP<span class="product-real-price">₹​1,00,000</span><span class="product-now-price">₹​98,599</span></p>
                </div>
                <div class="product-review">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
            </div>
        </div><!--End card-->
</div>

```
>Css

```css
body{
    margin: 50px;
}

.products{
    display: flex;
    overflow: auto;
}

.product{
    position: relative;
    width: 210px;
    margin: 8px;
    background: white;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
}

.product img{
    width: 200px;
    display: block;
    margin: auto;
    padding: 4px;
    border-radius: 8px;
}

img:hover{
    transform: scale(1.1);
}

.product-details{
    padding-left: 8px;
}

.product-details .product-title{
    font-size: 15px;
    font-weight: bold;
    font-family: sans-serif;
}

.product-price{
    font-family: sans-serif;
}

p,.product-real-price,.product-now-price{
    padding: 0 3px;
    font-size: 14px;
    font-weight: 500;
}

.product-real-price{
    color: #e61212;
    text-decoration: line-through;
}

.product-now-price{
    color: #265c26;
}

.product-details .product-review{
    color: #ffa500;
    padding-bottom: 7px;
}

````

<details><summary>Credits</summary>
<p>

#### </ᴄʀᴋ>
    
    MuhammedHabeeb

</p>
</details>