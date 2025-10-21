
Starting script (SECTION version)...
============================================================
Using default settings
============================================================

============================================================
Processing 1 dimensions in SECTION view...
============================================================

============================================================
DIMENSION 1/1 (ID: 21229367)
============================================================
View scale: 1:24
Text size: 0.0078 feet
Found 7 segments
Seg 0: '2 3/4"' at X=-184.9825 Y=-53.3207 Z=24.6734 value=0.2265
Seg 1: '6 5/8"' at X=-184.9825 Y=-52.9290 Z=24.6734 value=0.5569
Seg 2: '3 5/8"' at X=-184.9825 Y=-52.4996 Z=24.6734 value=0.3021
Seg 3: '3 5/8"' at X=-184.9825 Y=-52.1975 Z=24.6734 value=0.3021
Seg 4: '10 7/8"' at X=-184.9825 Y=-51.5933 Z=24.6734 value=0.9063
Seg 5: '3 5/8"' at X=-184.9825 Y=-50.9891 Z=24.6734 value=0.3021
Seg 6: '11 5/8"' at X=-184.9825 Y=-50.3558 Z=24.6734 value=0.9645

Analyzing 7 segments...
Dimension direction: (0.0000, 1.0000, 0.0000)
Perpendicular direction: (-1.0000, 0.0000, 0.0000)

--- Analyzing segments with TextNotes (accurate) ---
TextNote size = 0.5677 x 0.3071
Seg 0: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 1: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 2: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 3: TextNote size = 0.5677 x 0.3071
TextNote size = 0.6874 x 0.3071
Seg 4: TextNote size = 0.6874 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 5: TextNote size = 0.5677 x 0.3071
TextNote size = 0.6874 x 0.3071
Seg 6: TextNote size = 0.6874 x 0.3071
Seg 0: '2 3/4"' width=0.5677 value=0.2265 ratio=251% -> PROBLEM
Seg 1: '6 5/8"' width=0.5677 value=0.5569 ratio=102% -> PROBLEM
Seg 2: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 3: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 4: '10 7/8"' width=0.6874 value=0.9063 ratio=76% -> PROBLEM
Seg 5: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 6: '11 5/8"' width=0.6874 value=0.9645 ratio=71% -> PROBLEM
Adjacent overlap detected: Seg 0 <-> Seg 1
Adjacent overlap detected: Seg 1 <-> Seg 2
Adjacent overlap detected: Seg 2 <-> Seg 3
Adjacent overlap detected: Seg 3 <-> Seg 4
Adjacent overlap detected: Seg 4 <-> Seg 5
*** Problem segments: [0, 1, 2, 3, 4, 5, 6] ***
*** Clean segments: [] ***

Calculated offsets:
Vertical (perpendicular): 0.2813
Horizontal (parallel): 0.3750

--- Processing edge segments ---
Moved FIRST edge Seg 0 (offset: 0.6245, text_width: 0.5677)
LAST edge Seg 6 fits well (ratio 71%), not moving
Remaining problems: [1, 2, 3, 4, 5, 6]

--- Using ALL PROBLEMS strategy ---
Processing 7 problem segments (all problems mode)
Dimension direction: (0.000000000, 1.000000000, 0.000000000)
Perpendicular direction: (-1.000000000, 0.000000000, 0.000000000)
Split: 3 in group 1, 4 in group 2
Cleaned up temporary TextNote type

============================================================
ERROR!
============================================================
Traceback (most recent call last):
File "C:\Users\andriy.b\AppData\Roaming\pyRevit\Extensions\ABScripts.extension\MyTools.tab\Dimensions.panel\MoveDim-S.pushbutton\script.py", line 1587, in main
count = create_leaders_for_dimension(d, av)
File "C:\Users\andriy.b\AppData\Roaming\pyRevit\Extensions\ABScripts.extension\MyTools.tab\Dimensions.panel\MoveDim-S.pushbutton\script.py", line 1521, in create_leaders_for_dimension
success_count += process_all_problems_section(
File "C:\Users\andriy.b\AppData\Roaming\pyRevit\Extensions\ABScripts.extension\MyTools.tab\Dimensions.panel\MoveDim-S.pushbutton\script.py", line 967, in process_all_problems_section
ref_center = get_textnote_center_bottom(first_tn, view)
NameError: global name 'get_textnote_center_bottom' is not defined
