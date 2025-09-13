# Login-Page
...
# Login-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login Page</title>
  
</head>
<body>
    <div class="login-container">
        <h2>Login</h2>
        <form action="/login" method="POST">
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required>

            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>

            <label>
                <input type="checkbox" name="remember"> Remember me
            </label>

            <button type="submit">Login</button>
        </form>
    </div>
</body>
</html>
