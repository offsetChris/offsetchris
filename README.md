# offsetchris
offsetchris.com code base. More information to come soon as this is built out.

##Sass structure

**basics**
Typography, basic page layout set up, icons etc

**bits**
Small independent ui elements that are self contained and do not contain any other ui elements. each "bit" can not be separated out into smaller pieces it is a self contained unit. a basic building block.

**pieces**
A small group of bits that come together into a ui component. each piece can be reused in other areas of the ui and can be modified with simple modifier classes. 

**whole**
These are overall layouts and template modifiers that change the look of smaller pieces within. 

*Naming References: *
*The basic convention of my sass structure is inspired by Atomic Design and BEM methodologies utilizing naming from a Minneapolis art installation by Lawrence Weiner, 2005 Walker Art Center. *