# charan2327
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .main {
            background-color: #f5f5f5;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
            padding: 20px;
            width: 300px;
        }
        .main h2 {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-align: center;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            color: #555;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="password"],
        select {
            width: 100%;
            margin-bottom: 15px;
            padding: 10px;
            box-sizing: border-box;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button[type="submit"] {
            padding: 10px;
            border-radius: 10px;
            border: none;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="main">
        <h2>Registration Form</h2>
        <form action="">
            <label for="first">First Name:</label>
            <input type="text" id="first" name="first" required>

            <label for="last">Last Name:</label>
            <input type="text" id="last" name="last" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password"
                   pattern="^(?=.\d)(?=.[a-zA-Z])(?=.*\W).{8,}$"
                   title="Password must contain at least one number, one letter, one special character, and be at least 8 characters long"
                   required>

            <label for="repassword">Re-type Password:</label>
            <input type="password" id="repassword" name="repassword" required>

            <label for="mobile">Contact:</label>
            <input type="text" id="mobile" maxlength="10" required>

            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>

            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .main {
            background-color: #f5f5f5;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
            padding: 20px;
            width: 300px;
        }
        .main h2 {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-align: center;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            color: #555;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="password"],
        select {
            width: 100%;
            margin-bottom: 15px;
            padding: 10px;
            box-sizing: border-box;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button[type="submit"] {
            padding: 10px;
            border-radius: 10px;
            border: none;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="main">
        <h2>Registration Form</h2>
        <form action="">
            <label for="first">First Name:</label>
            <input type="text" id="first" name="first" required>

            <label for="last">Last Name:</label>
            <input type="text" id="last" name="last" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password"
                   pattern="^(?=.\d)(?=.[a-zA-Z])(?=.*\W).{8,}$"
                   title="Password must contain at least one number, one letter, one special character, and be at least 8 characters long"
                   required>

            <label for="repassword">Re-type Password:</label>
            <input type="password" id="repassword" name="repassword" required>

            <label for="mobile">Contact:</label>
            <input type="text" id="mobile" maxlength="10" required>

            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>

            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
