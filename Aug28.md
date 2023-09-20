# **CLASS NOTES** by Taemour Zaidi

### What is an image in computer graphics?
- A visual representation of something

### What is a digital image?
- A binary representation of visual data.
- These images can take the form of photographs, graphics, and individual video frames. Therefore, an image is a picture that was created or copied and stored in electronic form.

## Image File Formats

Image files are composed of digital data in image file formats so that the data can be displayed on a digital display or printed out using a printer

**There are two main types of image file formats:**
1. Native image files: they are specifically to be used with one software. Like aseprite has `.ase` format.
2. Common Image File Formats: they can be used by multiple different types of software, more general use files.

## Native File Formats
- Many applications have their own native file format
- This type of file format is created by a specific software or application and can retain all needed information about the image such as layers, transparency, masks and other adjustments.
- It is always good to save a version of an image in the native format if you plan to make future edits to the image, because the native file format will keep all editing information.
- **Raster image editors:**
    - Adobe Photoshop document `.psd`
    - GIMP Experimental Computing Facility `.xcf`
- **Vector image editors:**
    - Adobe Illustrator `.ai`
    - CorelDRAW `.cdr`

## Comon File Formats
- **TIFF (Tagged Image File Format):**
    - `.tif`, `.tiff`
    - Lossless (will not loose quality, will remain the same as the original)
    - Very high-quality images
    - Very large file sizes
    - No compression
    - Best for high quality prints, professional publications, archival copies
    - Save transparency
- **BMP (Bitmap):**
    - `.bmp`
    - Developed vy Microsoft for Windows
    - Lossless
    - Very high-quality images
    - Very large file sizes
    - No compression
    - Best for high quality scans, archival copies
    - It is generally deprecated in favor of TIFF files (due to BMP being a proprietary format)
- **JPEG (Joint Photographic Experts Groups):**
    - .jpg, .jpeg
    - Lossy:
        1. Image is compressed to make a smaller file
        2. The compression creates a loss in quality but this loss is generally not noticeable
    - Best for web images
    - Can chose amount of compression when saving in image editing programs like Adobe Photoshop or GIMP
- **GIF (Graphics Interchange Format):**
    - .gif
    - Lossless (compression without loss of quality)
    - Small file sizes
    - Supports only 256 colors
    - Save transparency
    - Can be animated
    - Best for web images
    - Portable
- **PNG (Portable Network Graphics):**
    - `.png`
    - Designed to enhance and replace `.gif` format
        - PNG files are able to handle up to 16 million colors, unlike the 256 colors supported by GIF
    - Lossless
    - Saves transparency
    - Best for web images
- **EPS (Encapsulated PostScript):**
    - .eps
    - Common vector file type
    - Can be opened in many illustration applications such as Adobe Illustrator or CorelDRAW
    - No compression
    - Save vector information
    - Best for vector artwork/illustrations
- **RAW**
    - `.raw`, `.cr2`, `.nef`, `.orf`, `.sr2`, etc
    - Unprocessed images
    - Created by a camera or scanner
    - Many digital SLR cameras can shoot in RAW, whether it be `.raw`, `.cr2`, or `.nef`
    - These RAW images are the equivalent of a digital negative
        - They hold a lot of image information, but still need to be processed in an editor such as Adobe Photoshop or Lightroom.
    - Lossless
    - Very large file sizes
    - Save metadata
    - Contain lots of imformation
    - Best for photography
    
## Image Resolution
- A pixel is one of the small fots or squares that make up an image on a computer screen
- Image resolution regers to how many pixels are displayed per inch of an image.
- Higher resolutions mean that there are more pixels per inch (PPI) resulting in more pixel information and creating a high-quality, crisp image.
- Images with lower resolutions have fewer pixels, and if those few pixels are too large (usually when an image is stretched), they can become invisible
- An image tyhat has a resolution of 600 ppi will contain 600 pixels within each inch of the image
- 600 pixels is a lot of pixels to live in just one inch, which is why 600 ppi images will look very crisp and detailed
- Now, compare that to an image with 72 ppi, which has a lot fewer pixels per inch

## QUIZ
1. **When scanning or photographing, always try and capture the image at the largest resolution. Why?**
    - It's better to have more information than not enough! It's much easier for image editing applications, like Photoshop, to discard any unwanted image information (reducing the size of an image) than it is to create new pixel information (enlarge an image). 

2. **What are PPI & DPI? Is there a difference between them in terms of computer graphics? Explain!**
    - These two acronyms are often used interchangeably although they do have different meanings.
        - PPI (Pixels Per Inch) refers display resolution, or how many individual pixels are displayed in one inch of a digital image.
        - DPI (Dots Per Inch) refers to printer resolution, or the number of dots of ink on a printed image.






