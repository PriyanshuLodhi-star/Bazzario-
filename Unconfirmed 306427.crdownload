
let cart = [];

let product1 = {
    name: "Fresh Vegetables",
    price: 80
};

let product2 = {
    name: "Chocolate Cake",
    price: 450
};

let product3 = {
    name: "Handmade Vase",
    price: 250
};

let product4 = {
    name: "Decorative Lamp",
    price: 550
};

let product5 = {
    name: "Window Curtains",
    price: 650
};

let product6 = {
    name: "Cotton Fabric",
    price: 300
};

let product7 = {
    name: "Casual Shirt",
    price: 500
};

let product8 = {
    name: "Fresh Bread",
    price: 60
};



function addProduct1() {
    cart.push(product1);

    document.getElementById("cartItems").innerHTML +=
        "<p>Fresh Vegetables - ₹80</p>";

    alert("Fresh Vegetables added to cart!");
}

function addProduct2() {
    cart.push(product2);

    document.getElementById("cartItems").innerHTML +=
        "<p>Chocolate Cake - ₹450</p>";

    alert("Chocolate Cake added to cart!");
}

function addProduct3() {
    cart.push(product3);

    document.getElementById("cartItems").innerHTML +=
        "<p>Handmade Vase - ₹250</p>";

    alert("Handmade Vase added to cart!");
}

function addProduct4() {
    cart.push(product4);

    document.getElementById("cartItems").innerHTML +=
        "<p>Decorative Lamp - ₹550</p>";

    alert("Decorative Lamp added to cart!");
}

function addProduct5() {
    cart.push(product5);

    document.getElementById("cartItems").innerHTML +=
        "<p>Window Curtains - ₹650</p>";

    alert("Window Curtains added to cart!");
}

function addProduct6() {
    cart.push(product6);

    document.getElementById("cartItems").innerHTML +=
        "<p>Cotton Fabric - ₹300</p>";

    alert("Cotton Fabric added to cart!");
}

function addProduct7() {
    cart.push(product7);

    document.getElementById("cartItems").innerHTML +=
        "<p>Casual Shirt - ₹500</p>";

    alert("Casual Shirt added to cart!");
}

function addProduct8() {
    cart.push(product8);

    document.getElementById("cartItems").innerHTML +=
        "<p>Fresh Bread - ₹60</p>";

    alert("Fresh Bread added to cart!");
}

function showCart() {
    document.getElementById("cartItems").innerHTML +=
        "<h3>Total Products: " + cart.length + "</h3>";
}

function checkout() {
    alert("Thank you for shopping with Bazario!");
}
function addVendorProduct() {

    let name = document.getElementById("productName").value;

    let price = document.getElementById("productPrice").value;

    let category = document.getElementById("productCategory").value;

    let product = {
        name: name,
        price: price,
        category: category
    };

    document.getElementById("vendorProducts").innerHTML +=
        "<div class='vendor-product'>" +
        "<h3>" + product.name + "</h3>" +
        "<p>Price: ₹" + product.price + "</p>" +
        "<p>Category: " + product.category + "</p>" +
        "</div>";

    alert("Product added successfully!");

}

let total = 2840;

function removeProduct(productId, price) {
    document.getElementById(productId).remove();

    total = total - price;

    document.getElementById("totalPrice").innerHTML = total;
    
    alert("Product removed from cart!");
}
 function checkout() {
    alert("Thank you for shopping with Bazario!");

    let count = localStorage.getItem("visitCount");

    if (count == null) {
        count = 0;
    }

    count++;

    localStorage.setItem("visitCount", count);

    window.location.href = "index.html";
}
