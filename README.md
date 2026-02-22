<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>payment form</title>
</head>
<body>
    <form action="">
        <h1>payment Form</h1>
        <h2>Contact Information</h2>
         <p>First Name: <input type="text" name="first name" required></p>
         <p>Last name:  <input type="text" name="last name" id="" required></p>
         <fieldset>
            <legend>Gender</legend>
        <p>
            Male <input type="radio" name="Gender" id="Male" required>
            Female <input type="radio" name="Gender" id="Female" required>
        </p>
        </fieldset>
        <p>address: <textarea name="address" id="address" cols="100" rows="8" required></textarea></p>
        <p>Email:  <input type="email" name="email" id="email" required></p>
        <p>pincode:  <input type="number" name="pincode" id="pincode" required></p>
        <h2>payment information</h2>
        <p>card type:
            <select name="card_type" id="card_type">
            <option value="">--select a card type--</option>
            <option value="Visa">visa</option>
            <option value="master card">master card</option>
            <option value="rupay">rupay</option>
            </select>
        </p>
        <p>
            card number  <input type="number" name="card_number" id="card_number" required>
        </p>
        <p>
            expiration date:  <input type="date" name="exp_date" id="exp_date" required>
        </p>    
        <p>CVV  <input type="password" name="CVV" id="CVV" required></p>
        <input type="submit" value="Pay Now">
    </form>
</body>
</html>
