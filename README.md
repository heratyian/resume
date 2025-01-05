```latex
%==========================
% SAMPLE RESUME IN LATEX
%==========================

\documentclass[letterpaper,10pt]{article}

%---------------------------
% PACKAGES AND MARGINS
%---------------------------
\usepackage[margin=1in]{geometry} % Adjust margins as needed
\usepackage{parskip}              % No paragraph indent, extra spacing
\usepackage{hyperref}             % For clickable URLs and links
\usepackage{setspace}             % For line spacing if needed
\setstretch{1.1}                  % Slight line spacing

%---------------------------
% CUSTOM COMMANDS
%---------------------------
\newcommand{\resheading}[1]{
  \vspace{10pt}
  \textbf{\large #1}
  \vspace{5pt}
  \hrule
  \vspace{5pt}
}

%---------------------------
% DOCUMENT START
%---------------------------
\begin{document}

%==========================
% CONTACT INFO
%==========================
\begin{center}
    {\LARGE \textbf{John Doe}} \\
    1234 Main Street, City, Country 12345 \\
    Phone: (123) 456-7890 \quad\textbullet\quad 
    Email: \href{mailto:johndoe@email.com}{johndoe@email.com}
\end{center}

%==========================
% SUMMARY / OBJECTIVE
%==========================
\resheading{Summary}
Highly motivated professional with experience in web development and a keen interest in full-stack solutions. Strong background in JavaScript and Python, with proven project management skills.

%==========================
% EDUCATION
%==========================
\resheading{Education}
\textbf{Bachelor of Science in Computer Science} \hfill 2018 -- 2022 \\
University of Example, City, Country \\
Relevant Coursework: Data Structures, Algorithms, Databases, Web Development

%==========================
% EXPERIENCE
%==========================
\resheading{Experience}

\textbf{Software Engineer Intern} \hfill Summer 2021 \\
XYZ Tech Company, City, Country
\begin{itemize}
    \item Developed front-end features using React and Redux.
    \item Collaborated with cross-functional teams to optimize REST APIs.
    \item Improved performance by 20\% on a customer-facing web app.
\end{itemize}

\textbf{Freelance Web Developer} \hfill 2020 -- 2021 \\
\begin{itemize}
    \item Built responsive websites for small businesses using HTML, CSS, and JavaScript.
    \item Integrated e-commerce solutions to increase online sales by 30\%.
    \item Worked closely with clients to gather requirements and provide ongoing support.
\end{itemize}

%==========================
% PROJECTS
%==========================
\resheading{Projects}

\textbf{Personal Portfolio Website} \hfill (2022)
\begin{itemize}
    \item Showcases my work, experience, and blog.
    \item Implemented using Next.js, styled-components, and hosted on Vercel.
\end{itemize}

\textbf{Machine Learning Capstone} \hfill (2021 -- 2022)
\begin{itemize}
    \item Developed a sentiment analysis model using Python and scikit-learn.
    \item Achieved 92\% accuracy on a real-world Twitter dataset.
    \item Deployed via a Flask REST API and Docker containers on AWS.
\end{itemize}

%==========================
% SKILLS
%==========================
\resheading{Skills}

\begin{itemize}
    \item \textbf{Languages}: Python, JavaScript, C++, Java
    \item \textbf{Frameworks/Libraries}: React, Node.js, Express, Django
    \item \textbf{Tools}: Git, Docker, AWS, Linux
    \item \textbf{Soft Skills}: Team Collaboration, Agile/Scrum, Problem-Solving
\end{itemize}

%==========================
% ACTIVITIES / LEADERSHIP
%==========================
\resheading{Activities \& Leadership}

\textbf{Computer Science Club}, University of Example (2019 -- 2022)
\begin{itemize}
    \item Organized weekly coding challenges and tech talks.
    \item Mentored new members in programming fundamentals.
\end{itemize}

\textbf{Hackathon Volunteer}, DevFest (2021)
\begin{itemize}
    \item Coordinated event logistics for a 500+ participant hackathon.
    \item Assisted teams with technical troubleshooting.
\end{itemize}

%==========================
% END DOCUMENT
%==========================
\end{document}

```
