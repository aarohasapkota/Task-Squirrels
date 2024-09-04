# Step - By - Step Tasks
  ## Step 0: Setup Your Project
  ### Changing Mocked Tasks
      I downloaded the Lab_1 Zip File and Opened the file in xcode.
      I added my own mocked tasks and deleted the original mocked tasks.
  <img width="858" alt="Screenshot 2024-08-25 at 3 29 44 PM" src="https://github.com/user-attachments/assets/a63e94ed-ac5e-4ebf-b980-38f15a745874">
  
  ### Running App
  <img width="471" alt="Screenshot 2024-08-25 at 3 30 32 PM" src="https://github.com/user-attachments/assets/9bc6363e-2fff-4a15-a0d8-4cd32f6803f5">
  
  ### Adding Task
  <img width="471" alt="Screenshot 2024-08-25 at 3 31 02 PM" src="https://github.com/user-attachments/assets/99ea1f9d-febe-4ac4-97d5-c6d8b92d92f3">
  
  ### Attempting to leave Title and Description Blank
  <img width="471" alt="Screenshot 2024-08-25 at 3 32 37 PM" src="https://github.com/user-attachments/assets/bdae980b-6a49-418e-9584-8629a1d44ed6">

  ## Step 1: Get authorization to access the user's photo library
  ### Importing PhotosUI
  <img width="1440" alt="Screenshot 2024-08-25 at 3 41 34 PM" src="https://github.com/user-attachments/assets/26111120-16e9-446d-b65a-7e4372ea3c49">

  ### Adding Code to didTapAttachPhotoButton method. 
      This code checks and requests photo library authorization. didTapAttachPhotoButton method is called when "Attach Photo" Button is    Tapped.
  <img width="1440" alt="Screenshot 2024-08-25 at 3 42 56 PM" src="https://github.com/user-attachments/assets/5930f875-d54d-48d4-be7c-e94973c92951">

  ### Running the app and Screenshot of Crash
      Basically, we need to add the NSPhotoLibraryUsageDescription Key and a description of why the app is trying to access the library.
  <img width="1440" alt="Screenshot 2024-08-25 at 3 43 36 PM" src="https://github.com/user-attachments/assets/d8ce4fd7-e406-4f3b-9a54-eee235071126">

  ### Adding the Key and Description to Info.plist
      Info.plist stands for INFORMATION PROPERTY LIST. It's content is used sometimes used to display to the user like in our case and sometimes just for internal purpose for the system to identify our app.
  <img width="903" alt="Screenshot 2024-08-30 at 11 53 18 AM" src="https://github.com/user-attachments/assets/002919e1-9b11-46b4-be37-a8cd876de8bd">

  ### Running App After Adding the key.
  <img width="471" alt="Screenshot 2024-08-25 at 4 38 03 PM" src="https://github.com/user-attachments/assets/17d7dc3d-4076-485f-9dff-1f28cdce966e">

  #### Allowing Limit Access First
  <img width="471" alt="Screenshot 2024-08-25 at 4 38 17 PM" src="https://github.com/user-attachments/assets/7393b0b0-334e-41ed-82fa-bdd230445b7a">

  #### Allowing Full Access
  <img width="471" alt="Screenshot 2024-08-25 at 4 38 22 PM" src="https://github.com/user-attachments/assets/aee90933-3b37-4d81-b908-67171f0b4d30">

  <img width="471" alt="Screenshot 2024-08-25 at 4 38 40 PM" src="https://github.com/user-attachments/assets/be46a20c-a6cd-4826-aaf3-c9113178e817">

  ## Step 2: Create, setup and present the image picker
  ### Adding code to presentImagePicker() method in TaskDetailViewController.
      The Compiler Error is also highlighted. 
  <img width="1440" alt="Screenshot 2024-08-25 at 4 59 10 PM" src="https://github.com/user-attachments/assets/eb25fb9e-9826-4b22-8014-caf2154c0e1e">

  ### Adding an extension that declares the TaskDetailViewController conforms to the PHPickerViewControllerDelegate.
  <img width="1440" alt="Screenshot 2024-08-25 at 5 00 27 PM" src="https://github.com/user-attachments/assets/32d3bd22-2dc1-4888-9106-85d89a3ae622">

  ### Code after clicking the fix button
  <img width="1440" alt="Screenshot 2024-08-25 at 5 00 32 PM" src="https://github.com/user-attachments/assets/c1fc713e-17bc-40d8-9ba0-e2a1d02af942">

  ### Demo with Photo Picker but no other functionality
  <img width="471" alt="Screenshot 2024-08-30 at 12 11 55 PM" src="https://github.com/user-attachments/assets/d09f4749-0b8b-4c20-b7a4-530550631fae">

  ## Step 3: Get the location metadata from the chosen photo
  ### Adding code to picker(_:didFinishPicking:) method.
  <img width="1440" alt="Screenshot 2024-08-30 at 12 31 15 PM" src="https://github.com/user-attachments/assets/9156978f-11bd-40ef-b617-8d05b3398852">

  ### Running App and Adding Photo With Location
  <img width="471" alt="Screenshot 2024-08-30 at 12 35 00 PM" src="https://github.com/user-attachments/assets/8f0decb6-53c2-4d54-aef1-e65d20d5a063">
  
  ### Output to the terminal with Latitude and Longitude
  <img width="710" alt="Screenshot 2024-08-30 at 12 35 39 PM" src="https://github.com/user-attachments/assets/c96e9bb5-315e-49c4-b960-6f758dec6fdb">

  ### Verifying in Google Maps
    The Location was "Galata Tower" in Istanbul, Turkey. The latitude and longitude were correct.
  <img width="1437" alt="Screenshot 2024-08-30 at 12 36 30 PM" src="https://github.com/user-attachments/assets/cc1c1c18-2a05-44bc-9330-3f1a82a8495b">

  ## Step 4: Get the image from the chosen photo
  ### Adding code to get the chosen image into UIImage.
  <img width="1440" alt="Screenshot 2024-08-30 at 10 14 45 PM" src="https://github.com/user-attachments/assets/b988fa3a-cfa6-476d-883c-4c77d2aaf7b7">

  ### Output in the terminal after choosing photo.
  <img width="687" alt="Screenshot 2024-08-30 at 10 50 11 PM" src="https://github.com/user-attachments/assets/d7bc0979-dd46-4a29-8965-601a46687c07">

  ## Step 5: Setup the map view
    Adding code to add map view. I have played with the span to make it zoomed out and give more information about the location.
 <img width="1440" alt="Screenshot 2024-08-30 at 10 55 19 PM" src="https://github.com/user-attachments/assets/bd7bf9e0-5f5a-4587-bbbc-a649c70dc6bb">
 
  ### With Default Span
  <img width="471" alt="Screenshot 2024-08-30 at 10 57 46 PM" src="https://github.com/user-attachments/assets/e87007b6-cf99-419c-9686-26dc8c5bc691">

  ### With 0.1 Span
  <img width="471" alt="Screenshot 2024-08-30 at 11 00 43 PM" src="https://github.com/user-attachments/assets/18b1a0b4-f12c-4b83-ab41-6a82fc5c9d94">


  ## Step 6: Add an annotation
  <img width="1440" alt="Screenshot 2024-08-30 at 11 01 14 PM" src="https://github.com/user-attachments/assets/a070fe78-6bf0-43c9-86aa-d1fc7ab9b5d3">

  <img width="471" alt="Screenshot 2024-08-30 at 11 01 41 PM" src="https://github.com/user-attachments/assets/26e8ec65-b155-4ba4-93d5-7998d41ba2a2">

  ## Step 7: Use a custom annotation view to display the annotation
  ### Registering Custom Annotation View and Set MapView Delegate
  <img width="1440" alt="Screenshot 2024-08-30 at 11 05 40 PM" src="https://github.com/user-attachments/assets/f966135d-d2db-47db-9c59-84ebddfb7f90">
  
  ### Adding Extension to Fix the Error
  <img width="1440" alt="Screenshot 2024-08-30 at 11 07 23 PM" src="https://github.com/user-attachments/assets/67080de2-955d-442e-8085-f77b81afec67">
  
  ### Demo with Photo Attached
  <img width="471" alt="Screenshot 2024-08-30 at 11 07 37 PM" src="https://github.com/user-attachments/assets/881d7611-36fd-4362-a4cf-7e76dccdea48">

  ## Step 8: Add button to view the attached photo in another ViewController
  ### Adding "View Photo" Button and Connecting it with the ViewController Code
  <img width="1440" alt="Screenshot 2024-08-30 at 11 18 38 PM" src="https://github.com/user-attachments/assets/0b70fff6-7a6a-4b96-80c4-c536e6c09ae1">
  
  ### Creating the PhotoViewController Class
  <img width="1440" alt="Screenshot 2024-08-30 at 11 22 41 PM" src="https://github.com/user-attachments/assets/8b6da784-4ac1-4c83-8884-294921852080">

  ### Adding UiImageView In New Scene and Making a connection with ViewPhoto Button View
  <img width="1440" alt="Screenshot 2024-08-30 at 11 42 29 PM" src="https://github.com/user-attachments/assets/2af3f9fe-834c-4c82-8be7-b181b6fb807b">

  ### Adding the PhotoSegue Code
  <img width="1440" alt="Screenshot 2024-08-30 at 11 42 36 PM" src="https://github.com/user-attachments/assets/65ff71b8-0939-419c-982f-08912d1a88f0">

  ### Final Screens
  <img width="471" alt="Screenshot 2024-08-30 at 11 43 15 PM" src="https://github.com/user-attachments/assets/5895ef06-6f41-4b48-b3e2-e60efd1405d9">
  <img width="471" alt="Screenshot 2024-08-30 at 11 43 19 PM" src="https://github.com/user-attachments/assets/2735d651-5173-4508-8efe-58d92e4c2695">




  



  




  









  






  




