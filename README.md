# Sound & Vision - Artist Portfolio Landing Page

A responsive landing page for sound designers, music producers, and digital artists to showcase their work.

## Features

- Responsive design that works on all devices
- Modern UI with beautiful animations
- Music player for audio samples
- Image gallery with lightbox functionality
- Contact form with validation
- Mobile-friendly navigation

## Technologies Used

- HTML5
- CSS3
- JavaScript (vanilla)
- Tailwind CSS (via CDN)
- Font Awesome Icons

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser to view the site
3. Customize the content and styling to fit your needs

## Customization Guide

### Adding Your Music

1. Navigate to the Music section in `index.html`
2. Replace the placeholder album covers with your own images
3. Update the audio `src` attributes with links to your music files
4. Change the track titles and other details

```html
<div class="audio-player">
    <audio controls class="w-full">
        <source src="path/to/your-audio-file.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</div>
```

### Adding Your Artwork

1. Navigate to the Art Gallery section in `index.html`
2. Replace the placeholder images with your own artwork
3. Update the `alt` attributes with appropriate descriptions

```html
<div class="art-item overflow-hidden rounded-lg cursor-pointer hover:opacity-90 transition">
    <img src="path/to/your-artwork.jpg" alt="Your Artwork Title" class="w-full h-auto">
</div>
```

### Customizing Colors and Styling

1. You can modify the color scheme by editing the Tailwind classes in the HTML
2. For custom styling beyond Tailwind, edit the `styles.css` file
3. The main color scheme is built around purple tones, which you can change to match your brand

## Browser Compatibility

The site works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Contact Form

The contact form currently uses client-side validation only. To make it functional:

1. Create a backend endpoint to process the form data
2. Update the form submission code in `script.js` to send data to your endpoint

## License

Feel free to use and modify this template for your personal or commercial projects.

---

Created with ❤️ for artists who want to showcase their work in style. 