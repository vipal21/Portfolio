<!-- # Hello!
*Thanks for stopping by*. This repo serves as a kind of ever-changing portfolio of projects I'm currently excited about; please feel free to look around. -->
# Zeboc
A React-Native application for Telemedicine Solutions. This application's main features were video calling, live transcription, and chat. I used Amazon Chime for the video calling functionality, but it was developed in Swift, so I created RCTBridgeModule to communicate between them (React-Native and Swift). I used web-socket for the chat and live transcription. Because this was my first react native application, I interacted with a variety of components such as Text,ListView,Switch,TextView,TextFiled, and so on. Because many components in my application had the same design with minor differences, I created reusable components to reduce code duplication. In the application, I used redux for state management. At the same time, I used Axios for API calls.
I also included Stripe as a payment gateway. The application presented some design challenges. I needed to design a tag view with custom functionality, so I used a third-party library and modified it for my application.

I'm extremely pleased with how the project came out. I'm particularly proud of the app's  UI design, and easily-extended architecture.  

<p align="center">
<img src="images/zeboc/zeboc.png" width="1000" title="Zeboc">
</p>

# Alana
A Booking Platform for the Beauty Industry built in React-Native. As The app's design is very impressive, and it is still in development. This application's basic concept was to book appointments in various beauty businesses. User can follow their fashion designers and on their basics that they can see different types of products made by them. Furthermore, if the service like hair cut and beauty pallor is available, user can book the time slot and make reservation. The application is built on functional components, and I used react-hooks such as useState and useEffect to monitor data and perform operations. I added support for dark mode. Rather than creating two applications, one for the customer and one for the provider, I created a single application and managed the operations.

The most challenging aspect of the application was maintaining the payment status flow, which included payment success, payment failure, and returning the payable amount to the customer.

<p align="center">
<img src="images/alana/alana3.png" width="500" title="Alana">
<img src="images/alana/alana2.png" width="260" title="Alana">
</p>


# Battuta
This is a small application whose goal is to show the user nearby tourist attractions. The user can view the locations both in the list and on the map. The application allows the user to plan their trip and add and remove friends from that trip plan. 
So the main point of this application was that the client needed to reuse it for different countries. So I created a json file and placed the data in that json file on the server, and now we have different applications for different types of countries.The serach function allows the user to search for a location.

<p align="center">
<img src="images/battuta/battuta1.png" width="230"  title="Battuta">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/battuta/battuta.png" width="230" title="Battuta">
</p>


# DineNow

I created the application in Swift. The application was far too large and complex for our eight-person teams. For application development, we used MVC architecture and singletons. My main responsibility was to create various types of fill-in forms, add validation, and handle the API call response. I also created some animation in the app and designed the QR code scanner. We used stackviews in UI for this complex design.

I'm very happy with how the project turned out. I'm especially pleased with the app's animation, UI design, and extensible architecture. Sakura was built with Xcode and written entirely in Swift 5; it uses Auto Layout for UI design and makes extensive use of both UIView animations and CAEmitterLayers.

<p align="center">
<img src="images/DineNow/d1.png" width="240"  title="Word Guess">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/DineNow/d2.png" width="240" title="Word Guess">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/DineNow/d3.png" width="240" title="DineNow">
</p>

Dinenow offers:

Discover your favorite restaurants or try something new
- Filter by cuisine, price, type of food or even "Instagram friendly" restaurants in your area or in your favorite city
- Browse meaningful restaurant photos and see customer reviews and photos
- Browse dishes and drinks
- Customize your dishes

All order methods
- Delivery
- To pick up
- On site at the restaurant
- Pre-Orders & Reservations
- Track the status of your order and stay up to date

Order and pay on site at the restaurant
- Simply order and pay via the app in the restaurant
- Avoid long waiting times or queues and desperate waiter calls
- Avoid language barriers or misunderstandings
- Pay for your food whenever you want without the hassle of waiting

Pre-order food and reservations
- Order your food conveniently "just-in-time" in the restaurant
- Your meal will be served as soon as you enter the restaurant
- Reserve a table and then order and pay on the spot

Share group orders & invoice
- Make a group order together with your loved ones
- You decide who pays and how high the order limit per person should be
- Simply split your bill with your loved ones according to the number of people or dishes selected

your profile
- Store your preferred payment methods and delivery addresses for your next orders in your profile
- Personalize your profile by selecting intolerances and preferences
- Create a business profile for your business lunches
- Simply order past orders again


