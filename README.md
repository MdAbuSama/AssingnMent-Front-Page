# Assignment Cover Page Generator - RMSTU

A web-based tool for generating professional assignment cover pages for Rangamati Science & Technology University (RMSTU) students.

## Features

- 🎨 Professional and clean design matching RMSTU's branding
- 📝 Easy-to-use form for entering assignment details
- 👀 Real-time preview of the cover page
- 📄 PDF download functionality
- 📱 Responsive design that works on all devices
- 🎯 Form validation to ensure all required fields are filled
- 🔄 Reset form functionality
- 💫 Smooth animations and transitions

## How to Use

### Step 1: Fill in the Assignment Details

Enter the following information in the form:

1. **Assignment Title/Number** - e.g., "ASSIGNMENT – 01"
2. **Course Code** - e.g., "CSE173"
3. **Student Name** - Your full name
4. **Student ID** - Your university ID number
5. **Section** - Your class section
6. **Faculty Name** - Name of your course instructor
7. **Submission Date** - Date of submission (fill with current date)
8. **Department** - Your academic department

### Step 2: Preview the Cover Page

Click the **"Preview Template"** button to generate a preview of your assignment cover page. The system will:

- Validate all required fields
- Display a preview of your cover page
- Enable the download button
- Scroll to show the preview

### Step 3: Download as PDF

After previewing, click the **"Download PDF"** button to:

- Open the print dialog
- Save as PDF file
- Print directly if needed

### Step 4: Reset Form (Optional)

If you need to start over, click the **"Reset Form"** button to clear all fields and start fresh.

## File Structure

```
assignment-cover-generator/
│
├── index.html          # Main HTML file
├── image/
│   └── RMSTU-Logo.png    # University logo (replace with actual logo)
└── README.md           # This documentation file
```

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for Bootstrap and Font Awesome CDN)
- PDF reader (for viewing downloaded files)

## Browser Compatibility

- ✅ Google Chrome
- ✅ Mozilla Firefox
- ✅ Safari
- ✅ Microsoft Edge
- ✅ Opera

## Printing Instructions

For best results when printing:

1. Use A4 size paper
2. Set margins to "Default" or "Minimum"
3. Ensure "Background graphics" is enabled in print settings
4. Use high-quality paper for professional appearance

## Customization

### Changing the Logo

Replace the `./image/RMSTU-Logo.png` file with your institution's logo. Recommended dimensions: 500x100 pixels.

### Adding New Fields

To add new fields to the form:

1. Add the input field in the form section
2. Add corresponding display element in the cover page template
3. Update the JavaScript `previewTemplate()` function

## Troubleshooting

### Common Issues

1. **Preview not working**: Ensure all required fields are filled
2. **PDF download issues**: Check browser pop-up settings
3. **Layout problems**: Use Chrome or Firefox for best compatibility
4. **Logo not displaying**: Check if the logo file exists in the image folder

### Error Messages

- **"Please fill out all required fields"**: Complete all form fields
- **"Please click Preview Template first"**: Generate preview before downloading
- **"Opening print dialog"**: PDF download is in progress

## Technical Details

- Built with HTML5, CSS3, and JavaScript
- Uses Bootstrap 5.3.0 for responsive design
- Font Awesome 6.4.0 for icons
- No backend required - works entirely in browser
- Print CSS optimized for A4 paper

## Development

**Developed and Designed by:** Rajdip  
**Contact:** srajdip920@gmail.com

### Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Icons**: Font Awesome 6.4.0
- **Print Optimization**: CSS Print Media Queries
## Support

For technical issues, feature requests, or customization needs, please contact:

**Developer:** Abu Sama  
**Email:** abusaamaa1997@gmail.com

For university-specific issues, please contact your institution's IT department.

## License

This tool is provided for educational use by Northern University Bangladesh students.

---

**Note**: This tool is designed specifically for NUB students and follows the university's assignment cover page format requirements. Developed with ❤️ by Abu Sama.
