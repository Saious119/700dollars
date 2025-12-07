# 700 Dollars - Simple Image Website

A minimal Node.js website that displays a single image.

## Setup Instructions

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Add Your Image**
   - Place your image file in the `public` folder
   - Name it `image.jpg` (or update the filename in `public/index.html` to match your image name)
   - Supported formats: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, etc.

3. **Run the Server**
   ```bash
   npm start
   ```

4. **View the Website**
   - Open your browser and navigate to: `http://localhost:3000`

## Project Structure

```
700dollars/
├── public/
│   ├── index.html       # Main HTML page
│   └── image.jpg        # Your image (to be added)
├── server.js            # Express server
├── package.json         # Node.js dependencies
└── README.md           # This file
```

## Customization

- To change the port, set the `PORT` environment variable:
  ```bash
  PORT=8080 npm start
  ```

- To use a different image filename, update the `src` attribute in `public/index.html`:
  ```html
  <img src="your-filename.png" alt="Main Image">
  ```

## Notes

- The website is responsive and will center the image on any screen size
- The image will scale to fit the viewport while maintaining aspect ratio
- A dark background (#1a1a1a) provides good contrast for most images