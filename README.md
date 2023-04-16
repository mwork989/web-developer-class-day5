

position: static;- The element is positioned according to the normal flow of the document.  This is Default value , top, right, bottom,left z-index
position: relative; Initally the element  is positioned according to the normal flow of the document, and then offset relative to itself based on the values of top, right, bottom, and left.

position: absolute; Poitionining will be based on view port 
The element is removed from the normal document flow, and no space is created for the element in the page layout. 

position: fixed; The element is removed from the normal document flow, and no space is created for the element in the page layout.
position: sticky; The element is positioned according to the normal flow of the document, and then offset relative to its nearest scrolling ancestor and containing block (nearest block-level ancestor),

/* Global values */
position: inherit; either mention or not mention based on css property to be inhertied
position: initial; static,realtive
position: revert; to override the parent css values
position: revert-layer; 
position: unset;to override the parent css values