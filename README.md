# MGK_booklet

MGK_booklet is a LaTeX template for conference booklets. It was created as a 
LaTeX only template from the [AMCOS_booklet](https://github.com/maximelucas/AMCOS\_booklet),
by stripping the python scripts and using LaTeX environments to specify abstracts
for talks and posters.


### Features

- Templates for the following sections: About, Timetable, List of Abstracts (for talks), List of Abstracts (for posters), List of Participants, Useful Information, Partner Institutions and Sponsors.

- LaTeX environments to display the timetable, and a (long and short version of) list of abstracts, of posters, and of participants.

- Automated creation of a short or long version of the booklet via a one-word option in the template.

- Easily customisable in terms of layout, colours, and content.

## Usage 

### General

Simply use the provided LaTeX environments to create the abstracts and place them
in the abstracts folder. You can now input them in the `main.tex` file as shown 
in the example `main.tex` file.

### Directory structure

```
-- main.tex
-- other .tex files
-- abstracts
    |-- figures/
        |-- image files for abstracts
-- images/
    |-- image files for booklet (logos etc.)
```

### How to cite

Please acknowledge any use of this template and explicitly link to this page with:  
`The open-source LaTeX template, MGK_booklet, used to generate this booklet is available at https://github.com/jqfeld/MGK\_booklet`  


### Credits 

This template is a modified version of [AMCOS_booklet](https://github.com/maximelucas/AMCOS\_booklet).
All modifications were done by Patrick Preissing and Jan Kuhfeld.
The original template was developped by Maxime Lucas and Pau Clusella.  

