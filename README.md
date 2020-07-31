# text_editor
Basic command line text editor written in C.

Completed as part of the coursework for Foundations of Algorithms.

    Commands:
        
- .b – break the current line, so that the next input token starts at the beginning of the next line;
- .p – leave a blank line and start a new paragraph without altering the margins, with the next inputtoken starting the new paragraph;
- .l nn – alter the left margin from its current value (default initial value of 4) to the new value nn, and start a new paragraph;
- .w nn – alter the width of each line from its current value (default initial value of 50) to the new value nn, and start a new paragraph.
- .c – take the remaining contents of this line and center them within the current output width. If the remaining contents cannot fit within the current output width, then it should be placed so that it starts at the left margin and overflows beyond the current width. When there is an odd number of spaces to be assigned, the rounded-down half should be at the beginning of the line, and the rounded-up half at the end of the line.
- .h nn – take the remainder of the contents of this line and use them as a section heading at the level indicated by nn. The Section/subsection/subsubsection number should be printed, and then the complete heading on a single line, even if it is longer that the current width. Headings at level nn reset the numbering for headings level nn + 1, nn + 2, and so on; and (to avoid non-computing people from being confused) all headings start their counting from one. At most five levels of headings may occur, counting from nn = 1 (the top-level heading) to nn = 5. All headings are always preceded and followed by a paragraph boundary, and level-1 headings are also preceded by a full-width line of “-” characters.
