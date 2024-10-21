<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coding Academy</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Coding Academy</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#courses">Courses</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to Coding Academy</h2>
            <p>Learn to code and build amazing projects!</p>
            <button id="getStartedBtn"><a href="https://mail.google.com/mail/u/0/#inbox?compose=jrjtXVbTlWlLbvkVqVsdnVpHRdjqGPKdbCMJxfkKmSxpJdGRNznRSmXcbQdKklcRbjpxKbKh">Get Started</a></button>
        </section>

        <section id="courses">
            <h2>Courses Offered</h2>
            <ul>
                <li><strong>Python:</strong> Learn the basics of Python programming.</li>
                <li><strong>HTML & CSS:</strong> Build beautiful and responsive websites.</li>
                <li><strong>Java:</strong> Understand object-oriented programming.</li>
                <li><strong>JavaScript:</strong> Make your websites interactive.</li>
            </ul>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>We are passionate about teaching coding and helping you grow your skills.</p>
        </section>
    </main>
<section>
<h1>Contact us</h1>
    <p>

    Email: Daviesj1245@gmail.com
Any Questions ask us and if you want to purchase the courses just contact us and we will send you a course.
</p>
<br> 
<br>
<p>Thanks</p>



</section>
    <footer>
        <p>&copy; 2024 Coding Academy</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 1rem;
}

section {
    margin-bottom: 2rem;
    background: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 1rem;
    position: relative;
    bottom: 0;
    width: 100%;
}

button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin: 0.5rem 0 0.2rem;
}

form input {
    padding: 0.5rem;
    margin-bottom: 1rem;
}
</style>
<script>
    
document.getElementById('getStartedBtn').addEventListener('click', function() {
    alert('Get ready to dive into the world of coding!');
});

document.getElementById('contactForm').addEventListener('submit', function(event) {
    event.preventDefault();
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    document.getElementById('formMessage').innerText = `Thank you, ${name}! We'll reach out to you at ${email}.`;
    this.reset();
});
</script>
