This assignment focuses on finding the largest perimeter among several shapes represented by files. You will implement new methods in the PerimeterAssignmentRunner class to achieve this. The PerimeterAssignmentRunner class already includes a printFileNames method, which creates a DirectoryResource to select multiple files and iterates over them to print their names.

Goals:

1. Implement the getLargestPerimeterMultipleFiles method:
   - Create a DirectoryResource to select multiple files.
   - Iterate over each selected file.
   - Convert each file into a FileResource and calculate the perimeter of the shape.
   - Return the largest perimeter among all shapes in the selected files.

2. Implement the testPerimeterMultipleFiles method:
   - Call getLargestPerimeterMultipleFiles and print out the largest perimeter.
   - Select files when running this method.

3. Implement the getFileWithLargestPerimeter method:
   - Create a DirectoryResource to select files.
   - Return the name of the file with the largest perimeter.

4. Implement the testFileWithLargestPerimeter method:
   - Call getFileWithLargestPerimeter and print the name of the file with the largest perimeter.

Discussion:

1. For getLargestPerimeterMultipleFiles:
   - Create a DirectoryResource to select multiple files.
   - Iterate over each selected file.
   - Convert each file into a FileResource and calculate the perimeter of the shape.
   - Compare perimeters to find the largest one.
   - Return the largest perimeter.

2. For testPerimeterMultipleFiles:
   - Call getLargestPerimeterMultipleFiles and store the result.
   - Output the largest perimeter.
   - Ensure to call this method in the main method to see the output.

3. For getFileWithLargestPerimeter:
   - Initialize a File object with an empty value.
   - Iterate over each file in the directory.
   - Update the File object with the file containing the largest perimeter.
   - Return the name of the file.

4. For testFileWithLargestPerimeter:
   - Call getFileWithLargestPerimeter and store the result.
   - Output the name of the file with the largest perimeter.
   - Make sure to call this method in the main method to see the output.

Remember to call the appropriate methods in the main method to see the output of testPerimeterMultipleFiles and testFileWithLargestPerimeter.
