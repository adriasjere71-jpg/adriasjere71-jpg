
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sign in to GitHub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f6f8fa;
      color: #1f2328;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
    }

    .login-box {
      background: white;
      border: 1px solid #d1d9e0;
      border-radius: 8px;
      padding: 28px;
      width: 300px;
    }

    h1 {
      text-align: center;
      font-size: 24px;
      font-weight: normal;
    }

    label {
      display: block;
      margin: 16px 0 8px;
    }

    input {
      box-sizing: border-box;
      width: 100%;
      padding: 10px;
      border: 1px solid #d1d9e0;
      border-radius: 6px;
    }

    button {
      width: 100%;
      margin-top: 20px;
      padding: 11px;
      background: #1f883d;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    .note {
      text-align: center;
      font-size: 12px;
      color: #59636e;
      margin-top: 18px;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <h1>Sign in to GitHub</h1>

    <form id="loginForm">
      <label for="username">Username or email address</label>
      <input id="username" type="text"
             placeholder="Enter username" required>

      <label for="password">Password</label>
      <input id="password" type="password"
             placeholder="Enter password" required>

      <button type="submit">Sign in</button>
      <p id="message" class="note"></p>
    </form>

    <p class="note">
      New to GitHub?
      <a href="https://github.com/signup">Create an account</a>
    </p>
  </div>

  <script>
    document.getElementById("loginForm")
      .addEventListener("submit", function(event) {
        event.preventDefault();
        document.getElementById("message").textContent =
          "Demo page only. Visit github.com to sign in securely.";
      });
  </script>
</body>
</html>
