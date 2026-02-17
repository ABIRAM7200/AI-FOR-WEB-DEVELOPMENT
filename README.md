# ABIRAM Cafe – Grand Launch Event Registration

## Overview
This is an HTML-based registration page for **ABIRAM Cafe's Grand Launch Event**. The page features a modern, visually appealing design with multimedia content and an interactive registration form.

## Features

### 🎨 Design
- **Color Scheme**: Red (#ff3333) and Yellow (#ffd633) with gradient background
- **Font**: Google Fonts (Poppins for body, Pacifico for heading)
- **Responsive Layout**: Clean, centered container with rounded corners and shadow effects
- **Modern UI**: Smooth transitions and hover effects

### 📺 Media Elements
- **Event Banner Image**: Displays promotional cafe launch image
- **Promotional Video**: Embedded MP4 video player for event preview
- **Background Music**: Audio player for cafe mood music

### 📝 Registration Form
The form collects the following information:
- **Full Name** - Required text input
- **Email Address** - Required email input
- **Date of Attendance** - Required date picker
- **Number of Guests** - Dropdown selection (1, 2, 3, 4+)
- **Preferred Session** - Radio buttons (Morning ☀️ or Evening 🌙)
- **Special Requests** - Optional textarea for messages
- **Invitation Screenshot** - Optional file upload
- **Submit Button** - Eye-catching registration confirmation button

## File Structure

### HTML Elements
```
<header>              - Page title and subtitle
├── h1              - "ABIRAM Cafe" heading
└── p               - Registration subtitle

<container>         - Main content wrapper
├── .banner         - Event promotional image
├── video           - Promotional video player
├── audio           - Background music player
├── form            - Registration form with all fields
└── <footer>        - Copyright information
```

### Styling Highlights
- **Grid Layout**: 2-column form layout for desktop display
- **Textarea**: Full-width special requests field
- **Submit Button**: Red background with hover effect (darkens on hover)
- **Border Radius**: Consistent rounded corners throughout (10px-40px)
- **Box Shadow**: Subtle shadow for depth

## Required Assets
Before using this page, ensure you have the following media files in the same directory:
- `cafe-banner.jpg` - Event banner image
- `promo-video.mp4` - Promotional video file
- `background-music.mp3` - Background audio file

## How to Use

1. **Open in Browser**: Simply open the `abi.html` file in any modern web browser
2. **Fill Registration Form**: Users can enter their details and select preferences
3. **View Media**: Promotional video and background music are playable directly on the page
4. **Submit**: Click "🎉 Register Now 🎉" to submit the registration

## Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Customization

You can easily customize:
- **Colors**: Change hex codes in the `<style>` section
- **Text**: Update cafe name, event details, and form labels
- **Media**: Replace source paths for banner, video, and audio
- **Fonts**: Modify Google Font imports and family names
- **Form Fields**: Add or remove form inputs as needed

## Notes
- Form currently has no backend—submissions won't be saved without server-side handling
- Add `name` attributes to form inputs to enable proper form submission
- Consider adding validation scripts for enhanced user experience
- Media files must be accessible (same directory or valid URLs)

---
**Created for**: ABIRAM Cafe Grand Launch Event  
**Year**: 2026  
**Status**: Ready to use ✅
