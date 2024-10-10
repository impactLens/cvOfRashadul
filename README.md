%----------------------------------------------
%	PACKAGES AND OTHER DOCUMENT CONFIGURATIONS
%----------------------------------------------
\documentclass[twocolumn, a4paper,10pt]{article}

\usepackage[top=1cm,bottom=2cm,left=2cm,right=1cm]{geometry}	% Use A4 paper margins

\usepackage[english]{babel}
\usepackage{graphicx}
\usepackage{color}
\usepackage[usenames,dvipsnames]{xcolor}

\usepackage[square, numbers, comma, sort&compress]{natbib}

%Hiding the weblink means: no color on the weblink
\usepackage [hidelinks] {hyperref}
\usepackage{fancyhdr}
\usepackage{xcolor} % Required for specifying custom colors

%Remove the tab or indent of beginning of sentence
\setlength{\parindent}{0cm}


\usepackage{setspace}
\setstretch{1.0} % Line spacing of 1.3

\usepackage{times}

%\setlength{\oddsidemargin}{0mm} % Adjust margins to center the colored title box
%\setlength{\evensidemargin}{0mm} % Margins on even pages - only necessary if adding more content to this template

\definecolor{grey}{rgb}{0.9,0.9,0.9} % Color of the box surrounding the title - these values can be changed to give the box a different color

%Gap between header and the text beginning
%\setlength{\headsep}{12pt}

\usepackage[absolute]{textpos}

\usepackage{ragged2e}

\definecolor{blues}{rgb}{16,52,231}

\usepackage{tikz}
\usepackage{pgfplots}

\usepackage{datetime}

\newdateformat{usvardate}{%
	\dayofweekname{\THEDAY}{\THEMONTH}{\THEYEAR}{ }\monthname[\THEMONTH]{ }\twodigit{\THEDAY}{ }\hhmmsstime{ } BST +06:00{ }{\THEYEAR}
}

\definecolor{r}{RGB}{78,82,96}
\definecolor{z}{RGB}{174,70,44}
\definecolor{zz}{RGB}{227,23,23}

\usepackage[bottom]{footmisc}

\pagestyle{fancy}
\fancyhf{}

\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

%==============FONT==============
\usetikzlibrary{decorations.text}
\usepackage{amssymb}
%\usepackage{fontspec}
%\setmainfont[Ligatures=TeX]{CAMBRIA_1.ttc}
%\newfontfamily\myfont{CAMBRIA_1.ttc}
%==============FONT==============


%==============HEADER AND FOOTER==============
%\lhead{{\fontsize{30pt}{6pt}\bfseries RASHADUL ISLAM} \\ {\fontsize{10pt}{6pt} \selectfont B.Sc (double undergraduate)\\System Software, Software Engineering, Canada-Bangladesh} \\}


%}% end of lhead

%\rhead{\fontsize{10pt}{6pt}DevOP Full Stack, Consultant IT, Infrastructure \& ICT, Entrepreneur, Business development mentor, Big Data Analyst, Artificial Intelligence \& Nanotechnology [Research Objectives], Algorithm Trade Smith, Product or Service Ecosystem Designer, Organization Branding \& Policy Designer, Open Source Ambassador, Keynote Speaker.  \\}

%\rhead{\includegraphics[width=2cm]{RashadulIslamPICTURE2.jpg}}
%\cfoot{Rashadul Islam \par Revised on: { \input{|"date"}} \ Page \thepage}
\cfoot{Rashadul Islam \par Revised on: {\usvardate} \ Page \thepage}
%==============HEADER AND FOOTER==============

% section number to letters
\renewcommand*{\thesection}{\Alph{section}.}

% line number for csc,cse, devop job
\usepackage{lineno}
%\linenumbers

\usepackage{multirow} 

\begin{document}

% put line no in DevOP job
%\linenumbers

%========BODY OF THE LETTER==========
%\vspace*{0.1cm}

%========START RESUME==========
%\maketitle
\pagenumbering{arabic}
%\fontsize{10}{10}\selectfont

%{\fontsize{36pt}{6pt} \selectfont Rashadul Islam}\\ {\fontsize{10pt}{6pt} \selectfont B.Sc. CSE, CSC\\ \textit{Specialization: System Software, Software Engineering} \\ Canada-Bangladesh\\}

