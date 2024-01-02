# Resume
Overleaf Resume Code 
%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    \textbf{\Huge \scshape Rohan Patil} \\ \vspace{1pt}
    \small 8007552883 $|$ \href{mailto:rohanpatil4404@gamil.com}{{rohanpatil4404@gamil.com}} $|$ 
    \href{https://www.linkedin.com/in/rohan-patil-6b31a3250/}{{\underline{linkedin.com/in/rohan-patil}}} $|$
    \href{https://github.com/RohanPatil214}{{\underline{github.com/RohanPatil}}}
    
    
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Bachelor of Science, (B.S.) - Computer Science}{Karad, Maharashtra}
      {S.G.M. College, (Shivaji University)}{Jun-2019 - Apr-2023}
      \resumeItemListStart
        \resumeItem {Crafted a user-friendly web app with a \textbf{25\%} increase in user engagement, leveraging HTML, CSS, JS, Bootstrap, Python, and Flask}
        \resumeItem{led a college event and taught classmates about \textbf{cybersecurity}, demonstrating organisational \& leadership skills.}
      \resumeItemListEnd
    \resumeSubheading
      {Higher Secondary Certificate, (HSC) - Computer Science}{Karad, Maharashtra}
      {S.G.M. College, (HSC, Pune)}{Jul-2017 - Feb-2019}
       \resumeItemListStart
        \resumeItem{Founded and led a club named 'SGMCK' focused on demonstrating passion and Students Problem.}
        \resumeItem{Relevant Coursework: C, C++, HTML, Database Management System, Operating System, Computer Network.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart
  \resumeSubheading
      {Machine Learning intern}{Dec-2023 - Present}
      {Codsoft}{REMOTE}
      \resumeItemListStart
       \resumeItem{Applying \textbf{ML algorithms}, statistical methods for predictive models, extracting insights
from diverse datasets for informed decision-making.}
        \resumeItem{Working on projects like Movie Genre Classification, Credit Card Fraud Detection}
         \resumeItem{Creating a Machine Learning model using Naive Bayes, Logistic Regression,Decision trees, Random Forest.}
    \resumeItemListEnd
    \resumeSubheading
      {Data Science intern}{Dec-2023 -  Dec-2023}
      {Bharat intern}{REMOTE}
      \resumeItemListStart
        \resumeItem{Implemented advanced \textbf{NLP techniques}, elevating SMS classifier accuracy.}
        \resumeItem{Refined Computer Vision models for enhanced image recognition capabilities.}
    \resumeItemListEnd
    \resumeSubheading
      {Data Science intern}{July-2023 - Present}
      {Learnbay}{REMOTE}
      \resumeItemListStart
        \resumeItem{Leveraged \textbf{Python \& SQL} to analyze and extract insights from large datasets}
        \resumeItem{Applied statistical methods and machine learning algorithms to solve real-world
business problems}
        \resumeItem {Enhanced data quality and cleaning procedures, ensuring accuracy in analytical
models.}
        \resumeItem {Currently pursuing advanced coursework in Data Science to further refine skills.}
    \resumeItemListEnd
    
  \resumeSubHeadingListEnd


%-------------------------------------------
%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
\resumeItemListStart
            \resumeItem{\textbf{Programming Languages}{: Python, SQL, C/C++, HTML}}
            \resumeItem{\textbf{Data Science and Miscellaneous Technologies}{: Data Science Pipeline(collection, cleansing, visualization, modeling, interpretation), Statistics, Hypothesis Testing.}}
            \resumeItem{\textbf{Extra Skills} :Machine Learning , Exploratory Data Analysis-EDA, Tensorflow, Scikit-learn, CSS, Bootstrap, Flask, Debugging and Troubleshoot, Team collaboration, Product Marketing, Technical documentation, Penetration testing}
\resumeItemListEnd


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{SMS Spam classifier}}
          {{ $:$ \emph{Multinomial Naive Bayes}}}
          \resumeItemListStart
            \resumeItem {Used MNB Algorithm for SMS classifier, got     \textbf{93\% Accuracy}, and \textbf{88\% Precesion }, also got good score in Recall \& F1-score}
            \resumeItem{Reduced customer service costs by \textbf{10\%} with highly accurate (\textbf{91/\%}
            )SMS spam filtering using MNB.}
            \resumeItem{Worked on \textbf{Data Preprocessing, Feature Extraction, Model Training, Model Evalution} and \textbf{Deployment}}
          \resumeItemListEnd
    \resumeSubHeadingListEnd

%-----------CERTIFICATES-----------
\section{CERTIFICATES}
\resumeSubHeadingListStart
  \resumeSubheading
    {Python For Data Science}{Learnbay}{}{Jul-2023 - Nov-2023}
    \resumeItemListStart
      \resumeItem{Learnbay - 252jk5ff}
    \resumeItemListEnd
  \resumeSubheading
    {Cyber Security Course}{Drop.Org}{}{Aug-2023 - Jan-2023}
    \resumeItemListStart
      \resumeItem{Development \& Research Organization Planning(DROP.ORG.IN) - DCSC-RPB0922.}
    \resumeItemListEnd
  % Add more certifications as needed, following the same structure
\resumeSubHeadingListEnd

%%

\begin{comment}
    {\emph{Research Work} $|$ {Jan 2021 - July 2022}}
    {\emph{Natural Language Processing} $|$ {Feb 2021 - May 2021}}
\end{comment}

%-------------------------------------------
\end{document}
