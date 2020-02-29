# Waterloo Rocketry Operations Procedures

This is the repository for storing all operations procedures (checklists and
instructions for performing rocket engine assemblies, engine tests, and rocket
launches) used by Waterloo Rocketry. All operations procedures (ops) are
written in LaTeX for consistent and aesthetic appearance.

## Instructions for Writing New Ops

After cloning this repository, you should be able to compile any of the `.tex`
files at the root level using the command:

`pdflatex ops_file.tex`

If this command fails, please check your LaTeX install. You can download LaTeX
[here](https://www.latex-project.org/get/).

Most new ops start with the template file `standard_template.tex`. It's highly
recommended that you copy this file into a new tex file and make edits there,
instead of starting from an empty file. This template follows the recommended
ops structure, and includes examples of how to use the features of LaTeX (both
the default ones, and the custom features written by our team).

## Recommended Ops Structure/Guidelines

These are the recommended sections to include in your ops document, and the
information to include in them.

1. Titlepage. Includes:
   - The team logo, for sweet sweet branding
   - The title of the document (like "Kismet Hybrid Rocket Engine Static Fire
     3" or "UXO Hybrid Rocket 2018 IREC")
   - A subtitle line
   - The date that the document was compiled on. This date allows us to make
     changes to a document and figure out which of two versions is more
recent/up to date.
   
2. Background Section
   
   If the ops file contains multiple procedures (for example, the setup
procedures and the test procedures), this section should declare all of the
procedures. This section should also contain a subsection for all of the
personnel involved in the procedure, and what the position names and roles are.
Please use position names (like "Primary Fill Operator") instead of the
person's name, since the person running the test may change.
   
   There should also be a sign-off section, in which each of the test personnel
have a line to sign on to declare that they've read the procedure they're about
to be carrying out. It's very easy for bugs to creep into checklists, and we
want to catch those bugs as early as possible (i.e., before we start running
the procedure).
   
3. The Checklists

   All checklists start with a `\subsection` title (Like "Cold Flow Test
Procedure" or "Prior to Start") followed by a list of instructions to complete,
in order, to carry out the procedure.
   
   All checklist items should start with the name of the person who is supposed
to carry out that instruction. This reduces confusion and allows us to ensure
that all personnel are safe during the procedure. Since people will be reading
these checklists individually before the test/launch/assembly, having the name
of the person in the procedure will keep everyone on the same page.
   
   For most tests, every item on a checklist is going to be read out over the
radio. Please keep the items clear and concise.
   
   If some instructions are conditional (for example, "if you see a leak, do
the following steps"), those instructions should be indented from the top level
to make that clear.
