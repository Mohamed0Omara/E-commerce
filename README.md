# ShopKaro

Shopkaro is an e-commerce app that utilizes modern Android technologies, including Jetpack Compose, MVVM architecture, Retrofit, and Hilt. The app allows users to authenticate, view products, add them to the cart, and place orders using Firebase Authentication and Firebase Realtime Database. The products are fetched from the Fakestore API.

## Features
1. Authentication using Firebase Authentication with email and password.
2. Dependency injection with Hilt.
3. Fetches products using the Fakestore API.
4. Users can add products to the cart, which is stored in Firebase Realtime Database.
5. Users can place orders by adding shipping details and choosing a payment method.
6. Utilizes nested navigation and a bottom bar.
7. Fully created with Jetpack Compose.


## Screenshot

|                                                                                                                         |                                                                                                               |                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| ![login](https://github.com/user-attachments/assets/147360a5-b685-4c84-afbf-78f4e7eae6fc)                               | ![signup](https://github.com/user-attachments/assets/2545a0d9-3005-4356-9720-d4830b9152ed)                    | ![home](https://github.com/user-attachments/assets/77eb7c2b-c491-4d0d-8579-bf2e9c5e6bb1)                       |
| ![product detail](https://github.com/user-attachments/assets/043f2c34-16d2-49d4-9359-d390a2fdfa19)                      | ![cart](https://github.com/user-attachments/assets/00f77a08-8890-47bd-abb4-9b0f0d1a4676)                      | ![payment](https://github.com/user-attachments/assets/3ba88061-798b-4329-b4c8-dfa09dcb3336)                    |
| ![order placed](https://github.com/user-attachments/assets/e41361bb-3ea5-4323-8f29-877281e71877)                        | ![profiile](https://github.com/user-attachments/assets/98078322-540d-4cb3-bd32-96a02a81bd1f)                  | ![order detail](https://github.com/user-attachments/assets/8088a35b-0f8c-489e-9627-2e8b16f2c866)                |



## Package Structure

* [`data`](app/src/main/java/com/example/shopkaro/data): Responsible for producing data. Contains API, repository, and model classes.
* [`di`](app/src/main/java/com/example/shopkaro/di): Hilt modules.
* [`ui`](app/src/main/java/com/example/shopkaro/ui): UI layer of the app.
    * `nav`: Contains app navigation and destinations.
    * `screens`: Contains UI components.
    * `theme`: Material3 theme.
* [`utils`](app/src/main/java/com/example/shopkaro/utils): Utility classes used across the app.


## Build With

[Kotlin](https://kotlinlang.org/):
As the programming language.

[Jetpack Compose](https://developer.android.com/jetpack/compose) :
To build UI.

[Jetpack Navigation](https://developer.android.com/jetpack/compose/navigation) :
For navigation between screens.

[Retrofit](https://square.github.io/retrofit/):
Used for making network requests to fetch product data from the Fakestore API.

[Hilt](https://developer.android.com/training/dependency-injection/hilt-android) :
For injecting dependencies.

[Coil](https://coil-kt.github.io/coil/compose/) :
To load image asynchronously.
