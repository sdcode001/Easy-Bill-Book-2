## Easy Bill Book


### Problem Statement:
In our daily life, we see our local shops and university/college canteens maintain notebooks to write customers bills/dues but sometimes it's very difficult to find old bills and keep all the past records. In this system sometimes customers are also get confused about their dues and then it becomes very problematic for both customer and shop owner. Another problem is all shops don't have their own website where they can show all the products/food items available and price lists to their customers. So here we can solve all the problems mentioned above using a mobile application that is very user-friendly and effective.
    
### Proposed Solution :
This "Easy Bill Book" app can maintain all customer's bills/payments/dues in the database. user(the shop owner) can easily register all customers with their names and phone numbers and at the same time a notification SMS will be sent to that customer. after registering customer shop owner can update their bill/due records when a new payment is done and at the same time a notification SMS will be sent to that customer on his/her registered phone number from shop owners phone mentioning shop name and in this way, both customer and shop owner stay updated. if the shop owner wants to remove a customer form list,he/she can easily do it using delete button and the customer record gets deleted from the database. Records of all the customers will show on the home page in listed row format. There is an option where shop owner can set his/her shop name on the app and also this will be mentioned in all the SMS notifications.In addition, there is a bell button on home screen through which user can send a SMS notification of payment details and dues to all customers And finally comes to a very important feature that is there is a separate products list where user can store products details in a list and add new products and a notify button is given by which user can send SMS of product list and updates to all customers so that customers will get to know which product is available and which not. 

![Slide1](https://user-images.githubusercontent.com/92887905/147879333-b5dc36bc-b1ac-4a69-8825-05fe67002368.JPG)

### Functionality & Concepts used :
Following are few android concepts used to achieve the functionalities in app :
#### LinearLayout: All the activities uses LinearLayout to position buttons,textviews,edittexts and recyclerviews.
#### RecyclerView: To show customer records,name and phone number recyclerview is used in vertical mode.Recyclerview is also used to show product list.
#### Adapters: RecyclerView Adapters are used to make connection between databases and recyclerviews.
#### SmsManager: This api is used to send SMS from users phone to customers phone numbers.
#### Database: Here two SQlite databases is used. one to store customer records and another for product lists.
#### SharedPreferences: To store the shop name sharedpreferences is used here.A separate class is made for sharedpreferences and its methods.
#### AlertDialog: Alertdialogs are used to update customers records,to alert about deletion,to alert about sending SMS.

### Application Link & Future Scope :
I have uploaded this app on playstore 1 day ago(1/1/2022) and find some problem on publication on playstore.i will fix a reupload it so it will take some days to pubish.here is my playstore developer account link and it will available here: 
https://play.google.com/store/apps/developer?id=dEySoUvIk and release APK also available in this repository


Coming to the future plan: i want to make this app a server clint based app.shop owner will have server site app where he/she can set product menu and all product details and using clint site app customers can select and order the products from there phone and also this app will have google map through which customers can track their orders.
