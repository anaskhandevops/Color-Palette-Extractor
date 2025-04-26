# 🎨 Image Color Palette Extractor

A simple web-based tool to extract the dominant colors from an uploaded image file. It analyzes the image using HTML Canvas and displays a palette of the most prominent colors found. ✨

---

## ✨ Features

* 🖼️ **Image Upload:** Select JPG, PNG, GIF, etc., from your device.
* 👁️ **Image Preview:** See a small preview of your uploaded image.
* 🎨 **Dominant Color Extraction:** Analyzes pixels to find the most frequent color groups using a binning technique.
* 🌈 **Palette Display:** Shows extracted colors as visual swatches.
* #️⃣ **HEX Code Display:** Provides the hexadecimal code for each color.
* 🖱️ **Click-to-Copy:** Easily copy HEX codes by clicking the swatches.
* 📱 **Responsive Design:** Adapts to different screen sizes.
* ⏳ **Loading Indicator:** Shows visual feedback during processing.
* 💬 **User Feedback:** Displays success or error messages.

---

## 🚀 How to Use

1.  Clone this repository or download the files.
2.  Open the `index.html` file in your web browser.
3.  Click the "Choose Image File" button and select your image.
4.  A preview and filename will appear.
5.  Click the "Extract Colors" button.
6.  Wait for the ⏳ analysis.
7.  The dominant colors 🎨 will appear below.
8.  Click any color swatch to copy its HEX code! ✨

---

## 💻 Technology Stack

* **HTML:** Page structure.
* **CSS (Tailwind CSS):** Styling & layout (via CDN).
* **JavaScript:** File handling, image preview, canvas manipulation, color analysis, DOM updates, user interactions.
* **HTML Canvas API:** Used to draw the image and access pixel data.

---

## 🤝 Contributing

Contributions are welcome! 🎉 Whether it's bug fixes, feature additions, or documentation improvements, please feel free to contribute.

**How to Contribute:**

1.  **Fork the Repository:** Click the 'Fork' button at the top right of the repository page.
2.  **Clone Your Fork**
3.  **Create a New Branch:** Create a descriptive branch name for your changes.
    ```bash
    git checkout -b feature/your-awesome-feature
    # or
    git checkout -b fix/issue-description
    ```
4.  **Make Your Changes:** Implement your feature or fix the bug.
5.  **Test Your Changes:** Ensure your changes work as expected and don't break existing functionality.
6.  **Commit Your Changes:** Write clear and concise commit messages.
    ```bash
    git add .
    git commit -m "feat: Add awesome new feature"
    # or
    git commit -m "fix: Resolve issue with color calculation"
    ```
    *(Consider using [Conventional Commits](https://www.conventionalcommits.org/) for commit messages).*
7.  **Push to Your Fork:**
    ```bash
    git push origin feature/your-awesome-feature
    ```
8.  **Open a Pull Request (PR):** Go to the original repository on GitHub and open a Pull Request from your forked branch to the main branch of the original repository.
    * Provide a clear title and description for your PR.
    * Reference any related issues (e.g., "Closes #123").

**Reporting Bugs:**

* Use the GitHub Issues tab.
* Provide a clear title and description.
* Include steps to reproduce the bug.
* Mention your browser and operating system if relevant.

**Suggesting Enhancements:**

* Use the GitHub Issues tab.
* Provide a clear title and detailed description of the proposed enhancement and its potential benefits.

---

## 💡 Potential Enhancements

* **Advanced Algorithms:** Implement k-means clustering or Median Cut for color quantization.
* **Palette Size:** Allow users to select the number of colors (e.g., 4, 8, 16).
* **Color Formats:** Add options to copy RGB or HSL values.
* **Background Removal:** Option to ignore large background areas.
* **Drag & Drop:** Implement drag-and-drop image uploads.
* **Performance:** Optimize JS, potentially using Web Workers.

---

Happy Coding! 💻
