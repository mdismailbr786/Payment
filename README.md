<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Form</title>
</head>
<body>
    <form action="">
        <h1 style="color:blue;">Payment Form</h1>
        <p>Required Fileds are followed by *</p>
        <h2>Contact Information</h2>
        <p>Name:* <input type="text" name="name" required></p>
        <fieldset>
            <legend>Gender *</legend>
        <p style="color: red;">
            Male <input type="radio" name="Gender" id="male" required>
            Female <input type="radio" name="Gender" id="female">
        </p>
    </fieldset>
    <p>Address: <textarea name="address" id="address" cols="110" rows="2"></textarea> </p>
    <p>Email: *<input type="email" id="email" required></p>
    <p>Pincode: *<input type="number" name="pincode" id="pincode" required ></p>
    <h2>Payment Information</h2>
    <p>Card Type:*
        <select name="card_type" id="card_type" required>
            <option value="">--Select a Card Type--</option>
            <option value="visacard">Visa</option>
            <option value="mastercard">MasterCard</option>
            <option value="rupaycard">RupayCard</option>
        </select>
    </p>
    <p>
        Card Number* <input type="number" name="caer_number" id="card_number" required>
    </p>
    <p>
        Card Expration Date *<input type="date" name="exp_date" id="exp_date" required>
    </p>
    <p>CVV *<input type="password" name="cvv" id="cvv" required></p>
    <input type="Submit" value="Pay Now">


    </form>
</body>
</html>
