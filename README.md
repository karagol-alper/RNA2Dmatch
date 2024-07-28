# RNA2Dmatch

The alignStructures() function retrieves user input, validates it, and calls the alignment algorithm. The needlemanWunsch() implements the Needleman-Wunsch algorithm for global sequence alignment [1]. By doing this the codes incomporates a scoring system for matches, mismatches, gaps, and a traceback procedure to reconstruct the optimal alignment. Then, displayAlignment() formats and displays the alignment results, including: sequence position numbering and line-by-line output for readability.


# Please cite:
1)	Needleman, S. B., & Wunsch, C. D. (1970). A general method applicable to the search for similarities in the amino acid sequence of two proteins. Journal of molecular biology, 48(3), 443-453.
