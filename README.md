<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Collab - Login</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f7f7f7;
        }
        .container {
            width: 300px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        h1 {
            color: #333;
        }
        button, input[type="text"], input[type="email"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            background-color: #ff4081;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff1e63;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Welcome to Artist Collab!</h1>
        <button>Sign up with Email</button>
        <button>Login with Google</button>
        <button>Login with Facebook</button>

        <form id="signup-form">
            <h2>Sign Up</h2>
            <input type="text" name="name" placeholder="Name" required>
            <input type="number" name="age" placeholder="Age" required>
            <input type="email" name="email" placeholder="Email" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Sign Up</button>
        </form>

        <form id="login-form">
            <h2>Login</h2>
            <input type="email" name="email" placeholder="Email" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Collab - Profile Setup</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #fafafa;
        }
        .container {
            width: 400px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        input[type="text"], input[type="number"], button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            background-color: #ff4081;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff1e63;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Set Up Your Profile</h2>
        <form id="profile-form">
            <input type="text" name="name" placeholder="Name" value="Pre-filled Name" readonly>
            <input type="number" name="age" placeholder="Age" value="Pre-filled Age" readonly>
            <input type="number" name="experience" placeholder="Years of Experience">
            <input type="text" name="skills" placeholder="Primary Skills (e.g., Painter, Musician)">
            <label>Upload your best creative work as your display picture:</label>
            <input type="file" name="profile_picture">
            <button type="submit">Complete Profile</button>
        </form>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Collab - Swipe Interface</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .profile-card {
            width: 300px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            position: relative;
        }
        .profile-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            margin: 10px;
            cursor: pointer;
            background-color: #ff4081;
            color: white;
        }
        button:hover {
            background-color: #ff1e63;
        }
    </style>
</head>
<body>

    <h2>Swipe to Connect</h2>
    <div class="profile-card">
        <img src="profile-pic.jpg" alt="Artist Profile Picture">
        <h3>John Doe</h3>
        <p>Age: 30</p>
        <p>Experience: 5 years</p>
        <p>Skills: Painter, Sculptor</p>
        <button id="left-swipe">Not Interested</button>
        <button id="right-swipe">Interested</button>
    </div>

    <script>
        document.getElementById('left-swipe').onclick = function() {
            alert('You swiped left!');
        };

        document.getElementById('right-swipe').onclick = function() {
            alert('You swiped right!');
        };
    </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Collab - Match</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #fafafa;
            text-align: center;
        }
        .container {
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        button {
            padding: 10px 20px;
            background-color: #ff4081;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff1e63;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>It's a Match!</h2>
        <p>You both swiped right! Ready to connect and collaborate?</p>
        <button>Pay ₹99 to Start Conversation</button>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Collab - Payment</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f5f5f5;
        }
        .container {
            width: 400px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        button {
            padding: 10px 20px;
            background-color: #ff4081;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff1e63;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Complete Payment</h2>
        <p>Pay ₹99 to connect with <strong>[Artist Name]</strong>.</p>
        <button id="rzp-button1">Pay Now</button>
    </div>

    <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
    <script>
        var options = {
            "key": "YOUR_RAZORPAY_KEY_ID",
            "amount": "9900",
            "currency": "INR",
            "name": "Artist Collab",
            "description": "Payment for Artist Collaboration",
            "image": "https://your-logo-url.com/logo.png",
            "handler": function (response) {
                alert("Payment Successful! Payment ID: " + response.razorpay_payment_id);
            },
            "prefill": {
                "name": "Your Name",
                "email": "your-email@example.com",
                "contact": "9999999999"
            },
            "theme": {
                "color": "#ff4081"
            }
        };

        document.getElementById('rzp-button1').onclick = function(e) {
            var rzp1 = new Razorpay(options);
            rzp1.open();
            e.preventDefault();
        };
    </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Collab - Chat</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            height: 100vh;
            margin: 0;
        }
        .chat-header {
            background-color: #ff4081;
            color: white;
            padding: 10px;
            text-align: center;
        }
        .chat-container {
            flex: 1;
            padding: 20px;
            background-color: #f5f5f5;
            overflow-y: auto;
        }
        .message {
            margin: 10px 0;
            padding: 10px;
            border-radius: 8px;
            max-width: 60%;
        }
        .message.sent {
            background-color: #e0ffe0;
            align-self: flex-end;
        }
        .message.received {
            background-color: #ffe0e0;
            align-self: flex-start;
        }
        .chat-input {
            display: flex;
            padding: 10px;
            background-color: white;
            border-top: 1px solid #ddd;
        }
        input[type="text"] {
            flex: 1;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            padding: 10px;
            background-color: #ff4081;
            color: white;
            border: none;
            border-radius: 5px;
            margin-left: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <div class="chat-header">
        <h2>Chat with [Artist Name]</h2>
    </div>

    <div class="chat-container" id="chat-box">
        <!-- Example Messages -->
        <div class="message received">Hey, let's collaborate on something!</div>
        <div class="message sent">Sure! What kind of project are you thinking about?</div>
    </div>

    <div class="chat-input">
        <input type="text" id="chat-message" placeholder="Type a message...">
        <button id="send-btn">Send</button>
    </div>

    <script>
        document.getElementById('send-btn').onclick = function() {
            var messageText = document.getElementById('chat-message').value;
            if (messageText) {
                var chatBox = document.getElementById('chat-box');
                
                var messageDiv = document.createElement('div');
                messageDiv.classList.add('message', 'sent');
                messageDiv.innerText = messageText;

                chatBox.appendChild(messageDiv);
                chatBox.scrollTop = chatBox.scrollHeight;

                document.getElementById('chat-message').value = '';
            }
        };
    </script>

</body>
</html>
