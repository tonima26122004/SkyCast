<h1>**SkyCast Weather App**</h1>

**Overview:**
SkyCast is a simple yet powerful weather application for Android devices that provides users with accurate weather forecasts. It utilizes the OpenWeatherMap API to fetch weather data and displays it in an intuitive and user-friendly interface following Material Design principles

<h3>App logo</h3>
<img src="https://github.com/tonima26122004/SkyCast/assets/113163028/9eff9086-464a-4367-af4f-55f92eaf7ce8" alt="app" width="240" height="240">
<h3>App View</h3>
<img src="https://github.com/tonima26122004/SkyCast/assets/113163028/9e90d049-6d53-4673-aee7-f217eddc1227" alt="app" width="360" height="640">




**Requirements:**
- JDK 8
- Material Components 1.5.0-alpha04
- Android SDK 31
- Supports API Level 24+ (Nougat)

**Dependencies:**
- Support Libraries: appcompat, constraintlayout, linearlayout
- Material Design: material textfield textinput TextInputEditText, material textfield textinput TextInputLayout
- Square Picasso: For image loading
- Volley: HTTP library for faster networking

**Installation:**
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your_username/SkyCast.git
   ```
2. Import the project into Android Studio.
3. Ensure that JDK 8 is configured in your project settings.
4. Add Material Components, Picasso, and Volley dependencies to your `build.gradle` file:
   ```gradle
   implementation 'com.google.android.material:material:1.5.0-alpha04'
   implementation 'com.squareup.picasso:picasso:2.8'
   implementation 'com.android.volley:volley:1.2.1'
   ```

**Usage:**
1. Obtain an API key from OpenWeatherMap by signing up at [OpenWeatherMap API](https://openweathermap.org/api).
2. Replace `'YOUR_API_KEY'` in the `Constants.java` file with your obtained API key:
   ```java
   public class Constants {
       public static final String API_KEY = "YOUR_API_KEY";
   }
   ```
3. Build and run the application on your Android device or emulator.

**Features:**
- **Current Weather:** View the current weather conditions including temperature, humidity, wind speed, etc.
- **Forecast:** Get a 5-day forecast to plan ahead.
- **Location-based Weather:** Automatically fetches weather data based on the user's current location.
- **Search:** Search for weather conditions in any location worldwide.

**Contributing:**
Contributions are welcome! If you'd like to contribute to SkyCast, please fork the repository, make your changes, and submit a pull request.

**License:**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

**Credits:**
SkyCast Weather App is developed by **Tonima Das** and is inspired by the wonderful work of the Android developer community.

**Contact:**
For any queries or feedback, please contact **tonimadas348@gmail.com**

**Acknowledgments:**
Special thanks to OpenWeatherMap for providing the weather data API and to the developers of Material Design, Picasso, and Volley for their excellent libraries.
