# Telephone Number Validator in JavaScript

## Introduction

This JavaScript code is a Telephone Number Validator. It checks whether a given string represents a valid US phone number. The validation includes various formats commonly used for US phone numbers, such as `555-555-5555`, `(555)555-5555`, and `1 555 555 5555`. The purpose of this code is to provide a reliable method for validating user input in the context of US phone numbers.

## How it Works

The `telephoneCheck` function in the code performs the following steps:

1. **Regular Expression:**

   - The function uses a regular expression (`phoneRegex`) to define the pattern for a valid US phone number. This pattern allows for flexibility in formatting while ensuring the presence of the area code and, if provided, a country code of 1.

2. **Validation:**
   - The input string is tested against the regular expression using the `test` method. If the string matches the pattern, the function returns `true`, indicating a valid US phone number; otherwise, it returns `false`.

## Test Cases

The code includes a comprehensive set of test cases to validate its functionality. These test cases cover a range of scenarios, including different formats of valid US phone numbers and cases where the input should be considered invalid.

### Sample Test Cases

- `telephoneCheck("555-555-5555")` should return `true`.
- `telephoneCheck("1 555-555-5555")` should return `true`.
- `telephoneCheck("(555)555-5555")` should return `true`.
- `telephoneCheck("11 555-555-5555")` should return `false`.

## How to Use

1. Clone this repository to your local machine.
2. Open the JavaScript file (`telephoneValidator.js`) in your preferred code editor.
3. Modify the test cases or add your own if needed.
4. Run the script to see the results of the phone number validations.
