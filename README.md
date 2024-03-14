
# BizCardX-Extracting-business-card-data-with-OCR

- This user friendly streamlit application aims to extract relevant information from the uploaded business cards using easyOCR in python and extracted information will be displayed in the application's graphical user interface (GUI).User will be able to save the data and later on  update the saved information and delete the data from the application.


## Technologies Used
- Python
- EasyOCR
- MySQL
- Streamlit (UI)
## User Guide
### Steps:
 *Step 1*: There are two menu options - 'Upload Card' and 'View & Modify data' . Select 'Upload Card' to upload the business card from the device.

*Step 2*: You will get a preview of extracted information in an image and table format . Click on ' Upload to database' to upload the data to database.

*Step 3*: You can update any details in the 'View & Modify Data' section. Under 'Update Data' check the details , edit it and click on 'Update details' . Click 'View Data' to view the updated information.

*Step 4*: Under 'Delete Data' , select any card you want to delete and confirm to delete the card details from the database. 

## Developer Guide
1. **Install the required packages**: Python, Streamlit,easyOCR, and a database management system like SQLite or MySQL.
2. **Design the user interface**: Create a simple and intuitive user interface using Streamlit that guides users through the process of uploading the business card image and extracting its information. 
3. **Implement the image processing and OCR**: Use easyOCR to extract the relevant information from the uploaded business card image. You can use image processing techniques like resizing, cropping, and thresholding to enhance the image quality before passing it to the OCR engine.
4. **Display the extracted information**: Once the information has been extracted,display it in a clean and organized manner in the Streamlit GUI.
5. **Implement database integration**: Use a database management system like SQLite or MySQL to store the extracted information along with the uploaded business card image. User should be able to edit and delete the data through the streamlit UI


## Snaps of the Application

## Screenshots

![img 1](https://i.ibb.co/zRtMBCV/Screenshot-2024-03-14-201947.png)

![img 2](https://i.ibb.co/gjGGMmB/Screenshot-2024-03-14-202250.png)

![img 3](https://i.ibb.co/fGCPQPc/Screenshot-2024-03-14-202657.png)

![img 4](https://i.ibb.co/Pjrhr58/Screenshot-2024-03-14-203037.png)
