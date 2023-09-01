 ## Responsive Login Form 1.3

This is a responsive login form built with HTML, CSS, and JavaScript. It includes validation for email and password inputs.

### Step 1: HTML

The HTML code creates the basic structure of the login form. It includes a header, a form, and two input fields for email and password.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Email and Password Validation</title>
    <link rel="stylesheet" href="css/style.css" />
    <link
      href="https://unpkg.com/boxicons@2.1.2/css/boxicons.min.css"
      rel="stylesheet"
    />
  </head>
  <body>
    <div class="container">
      <header>Signup</header>
      <form action="https://www.codinglabweb.com/">
        <div class="field email-field">
          <div class="input-field">
            <input type="email" placeholder="Enter your email" class="email" />
          </div>
          <span class="error email-error">
            <i class="bx bx-error-circle error-icon"></i>
            <p class="error-text">Please enter a valid email</p>
          </span>
        </div>
        <div class="field create-password">
          <div class="input-field">
            <input
              type="password"
              placeholder="Create password"
              class="password"
            />
            <i class="bx bx-hide show-hide"></i>
          </div>
          <span class="error password-error">
            <i class="bx bx-error-circle error-icon"></i>
            <p class="error-text">
              Please enter atleast 8 charatcer with number, symbol, small and
              capital letter.
            </p>
          </span>
        </div>
        <div class="
