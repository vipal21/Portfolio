<!-- # Hello!
*Thanks for stopping by*. This repo serves as a kind of ever-changing portfolio of projects I'm currently excited about; please feel free to look around. -->
# Zeboc
A React-Native application for Telemedicine Solutions. This application's main features were video calling, live transcription, and chat. I used Amazon Chime for the video calling functionality, but it was developed in Swift, so I created RCTBridgeModule to communicate between them (React-Native and Swift). I used web-socket for the chat and live transcription. Because this was my first react native application, I interacted with a variety of components such as Text,ListView,Switch,TextView,TextFiled, and so on. Because many components in my application had the same design with minor differences, I created reusable components to reduce code duplication. In the application, I used redux for state management. At the same time, I used Axios for API calls.
I also included Stripe as a payment gateway. The application presented some design challenges. I needed to design a tag view with custom functionality, so I used a third-party library and modified it for my application.

I'm extremely pleased with how the project came out. I'm particularly proud of the app's animation, UI design, and easily-extended architecture. Sakura was built with Xcode and written entirely in Swift 5; it utilizes Auto Layout for UI design, and makes extensive use of both UIView animations and CAEmitterLayers.  
<p align="center">
<img src="images/zeboc/zeboc.png" width="400"  title="Word Guess">
</p>
