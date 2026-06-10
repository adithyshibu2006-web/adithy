<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>My Portfolio</h1>
        <p>My portfolio</p>
        <p>
            This portfolio provides information about my background, skills,
            projects, achievements, and contact details. It is created using
            basic HTML tags without CSS.
        </p>
    </header>

    <!-- Home Section -->
    <section id="home">
        <h2>Home</h2>

        <p>
            Hello! My name is adithy , and I am an aspiring web developer.
            I enjoy creating websites and learning new technologies that help
            solve real-world problems.
        </p>

        <p>
            This portfolio serves as a platform to showcase my skills,
            educational background, project experience, and personal interests.
            Through continuous learning and practice, I strive to improve my
            technical abilities and professional knowledge.
        </p>

        <p>
            Web development is a field that combines creativity and logical
            thinking. I am passionate about building responsive and user-friendly
            websites that provide value to users.
        </p>
    </section>

    <hr>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>

        <p>
            I am a dedicated student and technology enthusiast with a strong
            interest in software development and web technologies. My journey
            into programming started with curiosity and has grown into a passion
            for creating useful applications.
        </p>

        <p>
            I enjoy learning HTML, CSS, JavaScript, Python, and database
            management. Apart from coding, I like reading technical articles,
            exploring innovative ideas, and participating in collaborative
            projects.
        </p>

        <p>
            My goal is to become a skilled full-stack developer capable of
            designing and developing efficient software solutions. I believe
            that continuous learning and practical experience are essential
            for success in the technology industry.
        </p>
    </section>

    <hr>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>

        <table border="1">
            <tr>
                <th>Qualification</th>
                <th>Institution</th>
                <th>Year</th>
            </tr>
            <tr>
                <td>High School</td>
                <td>ABC Higher Secondary School</td>
                <td>2020</td>
            </tr>
            <tr>
                <td>Diploma in Computer Science</td>
                <td>XYZ Polytechnic College</td>
                <td>2023</td>
            </tr>
            <tr>
                <td>Bachelor's Degree</td>
                <td>University of Technology</td>
                <td>2026</td>
            </tr>
        </table>

        <p>
            Throughout my academic journey, I have focused on developing
            technical and problem-solving skills. My educational experiences
            have provided a strong foundation in computer science concepts and
            software development practices.
        </p>
    </section>

    <hr>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>

        <ul>
            <li>HTML</li>
            <li>CSS Basics</li>
            <li>JavaScript</li>
            <li>Python Programming</li>
            <li>Database Management</li>
            <li>Problem Solving</li>
        </ul>

        <p>
            I have developed these skills through academic projects,
            self-learning, online courses, and practical implementation.
            Each new project provides an opportunity to improve and expand
            my knowledge.
        </p>

        <p>
            I am constantly working on enhancing my technical expertise and
            staying updated with modern development tools and technologies.
        </p>
    </section>

    <hr>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>

        <article>
            <h3>Student Management System</h3>
            <p>
                A web-based application designed to manage student records,
                attendance, and academic information efficiently.
            </p>
        </article>

        <article>
            <h3>Online Portfolio Website</h3>
            <p>
                A personal website created to showcase skills, projects,
                educational qualifications, and contact information.
            </p>
        </article>

        <article>
            <h3>Library Management System</h3>
            <p>
                A software project that helps maintain book inventories,
                issue records, and return transactions within a library.
            </p>
        </article>

        <p>
            These projects have helped me gain hands-on experience in software
            design, coding, testing, and documentation. Working on projects
            also improves teamwork, communication, and analytical skills.
        </p>

        <p>
            I look forward to developing more innovative applications that
            address practical challenges and contribute positively to society.
        </p>
    </section>

    <hr>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>

        <p>
            If you would like to collaborate, discuss a project, or simply
            connect, please fill out the form below.
        </p>

        <form action="#" method="post">

            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name"><br><br>

            <label for="email">Email Address:</label><br>
            <input type="email" id="email" name="email"><br><br>

            <label for="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone"><br><br>

            <label for="subject">Subject:</label><br>
            <input type="text" id="subject" name="subject"><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="6" cols="40"></textarea><br><br>

            <label>Preferred Contact Method:</label><br>
            <input type="radio" id="emailContact" name="contactMethod">
            <label for="emailContact">Email</label>

            <input type="radio" id="phoneContact" name="contactMethod">
            <label for="phoneContact">Phone</label><br><br>

            <input type="checkbox" id="agree" name="agree">
            <label for="agree">
                I agree to share my information for communication purposes.
            </label><br><br>

            <input type="submit" value="Send Message">
            <input type="reset" value="Clear Form">

        </form>

        <p>
            You can also reach me through email, professional networking
            platforms, or direct communication channels. I am always open
            to learning opportunities and meaningful collaborations.
        </p>
    </section>

    <hr>

    <!-- Footer -->
    <footer>
        <h3>Portfolio Summary</h3>

        <p>
            Thank you for visiting my portfolio website. This webpage was
            developed using basic HTML elements including headings,
            paragraphs, tables, lists, navigation links, sections,
            articles, forms, and footer elements.
        </p>

        <p>
            My portfolio reflects my passion for technology, learning,
            and professional growth. I am committed to improving my skills
            and contributing to impactful projects in the future.
        </p>

        <p>
            © 2026 My Portfolio. All Rights Reserved.
        </p>
    </footer>

</body>
</html>
