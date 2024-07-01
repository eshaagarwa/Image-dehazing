# 🌫️ **Haze Removal Using Dark Prior Channel** 🌫️

## 📚 Project Overview

Welcome to our final year project! We're addressing the common issue of haziness in images with the **Dark Prior Channel** method. 🌫️ Dust, haze, and fog can obscure details and diminish image quality, making it hard to see what's important. Our project aims to tackle this by refining and enhancing ground truth images, removing unwanted distortions for clearer and more vibrant visuals. 🚀✨

### Example: Hilly Valley

Here's an example demonstrating our method on a hilly valley scene:

![Hazy Image](https://upload.wikimedia.org/wikipedia/commons/6/6e/Foggy_valley.jpg) <!-- Hazy image example -->
![Clear Image](https://upload.wikimedia.org/wikipedia/commons/3/37/Clear_mountain_valley.jpg) <!-- Clear image example -->

## 🔍 Methodology

The **Dark Prior Channel** technique is designed to improve image clarity by leveraging the unique properties of haze-free images. Here’s how it works:

1. **Pixel Intensity Analysis**: In images without haze, some pixels exhibit very low intensity in at least one color channel. 🌈
2. **Haze Estimation**: By identifying these dark pixels, we estimate the haze in the image. 📉
3. **Haze Removal**: We then apply our findings to clear the haze, dust, and fog, enhancing the overall image quality. 🖼️

![Haze Removal Process](https://upload.wikimedia.org/wikipedia/commons/4/4f/Dehazing_example.png) <!-- Example of haze removal process -->

## 🚧 Challenges

Despite achieving promising results, we face several challenges:

- **Resource Limitations**: Our ability to perform high-level haze removal is constrained by limited resources. 🛠️💡
- **Complexity of Haze**: Some images present more complex haze patterns that are harder to remove completely. 🌀

## 🌟 Achievements

- **Enhanced Image Clarity**: Our method has successfully improved the visibility of key details in hazy images. 🏆
- **Valuable Insights**: The project contributes to a better understanding of haze removal techniques and their practical applications. 📊🔍

## 📸 Visual Results

Here are some examples of our work:

- **Before Dehazing**: ![Before Dehazing](https://upload.wikimedia.org/wikipedia/commons/6/6e/Foggy_valley.jpg) <!-- Hazy image example -->
- **After Dehazing**: ![After Dehazing](https://upload.wikimedia.org/wikipedia/commons/3/37/Clear_mountain_valley.jpg) <!-- Clear image example -->

## 🛠️ How to Use

To see our method in action or integrate it into your projects, check out our code and examples provided in this repository. For detailed instructions and usage, refer to the documentation.

---

Thank you for exploring our project! Feel free to provide feedback or contribute. 🙌💬

