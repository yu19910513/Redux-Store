# Redux-Store

Refractor platform from using global state React's Contect API to Redux.

## Description
The website designed to allow user to login and purchase items, also see their order history.


## User Story
```
- AS a senior engineer working on an e-commerce platform
- I WANT my platform to use Redux to manage global state instead of the Context API
- SO THAT my website's state management is taken out of the React ecosystem
```

## Usage
- This e-commerce website are sortec by categories.
- Users are able add items from the homepage, category page and product detail page(PDP).
- Users also able to delete item from PDP or cart.
- Users also able to update the quantity of the items in the cart.
- To continue to purchase their items, users must sign up and login.
- Payments are handled by Stripe.
- Once user paid, it will redirect them to the sucess page.
- All the items pruchased will be saved in the history.


## Gif Walkthrough
![](client/public/images/addcart.gif)
![](client/public/images/login-payment.gif)


## Technologies Use
<p><a href="https://redux.js.org/">Redux</a></p>
<p><a href="https://reactjs.org/">React.js</a></p>
<p><a href="https://www.mongodb.com/">MongoDB</a></p>
<p><a href="https://nodejs.org/">Node.js</a></p>


## MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
