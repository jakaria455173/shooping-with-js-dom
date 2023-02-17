# shooping-with-js-dom


### All Html Code :)

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

     <link href="https://cdn.jsdelivr.net/npm/daisyui@2.50.1/dist/full.css" rel="stylesheet" type="text/css" />
     <script src="https://cdn.tailwindcss.com"></script>
     <script src="https://cdn.tailwindcss.com"></script>
     <!--* ====castom css file link up===== *-->
     <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="max-w-7xl mx-auto">
        <div class="navbar bg-pink-300 text-white px-10">
            <div class="flex-1">
              <a class="btn btn-ghost normal-case text-xl">Fotafot</a>
            </div>
            <div class="flex-none">
              <div class="dropdown dropdown-end">
                <label tabindex="0" class="btn btn-ghost btn-circle">
                  <div class="indicator">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" /></svg>
                    <span class="badge badge-sm indicator-item">8</span>
                  </div>
                </label>
                <div tabindex="0" class="mt-3 card card-compact dropdown-content w-52 bg-base-100 shadow">
                  <div class="card-body">
                    <span class="font-bold text-lg">8 Items</span>
                    <span class="text-info">Subtotal: $999</span>
                    <div class="card-actions">
                      <button class="btn btn-primary btn-block">View cart</button>
                    </div>
                  </div>
                </div>
              </div>
              <div class="dropdown dropdown-end">
                <label tabindex="0" class="btn btn-ghost btn-circle avatar">
                  <div class="w-10 rounded-full">
                    <img src="img/carousel.jpg" />
                  </div>
                </label>
                <ul tabindex="0" class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
                  <li>
                    <a class="justify-between">
                      Profile
                      <span class="badge">New</span>
                    </a>
                  </li>
                  <li><a>Settings</a></li>
                  <li><a>Logout</a></li>
                </ul>
              </div>
            </div>
          </div>
    </header>

    <main class="max-w-7xl mx-auto">
        <section class="grid grid-cols-2">
            <div class="bg-pink-100 pt-6 px-4">
                <div class="flex flex-wrap">
                    <div class="card card-compact w-[32%] bg-base-100 shadow-xl mr-2 mb-3">
                        <figure><img src="img/coffee.jpg" alt="Shoes" /></figure>
                        <div class="card-body">
                          <h2 id="coffee-name" class="card-title">Coffee Js</h2>
                          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                          <div>
                            <h3 class="text-lg font-semibold">Price: $<span id="coffee-price">100</span></h3>
                            <h3 class="text-lg font-semibold">Quantity: <span id="coffee-quantity">5</span></h3>
                          </div>
                          <div class="card-actions justify-end">
                            <button id="coffee-js-btn" class="bg-pink-600 text-white px-3 rounded-lg py-2">Add to cart</button>
                          </div>
                        </div>
                      </div>
                      <div class="card card-compact w-[32%] bg-base-100 shadow-xl mr-2 mb-3">
                        <figure><img src="img/coffee.jpg" alt="Shoes" /></figure>
                        <div class="card-body">
                          <h2 id="heart-name" class="card-title">Heart Js</h2>
                          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                          <div>
                            <h3 class="text-lg font-semibold">Price: $<span id="heart-price">200</span></h3>
                            <h3 class="text-lg font-semibold">Quantity: <span id="heart-quantity">15</span></h3>
                          </div>
                          <div class="card-actions justify-end">
                            <button id="heart-js-btn" class="bg-pink-600 text-white px-3 rounded-lg py-2">Add to cart</button>
                          </div>
                        </div>
                      </div>
                      <div class="card card-compact w-[32%] bg-base-100 shadow-xl mr-2 mb-3">
                        <figure><img src="img/coffee.jpg" alt="Shoes" /></figure>
                        <div class="card-body">
                          <h2 id="panda-name" class="card-title">Panda Js</h2>
                          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                          <div>
                            <h3 class="text-lg font-semibold">Price: $<span id="panda-price">400</span></h3>
                            <h3 class="text-lg font-semibold">Quantity: <span id="panda-quantity">25</span></h3>
                          </div>
                          <div class="card-actions justify-end">
                            <button id="panda-js-btn" class="bg-pink-600 text-white px-3 rounded-lg py-2">Add to cart</button>
                          </div>
                        </div>
                      </div>
                      <div class="card card-compact w-[32%] bg-base-100 shadow-xl mr-2 mb-3">
                        <figure><img src="img/coffee.jpg" alt="Shoes" /></figure>
                        <div class="card-body">
                          <h2 id="umbrella-name" class="card-title">Umbrella Js</h2>
                          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                          <div>
                            <h3 class="text-lg font-semibold">Price: $<span id="umbrella-price">600</span></h3>
                            <h3 class="text-lg font-semibold">Quantity: <span id="umbrella-quantity">
                                5</span></h3>
                          </div>
                          <div class="card-actions justify-end">
                            <button id="umbrella-js-btn" class="bg-pink-600 text-white px-3 rounded-lg py-2">Add to cart</button>
                          </div>
                        </div>
                      </div>
                      <div class="card card-compact w-[32%] bg-base-100 shadow-xl mr-2 mb-3">
                        <figure><img src="img/coffee.jpg" alt="Shoes" /></figure>
                        <div class="card-body">
                          <h2 id="vue-name" class="card-title">Vue Js</h2>
                          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                          <div>
                            <input id="vue-price" class="py-1 border border-pink-600 px-1 w-[80%] rounded-lg mb-1" type="text" placeholder="Price">
                            <br>
                            <input id="vue-quantity" class="py-1 border border-pink-600 px-1 w-[80%] rounded-lg mb-1" type="text" placeholder="Quantity">
                          </div>
                          <div class="card-actions justify-end">
                            <button id="vue-js-btn" class="bg-pink-600 text-white px-3 rounded-lg py-2">Add to cart</button>
                          </div>
                        </div>
                      </div>
                </div>


            </div>
            <div class="bg-gray-600">
                <h1 class="text-center text-3xl py-5 underline text-white">Total Products: 00</h1>
                <div>
                    <table class="text-white mx-auto bg-gray-800 rounded-lg">
                        <thead>
                            <tr id="product-row">
                                <th class="pr-10 pl-4 py-4">No</th>
                                <th class="px-10 py-4">Name</th>
                                <th id="price" class="px-10 py-4">Price</th>
                                <th class="px-10 py-4">Quantity</th>
                                <th class="px-10 py-4">Total</th>
                            </tr>
                        </thead>
                        <tbody id="table-container" class="text-center text-green-600 font-semibold text-lg">

                        </tbody>
                    </table>
                </div>

                <h3 class="text-white text-3xl text-right pr-10 py-5">Total Product Amount: $<span id="amount">00</span></h3>
            </div>
        </section>
    </main>

    <!-- <script src="index.js"></script> -->
    <script src="product.js"></script>
