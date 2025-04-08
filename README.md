# 🗣️ Speech2Mesh

**Speech2Mesh** is an end-to-end pipeline that transforms spoken language into 3D printable mesh models—no CAD tools or technical design skills needed. It leverages the power of generative AI and 3D reconstruction to make 3D modeling accessible and intuitive.

---

## 📦 Project Structure

- `speech2mesh.ipynb` – Main Jupyter notebook demonstrating the complete pipeline.
- `report/DeepRobProjectReport.pdf` - Report PDF file with literature review.

---

## 🛠️ Features

- Converts speech into text using OpenAI’s **Whisper**.
- Generates multi-view images using **Stable Diffusion**.
- Reconstructs meshes using **InstantMesh**.
- Optional comparison with **Point-E** + **Point2Mesh**.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone [https://github.com/yourusername/speech2mesh.git](https://github.com/trushant05/speech2mesh.git)
cd speech2mesh
```

### 2. Create a Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install JupyterLab

```bash
pip install jupyterlab
```

### 4. Launch the Notebook

```bash
jupyter lab speech2mesh.ipynb
```

---

## ✍️ Authors

- Trushant Adeshara – [@trushantadeshara](https://www.trushant-adeshara.com)
- Pannaga Sudarshan  
- Kajal Awasthi  
- Saket Pradhan

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 📫 Acknowledgements

- Whisper by OpenAI  
- Stable Diffusion by StabilityAI  
- InstantMesh  
- Point-E, Point2Mesh  
