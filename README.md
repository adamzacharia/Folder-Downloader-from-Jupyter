# Folder-Downloader-from-Jupyter
## Folder Zipper

This Python script allows you to zip a folder using the `zipfile` module in Python. It provides a simple function `zip_folder()` which takes the path of the folder to be zipped and the desired path for the resulting zip file. The script recursively zips all files and subfolders within the specified folder.

### Usage
1. Ensure you have Python installed on your system.
2. Modify the `folder_to_zip` variable with the path of the folder you want to zip.
3. Modify the `zip_file_path` variable with the desired path for the resulting zip file.
4. Run the script.

### Example
```python
# Define folder path and zip path
folder_to_zip = 'Adam Minor Project'
zip_file_path = 'Adam_Minor_Project.zip'

# Zip the folder
zip_folder(folder_to_zip, zip_file_path)
```

### Dependencies
- Python 3.x

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize the description to fit your needs or add any additional information you find relevant!
