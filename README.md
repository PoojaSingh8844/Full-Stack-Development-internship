# Full-Stack-Development-internship
<html>

<head> </head>

<body>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cancer Awareness & Support</title>


    <style>
    </style>

    <header>
        <h1>Cancer Awareness & Support</h1>
    </header>

    <section>
        <h2>About Us</h2>
        <p>We are committed to spreading awareness, offering support, and inspiring hope for those affected by cancer. Together, we can make a difference.</p>
    </section>

    <section class="contact-form">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <section class="quotes">
        <h2>Daily Inspiration</h2>
        <p id="quote">Loading quote...</p>
    </section>




</body>

</html>

css

body {
    margin: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: #f9f9f9;
    color: #333;
}

header {
    background: url('https://source.unsplash.com/1600x600/?health,hope') no-repeat center center/cover;
    height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}

header h1 {
    font-size: 3rem;
    text-align: center;
}

section {
    padding: 2rem;
    max-width: 900px;
    margin: auto;
}

.contact-form {
    background: white;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 0.8rem;
    margin: 0.5rem 0;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.contact-form button {
    background: #e63946;
    color: white;
    border: none;
    padding: 1rem;
    width: 100%;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1rem;
}

.contact-form button:hover {
    background: #d62828;
}

.quotes {
    margin-top: 2rem;
    padding: 1.5rem;
    background: #fff3cd;
    border-left: 5px solid #ff9800;
    border-radius: 6px;
}

@media (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }
}
