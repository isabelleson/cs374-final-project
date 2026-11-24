# Project Proposal:
Direction B: Music Path
We wish to create a language that can at least express the chromatic scale of the treble clef, and time durations using whole notes, half notes, quarter notes, eighth notes, and sixteenth notes, as well as their corresponding rests, and measures (which will be used to denote end of file). 
As a stretch goal in order, we would like to implement bass clef (altos will have to transpose), dynamics, articulation, key signature, time signature, repeats and codas, ledger lines, audio plugin, triplets. 

Feature: Check notes + rest add up to given time signature (4/4) in a measure. So four quarter notes should be true, five quarter notes should not. 

## Proposed steps: 
1) BNF Grammar
2) Decide how to get the terminal in the code
3) Most likely representing music with text
4) Build a lexer
5) Build a parser

## Design Scorecard: 
**Readability**: can a reader who did not write the code follow it quickly?

**Writability**: can an author produce correct code quickly?

**Reliability**: how well does the language keep a program from doing the wrong thing without anyone noticing?

**Implementation cost**: Must be done by Dec 14th

## Team Charter: 
**Role Rotation Plan**: Coordinator, Builder, Evaluator, Scribe
We will rotate Coordinator, Builder, and Evaluator by sprint, ensuring that each person gets each role at least once. We will divide the Scribe role among us so everyone documents their own code and logs their decisions.

**External Communication**:  We will communicate via text for most, if not all, external communication. We will strive to answer each other within 24 hours unless communicated reasons provided such as illness, car accident, or other life-threatening event. 

**Preparation Norms**: As we are not meeting in class, we will instead outline preparation norms for meetings. Everyone must have a charged laptop (or charger), must have completed agreed-upon tasks before the meeting, or communicated issues beforehand. Roles should be assigned during meetings, so that everyone is aware of what is expected of them.

**Disagreement Resolution**: For technical disagreements, we will discuss pros and cons, and if an agreement cannot be reached, put it to a vote. In the case of a tie, the Coordinator will act as a tie-breaker. In case of personal disagreements we will all be adults and calmly discuss our issues, taking breaks as needed. If escalation is needed we will find a third party to help navigate the situation (most likely Dr. Mongan). 
