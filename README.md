# latex_tools

This is a toolbox for paper writting using Latex. Tools inlcude:

addbib [Keyword1] [Keyword2] ... [RefFile]
	Search citation keys [KeywordN] in a bibtex library and print the full citation information into [RefFile]. Print on screen if no [RefFile] is specified.

gridfig [M] [N] [FigList] [OutputFig] [Aspect ratio (Optional)]
	Merge several figures in one in a MxN matrix.
	M: # of columns
	N: # of rows
	FigList: a txt file containing the list of figures, should be in the left-to-right, top-to-bottom order to be placed in the M by N grid
	OutputFig: filename of the output figure (do not include filename extension, .pdf will be added automatically)
	Aspect ratio: optional, the aspect ratio of each subfigure (ratio of width to height), the original aspect ratio is kept if not set 
