<div align="center">
<br/>

<!-- Banner -->
<img src="https://github.com/user-attachments/assets/de2384ff-a586-4dd6-b714-de2ae8756058" width="1800px" alt="Vestia_banner">
<br/>

<!-- Tech Badges -->
<div>
<img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt="Express.js">
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
</div>
<!-- Title -->
<h3>E-commerce Clothes Shopping Platform</h3>
<h6>Mini-project | Beginner friendly </h6>
</div>
<br/>

<!-- Index -->

## <a name="table">Contents</a>

1. 👋 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 📃 [Pages Contained](#page-contained)
5. 🚀 [Quick Start](#quickStart)
6. 🔗 [Assets](#assets)
7. 🎴 [ScreenShorts](#ScreenShorts)

<br/>
<!-- Introduction -->

## <a name="introduction"> 👋 Introduction</a>

<p>
Vestia is an e-commerce platform that makes shopping for fashionable and modern clothing effortless. It offers a seamless experience for users to explore a wide range of men's and women's clothing, find the perfect fit, and enhance their wardrobe.

Vestia aims to be your go-to destination for stylish apparel that matches your unique taste.

</p>

<br/>

<!-- Tech Stack -->

## <a name="tech-stack"> ⚙️ Tech Stack</a>

- Express.js
- MongoDB
- JavaScript
- HTML
- CSS

<br/>

<!-- Features  -->

## <a name="features"> 🔋 Features</a>

⭐ **Simple User Registration:** Register with just your email to start shopping.

⭐ **Browse Clothing:** Explore men's and women's fashion collections.

⭐ **Detailed Product View:** View complete details for each item.

⭐ **Add to Cart:** Add your favorite items to the cart.

⭐ **Manage Cart:** Increase or decrease the items , Choose from multiple sizes , Remove items.

⭐ **Responsive:** Full responsiveness across devices for consistent user experience.

<br/>

<!-- Features  -->

## <a name="page-contained"> 📃 Pages Contained</a>

1. **Home Page:** Overview of featured products and categories.
2. **Product Details Page:** Detailed view of selected products.
3. **Cart Page:** Manage items before proceeding to checkout.

<br/>

<!-- Quick Start -->

## <a name="quickStart">🚀 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Aditya356-c/Vestia-Ecommerce.git
cd Vestia-Ecommerce
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project (client & server) and add the following content:

```env
SERVER_PORT = (example : 8080)
CLIENT_PORT = (example : http://localhost:5500)
MONGODB_URI = (example : mongodb+srv://<username>:<password>@cluster0.mongodb.net/<yourDatabaseName>?retryWrites=true&w=majority)
```

**In ApiService.js file**

```bash
BASE_URL: "<YOUR-SERVER-URL>/api/v1/"
```

**Running the Project**

```bash
npm run dev
```

<br/>

<!-- Assets -->

## <a name="assets">🔗 Assets</a>

MongoDB Atlas : https://www.mongodb.com/atlas

<details>
<summary><code>Project.json</code></summary>

###### Copy from here or Download from ` example_data` folder

```
[
    {
        "name": "Classic Comfort Fit Joggers",
        "description": "These joggers are designed to offer ultimate comfort and style. Crafted from a soft, breathable cotton blend, they are perfect for lounging at home, running errands, or light workouts. Featuring an elastic waistband with a drawstring, tapered legs, and side pockets for convenience, these joggers provide a relaxed yet trendy fit. Pair them with your favorite t-shirt or hoodie for a laid-back look.",
        "price": 49.99,
        "ondiscount": true,
        "discountPrice": 39.99,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 10,
        "image": "https://i.pinimg.com/736x/9b/29/7d/9b297d42bc5503a8e784025d96fe897f.jpg",
        "createdAt": "2025-01-06T00:00:00Z"
    },
    {
        "name": "Slim Fit Denim Jeans",
        "description": "Elevate your wardrobe with these stylish slim-fit denim jeans. Designed to contour to your body while allowing freedom of movement, these jeans feature high-quality denim fabric that ensures durability and long-lasting color. With a classic five-pocket design and button fly, they are versatile enough for both casual outings and semi-formal occasions. Pair them with sneakers and a t-shirt for a modern look.",
        "price": 23.20,
        "ondiscount": false,
        "discountPrice": null,
        "category": "women",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 15,
        "image": "https://i.pinimg.com/736x/4b/13/c4/4b13c402f0b1b35c542fff5baafd06dd.jpg",
        "createdAt": "2025-01-08T00:00:00Z"
    },
    {
        "name": "Cotton Crew Neck T-Shirt",
        "description": "Stay comfortable and stylish with this premium cotton crew neck t-shirt. Made from 100% pure cotton, this t-shirt offers unmatched breathability and softness, making it ideal for daily wear. The minimalist design and versatile color make it easy to pair with jeans, shorts, or joggers. It's perfect for layering under jackets or wearing on its own for a clean, casual look.",
        "price": 19.99,
        "ondiscount": true,
        "discountPrice": 14.99,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 20,
        "image": "https://i.pinimg.com/736x/b5/1b/d3/b51bd335ee78c257b29a4b9affb6a387.jpg",
        "createdAt": "2025-01-05T00:00:00Z"
    },
    {
        "name": "Leather Biker Jacket",
        "description": "Exude confidence and style with this premium leather biker jacket. Made from high-quality leather, this jacket features a classic asymmetrical zipper design, metal hardware accents, and a comfortable inner lining. Perfect for chilly evenings or adding an edgy touch to your outfit, this jacket is a timeless addition to your wardrobe. Pair it with dark jeans and boots for a bold look.",
        "price": 92.80,
        "ondiscount": false,
        "discountPrice": null,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 0,
        "image": "https://i.pinimg.com/736x/e9/f9/5d/e9f95d57a0b683c919b7319f5d036827.jpg",
        "createdAt": "2025-01-07T00:00:00Z"
    },
    {
        "name": "Chino Pants",
        "description": "A wardrobe essential, these chino pants are the perfect blend of comfort and style. Crafted from a durable cotton fabric with a slight stretch, these pants offer all-day comfort. Their sleek design makes them suitable for both formal and casual settings. Dress them up with a button-down shirt and loafers, or keep it casual with a t-shirt and sneakers.",
        "price": 23.20,
        "ondiscount": true,
        "discountPrice": 13.92,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 12,
        "image": "https://i.pinimg.com/736x/ba/51/ce/ba51cebef5ea7a2e4e4dc4ef26c3d3be.jpg",
        "createdAt": "2025-01-09T00:00:00Z"
    },
    {
        "name": "Dangri Dress Dresses Jumpsuit shirts",
        "description": "A versatile dangri dress made from a durable yet lightweight fabric, perfect for casual outings or chic daywear. With adjustable straps and a flattering fit, it pairs beautifully with both t-shirts and blouses.",
        "price": 25.52,
        "ondiscount": false,
        "discountPrice": null,
        "category": "women",
        "sizes": [
            "XS",
            "SM",
            "MD",
            "L"
        ],
        "stock": 5,
        "image": "https://i.pinimg.com/736x/bf/12/61/bf1261040154fa4e9055b533c7d0a80d.jpg",
        "createdAt": "2025-01-11T00:00:00Z"
    },
    {
        "name": "F Spinola - Creative Director in Mexico, Mexico",
        "description": "Celebrate creativity and innovation with this uniquely designed t-shirt. Inspired by the vibrant artistry of Mexico, it combines style and comfort in soft, breathable cotton. Perfect for showcasing your appreciation for design and culture, this t-shirt is a versatile addition to any wardrobe.",
        "price": 10.44,
        "ondiscount": true,
        "discountPrice": 6.96,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 22,
        "image": "https://i.pinimg.com/736x/ca/d9/e2/cad9e2fa8a35b89112e771f9e7d5dfb3.jpg",
        "createdAt": "2025-01-06T00:00:00Z"
    },
    {
        "name": "Elegant Summer Dress",
        "description": "A chic summer dress crafted from lightweight, breathable fabric, ideal for warm weather. Its elegant design and vibrant colors make it perfect for casual outings or special occasions.",
        "price": 79.95,
        "ondiscount": false,
        "discountPrice": null,
        "category": "women",
        "sizes": [
            "SM",
            "MD",
            "L"
        ],
        "stock": 15,
        "image": "https://i.pinimg.com/736x/33/63/be/3363be6d6b1450df77a82032fafc6126.jpg",
        "createdAt": "2025-01-10T00:00:00Z"
    },
    {
        "name": "Men's Wool Blazer",
        "description": "Elevate your formal wear with this sophisticated wool blazer. Made from high-quality wool, this blazer features a classic two-button design and a fitted silhouette. Perfect for business meetings, formal events, or special occasions, this blazer is a timeless addition to your wardrobe. Pair it with a dress shirt and trousers for a sharp look.",
        "price": 62.06,
        "ondiscount": true,
        "discountPrice": 50.46,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 10,
        "image": "https://i.pinimg.com/736x/50/cb/6d/50cb6dfbf7094b3c16a057c61b921077.jpg",
        "createdAt": "2025-01-07T00:00:00Z"
    },
    {
        "name": "Balloon Sleeve Hem Ruffle Chiffon Shirt Top",
        "description": "A stylish chiffon top featuring balloon sleeves and delicate ruffles at the hem, adding a feminine and elegant touch to any outfit. Perfect for casual and semi-formal occasions.",
        "price": 10.44,
        "ondiscount": false,
        "discountPrice": null,
        "category": "women",
        "sizes": [
            "XM",
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 12,
        "image": "https://i.pinimg.com/736x/96/2c/40/962c40233d8eeb36148d690d496e8746.jpg",
        "createdAt": "2025-01-09T00:00:00Z"
    },
    {
        "name": "Gray Hoodie",
        "description": "Keep your little one warm and stylish with this boys' hoodie. Made from 100% cotton, this hoodie features a comfortable fit and a fun design. Perfect for casual outings, playdates, or everyday wear, this hoodie is a great addition to your child's wardrobe. Pair it with jeans or shorts for a cool look.",
        "price": 23.20,
        "ondiscount": true,
        "discountPrice": 17.40,
        "category": "men",
        "sizes": [
            "MD",
            "L"
        ],
        "stock": 25,
        "image": "https://i.pinimg.com/736x/ef/e5/9a/efe59ade39ef6ee1dc490d85b40ae2b4.jpg",
        "createdAt": "2025-01-08T00:00:00Z"
    },
    {
        "name": "Handmade Women's High-Waisted Green Wool Maxi Skirt - Elegant A-Line W",
        "description": "This elegant high-waisted wool maxi skirt is the epitome of sophistication. Crafted from soft green wool, its A-line design flatters all body types. Ideal for formal gatherings and special occasions, it pairs beautifully with blouses and boots.",
        "price": 33.63,
        "ondiscount": false,
        "discountPrice": null,
        "category": "women",
        "sizes": [
            "full"
        ],
        "stock": 18,
        "image": "https://i.pinimg.com/736x/a7/47/80/a74780cd87b07578b13a82757c69c00b.jpg",
        "createdAt": "2025-01-11T00:00:00Z"
    },
    {
        "name": "Red Flared Anarkali Suit Set",
        "description": "This stunning red Anarkali suit set features intricate embroidery and a flared silhouette, making it perfect for weddings, festivals, and special occasions. Pair it with traditional jewelry for a regal look.",
        "price": 40.59,
        "ondiscount": true,
        "discountPrice": 33.63,
        "category": "women",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 8,
        "image": "https://i.pinimg.com/736x/7c/77/0a/7c770a30f81a6647395d291e6494861b.jpg",
        "createdAt": "2025-01-06T00:00:00Z"
    },
    {
        "name": "Short Sleeve Lapel Polo Shirts - Champlain Color",
        "description": "A classic polo shirt crafted from breathable cotton, ideal for casual and semi-formal occasions. The champlain color adds a sophisticated touch to your wardrobe.",
        "price": 8.12,
        "ondiscount": false,
        "discountPrice": null,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L",
            "XL"
        ],
        "stock": 15,
        "image": "https://i.pinimg.com/736x/04/a8/91/04a8916b97e9967fd88857f08de72d6a.jpg",
        "createdAt": "2025-01-10T00:00:00Z"
    },
    {
        "name": "Cozy Knit Sweater",
        "description": "A warm and cozy knit sweater made from a soft wool blend, featuring a chunky cable-knit design, a relaxed fit, and a turtleneck collar. Perfect for chilly days and casual wear.",
        "price": 23.20,
        "ondiscount": true,
        "discountPrice": 11.60,
        "category": "women",
        "sizes": [
            "XS",
            "SM",
            "MD",
            "L"
        ],
        "stock": 12,
        "image": "https://i.pinimg.com/736x/c6/24/b1/c624b18ce5f91398c4a64e5f7a4d0e98.jpg",
        "createdAt": "2025-01-07T00:00:00Z"
    },
    {
        "name": "Bell Bottom Jeans",
        "description": "Vintage-inspired bell-bottom jeans with a modern twist. These jeans feature a flattering high-waist design and a comfortable fit, perfect for casual outings or a retro-themed look.",
        "price": 37.70,
        "ondiscount": true,
        "discountPrice": 23.19,
        "category": "women",
        "sizes": [
            "one size"
        ],
        "stock": 0,
        "image": "https://i.pinimg.com/736x/63/9a/a1/639aa1f21903ef3fa9ae3337fc78abb1.jpg",
        "createdAt": "2025-01-07T00:00:00Z"
    },
    {
        "name": "Emporio Armani Trousers - Moon Rock",
        "description": "Sophisticated and stylish, these Emporio Armani trousers in moon rock color are made from premium fabric. Perfect for formal and semi-formal occasions, they offer a sleek fit and timeless design.",
        "price": 25.52,
        "ondiscount": true,
        "discountPrice": 20.88,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L"
        ],
        "stock": 15,
        "image": "https://i.pinimg.com/736x/ac/90/86/ac9086d088572a26f0cbbaff99ba4392.jpg",
        "createdAt": "2025-01-0T00:00:00Z"
    },
    {
        "name": "Classic Linen Jam Shorts - Chocolate",
        "description": "Comfortable and airy linen shorts that are ideal for summer days or tropical vacations. The chocolate color adds a rich and stylish touch to these versatile shorts. Made from premium linen fabric, these shorts ensure breathability and comfort throughout the day. Featuring an elastic waistband and side pockets, they are as functional as they are stylish.",
        "price": 8.12,
        "ondiscount": true,
        "discountPrice": 5.80,
        "category": "men",
        "sizes": [
            "SM",
            "MD",
            "L"
        ],
        "stock": 20,
        "image": "https://i.pinimg.com/736x/1b/15/96/1b1596285f9360cab6e48993b3d0d902.jpg",
        "createdAt": "2025-01-12T00:00:00Z"
    }
]
```

</details>
<br>
<blockquote>notice : Image links provided in the example data are not guaranteed to be copyright-free. Additionally, these image links may work or not work in the future. Please review and ensure compliance with copyright regulations before using these images.</blockquote>

<br>

<!-- ScreenShorts-->

## <a name="ScreenShorts">🎴 ScreenShorts</a>

<img src="https://github.com/user-attachments/assets/3d540442-ee52-4cce-8ce7-4c4adeaaffe1" alt="hero_Section">
<img src="https://github.com/user-attachments/assets/e94393f4-c5dc-46fd-ab2b-16608d8d0267" alt="newArrival_Section">
<img src="https://github.com/user-attachments/assets/830ed951-ba1e-474e-97de-04247de6c1ce" alt="menWear_Section">
<img src="https://github.com/user-attachments/assets/6728329f-e182-4fc7-b146-b2969cef1d12" alt="productDetail_page">
<img src="https://github.com/user-attachments/assets/cc9c7237-211c-458a-b3e7-a046cb16eab8" alt="cart_page">
<img src="https://github.com/user-attachments/assets/13e8e188-4c20-4bf6-a17a-f0c5b0977890" alt="Register_model">

<br/>
<!-- Footer  -->
<i>If you find this project helpful or inspiring, please give it a star ! 🌟 </i>
<br/>
<br/>
<b>Thank you for checking out Vestia! Happy coding! 🚀</b>
