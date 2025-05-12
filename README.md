# random_password_generator

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Java CI with Maven](https://github.com/khemraj-git/random_password_generator/actions/workflows/maven.yml/badge.svg)](https://github.com/khemraj-git/random_password_generator/actions/workflows/maven.yml)
[![GitHub Stars](https://img.shields.io/github/stars/khemraj-git/random_password_generator?style=social)](https://github.com/khemraj-git/random_password_generator/stargazers)

A simple yet effective command-line Java application to generate strong, random passwords based on your specified criteria. You can customize the length of the password and choose which character sets to include: uppercase letters, lowercase letters, digits, and special characters.

## Features

* **Customizable Length:** Specify the exact length of the password you need.
* **Character Set Selection:** Choose to include or exclude uppercase letters, lowercase letters, digits, and special characters.
* **Secure Randomness:** Utilizes Java's `SecureRandom` class for cryptographically strong random number generation, ensuring the generated passwords are unpredictable.
* **Command-Line Interface:** Easy to use directly from your terminal.
* **Clear Output:** Displays the generated password in the console.

## Getting Started

### Prerequisites

* **Java Development Kit (JDK):** Ensure you have Java installed on your system. You can download it from [Oracle's website](https://www.oracle.com/java/technologies/javase-downloads.html) or use an open-source distribution like [OpenJDK](https://openjdk.java.net/).
* **Maven (Optional):** If you want to build the project using Maven (as indicated by the CI badge), ensure it's installed. You can download it from [Apache Maven](https://maven.apache.org/download.cgi).

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/khemraj-git/random_password_generator.git](https://github.com/khemraj-git/random_password_generator.git)
    cd random_password_generator
    ```

2.  **Compilation:**

    * **Without Maven:** Navigate to the directory containing the `PasswordGenerator.java` file (likely the root of the repository) and compile it:
        ```bash
        javac PasswordGenerator.java
        ```

    * **With Maven:** If you have Maven installed, you can build the project using the following command from the root of the repository:
        ```bash
        mvn clean install
        ```
        This will create a JAR file in the `target` directory, likely named something like `random_password_generator-1.0-SNAPSHOT.jar`.

### Usage

1.  **Running the Application:**

    * **Without Maven:** Navigate to the directory containing the compiled `.class` file and run the application:
        ```bash
        java PasswordGenerator
        ```

    * **With Maven (after building):** Navigate to the `target` directory and run the generated JAR file. You might need to adjust the filename based on your Maven build:
        ```bash
        java -jar target/random_password_generator-1.0-SNAPSHOT.jar
        ```

2.  **Following the Prompts:** The application will then prompt you to enter the desired length of the password and whether to include uppercase letters, lowercase letters, digits, and special characters (by typing `y` for yes or `n` for no).

    ```
    Enter the length of the password: 16
    Include uppercase letters? (y/n): y
    Include lowercase letters? (y/n): y
    Include digits? (y/n): y
    Include special characters? (y/n): y
    Generated password: aB3!dFgH7jKlMnOp
    ```

## Contributing

Contributions are welcome! If you have any ideas for improvements, bug fixes, or new features, feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature`).
3.  Make your changes.
4.  Commit your changes (`git commit -am 'Add some feature'`).
5.  Push to the branch (`git push origin feature/your-feature`).
6.  Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE). See the `LICENSE` file for more details.

## Author

[khemraj-git](https://github.com/khemraj-git)

## Acknowledgements

* This project utilizes the `SecureRandom` class from the Java Security API for secure random number generation.

---

**Key changes made to align with your repository:**

* **Repository URLs:** The clone URL and the CI/Stars badge links now correctly point to `khemraj-git/random_password_generator`.
* **Author:** The author section now includes your GitHub username with a link to your profile.
* **Maven JAR Name:** The usage instructions for Maven now reflect the likely naming convention of your JAR file.

**To make this README perfect for your repository, ensure you:**

1.  **Create a `LICENSE` file** in the root of your repository if you haven't already. Choose the MIT license (or another license you prefer) and add its content to this file.
2.  **Replace `[khemraj-git]`** in the Author section with your actual name if you prefer that.
3.  **Commit and push this `README.md` file** to your `random_password_generator` repository on GitHub.

This updated README should provide clear and accurate information for anyone visiting your repository! Let me know if you have any other questions.
