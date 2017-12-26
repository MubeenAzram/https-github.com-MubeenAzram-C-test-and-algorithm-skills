Given a Sudoku data structure with size NxN, N > 0 and √N == integer, write a method to validate if it has been filled out correctly. The data structure is a multi-dimensional Array, ie:

        int[][] goodSudoku1 = {
            new int[] {7,8,4,  1,5,9,  3,2,6},
            new int[] {5,3,9,  6,7,2,  8,4,1},
            new int[] {6,1,2,  4,3,8,  7,5,9},
            new int[] {9,2,8,  7,1,5,  4,6,3},
            new int[] {3,5,7,  8,4,6,  1,9,2},
            new int[] {4,6,1,  9,2,3,  5,8,7},
            new int[] {8,7,6,  3,9,4,  2,1,5},
            new int[] {2,4,3,  5,6,1,  9,7,8},
            new int[] {1,9,5,  2,8,7,  6,3,4}
        };
Rules for validation Data structure dimension: NxN where N > 0 and √N == integer Rows may only contain integers: 1..N (N included) Columns may only contain integers: 1..N (N included) ‘Little squares’ (3×3 in example above) may also only contain integers: 1..N (N included) Note that a file is included for this, download it here. Feel free to use it, it’s optional. The result must be a single file which contains at least the method that returns true or false, when given a jagged array of type integer. Points awarded for code elegance, usage of trends and modern frameworks. (i.e. LINQ) Extra points for usage of advanced frameworks and clever re-factorization. This test is mandatory.

It took less than 1 hour.
