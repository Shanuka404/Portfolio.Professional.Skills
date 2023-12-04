<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <link rel="stylesheet" href="Profile.css">

    <script>
        function toggleDiplomaResults() {
            var diplomaSection = document.getElementById("diploma-section");
            if (diplomaSection.style.display === "none" || diplomaSection.style.display === "") {
                diplomaSection.style.display = "block";
            } else {
                diplomaSection.style.display = "none";
            }
        }
    </script>
</head>

<body>
    <header>
        <nav>
            <div class="fixed-navbar">
                <div class="navbar">
                    <div class="brand">
                        <a href="#">Professional Skills</a>
                    </div>
                    <ul class="navbar">
                        <li class="nav-item dropdown">
                            <a href="javascript:void(0)" class="dropbtn">Lectures</a>
                            <div class="dropdown-content">
                                <a href="Introduction.html">Introduction</a>
                                <a href="CVWriting.html">CV Writing</a>
                                <a href="Interview.html">Interview Skills</a>
                                <a href="PortfolioWriting.html">Portfolio Writing</a>
                                <a href="Speaking.html">Speaking Skills</a>
                                <a href="EmailWriting.html">Email Writing</a>
                                <a href="NegotiationSkills.html">Negotiation Skills</a>
                                <a href="TelephoneEtiquettes.html">Telephone Etiquettes</a>
                                <a href="AbstractWriting.html">Abstract Writing</a>
                                <a href="ProposalWriting.html">Proposal Writing</a>
                                <a href="EmotionalIntelligence.html">Emotional Intelligence</a>
                                <a href="EtiquetteProfessionalism.html">Etiquette, professionalism</a>
                            </div>
                        </li>
                        <li class="nav-item"><a href="Profile.html">Profile</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
<br><br><br>
<header>
    <h1 class="logo">Profile Details</h1>
    
</header>

    <div class="profile-container">
        
        <div class="profile-details">
            <img src="Image/Picture.png" alt="Profile Picture" class="profile-picture">
            <div class="details">
                <ul>
                    <li><strong>Name :</strong> S.D.Ranaweera</li>
                    <li><strong>ID No :</strong> 200000202360</li>
                    <li><strong>DOB :</strong> 02 Jan 2000</li>
                </ul>
            </div>
            <div class="contacts">
                <h2>Contacts</h2>
                <ul>
                    <li><strong>E mail:</strong> shanukadeva2000@gmail.com</li>
                    <li><strong>Address:</strong> 229- Medikalewatta, Helakandana, Horampella, Minuwangoda.</li>
                    <li><strong>TP number:</strong> 076 6 871 663</li>
                </ul>
            </div>
            <div class="bio">
                <h2>Biography</h2>
                <p>• Goal centric undergraduate with a go-getter attitude, specialized in the field of Information Technology, seeking a dynamic and challenging work environment which will provide an excellent opportunity for career progression.</p>
            </div>
        </div>

        <div class="education">
            <h2>Education Qualification</h2>
            <ul>
                <li>BSc (Hons) Computer Science and Software Engineering</p></li>
                <p>2022 – Present</p>
                <p>(SLIIT Academy (Pvt) Ltd.)</p>
                <br>
                <li><p>Diploma in Engineering Science</p></li>
                <p>2019 – 2020</p>
                <p>(Australian College of Business and Technology.)</p>
                <br>
                <li><p>G.C.E (Advanced Level) – 2018 (Mathematic Stream)</p></li>
                <p>(Nalanda Boys’ college Minuwangoda, With two passes to combined mathematics and physics.)</p>
            </ul>
        </div>

        <div class="skills">
            <h2>Skills and Competence</h2>
            <ul>
                <li>• Knowledge in OOP Concept in Java, Data Structures & Algorithms.</li>
                <li>• Basic knowledge in C++, C.</li>
                <li>• Familiar with NetBeans, IntelliJ IDEA, Android Studio, Virtual Studio.</li>
                <li>• Skills and knowledge in MySQL & SQL server, JavaScript, PHP, CSS</li>
                <li>• Skills and knowledge in UML diagrams design. (Activity diagram, sequence diagram, physical diagram, use case diagram)</li>
            </ul>
        </div>

        <div class="projects">
            <h2>Projects Completed</h2>
            <ul>
                <li>• Developed an E-Commerce web site for online shopping using Virtual Studio.</li>
                <li>• Developed a desktop application using Java in IntelliJ IDEA for a management system.</li>
                <li>• Developed a desktop application for a gym using NetBeans.</li>
                <li>• Develop an E-commerce android application for an online
                    shopping.</li>
            </ul>
        </div>
         

        <div class="achievements">
            <h2>Special Achievements</h2>
            <p>• Participated in Olympiad in Mathematics.</p>
        </div>
    </div>
