# Features ```lakhi-nakhjo```

## Timeline
Please follow [this link](https://docs.google.com/spreadsheets/d/1Qd_cBgxiLG6i_SvIzYWsGMkq9Y9_UmCxL4SOiVV-wFQ/edit?usp=sharing) to get to the timeline of this project, I'll keep the things updated as we add new feature.

## User
 - Register, this thing should only be using OTP from mobile/email. or OAuth from Google or Apple.
 - They should have an option to add mobile and email.
 - Login with multiple thing, mobile/email/OAuth

## User Roles
 - We will have two roles for the user of the app. 
   - Customer
   - Seller

### Customer
 - They will only see the entries made by the seller, they shell not be able to edit any entries which is not created
by them.
 - They should also be able to pay using the API application that they have installed on their phone.
 - They will also be able to see all the sellers whom they have to pay the money.

### Seller
 - They will be able to add the entries.
 - See the list of all the customers in his and how much money is pending for a given customer.
 - They should also be able to set a limit in general this will apply to all of the customers by default, and there
should also be an option to set a customer wise limit, this limit can be grater or less then seller's default limit.
 - All the sellers will by-default be a customers as well.

## Entries
 - These are book entries and will only be created by the seller, and the customer will accept the entries after
verifying all the things.
 - We will have a box for the seller to list out all the things as they need them. And this description will
be visible to the customer. This box will have tags containing the name of the item, the quantity, and a little x for
removing the item. Here is the little text representation: ```(Wafers 5 | X)```.
 - Once the entry is created the customer have to accept the entry inorder to be included in the final calculation.
 - When ever the any of the user is on a list page of the entries they should see the pending entries on the top.
