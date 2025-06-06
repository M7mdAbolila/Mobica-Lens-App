# Mobica-Lens-App (Data Science Visual Search App)
Mobica Lens is a Flutter application that allows users to take or upload a photo and find visually similar products using advanced image processing and search features.
# 🎥 Demo & Screenshots
Preview the core features for **old version**

https://github.com/user-attachments/assets/60b3696a-2355-4aa9-8aca-f4b038291fba

## Features
- **Take or Upload Photo**
  - Users can capture a new photo using the device camera or select an existing image from the gallery.
  - Images are resized for optimal upload and processing.
    
![image](https://github.com/user-attachments/assets/5fa1a1a2-7c65-4ec3-a8fd-3f66d06e4924)

- **Find Similar Products**
  - After selecting a photo, the app sends the image to a backend service to find visually similar products.
  - Results are displayed in a grid view, showing the most similar products.
  - 
![image](https://github.com/user-attachments/assets/00611b6c-04af-4f8b-b8ff-55f6f2bf5c4d)

- **Error Handling**
  - User-friendly error messages are shown if image selection or product search fails.

- **Responsive UI**
  - Uses [ScreenUtil]for responsive layouts across different device sizes.
  - Custom widgets for buttons, loading indicators, and error messages.

- **Navigation**
  - Smooth navigation between screens: Home, Photo Selection, and Results.
