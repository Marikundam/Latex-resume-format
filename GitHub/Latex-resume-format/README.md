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
        \small#1 & #2\\
     %\small#3 &  #4} \\
    \end{tabular*}\vspace{-3pt}
}
\newcommand{\resumePublicationsheading}[2]{
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
%\setbool{acvSectionColorHighlight}{true}
%\renewcommand{\acvHeaderSocialSep}{\quad\textbar\quad}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------


\begin{center}
    \textbf{\Huge \scshape MARIKUNDAM  HARSHITHA} \\ \vspace{1pt}
    \small +91 9248171497 $|$\href{mailto:marikundamdec@Gmail.com}{{marikundamdec@gmail.com}} $|$ 
    \href{https://linkedin.com/in/} {{linked/marikundamharshitha}} $|$  \\
   \href{https://github.com/...}{{github.com/Marikundam}} $|$ 
    \href{https://www.hackerrank.com/...}{{hackerrank.com/marikundamdec}}
    
\end{center}


{%---------------INTRODUCTION-------------}
\section{}
\runsubsection{}

Driven student leveraging Undergrad in Electronics and Communication Engineering. Offers strong interpersonal and prioritization skills . Fervent to learn and explore more  techie  enigmas.


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Jawaharlal NehruTechnological University}{Hyderabad, Telangana}
      {Bachelor of Technology in Electronics Communication Engineering-9.25}{Aug. 2019 --  2023}
    \resumeSubheading
      {Narayana Junior College}{Hyderabad, Telangana}
      {MPC-98.3}{Aug. 2016-- June 2018}
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
     {Robotics Intern}{April 2022 -- May 2022}
      {Leap Robots}{Hyderabad}
      \resumeItemListStart
        \resumeItem{Worked on various sensors,micro-controllers and processors}
        \resumeItem{Deployed small scale projects using Internet of Things}
        \resumeItem{Explored 3D printing techniques}
      \resumeItemListEnd
      
% -----------Multiple Positions Heading-----------

    \resumeSubheading
      {Machine Learning Intern}{February 2020 -- July 2020}
      {Verzeo}{Hyderabad}
      \resumeItemListStart
        \resumeItem{Worked on Data analysis , cleaning, visualization , training the model , finally deploying using various ML algorithms.}
        \resumeItem{Implemented Ageing Signs Detection Model that can detect and localize the aging from image of a person with Wrinkles&dark spots.}
        \resumeItem{Explored Data Science pipeline -Artificial Intelligence,Neural Networks.}
    \resumeItemListEnd

   

%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
   
           \resumeProjectHeading
            {\textbf{1.Automatic music generator} $|$ \emph{Keras,Neural Networks}}{April2022 -- Present}
          \resumeItemListStart
            \resumeItem{Developing a automatic music generator for any style,genre and mood}
            \resumeItem{Platform uses Artificial Neural Networks ,inspired from Mubert music generator but here we are applying for Karnatik music}
            \resumeItemListEnd
             \resumeProjectHeading
          {\textbf{2.Twitter clone } $|$ \emph{BlockChain,React.js,MetaMask,HardHat}}{July  2022 -- August 2022}
          \resumeItemListStart
            \resumeItem{Worked on clones,NFT ,compilers and providers for BlockChain}
            \resumeItem{Developed a project/ app that runs on BlockChain which is encrypted}
            \resumeItemListEnd
             \resumeProjectHeading
          {\textbf{3.Home Automation using IoT } $|$ \emph{Arduino UNO, NodeMCU}}{February 2022 -- April 2022}
          \resumeItemListStart
            \resumeItem{Initially developed an  effective power usage bulb based on embedded systems, more of a green- building concept }
            \resumeItem{Implemented using sensors, gates ,mini- solar panels and then deployed buletooth door surveillance system}
            \resumeItem{Extended the idea more efficiently using IoT where one can control most of the electronic devices on cloud}
              \resumeItemListEnd
           
      \resumeProjectHeading
         {\textbf{4.Age Detecting System} $|$ \emph{ML,AI,Python,Tensor Flow}}{March 2020 -- July 2020}
          \resumeItemListStart
            \resumeItem{Developed a  Model that can detect and localize the ageing from image of a person with Wrinkles& dark spots.}
            
            \resumeItem{Pre-trained Efficient Net Models that comprise of the codes for the detection 
of wrinkles, dark spots and puffy eyes are downloaded.}
            \resumeItem{A Dataset comprising of a combination of Facial Images with a mix of Dark 
Spots, Wrinkles and Puffy Eyes is introduced for the purpose of analysis, 
training and testing.}
          \resumeItemListEnd
           
           
    \resumeSubHeadingListEnd
    
     
 
 
%----------COURSE PROJECT-----------
\section{Course Project}
\resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Wireless Power Transfer through Router}}\\
     { Implementation  of "wireless charging system by harnessing existing  Wi-Fi networks” using Simulink model based design without ruining internet efficiency }
 \resumeSubheading
  {Guided Projects}| {Coursera}
 
\begin{itemize}
 
\begin{itemize}
\item Deep Learning with PyTorch : Image Segmentation
\item Exploratory Data Analysis with Seaborn
\item Machine Learning Pipelines with Azure ML Studio
\end{itemize}
          
            
         
          \resumeItemListEnd










 
%-----------------PUBLICATIONS-----------------
    \section{Publications}
  \resumeSubHeadingListStart
    \resumeSubheading
      {3rd URSI Atlantic and Asia Pacific Radio Science Meeting (AT-AP-RASC)}{2022}
      {Climatology of lightning activities across the Equatorial African region }{}{ }
    \resumeSubheading
      {21st National Space Science Symposium}{31 JANUARY -4 FEBRUARY 2022}
      {
Long term variability in lightning occurrences over the Congo Basin Africa}{}
  \resumeSubHeadingListEnd
 





%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
    {\textbf{Languages}}{: Java, Python,  JavaScript, HTML/CSS } \\

     {\textbf{Frameworks}}{: React.js} \\

     {\textbf{Developer Tools}}{: VS Code, Visual Studio, PyCharm, IntelliJ,Vivado} \\

     {\textbf{Libraries}}{: pandas, Matplotlib,Keras}\\
     {\textbf{Other skills}}{:Artificial Intelligence,Machine Learning,UX Designing,Mern Stack,Internet of Things,BlockChain}\\
     {\textbf{Controllers/Processor}s}{:Arduino UNO, Raspberry Pi}


    }}
 \end{itemize}

 

%-----------CERTIFICATIONS---------
\section{Certifications}
 
 
\begin{itemize}
\item The Complete 2022 Web Development Bootcamp -Udemy
\item The Complete Facebook Ads & Marketing Course 2021 - Udemy
\item Foundations of User Experience (UX) Design - Google
\item AI For Everyone - DeepLearning.AI
\item Machine Learning with Python - Verzeo
\item Micro Mechatronics and Soft Robotics - IIIT Indore
 \end{itemize}

%----------FURTHER TENTATIVE INTERESTS---------------------------------
\section{ Interests}

\begin{itemize}
\item Novels,comics
\item Finance(stocks)
\item Psychology
\item Movies
\item Image segmentation,computer visualization
\end{itemize}


\end{document}
