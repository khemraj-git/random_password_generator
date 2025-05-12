# random_password_generator

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


### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/khemraj-git/random_password_generator.git](https://github.com/khemraj-git/random_password_generator.git)
    cd random_password_generator
    ```

2.  **Compilation:**

    * Navigate to the directory containing the `PasswordGenerator.java` file (likely the root of the repository) and compile it:
        ```bash
        javac PasswordGenerator.java
        ```


### Usage

1.  **Running the Application:**

    *  Navigate to the directory containing the compiled `.class` file and run the application:
        ```bash
        java PasswordGenerator
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
