
Starting script (SECTION version)...
============================================================
Using default settings
============================================================

============================================================
Processing 1 dimensions in SECTION view...
============================================================

============================================================
DIMENSION 1/1 (ID: 21252136)
============================================================
View scale: 1:24
Text size: 0.0078 feet
Found 9 segments
Seg 0: '2 3/4"' at X=-184.9825 Y=-53.3207 Z=25.1576 value=0.2265
Seg 1: '3"' at X=-184.9825 Y=-53.0801 Z=25.1576 value=0.2548
Seg 2: '3 5/8"' at X=-184.9825 Y=-52.8016 Z=25.1576 value=0.3021
Seg 3: '3 5/8"' at X=-184.9825 Y=-52.4996 Z=25.1576 value=0.3021
Seg 4: '3 5/8"' at X=-184.9825 Y=-52.1975 Z=25.1576 value=0.3021
Seg 5: '3 5/8"' at X=-184.9825 Y=-51.8954 Z=25.1576 value=0.3021
Seg 6: '3 5/8"' at X=-184.9825 Y=-51.5933 Z=25.1576 value=0.3021
Seg 7: '3 5/8"' at X=-184.9825 Y=-51.2912 Z=25.1576 value=0.3021
Seg 8: '3 5/8"' at X=-184.9825 Y=-50.9891 Z=25.1576 value=0.3021

Analyzing 9 segments...
Dimension direction: (0.0000, 1.0000, 0.0000)
Z range: 25.1576 to 25.1576 (const=True)
SECTION mode: Dimension in XY plane, perpendicular = UP (Z)
Perpendicular direction: (0.0000, 0.0000, 1.0000)

--- Analyzing segments with TextNotes (accurate) ---
TextNote size = 0.5677 x 0.3071
Seg 0: TextNote size = 0.5677 x 0.3071
TextNote size = 0.3071 x 0.2031
Seg 1: TextNote size = 0.3071 x 0.2031
TextNote size = 0.5677 x 0.3071
Seg 2: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 3: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 4: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 5: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 6: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 7: TextNote size = 0.5677 x 0.3071
TextNote size = 0.5677 x 0.3071
Seg 8: TextNote size = 0.5677 x 0.3071
Seg 0: '2 3/4"' width=0.5677 value=0.2265 ratio=251% -> PROBLEM
Seg 1: '3"' width=0.3071 value=0.2548 ratio=121% -> PROBLEM
Seg 2: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 3: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 4: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 5: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 6: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 7: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Seg 8: '3 5/8"' width=0.5677 value=0.3021 ratio=188% -> PROBLEM
Adjacent overlap detected: Seg 0 <-> Seg 1
Adjacent overlap detected: Seg 1 <-> Seg 2
Adjacent overlap detected: Seg 2 <-> Seg 3
Adjacent overlap detected: Seg 3 <-> Seg 4
Adjacent overlap detected: Seg 4 <-> Seg 5
Adjacent overlap detected: Seg 5 <-> Seg 6
Adjacent overlap detected: Seg 6 <-> Seg 7
Adjacent overlap detected: Seg 7 <-> Seg 8
*** Problem segments: [0, 1, 2, 3, 4, 5, 6, 7, 8] ***
*** Clean segments: [] ***

Calculated offsets:
Vertical (perpendicular): 0.2813
Horizontal (parallel): 0.3750

--- Processing edge segments ---
Moved FIRST edge Seg 0 (offset: 0.6245, text_width: 0.5677)
Moved LAST edge Seg 8 (offset: 0.3750, ratio: 188%)
Remaining problems: [1, 2, 3, 4, 5, 6, 7]

--- Using ALL PROBLEMS strategy ---
Processing 9 problem segments (all problems mode)
Dimension direction: (0.000000000, 1.000000000, 0.000000000)
Perpendicular direction: (0.000000000, 0.000000000, 1.000000000)
First edge (Seg 0) moved: True
Last edge (Seg 8) moved: True
Lifted Seg 0 above dimension line:
From: (-184.98,-53.66,25.00)
To: (-184.98,-53.66,25.29)
Split: 3 to left, 4 to right
Left group: [1, 2, 3]
Right group: [4, 5, 6, 7]
Stacking LEFT group over Seg 0
Reference: (-184.98,-53.66,25.29)
Seg 1 level 1: target=(-184.98,-53.66,25.57)
Seg 2 level 2: target=(-184.98,-53.66,25.85)
Seg 3 level 3: target=(-184.98,-53.66,26.13)
Stacking RIGHT group over midpoint
Anchor: (-184.98,-51.74,25.44)
Seg 4 level 1: target=(-184.98,-51.74,25.72)
Seg 5 level 2: target=(-184.98,-51.74,26.00)
Seg 6 level 3: target=(-184.98,-51.74,26.28)
Seg 7 level 4: target=(-184.98,-51.74,26.56)
Copied position to Seg 0: (-184.98,-53.66,25.29)
Copied position to Seg 1: (-184.98,-53.66,25.57)
Copied position to Seg 2: (-184.98,-53.66,25.85)
Copied position to Seg 3: (-184.98,-53.66,26.13)
Copied position to Seg 4: (-184.98,-51.74,25.72)
Copied position to Seg 5: (-184.98,-51.74,26.00)
Copied position to Seg 6: (-184.98,-51.74,26.28)
Copied position to Seg 7: (-184.98,-51.74,26.56)
Copied position to Seg 8: (-184.98,-50.33,25.00)

=== Successfully placed 11 leaders ===
Cleaned up temporary TextNote type

============================================================
Successfully created 11 leaders across 1 dimensions
============================================================
