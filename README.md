<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PowerFlash Technology - Feedback</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>PowerFlash Technology</h1>
        <p>We value your feedback. Please fill out the form below.</p>

        <form id="feedbackForm">
            <label for="name">Your Name:</label>
            <input type="text" id="name" placeholder="Enter your name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" placeholder="Enter your email" required>

            <label for="message">Your Feedback:</label>
            <textarea id="message" placeholder="Write your feedback here..." required></textarea>

            <button type="submit">Send Feedback</button>
        </form>

        <div id="contactInfo">
            <h3>Contact Us:</h3>
            <p>📞 Phone: <a href="tel:+94774403831">0774403831</a></p>
            <p>📧 Email: <a href="mailto:technologypowerflash@gmail.com">technologypowerflash@gmail.com</a></p>
            <p>📍 Address: PowerFlash, Adurathwila, Poddala, Galle, Sri Lanka.</p>
        </div>

        <div id="successMessage" class="hidden">
            ✅ Thank you for your feedback! We'll get back to you soon.
        </div>
    </div>

    <script src="script.js"></script>

</body>
</html>