{\fontsize{36pt}{6pt} \selectfont Rashadul Islam}\\ {\fontsize{10pt}{6pt} \selectfont B.Sc. (double undergraduate)\\ \textit{Specialization: System Software, Software Engineering} \\ Canada-Bangladesh\\}


{\fontsize{8pt}{6pt} \textit{ DevOP [Full Stack], Consultant IT, Computer Infrastructure \& ICT Architect, Entrepreneur, Business development mentor, Big Data Analyst, Artificial Intelligence \& Nanotechnology [Research], Algorithm, Product or Service Ecosystem Designer, Organization Branding \& Policy Designer, Open Source Ambassador, Keynote Speaker}}\\

%\includegraphics[width=2.5cm]{RashadulIslam.jpg}\\

%========CONTACT INFORMATION==========
{\fontsize{10}{8} Contact of Rashadul Islam}

\begin{table}[!ht]
	\footnotesize
	\begin{tabular}{p{2.5cm}p{5.5cm}}
		
		Cellular: & +8801714118395\\
		%E-Mail: & \href {mailto:rashadul.cse@gmail.com}{rashadul.cse@gmail.com}  \\
		E-Mail: & \href {mailto:systemd.rashadul@hotmail.com}{systemd.rashadul@hotmail.com}  \\
		Residence:	& House 13, Road 1 \par Mahadebpur (Noorpur), Alamnagar, \par Rangpur 5402, Bangladesh   \\
		Postal Address: & House 62, Floor 5, Siddique Bazar, \par Near Moti Shardar Mosque, \par Bangshal Thana,Dhaka 1100, Bangladesh   \\
		
	\end{tabular}
\end{table}

%========PERSONAL INFORMATION==========
{\fontsize{10}{8} Personal details}

\begin{table}[!ht]
	\scriptsize
	\begin{tabular}{p{2cm}p{3cm}p{3cm}}
		\multirow{5}{*}{\includegraphics[width=2.5cm]{RashadulIslam.jpg}}& &\\
		& Name: & RASHADUL ISLAM  \\
		& Name of Mother: & MAHFUJA KHATUN \\
		& Name of Father: & Md. SERAJUL ISLAM\\
		
		& Date of Birth: & JANUARY 01, 1984   \\
		& Nationality:& Bangladeshi by Birth   \\
		
	\end{tabular}
\end{table}


%========LANGUAGE ADAPTABILITY==========
{\fontsize{10}{8} Language Adaptability}

\begin{table}[!ht]
	\footnotesize
	\begin{tabular}{p{1.5cm}p{3.3cm}p{3cm}}
		
		& Estimated Band Score & Out of Score \\
		ENGLISH & 8.5 & 10 \\
		FRENCH & 6.5 & 10 \\
		BANGLA & 9.0 & 10 \\
		SPANISH & 5.5 & 10 \\
		
	\end{tabular}
\end{table}

%========TECHNICAL & TECHNOLOGY TOOLBOX==========
{\fontsize{10}{8} Technical \& Technology Toolbox}\\
{
	%\footnotesize
	\scriptsize
	J2SE
	J2EE
	Mariadb
	MySQL
	MySQL workbench
	Net beans
	JavaScript
	HTML5
	XML
	CSS
	Apace Tomcat
	JBOSS
	Oracle 19c
	Git
	SVN
	C++
	C
	Lisp
	Emacs
	Vim
	Xcode
	Atom
	Ansible
	Docker
	SaaS
	PaaS
	IaaS
	IoT
	Python
	Matlab
	SPSS
	R
	AutoCAD
	Blender
	Audacity
	AsciiDoc
	Amazon EC2
	Lamp server
	xampp
	Red hat
	Microsoft Windows server
	Open Suse
	IoS
	MacOS
	Android
	Raspberry pi
	Power BI
	IBM Watson
	Open shift
	Kubernetic
	Bugzilla
	Google workplace
	Microsoft 365
	Google Analytics
	YouTube studio
	CCNA toolkit
	Plant UML
	Smart Digital City \& Citizen Management
	Dynamic programming
	Agile or prince2 or scrum project management
}
\\\\
%=%=%========soft & hard skills==========
{\fontsize{10}{8}{Skills Set}}
\begin{center}
	\includegraphics[width=8cm]{skillsRoss.png}
\end{center}

%========INTERESTS==========
{\fontsize{10}{8} Interest}\\
{\scriptsize Tennis, Sailing, Kayaking, Swimming, Hiking, Rugby, Chess, Go, Poker, Maze design, Crossword, Beekeeping, Watching star constellation, birds flocking, fish schooling, animal herding and ant colony, Swimming, Golf, Sudoku, Magic Square, Billiards}\\

