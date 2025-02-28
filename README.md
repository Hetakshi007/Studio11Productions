**Studio 11 Internship Assignment**

**📌 Project Overview**

This project is part of the **AI Internship at Studio 11 Productions**,
where we developed a Generative AI tool to **automatically place
e-commerce product images into realistic lifestyle images**. The
implementation is based on the **Segment Anything Model (SAM)** from
Meta AI and runs using **free and open-source tools**.

**📂 Project Files**

-   **studio11.py** - Python script for image segmentation and
    placement.

-   **SampleImg.png** - Product image (wall painting used in this
    example).

-   **Living room.png** - Lifestyle image where the product is placed.

-   **README.md** - Instructions for running the project.

**🚀 Features Implemented**

✅ **Batch Processing** - Supports multiple product images.\
✅ **Realistic Placement** - Ensures accurate positioning & blending.\
✅ **Preserves Product Details** - Keeps the original product clarity.\
✅ **Uses Open-Source Tools** - SAM Model, OpenCV, NumPy, Matplotlib.\
✅ **Optimized for Colab & Local** - Works on both environments.

**🛠️ Installation & Setup**

**1️. Clone the GitHub Repository**

git clone
https://github.com/Hetakshi007/Studio11Productions 

**2️. Install Dependencies**

pip install git+https://github.com/facebookresearch/segment-anything.git

pip install opencv-python numpy matplotlib

**3️ .Download the SAM Model**

wget -O sam_vit_b_01ec64.pth
https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth

**📜 Usage Instructions**

**Run the Python Script**

python studio11.py

**Expected Output**

-   The script will place the painting from SampleImg.png onto the wall
    in Living room.png.

-   The final output will be displayed with the painting properly
    placed.

-   **📬 Submission Details**

```{=html}
<!-- -->
```
-   **GitHub Repository:**
    https://github.com/Hetakshi007/Studio11Productions

-   **Submission Format:** .ipynb and .py files uploaded to GitHub.
