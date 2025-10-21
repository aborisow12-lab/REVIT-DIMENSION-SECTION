
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
Z range: 24.6734 to 24.6734 (const=True)
SECTION mode: Dimension in XY plane, perpendicular = UP (Z)
Perpendicular direction: (0.0000, 0.0000, 1.0000)

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
Perpendicular direction: (0.000000000, 0.000000000, 1.000000000)
First edge (Seg 0) moved: True
Last edge (Seg 6) moved: False
Stacking ALL segments over first edge
Reference center: (-184.98,-53.66,24.52)
Seg 1 level 1: offset=(0.00,0.00,0.28) target=(-184.98,-53.66,24.80)
Seg 2 level 2: offset=(0.00,0.00,0.56) target=(-184.98,-53.66,25.08)
Seg 3 level 3: offset=(0.00,0.00,0.84) target=(-184.98,-53.66,25.36)
Seg 4 level 4: offset=(0.00,0.00,1.13) target=(-184.98,-53.66,25.64)
Seg 5 level 5: offset=(0.00,0.00,1.41) target=(-184.98,-53.66,25.93)
Seg 6 level 6: offset=(0.00,0.00,1.69) target=(-184.98,-53.66,26.21)
Copied position to Seg 0: (-184.98,-53.66,24.52)
Copied position to Seg 1: (-184.98,-53.66,24.80)
Copied position to Seg 2: (-184.98,-53.66,25.08)
Copied position to Seg 3: (-184.98,-53.66,25.36)
Copied position to Seg 4: (-184.98,-53.66,25.64)
Copied position to Seg 5: (-184.98,-53.66,25.93)
Copied position to Seg 6: (-184.98,-53.66,26.21)

=== Successfully placed 8 leaders ===
Cleaned up temporary TextNote type

============================================================
Successfully created 8 leaders across 1 dimensions
============================================================
