

![password2](https://github.com/user-attachments/assets/12ddd903-d35e-4a66-9650-bc523bb167d2)
![password1](https://github.com/user-attachments/assets/119cd6e8-6295-462c-a603-0f196525ec79)

# Libraries:

### React (react): 
The core library for building user interfaces in React Native.
### React Native (react-native): 
A framework for building mobile apps using JavaScript and React.
### Formik (formik): 
A library for managing form state and validation in React applications.
### Yup (yup):
A schema validation library used with Formik for defining validation rules.
### BouncyCheckbox (react-native-bouncy-checkbox): 
A library used to implement the bouncy checkbox component for including lowercase, uppercase, numbers, and symbols.


# Features:

### Password Generator: 
The core functionality of the app is to generate passwords based on user input.
### Form Validation: 
Formik and Yup are used to validate user input for the password length, ensuring it meets the specified criteria.
### User Input: 
The app allows users to:
-> Enter the desired password length using a text input.
-> Select options for including lowercase, uppercase, numbers, and symbols using checkbox-like components.
### Password Generation: 
Based on user input and selected options, a random password is generated and displayed.
### Reset Functionality:
A "Reset" button allows users to clear all selections and start over.
### Password Display: 
The generated password is displayed in a card with a "Long Press to copy" message.
### Styling: 
Styles are defined using StyleSheet.create and applied to various UI elements for a visually appealing interface.


# Additional Notes:

The code utilizes ScrollView to handle potential overflow of content if the user selects a very long password length.

The SafeAreaView ensures the app's content stays within safe areas on devices with notches or rounded corners.

The TouchableOpacity component enables users to interact with buttons for generating and resetting the password.

This React Native app demonstrates functionalities for user input, form validation, password generation, UI component usage, and basic styling.



