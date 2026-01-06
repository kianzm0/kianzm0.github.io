[kiyan_resume_site.html](https://github.com/user-attachments/files/24443283/kiyan_resume_site.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kiyan Zare - Computer Engineering Student</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', sans-serif;
            line-height: 1.7;
            color: #1a1a1a;
            background: #f8f9fa;
            min-height: 100vh;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        header {
            background: white;
            border-radius: 8px;
            padding: 50px 40px;
            text-align: center;
            box-shadow: 0 1px 3px rgba(0,0,0,0.06);
            margin-bottom: 40px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        header:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }

        h1 {
            font-size: 2.5em;
            color: #1a1a1a;
            margin-bottom: 10px;
            font-weight: 600;
            letter-spacing: -0.5px;
        }

        .subtitle {
            font-size: 1.1em;
            color: #6b7280;
            margin-bottom: 25px;
            font-weight: 400;
        }

        .languages {
            display: flex;
            justify-content: center;
            gap: 12px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .language-badge {
            background: #f3f4f6;
            color: #374151;
            padding: 6px 16px;
            border-radius: 6px;
            font-size: 0.9em;
            font-weight: 500;
            transition: all 0.3s ease;
            border: 1px solid #e5e7eb;
        }

        .language-badge:hover {
            background: #1a1a1a;
            color: white;
            transform: translateY(-2px);
        }

        .section {
            background: white;
            border-radius: 8px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.06);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .section:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }

        h2 {
            color: #1a1a1a;
            font-size: 1.5em;
            margin-bottom: 30px;
            font-weight: 600;
            letter-spacing: -0.3px;
        }

        .education-item, .experience-item {
            margin-bottom: 30px;
            padding: 20px;
            border-radius: 6px;
            transition: all 0.3s ease;
            border-left: 3px solid #e5e7eb;
        }

        .education-item:hover, .experience-item:hover {
            background: #f9fafb;
            border-left-color: #1a1a1a;
            transform: translateX(5px);
        }

        .education-item:last-child, .experience-item:last-child {
            margin-bottom: 0;
        }

        h3 {
            color: #1a1a1a;
            font-size: 1.15em;
            margin-bottom: 6px;
            font-weight: 600;
        }

        .date {
            color: #6b7280;
            font-size: 0.9em;
            margin-bottom: 12px;
            font-weight: 500;
        }

        p {
            color: #4b5563;
            line-height: 1.7;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 12px;
            margin-top: 20px;
        }

        .skill-item {
            background: #f3f4f6;
            color: #374151;
            padding: 16px;
            border-radius: 6px;
            text-align: center;
            font-weight: 500;
            transition: all 0.3s ease;
            border: 1px solid #e5e7eb;
            cursor: default;
        }

        .skill-item:hover {
            background: #1a1a1a;
            color: white;
            transform: translateY(-3px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .interests {
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
        }

        .interest-tag {
            background: white;
            padding: 12px 20px;
            border-radius: 6px;
            color: #374151;
            font-weight: 500;
            border: 1px solid #e5e7eb;
            transition: all 0.3s ease;
            cursor: default;
        }

        .interest-tag:hover {
            background: #1a1a1a;
            color: white;
            border-color: #1a1a1a;
            transform: translateY(-2px);
        }

        .contact-info {
            text-align: center;
            font-size: 1em;
            color: #4b5563;
            line-height: 2;
        }

        .contact-info a {
            color: #1a1a1a;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            padding: 2px 4px;
            border-radius: 4px;
        }

        .contact-info a:hover {
            background: #f3f4f6;
            color: #000;
        }

        @media (max-width: 768px) {
            .container {
                padding: 40px 16px;
            }

            h1 {
                font-size: 2em;
            }

            .subtitle {
                font-size: 1em;
            }

            header, .section {
                padding: 30px 24px;
            }

            .skills-grid {
                grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Kiyan Zare</h1>
            <p class="subtitle">Computer Engineering Student | AI & Robotics Enthusiast</p>
            <div class="languages">
                <span class="language-badge">🇮🇷 Persian</span>
                <span class="language-badge">🇪🇸 Spanish</span>
                <span class="language-badge">🇺🇸 English</span>
            </div>
        </header>

        <div class="section">
            <h2>Education</h2>
            <div class="education-item">
                <h3>California State University, Northridge (CSUN)</h3>
                <p class="date">Sophomore | Computer Engineering | GPA: 4.0</p>
                <p>Building a strong foundation in computer systems, programming, and engineering principles with perfect academic standing.</p>
            </div>
            <div class="education-item">
                <h3>University of Granada, Spain</h3>
                <p class="date">Study Abroad | One Semester</p>
                <p>International academic experience enhancing cross-cultural communication and technical skills.</p>
            </div>
            <div class="education-item">
                <h3>Valencia Polytechnic University, Spain</h3>
                <p class="date">Study Abroad | One Semester</p>
                <p>Advanced coursework in engineering with exposure to European educational methodologies.</p>
            </div>
            <div class="education-item">
                <h3>Roshd Secondary School, Tehran</h3>
                <p class="date">High School Diploma | Mathematics & Physics | GPA: 4.0</p>
                <p>Graduated with honors specializing in mathematics and physics, establishing a strong analytical foundation for engineering studies.</p>
            </div>
        </div>

        <div class="section">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-item">C++</div>
                <div class="skill-item">Python</div>
                <div class="skill-item">Java</div>
                <div class="skill-item">HTML</div>
                <div class="skill-item">WordPress</div>
            </div>
        </div>

        <div class="section">
            <h2>Areas of Interest</h2>
            <div class="interests">
                <span class="interest-tag">🤖 Artificial Intelligence</span>
                <span class="interest-tag">🦾 Robotics</span>
                <span class="interest-tag">⚙️ Automation</span>
            </div>
        </div>

        <div class="section">
            <h2>Certifications & Achievements</h2>
            <div class="experience-item">
                <h3>DELE C1 Spanish Language Certificate</h3>
                <p class="date">Instituto Cervantes, Spain</p>
                <p>Achieved advanced C1 proficiency in Spanish in less than 9 months from beginner level, demonstrating exceptional language acquisition ability and dedication to cross-cultural communication.</p>
            </div>
        </div>

        <div class="section">
            <h2>Publications</h2>
            <div class="experience-item">
                <h3>The Waves - Student Essay Collection</h3>
                <p class="date">Published Student Author</p>
                <p>Selected for publication in The Waves, a prestigious collection of student essays used in university literature and English departments across the nation.</p>
            </div>
        </div>

        <div class="section">
            <h2>Leadership & Organizations</h2>
            <div class="experience-item">
                <h3>CSUN New Student Orientation (NSO) - Volunteer Leader</h3>
                <p class="date">December 2025 - Present</p>
                <p>Guide and mentor incoming students through university transition, providing campus resources information and fostering welcoming community environment. Demonstrate leadership through peer mentorship and orientation program facilitation.</p>
            </div>
            <div class="experience-item">
                <h3>Iranian Student Association, CSUN - Treasurer</h3>
                <p class="date">January 2025 - May 2025</p>
                <p>Managed organizational finances including donated funds for cultural events and university fundraising transfers. Created invoices and financial tracking tables in Excel, drafted budgets and cost analyses, and coordinated membership fee collection. Developed teamwork and communication skills through collaborative decision-making and clear articulation of financial strategies to executive board members.</p>
            </div>
        </div>

        <div class="section">
            <h2>Experience</h2>
            <div class="experience-item">
                <h3>Matador Achievement Center, CSUN - Tutoring Assistant</h3>
                <p class="date">December 2025 - Present</p>
                <p>Provide academic support to CSUN student-athletes in calculus, pre-calculus, Spanish, physics, and science. Deliver personalized tutoring sessions that balance rigorous academics with athletic schedules, helping students achieve academic excellence.</p>
            </div>
            <div class="experience-item">
                <h3>ESN Valencia - Tour Guide & Program Director</h3>
                <p class="date">January 2023 - December 2023</p>
                <p>Planned and managed cultural tours across Valencia and Spain for international Erasmus students. Led multilingual teams, provided customer service in multiple languages, and took initiative in organizing logistics for large-scale events. Interpreted constantly between Spanish, English, and Persian to facilitate cross-cultural communication and ensure seamless program execution.</p>
            </div>
            <div class="experience-item">
                <h3>Amina Group - SEO Content Intern</h3>
                <p class="date">February 2022 - April 2022</p>
                <p>Gathered and optimized digital content for Google search engine visibility, successfully elevating websites to first-page rankings through strategic SEO implementation and content enhancement.</p>
            </div>
        </div>

        <div class="section">
            <h2>Projects & Competitions</h2>
            <div class="experience-item">
                <h3>Football Robotics Competition</h3>
                <p class="date">10th Grade | Roshd Secondary School, Tehran</p>
                <p>Collaborated in a team to design and program an autonomous football-playing robot using C++. Applied object-oriented programming, sensor integration, and real-time decision algorithms to solve complex navigation and strategy challenges in a dynamic competitive environment.</p>
            </div>
        </div>

        <div class="section contact-info">
            <h2>Let's Connect</h2>
            <p>📧 Email: <a href="mailto:kian.zara@yahoo.com">kian.zara@yahoo.com</a></p>
            <p>💼 LinkedIn: <a href="https://www.linkedin.com/in/kiyan-zare-98757b343" target="_blank">linkedin.com/in/kiyan-zare</a></p>
        </div>
    </div>
</body>
</html>
