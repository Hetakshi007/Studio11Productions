
This project is a Generative AI tool that automatically places e-commerce product images into realistic lifestyle scenes. It seamlessly integrates product images while preserving details, scale, and perspective.

📌 Features
•	Batch Processing: Handles multiple product images at once.
•	Realistic Placement: Ensures natural lighting, perspective, and scale.
•	Preserves Product Details: Maintains clarity and integrity of the original product.
•	Flexible Adjustments: Allows resizing and positioning customization.

🛠️ Installation & Setup
1️. Clone the Repository
git clone https://github.com/Hetakshi007/Studio11Productions.git
cd Studio11Productions

2️. Install Dependencies
Ensure you have Python installed. Then, install the required libraries:
pip install opencv-python matplotlib torch segment-anything numpy

3️. Run the Script
If using a Jupyter Notebook:
jupyter notebook
Then open studio11.ipynb and run the cells.
If running the Python script:
python studio11.py

4️. Run on Google Colab
You can also run the project directly on Google Colab without installing dependencies.
•	https://colab.research.google.com/drive/1k99KmcSiqBC0w6AMIxCluOzsPtOwDlQS 
•	Upload the images (SampleImg.png and Living room.png) to /content/ before running the script.
•	Install dependencies in Colab using:
!pip install opencv-python matplotlib torch segment-anything numpy

🖼️ Sample Images
•	Sample Image: (SampleImg.png) - The e-commerce product.
•	Lifestyle Scene: (Living room.png) - The background where the product is placed.

✅ Output Example
The tool will generate an output image where the product is realistically placed in the lifestyle scene.
________________________________________
📝 Notes:
•	Ensure the sample and lifestyle images are correctly named and located in the working directory.
•	Modify the placement coordinates in the script if adjustments are needed.
🔹 Created as part of the AI Internship at Studio 11 Productions.
