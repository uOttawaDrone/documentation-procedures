# Template for R&D Reports
These are the guidelines to follow when proposing new designs or studies.
> The main focus is on the take-away and conclusion of a report/study.
### Max of three active designs at any time.
### File naming convention

Use the format: _report_YYMMDD_part_studytype#.md_ 

> Where YYMMDD is the year, month and date.   
> Part is the name of the part looked at, studytype is a descriptive name for the study and # its iteration. 

* _report_200208_frame_armDrag4_.md represents November 18, 2019
### Template

> Replace things with % around them.     
> Anything without a * infront of it can be from a sentence to a paragraph long.

```
   # Report %Part studytype and iteration% - %DATE YYYY/MM/DD%
    
    ** Authors:** %Your Name1%, %Your Name2%, %Your Name3%
   # TLDR
   %Include the important points here%
   # Prep
   
   ## Objective
   
   %Write a sentence or two about the objective%  
   %Toss in a hypothesis if its really uncertain whats gonna happen%
   
   ## Study
   %Detail the logic/science behind this improvement%
   %Include a summary of any papers you have read or are citing%
   %Include the results from a SW flow or structural simulation%
   %If none of these apply explain why we'd want to this%
   Note: Its not cause there is a SW sim that the part is feasible. There are manufacturing constraints.
   
   ## Method
   %Detail any print methods or steps that need to be taken to obtain the sample/needed parts for testing%
   %Highlight crucial steps or important details. Also include things that need to be tested here.%
   
   # Test
   
   ## Tests Ran
   %Test 1%:
   * %What was tested%
   * %In what way was it testing the part%   
   %Test 2%:
    
    ## Results
    %Compare qualitative data to a control group (can be as simple as weight)%
    %Include any qualitative observations%
    
    ## Discussion 
    %Talk about results, was this an improvement in some way, make sure to include drawbacks even if small%
    %Focus on manufacturing and practicality aspects too, not only performance%
    %Other Take away from design%
     
    ## Figures(Rare)
    %Include a link to any tables or graphs%
    
    ## Pictures
    %Include pictures from the lab and from SW sim and CAD models%
    
    ### %Some relevant image title%
    
    ![%Image alt text%](%URL TO IMG (UPLOAD YOUR IMAGES TO GIT AND THEN LINK THEM)% "%Some title%")
    
    ### Source
    [Link to part](URL to GRABCAD workbench)    
    ### Citations
    %ASME or APA?%
```
    
