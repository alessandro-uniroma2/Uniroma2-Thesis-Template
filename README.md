# *(Unofficial)* Uniroma2 Thesis LaTeX Template

This is a slightly modified version of La Trobe latex [template](https://www.overleaf.com/latex/templates/unofficial-la-trobe-university-template/zfbdwvyrxshz) based on the classicthesis thesis template by [André Miede](https://bitbucket.org/amiede/classicthesis).

I've made slight changes so that everything aligns with Uniroma2 Science department template. 

## Organization
`thesis.tex` is the root document and includes the individual chapters. The content of the chapters can be found under `text/`. It is pretty self-explanatory. Figures can be placed under `figures/` or wherever you like. Bibliography should be put into `library.bib`. If you have multiple and/or large tables I recommend creating a separate folder and individula files for them and importing them.

## Listings, Tables, Figures

Samples for adding Listings, Figures and Tables so that they are automatically added to the listings are in Chapter 2.

## Configuration
You should replace the configuration at the top of `thesis.tex` with your actual information. That's it!

```latex
    % Thesis and submission:
    \newcommand{\myTitle}{Your Title}
    \newcommand{\annoaccademico}{AA-AA+1}
    \newcommand{\mySubmissionYear}{YYYY}
    \newcommand{\mySubmissionMonth}{MM}
    \newcommand{\mySubmissionDay}{DD}
    
    % Regarding yourself:
    \newcommand{\myFirstName}{First Name}
    \newcommand{\myLastName}{Last Name}
    \newcommand{\myWebsite}{My Website}
    \newcommand{\myBirthYear}{1979}
    \newcommand{\myBirthMonth}{January}
    \newcommand{\myBirthDay}{01}
    \newcommand{\myBirthPlace}{Rome}
    
    % Primary supervisor:
    \newcommand{\myProfTitle}{Prof.}
    \newcommand{\myProfFirstName}{Maurizio}
    \newcommand{\myProfLastName}{Talamo}
    \newcommand{\myProfWebsite}{http://dii.uniroma2.it/membro_personale/talamo-maurizio/}
    
    % Co-supervisor:
    \newcommand{\myOtherProfTitle}{Prof.}
    \newcommand{\myOtherProfFirstName}{Y}
    \newcommand{\myOtherProfLastName}{Y}
    \newcommand{\myOtherProfWebsite}{https://didatticaweb.uniroma2.it/docenti/curriculum/Y}
    
    % Co-examiner:
    \newcommand{\myOpponentProfTitle}{Prof.}
    \newcommand{\myOpponentProfFirstName}{Z}
    \newcommand{\myOpponentProfLastName}{Z}
    \newcommand{\myOpponentProfWebsite}{https://didattica.uniroma2.it/docenti/curriculum_vitae/Z}
    
    % University related:
    \newcommand{\myDepartment}{Department of Computer Science and Information Technology}
    \newcommand{\myFaculty}{Mathematical, Physical and Natural Sciences}
    \newcommand{\mySchool}{- of Computer Science}
    \newcommand{\myUni}{Uniroma2 "Tor Vergata" University}

```

## Compilation

In Overleaf, you'll need to use LaTeX 2021 to make this compile properly.