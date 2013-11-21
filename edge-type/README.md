Working with Edge Type Sample Data
==================================

Frame1: Filters and Fills in Data
--------------------------------
This example produces results on the playground. The result is a filtering for elements with @type of wp:Interaction. The result also has fills in the data for some gpml:GraphRefs, but not all. For example, the gpml:GraphRef for "gpmlFolder:edge-type-test.gpml#substrate2ToProduct2PointA" is not filled in, although it was filled in earlier in the result.

Frame2: Trying to filter subelements 
------------------------------------
Filtering works at the @type of wp:Interaction level, but it does nothing for ex:point: { @type: ex:port } level.

Frame3: Filtering to only show Reactions 
----------------------------------------
Successfully filters to only show elements of @type gpml:Reactions.

New Context, Compacted: Don't see any significant difference
------------------------------------------------------------

The only apparent differences are in json stylistic formatting.
