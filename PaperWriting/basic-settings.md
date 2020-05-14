### Some basic settings with Latex

#### Line
- `\linespread{1.5}`  line spacing 

#### paragraph 
- `\setlength{\parskip}{0.5\baselineskip}`  paragraph spacing
- indent (using package **indentfirst**)
   - `\setlength\parindent{2em}`  first line indent
   - ```
     \noindent
     \hangafter=1
     \setlength{\hangindent}{2em}
     ``` 
     add this in front of the paragraph which needs hanging indent
