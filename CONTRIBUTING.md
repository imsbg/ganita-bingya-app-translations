# Contributing to Ganita Bingya Translations

Thank you for your interest in contributing to the Ganita Bingya app! Your help in translating the app makes it accessible to a wider audience.

## How to Contribute

Follow these steps to add a new language or improve an existing one.

### Step 1: Fork the Repository

Click the "Fork" button at the top-right corner of this page to create your own copy of this repository.

### Step 2: Add or Update Translations using the GitHub UI

#### Adding a New Language

1.  In your forked repository, click **Add file** -> **Create new file**.
2.  In the file name box, type the path for the new language, e.g., `values-hi/strings.xml` for Hindi.
3.  Navigate to the base `values-or/strings.xml` file in another tab, copy its content, and paste it into your new file.
4.  Translate all the strings from Odia to the target language. Do not change the `name` attribute of the `<string>` tags.

    ```xml
    <!-- Before (Odia) -->
    <string name="welcome_message">ସ୍ଵାଗତ!</string>
    
    <!-- After (Example: Hindi Translation) -->
    <string name="welcome_message">स्वागत!</string>
    ```
5.  Commit the new file to your fork.

#### Updating an Existing Language

1.  In your forked repository, navigate to the language folder you wish to update (e.g., `values-en/`).
2.  Click on the `strings.xml` file.
3.  Click the pencil icon (✏️) to edit the file.
4.  Make your corrections or improvements and commit the changes.

### Step 3: Create a Pull Request

Go to the main page of your forked repository on GitHub. You will see a prompt to "Compare & pull request". Click it, review your changes, and submit the pull request. We will review your contribution and merge it.

Thank you for making Ganita Bingya better!
