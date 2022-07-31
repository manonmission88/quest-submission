# quest-submission
## Chapter One - Day 1 

### **Blockchain**

Blockchain is a record-keeping technology designed to make it impossible to hack the system or forge the data stored on it, thereby making it secure and immutable.

### **Smart Contract**

Smart contracts are computer programs or protocols for automated transactions that are stored on a blockchain and run in response to meeting certain conditions. 

### **Explain the difference between a script and a transaction**

Scripts means reading or viewing the data stored in the BlockChain. Scripts would not cost any money. Scripts do not modify the state of the BlockChain.

Transactions are the process of making changes in data on the BlockChain. A transaction would cost you money. Transaction modifies the state of the BlockChain.

## Chapter One - Day 2 

### What are the 5 Cadence Programming Language Pillars?

a) **Safety and Security**: Cadence is a secured programming language as it maintains the highest levels of safety and security. 
b)**Clarity**: The code written in Cadence is easy to read. The developers won’t have to struggle to understand the story the code conveys.
c)**Approachability**: Cadence is similar to other programming languages, so it is easy for learners to familiarize themselves with Cadence if they already know other Programming languages. 
d)**Developer Experience**: Because the code is clear and approachable, it is easy to understand the errors, debug and understand what the code in overall does.
e)**Resource Oriented Programming**: It is the most important feature of Cadence. I am assuming It is just like the concept of Object Oriented Programming used in other programming languages where objects and classes are the building blocks for the program. 

### In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful

These are the fundamental features of the Cadence programming language and the basic things better to know even before you write your smart contracts. I think this will help the developers regarding what to expect while they are writing their smart contracts, and the thing they will code in the near future will have those attributes. As every developer in the FLOW ecosystem will be aware of these pillars, there will be more uniformity in the code within the same application.

## Chapter Two - Day 1
<img width="1429" alt="day1-quest1 " src="https://user-images.githubusercontent.com/98479005/181842994-ef7b2591-df4e-4435-ab57-56654e8c630c.png">
<img width="1440" alt="day1-quest2" src="https://user-images.githubusercontent.com/98479005/181843059-89b21eb3-0539-4143-999d-d0a489e3edf7.png">

## Chapter Two - Day 2 

### Explain why we wouldn't call changeGreeting in a script.

Calling changeGreeting makes the modification on the chain of the data in the BlockChain. Because it’s making changes in the BlockChain, it has to be done in the transactions not in the scripts as the scripts are just meant for viewing the data. 

### What does the AuthAccount mean in the prepare phase of the transaction?
The AuthAccount in the prepare phase of the transaction means that we are making the account information from the user available for use in the transaction (after the user approves it).

### What is the difference between the prepare phase and the execute phase in the transaction?
The prepare phase is used to access data in the authorizers account, while the execute phase is used to call functions that change/modify the data in the account.

### 4 
<img width="1429" alt="q1" src="https://user-images.githubusercontent.com/98479005/181846366-496735c3-5138-46a2-9304-1d418eced7ae.png">
<img width="1420" alt="q2" src="https://user-images.githubusercontent.com/98479005/181846584-e42608d9-66ba-4e1b-a2e9-fe348639444b.png">
<img width="1402" alt="day 2-quest 3 " src="https://user-images.githubusercontent.com/98479005/181846606-d699796c-4758-47d7-b138-f11b403e209c.png">

## Chapter Two - Day 3 

### 1.In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.
<img width="1440" alt="Screen Shot 2022-07-31 at 4 27 27 PM" src="https://user-images.githubusercontent.com/98479005/182044206-2398cc4d-f508-4e24-a5f3-345ceb5265e9.png">

### 2. In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!


<img width="1434" alt="Screen Shot 2022-07-31 at 4 31 25 PM" src="https://user-images.githubusercontent.com/98479005/182044214-1adefbb6-60a2-4c26-a588-54e69a6fc852.png">

###  3.Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type)


Before knowing the force-unwrap operator we need to know about the Optionals. Optional types are denoted by the ? sign followed by the type. It means the type is either the type it is saying or the nil. 
For an example, 
var myname: String = “A_B”
Here myname always has to be a string.
 
If we have ? sign, it can also be of type nil. That is it does not necessarily have to be of the type String and we won’t get any compilation error even if it is nil.
 
So, Now comes the force-unwrap operator. This Operator (!) unwraps and optional type. 
Typically the force-unwrap operator unwraps an optional string type. If the type of the value of the dictionary element does not match the return type declared in the function we use force-unwrap operator. 
 
For example, if we have a dictionary. 
The return value type of the dictionary is optional. So, if we have to return that value from our function we need to make sure the return type of the function matches the value type returned by the dictionary. So, in our case we might use the force-unwrap operator to (!) change the value type to match the return type of the function
 
Pub fun main(): String {
Let example: {Int: String} = {10: “Mom”, 20: “Dad”, 30: “Brother}
Return example[10]!   //The value “Mom” is no longer an optional type. It now becomes the type string and we won’t have any errors in compilation.
}
 
#### 4.
The error message means that the function should have the return type of String but it is returning the Optional type String?
 
We are getting the error because of a mismatch in the declared return type of the function and the returned type that is actually being returned. 
 
We can fix it using the force-unwrap operator.
 
## Chapter Two - Day 4 

### 1, 2 , 3 

<img width="1438" alt="Screen Shot 2022-07-31 at 5 22 10 PM" src="https://user-images.githubusercontent.com/98479005/182045876-b8df9426-d390-4b52-9845-d99575299c36.png">

### 4 , 5

<img width="1421" alt="Screen Shot 2022-07-31 at 5 50 25 PM" src="https://user-images.githubusercontent.com/98479005/182046856-4b54dec1-67d4-4e88-9726-f3a8ca39902d.png">
<img width="1414" alt="Screen Shot 2022-07-31 at 5 50 44 PM" src="https://user-images.githubusercontent.com/98479005/182046860-43651cb2-74c0-4639-b0d0-21cb93a76216.png">









