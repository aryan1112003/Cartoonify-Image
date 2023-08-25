# Cartoonify Image Filters with OpenCV

Enhance your images with an array of captivating cartoon-style filters using the adept Python script by Aryan Acharya. Leveraging the potent OpenCV library, this repository offers a seamless transformation process. The script takes an input image, applies an eclectic blend of filters to induce enchanting cartoon-like effects, and seamlessly presents the original and filtered renditions side by side. It also provides the convenience of saving these filtered images with descriptive filenames.

## Prerequisites

Before embarking on the journey, ensure that the following prerequisites are met:

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Google Colab (for effortless image uploads)

Install the required libraries with a simple command:

```bash
pip install opencv-python numpy matplotlib
```

## How to Use

Follow these steps to harness the script's creative prowess:

1. Clone this repository to your local machine.
2. Open the script, `cartoonify_image.py`, in a Jupyter Notebook or Google Colab.
3. Execute the script cell by cell to experience its functionalities:

   - Apply diverse filters (blur, edges, sharp) to the input image.
   - Craft visually captivating cartoon-style images by blending color and filtered layers.
   - Witness both the original and cartoon-style filtered images displayed elegantly.
   - Save these transformative artworks with expressive filenames.

4. When prompted, upload the desired image for filtering, and let the script unfold its magic.

## Script Structure

The script's architecture is designed for efficiency and clarity:

1. **Import Necessary Libraries**: Essential libraries for image processing, filtering, and visualization are imported seamlessly.

2. **apply_filter Function**: A versatile function applies an array of filters (blur, edges, sharp) to a given image.

3. **cartoonify_image Function**: This function is the heart of the script, creating captivating cartoon-style images by meticulously layering color and filters.

4. **save_cartoon_image Function**: Preserve your creations with filenames that elegantly encapsulate the applied effects.

5. **Uploading Images**: Google Colab's `files.upload()` method simplifies image uploads.

6. **Applying Filters and Displaying Results**: Witness the transformation as uploaded images adorn diverse filters, their metamorphosis showcased through Matplotlib.

## Results and Saving

Behold a visual symphony as the script showcases the original image and five captivating variations: original, blur, edges, sharp, and a harmonious amalgamation of all filters. Each masterpiece comes with an eloquent title that encapsulates its essence, while filenames gracefully narrate the applied effects alongside the original image's name.

## Conclusion

Aryan Acharya's ingenious creation opens new vistas in digital image manipulation. By adhering to the script's guidance and orchestrating its magic, you breathe life into mundane images, summoning captivating transformations. This script is not just a guide; it's a canvas that lets you infuse innovation into your vision, conjuring an enthralling dance of cartoon-style filters.
