# Fourfold

### ₊⊹ About

Two images that are initially greyed out and split into four pieces. 
Then, when hovered over, the pieces join together to form a whole image, and the grey effect dissipates.

https://github.com/user-attachments/assets/7aa97713-7e24-4c81-9536-b23dd4e0df69

---

### ⚙️ Tech Stack

- **HTML5**
- **CSS3**

---

### 🖿 Project structure

 ```
Fourfold/
├── Assets/
│   ├── picture-1.jpg
│   └── picture-2.jpg
├── index.html
├── style.css
└── README.md
```

---

### .ᐟ.ᐟ How It Works

- Two images of the same size, so the cutouts won't be different

- The `--_g` option is what creates the cutouts in the photos

- The `mask` option determines which sides each of the four parts will occupy (left, top, bottom, right)

- `--i_` controls the spacing between the pieces. When you hover over the image (`img:hover`), the value changes to 10% and the pieces move, rearranging the photo in a different way

- `filter: grayscale()` turns everything black and white. On hover, it changes to `grayscale(0)`; when you hover over the image, it becomes colorful

- `transition: 0.3s linear` makes the change happen gradually in the photo, very slowly so it doesn’t jump all at once (`0.3s`)
