Page 1: index.html (Home Page)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Official home page of the Invertis Tech & Coding Club. Explore our coding activities, workshops, and upcoming events.">
    <title>Home - Tech & Coding Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f9; color: #333; line-height: 1.6; }
        header { background-color: #1a252f; color: white; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 1.5rem; font-weight: bold; }
        nav a { color: white; text-decoration: none; margin-left: 20px; font-size: 1rem; }
        nav a:hover, nav a.active { text-decoration: underline; color: #3498db; }
        .container { max-width: 1000px; margin: 2rem auto; padding: 0 1rem; }
        main { background: white; padding: 2.5rem; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        h1, h2 { color: #1a252f; }
        h1 { margin-top: 0; border-bottom: 2px solid #1a252f; padding-bottom: 10px; }
        section { margin-bottom: 2rem; }
        table { width: 100%; border-collapse: collapse; margin-top: 1rem; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: left; }
        th { background-color: #1a252f; color: white; }
        tr:nth-child(even) { background-color: #f9f9f9; }
        footer { text-align: center; padding: 1.5rem; background-color: #1a252f; color: white; margin-top: 3rem; }
    </style>
</head>
<body>

    <header>
        <div class="logo">Tech & Coding Club</div>
        <nav>
            <a href="index.html" class="active">Home</a>
            <a href="about.html">About</a>
            <a href="registration.html">Registration</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <div class="container">
        <main>
            <section>
                <h1>Welcome to the Tech & Coding Club</h1>
                <p>Welcome to our student community! We foster technical innovation, peer-to-peer coding sessions, hackathons, and software development workshops for students passionate about technology.</p>
            </section>

            <section>
                <h2>Club Activities & Initiatives</h2>
                <ul>
                    <li><strong>Weekly Coding Meetups:</strong> Problem-solving and data structure discussions.</li>
                    <li><strong>Web Development Workshops:</strong> Hands-on HTML, CSS, and JavaScript sessions.</li>
                    <li><strong>Annual Hackathon:</strong> 24-hour innovation challenge building live projects.</li>
                </ul>
            </section>

            <section>
                <h2>Upcoming Events Schedule</h2>
                <table>
                    <thead>
                        <tr>
                            <th>Event Name</th>
                            <th>Date</th>
                            <th>Time</th>
                            <th>Location</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>HTML & CSS Bootcamp</td>
                            <td>November 10, 2026</td>
                            <td>4:00 PM - 6:00 PM</td>
                            <td>Computer Lab 3</td>
                        </tr>
                        <tr>
                            <td>Git & GitHub Version Control</td>
                            <td>November 18, 2026</td>
                            <td>3:30 PM - 5:30 PM</td>
                            <td>Auditorium Hall B</td>
                        </tr>
                        <tr>
                            <td>Annual Winter Hackathon</td>
                            <td>December 5, 2026</td>
                            <td>9:00 AM Onwards</td>
                            <td>Main Innovation Center</td>
                        </tr>
                    </tbody>
                </table>
            </section>
        </main>
    </div>

    <footer>
        <p>&copy; 2026 Tech & Coding Club. All rights reserved.</p>
    </footer>

</body>
</html>

Page 2: about.html (Club Introduction Page)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Learn about the Tech & Coding Club mission, vision, and core leadership members.">
    <title>About Us - Tech & Coding Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f9; color: #333; line-height: 1.6; }
        header { background-color: #1a252f; color: white; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 1.5rem; font-weight: bold; }
        nav a { color: white; text-decoration: none; margin-left: 20px; font-size: 1rem; }
        nav a:hover, nav a.active { text-decoration: underline; color: #3498db; }
        .container { max-width: 1000px; margin: 2rem auto; padding: 0 1rem; }
        main { background: white; padding: 2.5rem; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        h1, h2 { color: #1a252f; }
        h1 { margin-top: 0; border-bottom: 2px solid #1a252f; padding-bottom: 10px; }
        section { margin-bottom: 2rem; }
        .team-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; margin-top: 1rem; }
        .team-card { background: #fafafa; border: 1px solid #ddd; padding: 15px; border-radius: 6px; text-align: center; }
        footer { text-align: center; padding: 1.5rem; background-color: #1a252f; color: white; margin-top: 3rem; }
    </style>
</head>
<body>

    <header>
        <div class="logo">Tech & Coding Club</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html" class="active">About</a>
            <a href="registration.html">Registration</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <div class="container">
        <main>
            <section>
                <h1>About Our Club</h1>
                <p>Founded with the mission to bridge the gap between academic theory and practical software engineering, the Tech & Coding Club provides an inspiring ecosystem for students to collaborate, build projects, and enhance their coding competence.</p>
            </section>

            <section>
                <h2>Our Vision & Mission</h2>
                <p><strong>Vision:</strong> To cultivate a thriving community of tech innovators and problem solvers prepared for modern software industries.</p>
                <p><strong>Mission:</strong> Conduct regular peer workshops, facilitate open-source contributions, and mentor students through real-world project development cycles.</p>
            </section>

            <section>
                <h2>Club Leadership & Core Members</h2>
                <div class="team-grid">
                    <div class="team-card">
                        <h3>Shivam Sharma</h3>
                        <p><strong>President & Lead Developer</strong></p>
                        <p>Web architecture and Git version control mentor.</p>
                    </div>
                    <div class="team-card">
                        <h3>Dr. R. Sharma</h3>
                        <p><strong>Faculty Advisor</strong></p>
                        <p>Department of Computer Science & Engineering.</p>
                    </div>
                    <div class="team-card">
                        <h3>Aarav Patel</h3>
                        <p><strong>Event Coordinator</strong></p>
                        <p>Manages hackathons and technical bootcamp logistics.</p>
                    </div>
                </div>
            </section>
        </main>
    </div>

    <footer>
        <p>&copy; 2026 Tech & Coding Club. All rights reserved.</p>
    </footer>

</body>
</html>

Page 3: registration.html (Club Registration Form Page)


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Register online to join the Tech & Coding Club.">
    <title>Registration - Tech & Coding Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f9; color: #333; line-height: 1.6; }
        header { background-color: #1a252f; color: white; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 1.5rem; font-weight: bold; }
        nav a { color: white; text-decoration: none; margin-left: 20px; font-size: 1rem; }
        nav a:hover, nav a.active { text-decoration: underline; color: #3498db; }
        .container { max-width: 750px; margin: 2rem auto; padding: 0 1rem; }
        main { background: white; padding: 2.5rem; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        h1 { color: #1a252f; margin-top: 0; border-bottom: 2px solid #1a252f; padding-bottom: 10px; }
        .form-group { margin-bottom: 1.2rem; }
        label { display: block; font-weight: bold; margin-bottom: 5px; color: #1a252f; }
        input[type="text"], input[type="email"], input[type="tel"], select, textarea {
            width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box; font-size: 1rem;
        }
        textarea { resize: vertical; height: 100px; }
        .radio-group, .checkbox-group { display: flex; gap: 15px; margin-top: 5px; align-items: center; }
        button { background-color: #1a252f; color: white; border: none; padding: 12px 20px; font-size: 1rem; border-radius: 4px; cursor: pointer; width: 100%; margin-top: 1rem; }
        button:hover { background-color: #34495e; }
        footer { text-align: center; padding: 1.5rem; background-color: #1a252f; color: white; margin-top: 3rem; }
    </style>
</head>
<body>

    <header>
        <div class="logo">Tech & Coding Club</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="registration.html" class="active">Registration</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <div class="container">
        <main>
            <h1>Student Club Registration Form</h1>
            <p>Fill out the details below to officially join the Tech & Coding Club for the current academic session.</p>

            <form action="#" method="POST">
                <div class="form-group">
                    <label for="fullname">Full Name:</label>
                    <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required>
                </div>

                <div class="form-group">
                    <label for="email">Email Address:</label>
                    <input type="email" id="email" name="email" placeholder="your.email@university.edu" required>
                </div>

                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" placeholder="9876543210" required>
                </div>

                <div class="form-group">
                    <label for="department">Department / Course:</label>
                    <select id="department" name="department" required>
                        <option value="">-- Select Your Course --</option>
                        <option value="cse">Computer Science & Engineering</option>
                        <option value="it">Information Technology</option>
                        <option value="ece">Electronics & Communication</option>
                        <option value="other">Other Engineering / Science</option>
                    </select>
                </div>

                <div class="form-group">
                    <label>Year of Study:</label>
                    <div class="radio-group">
                        <label><input type="radio" name="year" value="1" required> 1st Year</label>
                        <label><input type="radio" name="year" value="2"> 2nd Year</label>
                        <label><input type="radio" name="year" value="3"> 3rd Year</label>
                        <label><input type="radio" name="year" value="4"> 4th Year</label>
                    </div>
                </div>

                <div class="form-group">
                    <label>Areas of Technical Interest:</label>
                    <div class="checkbox-group">
                        <label><input type="checkbox" name="interests" value="web"> Web Dev</label>
                        <label><input type="checkbox" name="interests" value="ai"> AI / ML</label>
                        <label><input type="checkbox" name="interests" value="dsa"> DSA & Coding</label>
                    </div>
                </div>

                <div class="form-group">
                    <label for="comments">Why do you want to join this club?</label>
                    <textarea id="comments" name="comments" placeholder="Tell us about your goals..."></textarea>
                </div>

                <button type="submit">Submit Registration</button>
            </form>
        </main>
    </div>

    <footer>
        <p>&copy; 2026 Tech & Coding Club. All rights reserved.</p>
    </footer>

</body>
</html>

Page 4: contact.html (Contact Details Page)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Contact the Tech & Coding Club team via email, phone, or visit us on campus.">
    <title>Contact Us - Tech & Coding Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f9; color: #333; line-height: 1.6; }
        header { background-color: #1a252f; color: white; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 1.5rem; font-weight: bold; }
        nav a { color: white; text-decoration: none; margin-left: 20px; font-size: 1rem; }
        nav a:hover, nav a.active { text-decoration: underline; color: #3498db; }
        .container { max-width: 850px; margin: 2rem auto; padding: 0 1rem; }
        main { background: white; padding: 2.5rem; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        h1, h2 { color: #1a252f; }
        h1 { margin-top: 0; border-bottom: 2px solid #1a252f; padding-bottom: 10px; }
        section { margin-bottom: 2rem; }
        ul { padding-left: 20px; }
        li { margin-bottom: 8px; }
        .contact-box { background: #fafafa; border-left: 4px solid #1a252f; padding: 15px; margin-top: 1rem; border-radius: 4px; }
        footer { text-align: center; padding: 1.5rem; background-color: #1a252f; color: white; margin-top: 3rem; }
    </style>
</head>
<body>

    <header>
        <div class="logo">Tech & Coding Club</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="registration.html">Registration</a>
            <a href="contact.html" class="active">Contact</a>
        </nav>
    </header>

    <div class="container">
        <main>
            <section>
                <h1>Contact Us</h1>
                <p>Have questions about upcoming club workshops, membership details, or hackathons? Reach out to our core team through the contact channels below.</p>
            </section>

            <section class="contact-box">
                <h2>Official Contact Details</h2>
                <ul>
                    <li><strong>Email Support:</strong> <a href="mailto:codingclub@university.edu">codingclub@university.edu</a></li>
                    <li><strong>Phone Helpline:</strong> +91 (581) 234-5678</li>
                    <li><strong>Campus Location:</strong> Innovation Hub, Computer Science Department, Block B, Invertis University, Bareilly, Uttar Pradesh</li>
                    <li><strong>Office Hours:</strong> Monday to Friday — 3:00 PM to 5:30 PM</li>
                </ul>
            </section>
        </main>
    </div>

    <footer>
        <p>&copy; 2026 Tech & Coding Club. All rights reserved.</p>
    </footer>

</body>
</html>