%========MANAGED EXPERIENCE==========
\section{Work Experience}


\begin{table}[!ht]
	% \footnotesize
	\scriptsize
	\begin{tabular}{|p{3.5cm}|p{2cm}|p{2.5cm}|}
		\hline
		DESIGNATION \par ORGANIZATION & GEO LOCATION & YEAR \\ \hline
		
		Consultant IT/ICT \par S.F. Ahmed \& Co. & Bangladesh & Winter 2010 - Spring 2023\\ \hline
		
		Chief Global Operation Executive \par QUEST Consultancy & Bangladesh & Sep 2016 - Sep 2023\\ \hline
		
		Ambassador, Fedora project \par Open source community project under Red hat & Canada Region & Fall 2005 - Current\\ \hline
		
		DevOP ( full stack )  \par Java Enterprise Editions(ERP, SAP, Cloud Computing, WebApp, MobileApp, Microservice)  \par Contractual & Bangladesh - Canada & June 2003 - Current\\ \hline
		
		Mentor Entrepreneur \& Business Developer  \par SME \& NGO & Bangladesh & January 2009 - January 2023\\ \hline
		
		Author \par Technological Fiction \par Engineering Magazine, ECA, Concordia University & Canada & Fall 2003 - Current\\ \hline
		
		Technical \& Review Writer \par Contractual  \par Open contract & Bangladesh & August 2011 - September 2020\\ \hline
		
		Creative Writer \par Ads Agency \& Media Houses \par Contractual & Bangladesh & Summer 2006 - Current\\ \hline
		
		Consulting Analyst \par Data Science and Big Data \& statistical-economical-financial Analysis \par Contractual & Canada-Bangladesh & December 2011 - Current\\ \hline
		
		Faculty, Dept. of CSE \par Primeasia University & Bangladesh & Fall 2009 - Fall 2012\\ \hline
		
		Visiting Trainer [Funded by JICA]  \par Bangladesh Computer Council & Bangladesh & Summer 2010\\ \hline
		
		Organizer \par BASIS Soft Expo 2011 & Bangladesh & Winter 2011 \\ \hline
		
		%Organizer \par First convocation, Primeasia University & Bangladesh & Winter 2010 \\ \hline
		
		Technology, Lifestyle \& Glamour Writer  \par A media house, Dhaka & Bangladesh &  October 2016 - \par September 2020 \\ \hline
		
	\end{tabular}
\end{table}


\section{ Academic Details}
\begin{table}[!ht]
	%\footnotesize
	\scriptsize
	\begin{tabular}{|p{3cm}|p{2cm}|p{2.5cm}|}
		\hline
		DEGREE \\ SPECIALIZATION \\ YEAR & SCORES & INSTITUTE \par GEO LOCATION\\
		\hline
		
		B.Sc. in CSE \\ \textit{Specialization: Software Engineering} \\ \#2nd undergraduate \\ Fall 2018 - Fall 2020  & CGPA: 3.74 \par(out of 4.0) & IBAIS University, Bangladesh \\  \hline
		%&  \\
		B.Sc. in Computer Sci.\& Eng. \\ \textit{Specialization: System Software}\\ \#1st undergraduate  \\ Fall 2003 - Fall 2008 & CGPA: 3.00 \par(out of 4.0) &
		Concordia University, Canada \\  \hline
		%&  \\
		English as a Foreign Language  (ESL) \\
		Summer 2003 & Band Score: 8.5 \par(out of 10) &
		Acadia University, Canada\\ \hline
		%&  \\
		B.Sc. in Computer Sci.\\\textit{Major: Computer Science, Minor: Finance} \\
		Fall 2001 - Summer 2003 & CGPA: 3.23 \par(out of 4.0) &
		Independent University, Bangladesh \\ \hline
		%	&  \\
		HSC \\ \textit{Group: Science}\\ Rajshahi Board \\ 2000 &
		MARKS: 788 \par(out of 1000) &
		Cantt. Public School and College Rangpur, Bangladesh \\ \hline
		%&  \\
		SSC \\ \textit{Group: Science} \\ Rajshahi Board \\ 1998 &
		MARKS: 897 \par(out of 1000)&
		Rangpur Zilla School, Bangladesh\\ \hline
		
	\end{tabular}
\end{table}


% column break
\vfill\null
\columnbreak



