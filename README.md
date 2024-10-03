
# RecipeApp

RecipeApp is a mobile application designed to help users find and manage recipes. It allows users to search for recipes based on ingredients, save their favorite recipes, and view detailed cooking instructions.

## Features

- **Search Recipes**: Search for recipes using ingredients, keywords, or dietary preferences.
- **Save Favorites**: Users can save their favorite recipes for easy access later.
- **Recipe Details**: Each recipe includes a list of ingredients, cooking instructions, and nutritional information (if available).
- **User-Friendly UI**: Clean and intuitive user interface with easy navigation.

## Getting Started

### Prerequisites

- Android Studio
- Kotlin/Java programming knowledge
- Gradle

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/username/RecipeApp.git
   ```

2. Open the project in Android Studio.
3. Build the project using Gradle by running the following command:

   ```bash
   ./gradlew build
   ```

4. Run the app on an Android emulator or connected device.

### Project Structure

- **app**: Contains the main application code, including activities, fragments, and data handling.
- **gradle**: Configuration files for Gradle.
- **settings.gradle.kts**: Settings for project dependencies.
- **build.gradle.kts**: Build configuration file for the project.

### Technologies Used

- **Kotlin**: Primary language for Android development.
- **Retrofit**: For making API calls to fetch recipes.
- **Room**: To save favorite recipes locally.
- **MVVM Architecture**: For a clean separation of concerns.
- **Jetpack Compose**: For UI development.

## How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
