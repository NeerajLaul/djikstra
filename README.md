This code is designed to run on a Google coaboratory, as my computer is currently unavailable for heavy processing applications like this one.

All the import statements are present in the code, and the libraries and functions used are as follows:
1. Numpy - for mathematical operations.
2. Matplotlib.pyplot - For displaying results and visualisation
3. Open CV - For image processing, motly only for the map.
4. HeapQ - To handle the queue and the large amount of data being added and removed efficiently.
5. OS - For file operations.


HOW TO RUN:
Most effectively runs in google colaboratory, and can be run as is. To run in python, file mappings need to be changed in order to read file correctly from disk.
1. Open the file in google colaboratory or jupyter notebooks
2. Run the upper code block first (To generate the map canvas). This code is modular and can be modified to suit a variety of maps.
3. Run the main code block and input coordinated.
4. Since the visualisation tool being used is matplotlib, the axes are reversed, hence the input statements ask for ("Y and X") values instead of vice versa. This is important as it can change the outcome of the code.
5. Input the Y and X coordinate values of the start and end points in the input boxes and separate them with a space.
6. Let the code run for a few minutes, and you should see your path and explored nodes displayed in the output.