%========KEY PROJECTS==========
\section{Key Projects}
\begin{table}[!ht]
	%\footnotesize
	\scriptsize
	\begin{tabular}{|p{3cm}|p{2cm}|p{2cm}|}
		\hline
		TITLE\par ORGANIZATION\par GEO LOCATION & EFFORT & ACHIEVED LEVEL\\
		\hline
		Digital Infrastructure Designer \par Enterprise resource planning ( ERP ) \par Primeasia University \par  Dhaka, Bangladesh & Estimated effort 30000 hours & CMMI level 3 \par PMMI level 4 \par ACCESS level 2\\	\hline
		
		iSalesEngine \& Analytic Developer  \par J2EE, J2SE, C++, Python, Oracle, Apache Tomcat, Responsive HTML5, CSS, LISP  \par Quest Consultancy \par Bangladesh & Estimated effort 42240 hours & CMMI level 4 \par PMMI level 3 \par ACCESS level 3 \\	\hline
		
		Data Analyst (Customer purchase behavior, sales \& supply chain)  \par contractual, a medicine company \par UK & Estimated effort 50000 hours & CMMI level 4 \par PMMI level 4 \par ACCESS level 3\\	\hline
		
		Technical lead \& Technical Documentation\par MoHFW, LGED, BTCL, USAID, World Bank  \par Bangladesh &Estimated effort  12063980 hours & CMMI level 5 \par PMMI level 5 \par ACCESS level 4\\	\hline
		
		Organization developer \& Adjunct Faculty \par A leading private university \par Bangladesh &Estimated effort 32000 hours & CMMI level 3 \par PMMI level 2\par ACCESS level 1\\	\hline
		
		Associate Consultant IT and ICT \par S.F. Ahmed \& Co. \par Dhaka, Bangladesh & Estimated effort 200000 hours & CMMI level 5 \par PMMI level 5\par ACCESS level 2 \\	\hline
		
		Artificially Learning Cogs In Automated Smart Home System \& Analytic\par Sponsored Data Science Project\par Bangladesh & Estimated effort 61320 hours & CMMI level 5 \par PMMI level 5\par ACCESS level 1 \\	\hline
		
		
	\end{tabular}
\end{table}

%========JOURNAL PAPER \& ARTICLE==========
\section{Journals \& Articles}
\begin{enumerate}
	\setlength{\itemsep}{0pt}
	\setlength{\parskip}{0pt}
	\item Mantissa Problem In Artificial Intelligent Computing
	\item Sigma Rate In Errors Finding In Object Oriented Programming \& Compiler
	\item Newton's Pendulum In Production Environment As A Project Management Paradigm
	\item Artificially Intelligent Learning Cogs In Client Or Sales or Production Behavior Analysis
	\item Preemptive Algorithm: Systemic Schedule in Workflow Development
	\item Artificially Intelligent System: Optimized Sensors, IoT and Machine Learning models integration 
\end{enumerate}


% column break
\vfill\null
\columnbreak

%=====%========COURSE & PROFICIENCY SCORE (UNDERGRADUATE & POST GRADUATE AND MBA)==========
\section{Course's Proficiency \& Lecture}

[Undergraduate, Postgraduate \& MBA]

\begin{center}
	\includegraphics[width=8cm]{itCantBeTaught.png}
\end{center}

%========ACHIEVEMENTS==========
\section{Achievements \& Awards}
\begin{enumerate}
	\setlength{\itemsep}{0pt}
	\setlength{\parskip}{0pt}
	\item Second Position in Internal ACM Programming Contest\par Independent University Bangladesh Fall 2002
	\item Student on Duty (SoD)\par Registrar's, Admission and Financial Aid Office, IUB, Bangladesh Spring 2002-Winter 2003
	\item Registrar's Office list \& Gold Medalist\par CGPA above 3.75 in consecutive academic semester, a renowned university in Bangladesh 2019
	\item Outstanding Contribution in Student Life and Career Development \par Concordia University, Canada 2006
	\item Top 100 Students \par SSC and HSC, Rajshahi Board, Bangladesh 1998 - 2000
	\item Divisional Football Player\par Rangpur, Rajshahi, Bangladesh 1997
	\item High performance, impact, influential key employee, A renowned gaming organization in Canada
	
\end{enumerate}


%=======REFERENCES==========
\section{Reference or Recommendation}
All national and international references or recommendations will be exposed upon request.


\end{document}
