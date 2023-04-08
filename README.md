Section 1: Algorithms (10 pt)

Part A) Create a function in javascript / typescript that takes in a big number and converts it into the equivalent english text. Ex. If input was 1234, output must be One thousand, Two hundred, Thirty Four. Solutions must be valid up to 6 digits. Write unit tests to show that your function works.

Part B) Implement a binary search function and write code to run unit tests on the function.
Section 2: Single-Page-Application (15 pt)
Build a SPA to get and convert cryptocurrency exchange rates. You can use any open real-time API on the internet to fetch the rates. The Application will consist of three

widgets. The first widget consists of:

1. A drop down menu for the user to select the crypto currency they wish to exchange from, also known as the base currency (Ex. Eth)

2. A text field for the user to input & read the numerical value of the crypto currency (ex. 2.45 Eth)
   The second widget will consist of:

3. A drop down menu for the user to select the crypto currency they wish to exchange to,
   also known as the quota currency (Ex. USDT)

4. A text field for the user to input and read the numerical value for the crypto currency
   The third widget will be a read only component to display the exchange rate of the base currency against the quota currency. Ex. 1 ETH = 1,718.53 USDT
   You are required to:

5. Build the SPA using React or React Native

6. Display the real-time exchange rates of the to and from currencies

7. Allow the user to input a value in the base currency text box

8. Allow users to input a value in the “to” text box

9. User input must be calculated in real-time, that is, the user does not need to click on

   “Enter’ to see the conversion rate.
   Look at this reference as a guide: https://app.uniswap.org/#/swap
   Note:
   You are not required to swap or exchange the user's tokens. Just display the conversion based on user input. You can limit the token to the top 10 popular tokens in the drop menu if you wish.
   Marks are awarded based on fulfilled requirements, application performance and structure of code.
   Bonus marks will be awarded for effort put into the UX/UI design:
   ● Display loader while values are being calculates (see reference)
   ● Neat interface and modern appearance
   ● Responsiveness of design
