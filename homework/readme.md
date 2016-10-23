#WORK09
##sequence diagram

sequence diagram 1

code
```
people-> member:Register
member->Librarian:Borrow book
member<-Librarian:Checking member

member->Librarian:Return book
member<-Librarian:Checking period borrowed
```
<img src= "https://github.com/Siriphornyui/OOAD-WEEK10/blob/master/homework/s1.png">

sequence diagram 2

code
```
User->Login:member
User->Login:password
User<--Login:password fail 
User<--Login :a password again!

User->warehouse:access
product->warehouse:IDproduct
product->warehouse:Price
product->warehouse:QTY
product-->warehouse:Out of stock
 
User->warehouse:chcekingproduct

User->Seller:ordering product

Seller->User:Deliver
User->warehouse:stores
```
<img src= "https://github.com/Siriphornyui/OOAD-WEEK10/blob/master/homework/s2.png">

sequence diagram 3

code
```
Customer->Seller:buy product
Seller->Store:chceking product

Store-->Seller:Out of stock
Store-->Seller:have of stock

Seller->Customer:sell product
Product<-Customer:chceking product
Customer-->Seller:return product

Seller-->Customer:change product

```
<img src= "https://github.com/Siriphornyui/OOAD-WEEK10/blob/master/homework/s5.png">

sequence diagram 4

code
```
User->Login:email
User->Login:password
User<--Login:passwordoremail fail 
User<--Login :a password again!

User->Facebook:access
Facebook->Showpicture:System
Facebook->Showstatus:System
User->Facebook:updatepic
User->Facebook:updatestatus
```
<img src= "https://github.com/Siriphornyui/OOAD-WEEK10/blob/master/homework/s3.png">

sequence diagram 5

code
```
User->mobile:openApp
User->bankingmobile:Loginuser
User->bankingmobile:Loginpassword
mobile<--bankingmobile: fail 
User->bankingmobile: acess

User->bankingmobile:Checking money
bankingmobile->mobile:showmoney

bankingmobile->recipient:transfer money
bankingmobile->mobile:success
bankingmobile-->mobile:fail
```
<img scr= "https://github.com/Siriphornyui/OOAD-WEEK10/blob/master/homework/s4.png">



