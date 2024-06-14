# sait_mobile_ADR
sait group assignment group’s ADR 


Architecture Decision Record (ADR)
Title: Decision on Key Architectural Components for Retail Mobile App
Date: June 14, 2024

Context:

We are tasked with developing a mobile app for a retail company. The app will allow customers to browse and purchase products, view their order history, and track the status of their deliveries. It will also include a loyalty program feature, offline support, push notifications, integration with payment gateways, user behavior tracking, image optimization, and support for multiple languages.

Decision:

We have decided to implement the following key architectural components for the app:

App Type: Hybrid App

Hybrid app is suitable for mobile apps since it offers cross-platform compatibility with IOS and Android with effective cost, low maintenance, and utilizing frameworks like React Native, Flutter and Xamarin.
 It supports features such as offline browsing, datasyncing, push notification, various payment gateways, and new order update.
 
UI Framework:

Reactive native will be chosen for the application for its popularity when it comes to building a hybrid app with many external resources and a large community for developers to learn.
 Ensuring smooth users interaction with the application such as offline browsing and viewing order history, push notification, using the loyalty program features to earn and redeem points for future discount. 
 
Backend language: Node.js 

Node.js will be use as the backend language for the application since it provides great support for real-time data update and syncing great amounts of data smoothly when connects to the internet 
Good scalability that can handle increased load without requiring significant changes to the backend infrastructure 
High performance in I/O bound tasks to help process payment, tracking user behavior, push notification 

Permissions: Fine-grained access control

The access control allows or denies requests to use assets, such as data and resources.
The app helps comply with the privacy regulations.

Data storage: Oracle database or SQL Lite 

Oracle database provides advanced security to protect transactions. 
SQLite allows offline data access. 

Any additional frameworks or technology stacks: 
Paypal for multiple payment gateway features. The application is user friendly, cross platform, multiple currencies supported, etc 
