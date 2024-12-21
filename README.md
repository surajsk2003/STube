# STube  

## Overview  
STube is a simple and visually appealing webpage designed to display long and short video previews, similar to popular video platforms like YouTube. The webpage features a clean and responsive grid layout, showcasing video thumbnails, titles, author names, and statistics.  

## Features  

### Header Section  
- Includes a brand title (STube) styled like YouTube.  
- A search bar is centrally aligned for easy navigation.  

### Video Previews  
Each video preview consists of:  
- Thumbnail image of the video.  
- Channel icon/profile picture.  
- Video title, author name, and statistics (views and upload time).  
- Hover effects on thumbnails (optional for enhancement).  

### Responsive Grid  
- Videos are displayed in a grid format, dynamically adjusting to screen sizes.  

## Styling  
- Uses custom CSS for a modern and clean UI.  
- Incorporates Google Fonts for better typography.  

## File Structure  

project-folder/
├── index.html
├── css/
│   └── styles.css
├── images/
│   ├── pic1.jpeg
│   ├── pic2.jpeg
│   └── channel_icons/
│       ├── channel-1.jpeg
│       └── channel-2.jpeg
└── README.md



## How to Run  
1. Save the HTML code into a file named `index.html`.  
2. Place all referenced images (e.g., `pic1.jpeg`, `channel-1.jpeg`) in their respective folders:  
   - `/images` for thumbnails.  
   - `/channel_icons` for channel icons.  
3. Open `index.html` in any modern browser.  

## Customization  

### Add More Videos  
Copy the existing `<div class="video-preview">` block and replace the following:  
- Thumbnail image (`src` of `<img>`).  
- Video title (`<p class="video-title">`).  
- Author name (`<p class="video-author">`).  
- Video stats (`<p class="video-stats">`).  

### Change Branding  
- Update the title in the `<h1>` tag inside the header section.  
- Modify the font or color styles in the CSS section.  

## Dependencies  
- **Google Fonts**: The page uses the Roboto font from Google Fonts. Ensure an active internet connection for it to load.  
- **Modern Browser**: Use a browser like Google Chrome, Firefox, or Edge for the best experience.  

## Future Enhancements  

### Add Interactivity  
- Include hover effects on thumbnails.  
- Make the search bar functional.  

### Responsive Design  
- Improve responsiveness for smaller devices.  

### JavaScript Integration  
- Enable video playback on thumbnail click.  
- Add dynamic filtering based on search queries.  

## Author  
I created this project to demonstrate my HTML and CSS skills by building a functional and visually appealing video platform prototype.  

Feel free to modify and enhance!  
