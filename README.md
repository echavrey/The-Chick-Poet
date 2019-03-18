# The Chick Poet
 
A poetry generator, using Lisp (specifically the dialect Scheme, with the flavor Chicken). 

The documentation its of the PDF file "Pollito Poeta - Chavarria Eduardo", but in spanish. 
 
## Motivation
 
Passing the "Programming Languages" course on the first semester of the 2015.

## Functionality

This program, at first defines a dictionary of words called "y" (of Ohhh God Why!?). 

Everyword has the next structure (based on BNF Grammatic): 

    (TheKindOfWord (Word) )
    
    The Kind of Word, specifies if the word its a verb, an adverb, and adjective, a noun, a pronoun, etc. 
    
    Then the word its separated by its syllables (ex) *(am) (ple) , with an * on the accent. 

Then a lot of functions are created to take different kind of words, on different accent positions.

After that, the function "crearVersoEstructura" uses a randomness to select an structure for a sentence.

All the possible structures has examples to verify its correctness. 



## Usage
    1) Having Chicken Scheme installed. 

    2) Generate a copy of the file(egg) "Pollito Poeta - Chavarria Eduardo.egg", on the installation path. Usually C:\Program Files\Chicken Scheme\bin. 

    3) Open csi.exe

    4) Enter: load (load “Pollito Poeta - Chavarria Eduardo.egg”)

    5) Enjoy. 


## Contributors
 
 * [Eduardo Chavarría Rey](https://github.com/echavrey/) (Project Manager, Product Owner, Account Manager y Developer)