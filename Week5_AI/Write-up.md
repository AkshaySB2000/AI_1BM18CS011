<b><h1>Vacuum Cleaner Agent:</h1></b><br>

<b><i>Problem Statement:</i></b><br><br>
<ul>
<li>Given M x N grid(floor) create an agent that moves around the grid until the entire grid is clean.</li> 
<li>The agent starts at the first location i.e, (0,0) and moves across the grid in this case.</li>
<li>The agent can move left, right, up and down. Move the agent anyway you see fit until the floor is clean</li>
</ul><br>

<b><i>Floor Representation:</i></b><br><br>
Floor is representated as follows:<br>
floor = <br>[[1, 0, 0, 0], <br>[0, 1, 0, 1],<br> [1, 0, 1, 1]]<BR>
'1' represents dirty and '0' represents clean<br>

<b><i>Functions used:</i></b><br>
<ul>
<li>clean(floor) - To clean the cell i.e, replace '1' with '0'. Steps involved are:<br><br>
<ul>
<li>Check all cells in each row.</li>
<li>If the row index is even, check through the cells in right direction and clean them if dirty (change 1 to 0).</li>
<li>If the row index is odd, check through the cells in left direction and clean them if dirty (change 1 to 0)</li>
</ul></li><br>
<li>print_floor(floor) - Shows current position of the vaccum cleaner after every move it makes and the clean status of the cell (1 or 0).</li>
</ul>

