<!-- NAME OF THE PROJECT -->
# SPLIT-A-BILL

 <!-- ABOUT THE PROJECT -->
   ## About The Project

This project helps people to divide restaurant bill between people including tips with a very easy way doing that.

No ink or paper needed.

Ypu also can mo

### How to use the App.

You need to open Split a Bill Website using *Copy Path* method. 

Ater you opened a website you will see input window where it says "Bill", it is where customer type in total amount from their receipt:

####
 **```
     <input type="text" id="bill" placeholder="Bill">
     ```**

   ##### **Note: file - index.html.**

   Then customer needs to type between how many people that bill will be splited. You do that in input window that says "How many people?":

  ####
  **```
       <input type="text" id="people" placeholder="How many people?">
       ```**

   ##### **Note: file - index.html.**

   On a the end you will have an option to add or not add the tip. And you also can add different tip percentage:

   ####
   **```
             <option disabled>Select an option</option>
          ```**

   **```
              <option value="0.30">Wow! 30%💗 </option>
              ```**

   **```
              <option value="0.20">Good service! 20% 💙</option>
               ```**

   **```
              <option value="0.10">It was OK! 10% 🙂</option>
              ```**

   **```
              <option value="0.00" selected>No tip!🙅‍♀️</option>
              ```**

   ##### **Note: file - index.html.**

   And after that you finally press button **Calculate** to see how much each person needs to pay. Under the button you will see 3 columns: 

   -Bill per person

   -Tip per person

   -Total per person

   ####
   **```
       document.querySelector("#dividedBill").textContent = amountPerPerson;
       ```**
       
   **```
       document.querySelector("#dividedTip").textContent = tipPerPerson;
        ```**

   **```
        document.querySelector("#billAndTip").textContent = totalSum;
        ```**
  
##### **Note: file - index.js.**

   ### Built With 

   ####
  [JavaScript]
   
   

