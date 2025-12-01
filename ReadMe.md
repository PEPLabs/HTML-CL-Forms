# Create HTML Form Structure:

- Create three `<form>` elements with the IDs: `registrationForm`, `loginForm`, and `feedbackForm`.

---

# Name (Text Input):

- Use the `<label>` element with the text "Name:" and assign the `for` attribute the value "name".
- Use the `<input>` element with `type="text"`.
- Assign the ID `name` to this input field.
- Name the input field as `name` using the `name` attribute.
- Make this field required by adding the `required` attribute.

---

# Email (Email Input):

- Use the `<label>` element with the text "Email:" and assign the `for` attribute the value "email".
- Use the `<input>` element with `type="email"`.
- Assign the ID `email` to this input field.
- Name the input field as `email` using the `name` attribute.
- Make this field required by adding the `required` attribute.

---

# Password (Password Input):

- Use the `<label>` element with the text "Password:" and assign the `for` attribute the value "password".
- Use the `<input>` element with `type="password"`.
- Assign the ID `password` to this input field.
- Name the input field as `password` using the `name` attribute.
- Make this field required by adding the `required` attribute.

---

# Gender (Select Box):

- Use the `<label>` element with the text "Gender:" and assign the `for` attribute the value "gender".
- Use the `<select>` element to create a dropdown.
- Assign the ID `gender` to this select element.
- Name the select box as `gender` using the `name` attribute.
- Make this dropdown required by adding the `required` attribute.
- Inside the `<select>` element, include the following options:

    - `<option value="male">Male</option>`
    - `<option value="female">Female</option>`
    - `<option value="other">Other</option>`

---

# Birthdate (Date Input):

- Use the `<label>` element with the text "BirthDate:" and assign the `for` attribute the value "birthdate".
- Use the `<input>` element with `type="date"`.
- Assign the ID `birthdate` to this input field.
- Name the input field as `birthdate` using the `name` attribute.
- Make this field required by adding the `required` attribute.

---

# Accept Terms (Checkbox):

- Use the `<label>` element and assign the `for` attribute the value "terms".
- Use the `<input>` element with `type="checkbox"`.
- Assign the ID `terms` to this input field.
- Name the input field as `terms` using the `name` attribute.
- Set the value to `"yes"` using the `value` attribute.
- Add the statement **"I accept the terms and conditions"** inside the label.
- Make this field required by adding the `required` attribute.
- Close the label tag.

---

# Submit Button (Button Element Required):

- Use the `<button>` element with `type="submit"`.
- Each form must use the following exact button text:

    - Registration Form: **Register**
    - Login Form: **Login**
    - Feedback Form: **Submit Feedback**

- No ID or name attribute is necessary for the submit button unless you choose to add one.

---

# LoginEmail (Email Input):

- Use the `<label>` element with the text "LoginEmail:" and assign the `for` attribute the value "loginEmail".
- Link the label to an input field with:
    - `type="email"`
    - `id="loginEmail"`
    - `name="loginEmail"`
    - `required` attribute applied.

---

# LoginPassword (Password Input):

- Use the `<label>` element with the text "LoginPassword:" and assign the `for` attribute the value "loginPassword".
- Link the label to an input field with:
    - `type="password"`
    - `id="loginPassword"`
    - `name="loginPassword"`
    - `required` attribute applied.

---

# Comments (TextArea Field):

- Use the `<label>` element with the text "Comments:" and assign the `for` attribute the value "comments".
- Link the label to a `<textarea>` with:
    - `id="comments"`
    - `name="comments"`
    - `required` attribute applied.

---

# Rating (Rating Input):

- Use the `<label>` element with the text "Rating:" and assign the `for` attribute the value "rating".
- Link the label to an input field with:
    - `type="number"`
    - `id="rating"`
    - `name="rating"`
    - `min="1"`
    - `max="5"`
    - `required` attribute applied.
