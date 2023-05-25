<!DOCTYPE html>
<html>
<head>
    <title>Lab3_V2_Sly</title>
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>
    <section class="workspace">
        <div class="headerText">
            <h1>Payment</h1>
            <h2>Choose payment method below</h2>
        </div>
        <section class="paymentMethods">
            <div class="payBlock activePay">
                <div class="active_circle">✔</div>
                <img class="credit_card" src="./img/card.png" alt="credit card logo">
               <p>PAY WITH CREDIT CARD</p> 
            </div>
            <div class="payBlock">
                <img class="payLogo" src="./img/paypalLogo.png" alt="paypal icon">
                <p>PAY WITH PAYPAL</p>
            </div>
            <div class="payBlock">
                <img  class="payLogo" src="./img/amazonLogo.png" alt="amazon icon">
                <p>PAY WITH AMAZON PAYMENTS</p>
            </div>
        </section>
        <section class="information_form">
            <div class="billingInfo">
                <div class="billingText">
                    <div class="circle">1</div>
                    <h2>Billing info</h2>
                </div>
               <form action="info">
                    <div class="name">
                        <label for="firstname">Full Name</label><br>
                        <input type="text" name="firstname" id="firstname" placeholder="John Doe">
                    </div>
                    <div class="address">
                        <label for="address">Billing address</label><br>
                        <input type="text" name="address" id="address" placeholder="Fyrtorn" >
                        <div class="point"></div>
                    </div>
                    <div class="location">
                        <div>
                        <label for="city">city</label><br>
                          <input type="text" name="city" id="city" placeholder="Stockholm">
                        </div>
                        <div>
                            <label for="zip code">zip code</label><br>
                             <input type="text" name="zip code" id="zip code" placeholder="1284">
                        </div>
                    </div>
                    <div class="country">
                        <label for="country">country</label><br>
                        <select name="country" id="country">
                            <option value="Sweden">Sweden</option>
                            <option value="Sweden">Sweden</option>
                            <option value="Sweden">Sweden</option>
                            <option value="Sweden">Sweden</option>
                        </select>
                    </div>
               </form>
            </div>
            <div class="billingInfo">
                <div class="billingText">
                    <div class="circle">2</div>
                    <h2>Credit Card info</h2>
                </div>
                <div>
                    <form action="Card info">
                        <div class="card">
                            <label for="cardholder">Cardholder's Name</label><br>
                            <input type="text" name="cardholder" id="cardholder" placeholder="John Doe">
                        </div>
                        <div class="numder">
                            <label for="card number">card number</label><br>
                            <input type="text" name="card number" id="card number" placeholder="5645-6456-7665-0456">
                        </div>
                        <div class="yearInfo">
                            <div>
                                <label for="month">Exp.month</label><br>
                                <select  name="month" id="month">
                                
                                    <option value="12">12</option>
                                </select>
                            </div>
                            <div>
                                <label for="year">exp.year</label><br>
                                <select  name="year" id="year">
                                    <option value="18">18</option>
                                   
                                </select>
                            </div>
                        </div>
                        <div class="cvc">
                            <label for="cvc number">cvc number</label><br>
                            <input type="text" name="cvc number" id="cvc number" placeholder="468">
                        </div>
                       </form>
                </div>
            </div>
        </section>
        <section class="shopping_buttons">
            <div>
                <button class="button return_btn" type="button">return to store</button>
            </div>
            <div>
                <a class="link_text" href="#">back to shipping</a>
                <button class="button" type="button">proceed</button>
            </div>
        </section>
    </section>
</body>
</html>
