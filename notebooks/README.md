# Colab Usage

Open `notebooks/fire_detection_training.ipynb` in Google Colab using `File -> Open notebook -> GitHub`, then select this repository and notebook.

Before running any cells, switch Colab to a GPU runtime with `Runtime -> Change runtime type -> GPU`.

The notebook uses Colab paths under `/content`, downloads the dataset from Roboflow with the placeholder `YOUR_ROBOFLOW_API_KEY`, and saves the trained weights to `/content/drive/MyDrive/fire_detection/best.pt`.
