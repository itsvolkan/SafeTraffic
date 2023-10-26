# Safe Traffic - Android App

#### Video Demo [My project present](httpsyoutu.bew_kSpgqxxbs)

#### Description
Safe Traffic is an Android application designed to enhance road safety. It allows users to report incidents, rate drivers, and share comments about their experiences on the road. This project helps create awareness about traffic safety and encourages responsible driving.

### Files in the Project
- RatingActivity.java This file contains the code for user ratings, comments, and incident reporting.
- RatingListActivity.java Manages the user interface for viewing and searching for ratings and incidents.
- Vehicle.java Represents the data structure for a vehicle, including ratings, comments, and image URLs.
- VehicleAdapter.java Custom adapter for displaying vehicles and their details.
- image_popup_layout.xml Layout for displaying enlarged images when clicked.
- ImagePickerActivity.java Handles image selection for user ratings.
- MainActivity.java The main activity responsible for the app's primary functions.
- UpperCaseNoSpaceInputFilter.java A utility class for filtering and formatting user input.

### XML Layout Files
- activity_main.xml Main activity layout, representing the app's primary user interface.
- activity_rating.xml Layout for the activity where users can rate vehicles and report incidents.
- activity_rating_list.xml Layout for viewing and searching for ratings and incidents.
- image_popup_layout.xml Layout for displaying enlarged images when clicked.
- list_item_vehicle.xml Layout for individual items displayed in the rating list.



### Design Choices
- The project utilizes Firebase Realtime Database to store and retrieve user ratings and incident data.
- Images are stored in Firebase Storage, and URLs are stored in the database for image retrieval.
- Picasso is used to load and display images, ensuring a smooth user experience.

### Usage
1. Rating Vehicles In the RatingActivity, users can enter details such as the vehicle's plate, rating, comment, date, and location. They can also upload an image.
2. Viewing Ratings Users can view vehicle ratings and incidents using the RatingListActivity. They can search by the vehicle's plate number to find specific ratings.
3. Click to Enlarge Images When viewing a rating or incident, users can click on an image to see an enlarged version.

### Future Enhancements
- Implement real-time reporting and sharing with the police.
- Enhance the user interface for a more visually appealing experience.

### Acknowledgments
- Firebase for providing a robust and scalable backend solution.
- Picasso library for simplifying image loading and display.

### License
This project is open-source under the [MIT License](httpsopensource.orglicensesMIT).

Feel free to clone, modify, or contribute to this project. We appreciate your feedback and contributions.

