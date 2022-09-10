# CreditCardValidator
The C++ programming language is used to create a Credit Card Validator application that verifies the validity of a user's credit card number. It uses the Luhn algorithm to determine whether a credit card number is legitimate or not. Luhn's method is a straightforward checksum formula that can be used to verify a variety of identifications, including credit card numbers, IMEI numbers, and more, although it is most commonly used to verify credit card numbers.

### Overview
After entering the credit card number, the system verifies its validity and determines whether it is a Visa, MasterCard, American Express or another form of card. It verifies the authenticity of the card and the type of credit card by performing some basic operations and validations. Credit card numbers entered by the user are generated along with a message indicating whether the card is valid or invalid. If the credit card number entered is valid, the credit card type will also be printed.
- There are patterns in credit card numbers.
- Credit card number must contain 13 to 16 digits. It must start with:
    for Visa cards four
    for Master cards five
    37 for cards from American Express
    6 for cards from Discover
Luhn's algorithm can be used to solve the problem.

### Luhn Algorithm
Luhn's method, commonly referred to as the modulus 10 or mod 10 algorithm, is a straightforward checksum technique used to verify a large number of identification numbers, including Canadian social security numbers, IMEI numbers, and credit card numbers. A team of mathematicians invented the LUHN formula in the late 1960s. Credit card companies then quickly adopted it. Anyone can use the algorithm because it is freely available in the public domain. This technique is a common way to distinguish between legitimate numbers and numbers that have been entered incorrectly or otherwise on most credit cards and many government identification numbers. It was created to defend against inadvertent errors rather than deliberate attacks.

