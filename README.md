# Shopping-By-KMP (Compose Multiplatform application)

Welcome to the documentation for the Jetpack Compose Multiplatform Shopping Application! 
This is a cross-platform application that is built using Jetpack Compose Multiplatform, a declarative framework for sharing UIs across multiple platforms with Kotlin. 
The application allows users to browse, search, and purchase products from a shopping catalog on Android, iOS.

![Wallpaper](screenshots/banner.png)
![Wallpaper](screenshots/banner2.png)



https://github.com/razaghimahdi/Shopping-By-KMP/assets/61207818/a4702cbf-1449-48b0-88f1-bcb9c42d273e






## Give a Star! ⭐
If you like or are using this project to learn or start your solution, please give it a star. Thanks!

## Features ✨
| Feature                     | Status           |
|-----------------------------|------------------|
| Login, Sign Up              | ✔️ Implemented   |
| Home                        | ✔️ Implemented   |
| Product Detail and Comments | ✔️ Implemented   |
| Wishlist                    | ✔️ Implemented   |
| Cart                        | ✔️ Implemented   |
| Profile                     | ✔️ Implemented   |
| Search                      | ✔️ Implemented   |
| Category                    | ✔️ Implemented   |
| Edit Profile                | ✔️ Implemented   |
| Manage Address              | ✔️ Implemented   |
| Payment Method              | ✔️ Implemented   |
| My Orders                   | ✔️ Implemented   |
| My Coupons                  | ✔️ Implemented   |
| Notifications               | ✔️ Implemented   |
| Setting                     | ✔️ Implemented   |

## Tech Stack 📚
- Kotlin Multiplatform 
- Kotlin Coroutines 
- Compose Multiplatform 
- Material3 
- Ktor 
- Datastore 
- Precompose 
- Koin
- Coil
- Kotest
- Fake Data
<!-- - Mockk -->
<!-- - Turbine -->

## Development 💻

Firs, let me say the backend is also in progress. You can find the backend source code [here](https://github.com/soheilkhaledabdi/shop).

We appreciate any feedback or suggestions that you may have to help us improve the project.

We plan to add more features, improve the code quality, and make the application more user-friendly. 

Our goal is to create a high-quality, multiplatform shopping application that demonstrates the power and flexibility of Jetpack Compose.

Please stay tuned for updates and feel free to contribute to the project by submitting pull requests or opening issues. 
Together, we can create a great shopping application that meets the needs of users across multiple platforms.

## Challenges Faced 👨‍💻
During the development of this project, 
i encountered several challenges that required creative solutions. 
Some of the key challenges we addressed include:

#### Changing Font
Implementing font changes across different platforms while maintaining consistency and performance posed a significant challenge. 
I explored various approaches to ensure seamless font rendering on both Android and iOS.

#### Image Selection and Capture
Facilitating image selection from the gallery and capturing images from the device's camera presented technical hurdles, 
especially in a multiplatform environment. I devised strategies to handle image acquisition efficiently across platforms.

#### Image Upload via Ktor
Integrating image upload functionality using Ktor required careful consideration of network communication and server-side handling. 
I optimized the process to ensure smooth and reliable image uploads.

#### User Session Management
Managing user sessions securely across platforms demanded robust authentication mechanisms and session handling. 
I implemented strategies to maintain session integrity while prioritizing user privacy and security.

#### UI/UX Design
Crafting an intuitive and visually appealing user interface (UI) across different devices and screen sizes posed a creative challenge. 
I iterated on design concepts to deliver a cohesive and delightful user experience (UX) for our audience.

#### Permission Management for Camera Access
Implementing a permission manager to request access to the device's camera was crucial for enabling image capture functionality. 
I navigated platform-specific permission models to ensure a seamless and secure user experience.

#### Modifying Color of Status Bar
Customizing the color of the status bar to match the application's theme across platforms presented design and implementation challenges. 
I explored platform-specific APIs and styling techniques to achieve consistent and aesthetically pleasing status bar coloration.

These challenges underscored the complexity of developing a cross-platform shopping application and pushed us to innovate and refine our solutions continually.


## Architecture 🏢
The Jetpack Compose Multiplatform Shopping Application is built using the Clean Architecture and the MVI (Model-View-Intent) pattern. 

## Testing 🧪
Testing is a crucial aspect of software development to ensure the reliability and functionality of the application. 
In the Shopping-By-KMP project, we utilize various testing frameworks and tools to maintain the quality of our codebase.

<!--
### Android 📱

When Android is one of your targets, 
you can get the same experience for Android as if you were developing an Android app using Jetpack Compose.

| Splash                                            | Sign In                                           | Sign Up                                           | Main(Home)                                        |
|---------------------------------------------------|---------------------------------------------------|---------------------------------------------------|---------------------------------------------------|
| <img src="screenshots/android1.png" width="300"/> | <img src="screenshots/android2.png" width="300"/> | <img src="screenshots/android3.png" width="300"/> | <img src="screenshots/android4.png" width="300"/> |
-->
<!--
### IOS 📱
> iOS support is in Alpha. It may change incompatibly and require manual migration in the future.

Compose Multiplatform shares most of its API with Jetpack Compose, the Android UI framework developed by Google. 
You can use the same APIs to build user interfaces for both Android and iOS.


| Splash                                        | Sign In                                       | Sign Up                                       | Main(Home)                                    |
|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| <img src="screenshots/ios1.png" width="300"/> | <img src="screenshots/ios2.png" width="300"/> | <img src="screenshots/ios3.png" width="300"/> | <img src="screenshots/ios4.png" width="300"/> |
-->

## Backend 🌐
[This project](https://github.com/soheilkhaledabdi/shop) involves building a robust admin panel for managing an e-commerce platform. 
It utilizes **Laravel** for the backend structure and **Livewire** for dynamic frontend interactions. 
The panel comes with a comprehensive **API**, ensuring scalability and flexibility.

### Features
- **Admin Dashboard:** Manage products, categories, orders, and customers seamlessly.
- **Laravel & Livewire:** Leverage the power of Laravel's backend with Livewire for reactive UI.
- **Full API:** Enables external integrations and interactions with the shopping platform.

## Contributing
Contributions are welcome! If you have any feedback or suggestions, please don't hesitate to let us know. 
We appreciate your contributions and support. Also if you find a bug or would like to create a new feature, please submit a pull request.

## License
This library is licensed under the MIT License. See [LICENSE.txt](https://github.com/razaghimahdi/Shoping-By-KMP/blob/master/LICENSE)


### more ideas:
https://github.com/JetBrains/compose-multiplatform-ios-android-template

https://github.com/JetBrains/compose-multiplatform

Developed by Mahdi Razzaghi Ghaleh
