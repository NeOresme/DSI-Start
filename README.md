# DSI-Start
A repository to serve as a guinea pig for training for the Galvanize DSI

Exercise in the 'About Python Programming' training section. Begin to experiment with your own 'version' of how code operates by being most explicit and detail oriented. Ex.
1. Make the bed

2. The program is complete when the pillow, sheet and blanket are properly oriented on the bed. 

3. 
def move_item(item_name, item_location, new_item_location)
       grab(item_name, item_location)
       set_down(item_name, new_item_location)

def bed_corners(bed_corner_1, bed_corner_2, bed_corner_3, bed_corner_4)
       shortest_distance(bed_corner_1-to-bed_corner_2, bed_corner_3-to-bed_corner_4)
       medium_distance(bed_corner_1-to-bed_corner_3, bed_corner_2-to-bed_corner_4)
       longest_distance(bed_corner_1-to-bed_corner_4, bed_corner_2-to-bed_corner_3)

def sheet_corners(sheet_corner_1, sheet_corner_2, sheet_corner_3, sheet_corner_4)
       shortest_distance(sheet_corner_1-to-sheet_corner_2, sheet_corner_3-to-sheet_corner_4) 
       medium_distance(sheet_corner_1-to-sheet_corner_3, sheet_corner_2-to-sheet_corner_4)
       longest_distance(sheet_corner_1-to-sheet_corner_4, sheet_corner_2-to-sheet_corner_3)

def blanket_corners(blanket_corner_1, blanket_corner_2, blanket_corner_3, blanket_corner_4)
       shortest_distance(blanket_corner_1-to-blanket_corner_2, blanket_corner_3-to-blanket_corner_4)
       medium_distance(blanket_corner_1-to-blanket_corner_3, blanket_corner_2-to-blanket_corner_4)
       longest_distance(blanket_corner_1-to-blanket_corner_4, blanket_corner_2-to-blanket_corner_3)
       
def affix_corners(reference_item, subject_item)
       corner(1:1)
       corner(2:2)
       corner(3:3)
       corner(4:4)
       
move_item('pillow', 'bed', 'chair')
affix_corners('bed_corners', 'sheet_corners')
affix_corners('bed_corners', 'blanket_corners')
move_item('pillow', 'chair', 'bed')

Reasons for using comments
Send a message to someone reading your code
Exclude some code snippet from running
Provide function documentation
Leave TODO: statements in your code, for later development

to exclude/include a comment: cntrl+/

Basic operators: +-, */, **, //, %, ==
Scalar objects: str, int, float, bool
logic operators (and, or, not): <, >, <=, >=, ==, !=
And operation (both all must be true to be true)
Or operation (one must be true to be true)
Bitwise: and, or, not: &, |, ~      [exclusive or: ^]
RANKING (Highest to lowest: ~, &, ^, |, not, and, or)
Control Flow: if, elif, else
Use in comparision operators (5 != 3 --> True)

Standars for Lists:
-recognize a list 
-understand a collection
-generate a series of numbers using range 
-access values in a list 
-determine if something is a memeber of a list 
-slice a specific portion of a list
-recognize a nested list 
--a list is : ordered, mutable, accessible by index, dynamic, nested to arbitrary depth.
--print(range(start, stop, step)
list(range(100))
