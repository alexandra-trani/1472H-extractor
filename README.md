# 1472H-extractor
Extract text from 1472H with ease! 

As it stands, the extractor file pulls all the section headers, sections, and numeric identification from Chapter 5 of 1472H.
Tables and figures are all identified as 5.999.

## CSV Columns Extracted
Tag = Numerical reference to the chapter.section instance of the standard
Name = Name of the standard
Definition = if a definition exists, this is the definition	of the standard
MIL-STD	= Name of the MIL-STD document from which these standards are derrived.
ID = Unique identifier or primary key built by combining the MIL-STD and the tag 

## Future Work
I am in the process of converting this into a quick python function for easy calling at a later date. 
