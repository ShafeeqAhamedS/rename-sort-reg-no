# Dataset Creation Assist Project

Use the given Jupyter Notebook File to kinda automate the process.

## Steps

1. Create a clone of the repository in your local machine
2. Create a folder named  `images` in the root directory
3. Add the dataset from Google Drive to that folder and run the Jupyter Notebook File
4. Follow the execution & complete the task

## Documentation

### Custom Functions

#### display_image(image):

Display an image using Matplotlib in a Jupyter Notebook cell.

```
Parameters:
  image: NumPy array representing the image.
```

#### rename_file(image_path):

Rename a file using a 12-digit register number.
```
Parameters:
    image_path: Path to the image file.
```

#### move_to_folder(image_path, folder_name):

Move a file to the specified folder.
```
Parameters:
    image_path: Path to the image file.
    folder_name: Path to the destination folder.
```

### Main Function

#### main(image_path):
Orchestrates the main functionality of the script.
Displays the image, allows rotation, renames the file, and moves it to the respective folder based on user input.
```
Parameters:
    image_path: Path to the image file.
```

#### Driver Code
Processing Images in Root Folder:

Iterates through all image files in the specified root folder (./images).
Calls the main() function for each image file.
Allows rotation, renaming, and moving files based on user input.
Displays a message when all images are processed.

### Display Renamed Images:

Displays all renamed images with titles indicating the college code, batch, department code, and register number.
Additional Functionality

#### display_image_with_title(image, title):
Displays an image with a title using Matplotlib in a Jupyter Notebook cell.
```
Parameters:
    image: NumPy array representing the image.
    title: Title to be displayed with the image.
```
## Summary

The provided script processes a collection of images in a specified root folder. It allows users to rotate images, rename them with a 12-digit register number, and move them to different folders based on user input. Renamed images are then displayed with titles indicating their various attributes.