<br>
    

    <a onclick="toggleDiplomaResults()" target="_blank" class="view-cv">View SLIIT Result</a>

    <div id="diploma-section" style="display: none;">
        <header>
            <h1 class="logo">Diploma-Results at SLIIT</h1>
        </header>
    <div class="diploma-section">
        <h3>Orientation</h3>
        <div class="result-table">
            <table>
                <tr>
                    <th>Subjects</th>
                    <th>Result</th>
                </tr>
                <tr>
                    <td>Foundation of Mathematical Skills</td>
                    <td>(A)</td>
                </tr>
                <tr>
                    <td>Programming Skills in C</td>
                    <td>(A-)</td>
                </tr>
                <tr>
                    <td>Communication Skills</td>
                    <td>(B+)</td>
                </tr>
                <tr>
                    <td> Program Design Techniques</td>
                    <td>(B)</td>
                </tr>
            </table>
        </div>
        
        <br>

        <h3>Year 1 Semester 1</h3>
        <div class="result-table">
            <table>
                <tr>
                    <th>Subjects</th>
                    <th>Result</th>
                </tr>
                <tr>
                    <td>Introduction to Programming (C/C++)</td>
                    <td>(A+)</td>
                </tr>
                <tr>
                    <td>Mathematics for Computing</td>
                    <td>(A)</td>
                </tr>
                <tr>
                    <td>Data Communication Computer Networks</td>
                    <td>(C+)</td>
                </tr>
                <tr>
                    <td>Business English & Communication Skills</td>
                    <td>(C+)</td>
                </tr>
                <tr>
                    <td>Computing Fundamentals-Compulsory</td>
                    <td>(C)</td>
                </tr>
            </table>
        </div>

        <br>

        <h3>Year 1 Semester 2</h3>
        <div class="result-table">
            <table>
                <tr>
                    <th>Subjects</th>
                    <th>Result</th>
                </tr>
                <tr>
                    <td>Object Oriented Programming (JAVA)</td>
                    <td>(A-)</td>
                </tr>
                <tr>
                    <td>Database Management Systems</td>
                    <td>(B+)</td>
                </tr>
                <tr>
                    <td>Software Engineering-Compulsory</td>
                    <td>(B-)</td>
                </tr>
                <tr>
                    <td>Web Application Development</td>
                    <td>(B-)</td>
                </tr>
                <tr>
                    <td>Emerging Technologies and Frameworks-Compulsory</td>
                    <td>(incomplete)</td>
                </tr>
            </table>
        </div>
        
        <br>

        <h3>Year 2 Semester 1</h3>
        <div class="result-table">
            <table>
                <tr>
                    <th>Subjects</th>
                    <th>Result</th>
                </tr>
                <tr>
                    <td>Data Structures and Algorithms</td>
                    <td>(A)</td>
                </tr>
                <tr>
                    <td>Probability and Statistics</td>
                    <td>(A)</td>
                </tr>
                <tr>
                    <td>Human Computer Interaction</td>
                    <td>(B-)</td>
                </tr>
                <tr>
                    <td>Data Communication and Computer Networks II</td>
                    <td>(C+)</td>
                </tr>
                <tr>
                    <td>Operating Systems</td>
                    <td>(C)</td>
                </tr>
            </table>
        </div>
        
        <br>

        <h3>Year 2 Semester 2</h3>
        <div class="result-table">
            <table>
                <tr>
                    <th>Subjects</th>
                    <th>Result</th>
                </tr>
                <tr>
                    <td>Design & Analysis of Algorithms</td>
                    <td>(Still doing....)</td>
                </tr>
                <tr>
                    <td>Data Systems</td>
                    <td>(Still doing....)</td>
                </tr>
                <tr>
                    <td>Project & Professional Practice</td>
                    <td>(Still doing....)</td>
                </tr>
                <tr>
                    <td>Employability Skills Development</td>
                    <td>(Still doing....)</td>
                </tr>
                <tr>
                    <td>Computer Security</td>
                    <td>(Still doing....)</td>
                </tr>
                <tr>
                    <td>Profecianal skills</td>
                    <td>(Still doing....)</td>
                </tr>
            </table>
        </div>

    </div>
</div>

    <a href="PDF/cv.pdf" target="_blank" class="view-cv">View CV</a>
    <a href="PDF/DipInEngineeringScience.pdf" target="_blank" class="view-cv">View Engineering Certificate </a>

    <footer>
        <p>&copy; 2023 Professional Skills Portfolio</p>
    </footer>
</body>

</html>
