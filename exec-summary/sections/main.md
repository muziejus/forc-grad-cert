The growth of interdisciplinary, cutting-edge research that relies on research computing (RC), coupled with the increasingly computationally driven job market for doctoral students, presents an opportunity for Columbia University to produce PhDs who are ready and able to meet these needs, regardless of their career track. In offering a graduate certificate in research computing to doctoral students across the university, Columbia will aid their students as they prepare for distinguished careers. Additionally, the certification process invites participating PhD students to join the interdisciplinary community of scholars at Columbia, enabling new opportunities for distinctive research and collaboration.

## Curriculum

Building on the popularity of the Foundations for Research Computing (FRC) two-day sessions, we propose a certification process where all applicants will enroll in “Introduction to RC” before branching off to continue their coursework with approved courses closer to their fields of study. Successfully completing “Introduction to RC” and the required number of approved RC courses will earn applicants a Certificate in Research Computing.

“Introduction to RC” introduces data structures, analysis, and management in RC, attuned to the social and environmental contexts of RC. Students of the course will learn to describe and extend the qualities of exceptional RC, interpret and critique computational research, and design and develop a computationally intensive doctoral research project. The course is intentionally disciplinarily agnostic, yet designed by educators in different fields, ensuring its position as a vetted option to meet computational prerequisites as well.

Because of the nature of “Introduction to RC” as a known quantity, developed within Columbia, departments could further require it of incoming PhD students, thereby freeing up class time to focus on domain-specific applications of RC.

\def\chilllist#1{
\list{--}{\topsep=2pt\itemsep=0pt\parsep=0pt\parskip=0pt\labelwidth=8pt\leftmargin=8pt\itemindent=0pt\labelsep=2pt}
#1
\endlist
}

\begin{center}
\vskip 12pt
\usetikzlibrary {positioning}
\begin{tikzpicture}[
    level distance=48pt,
    sibling distance=2.25in,
    edge from parent path=
    {(\tikzparentnode.south) .. controls +(0, -1) and +(0,1)
                             .. (\tikzchildnode.north)},
    intro/.style={
      anchor=south,
      inner sep=12pt,
      rectangle,
      minimum width=6in,
      rounded corners=2pt,
      very thick,
      draw=black,
    },
    branch/.style={
      anchor=north,
      align=left,
      inner sep=8pt,
      rectangle,
      minimum width=2in,
      rounded corners=2pt,
      very thick,
      draw=black!50,
    }
]
  \node (intro) [intro] {
    \begin{tabular}{c}
      \LARGE \textsc{Introduction to Research Computing}
    \end{tabular}
  }
    child {node (textual) [branch] {%
    \begin{minipage}{1.75in}
    \flushleft \Large \textsc{Text Analysis}\\
        \normalsize Textual data analysis and natural language processing.\\[12pt] Sample courses:\chilllist{%
            \item Natural Language Processing (COMS 4705)
            \item Exploratory Data Analysis (STAT 5702)
            \item Literature in the Age of AI (CLEN 4728)}\end{minipage}
        }}
    child {node (numerical) [branch] {%
    \begin{minipage}{1.75in}
    \flushleft \Large \textsc{Data Analysis}\\
        \normalsize Numerical and statistical data analysis.\\[12pt] Sample courses:\chilllist{%
            \item Computational Statistics (STAT 6104)
            \item Bayesian Statistics (STAT 5224)
            \item Exploratory Data Analysis (STAT 5702)}\end{minipage}
        }}   
    child {node (datasci) [branch] {%
    \begin{minipage}{1.75in}
    \flushleft \Large \textsc{Data Science}\\
        \normalsize Machine learning and modeling.\\[12pt] Sample courses:\chilllist{%
            \item Analysis of Algorithms (COMS 4231)
            \item Machine Learning (COMS 4771)
            \item Bayesian Models for Machine Learning (EECS 6720)}\end{minipage}
        }
    };   
\end{tikzpicture}
\vskip 12pt
\end{center}

This sketch is further informed by the various, already-existing programs at Columbia that meet a similar need, but either limit the program to masters students (MS in Data Journalism, Quantitative Methods in the Social Science Master's Program) or to PhD students in specific schools (PhD Specialization in Data Science). Our goal is to work across the Columbia research community to provide opportunities for all PhD students to learn the fundamentals of RC. Additionally, we anticipate that Library- and FRC-provided workshops will supplement the needs of the applicants as they progress through the certification process.

## Administration

Our hope is that this certificate would be overseen by an advisory board appointed by the Research Computing Executive Committee, led by faculty both in the Graduate School of Arts and Sciences and the Fu Foundation School of Engineering and Applied Science. We further hope that the advisory board would leverage the close working relationships between CUIT, the Office of Research Initiatives, and the Libraries to provide support.
