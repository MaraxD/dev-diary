in TouchDesigner, create:
- a CHOP with one channel
    - can be a constant, an LFO, whatever (in this case they are the coordinates of the cursor)
- a table DAT with 2 cells
- a CHOP Execute python script for
    - negative CHOP values are sent to one cell
    - positive CHOP values are sent to the other