</body>
</html>

```


### All Javascript Code :)

```js
// This Function Use For All Id Get In Javascript  😀
function getElementId(getId) {
  const elementId = document.getElementById(getId)
  return elementId
}


// function all text element convert in number
function getTextElementValueById(elementId) {
  let getElement = document.getElementById(elementId)
  let getElementValue = parseInt(getElement.innerText)
  return getElement.innerText = getElementValue
}

// Funtion all elementIdGet & set new value
function setTextElementValueById(elementId, value) {
  let setElement = document.getElementById(elementId);
  setElement.innerText = value
}

let serial=0
function getProductPrice( productName, priceProduct, quantityProduct) {
  serial=serial+1
  let productNames = getElementId(productName).innerText
  let productPrice = getTextElementValueById(priceProduct)
  let productQuantity = getTextElementValueById(quantityProduct)
  let productTotalPrice = productPrice * productQuantity
  let tableContainer = getElementId('table-container')
  let productRow = document.createElement('tr')
  productRow.id='rowProduct'
  productRow.innerHTML = `
  <td>${serial}</td>
  <td>${productNames}</td>
  <td>${productPrice}</td>
  <td>${productQuantity}</td>
  <td id="price">${productTotalPrice}</td>
  `
  return tableContainer.append(productRow)
}


// calculate total product amount
function calculateTotal(priceProduct,pQuantity) {
  let productPrice = getTextElementValueById(priceProduct)
  let productQuantity = getTextElementValueById(pQuantity)
  let productTotalPrice = productPrice * productQuantity
  let total = getElementId('amount').innerText
  let finalTotal = parseInt(total)
  let totalPrice = productTotalPrice + finalTotal
  finalTotal=totalPrice
  return setTextElementValueById('amount',totalPrice)
}



// coffee js btn
getElementId('coffee-js-btn').addEventListener('click', function () {
  serial
  getProductPrice('coffee-name', 'coffee-price', 'coffee-quantity')
  calculateTotal('coffee-price','coffee-quantity')
})


// heart js btn
getElementId('heart-js-btn').addEventListener('click', function () {
  serial
  getProductPrice('heart-name', 'heart-price', 'heart-quantity')
  calculateTotal('heart-price', 'heart-quantity')

})


// panda js btn
getElementId('panda-js-btn').addEventListener('click', function () {
  serial
  getProductPrice('panda-name', 'panda-price', 'panda-quantity')
  calculateTotal('panda-price', 'panda-quantity')
})


// umbrella js btn
getElementId('umbrella-js-btn').addEventListener('click', function () {
  serial
  getProductPrice('umbrella-name', 'umbrella-price', 'umbrella-quantity')
  calculateTotal('umbrella-price', 'umbrella-quantity')
})

```
