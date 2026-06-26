# 📁 Dataset — IMDB 50K Movie Reviews

This folder is a placeholder for the dataset.
The actual CSV file is **not tracked by Git** (too large for GitHub).

---

## 🔗 Dataset Source

**Kaggle:** [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

| Field       | Details                                                       |
|-------------|---------------------------------------------------------------|
| Link        | https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews |
| File name   | `IMDB Dataset.csv`                                            |
| Columns     | `review` (text), `sentiment` (positive / negative)           |
| Rows        | 50,000                                                        |
| Size        | ~66 MB                                                        |

---

## ⬇️ How to Download

### Option 1 — Download Manually (Easiest)

1. Go to 👉 [https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
2. Click the **Download** button (top right)
3. Extract the ZIP file
4. Place `IMDB Dataset.csv` inside this `dataset/` folder

---

### Option 2 — Download via Kaggle API (Recommended)

#### Step 1: Install Kaggle CLI
```bash
pip install kaggle
```

#### Step 2: Set up your Kaggle API key
1. Go to [https://www.kaggle.com/settings](https://www.kaggle.com/settings)
2. Scroll to **API** section → Click **"Create New Token"**
3. This downloads `kaggle.json`
4. Place it here:
   - **Windows:** `C:\Users\<YourName>\.kaggle\kaggle.json`
   - **Linux/Mac:** `~/.kaggle/kaggle.json`

#### Step 3: Download the dataset
```bash
kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews -p ./dataset --unzip
```

The file `IMDB Dataset.csv` will be saved directly into the `dataset/` folder.

---

## 📌 Note

The `dataset/` folder is listed in `.gitignore` to prevent large files from being committed to GitHub.
If you want to share data with collaborators, use the Kaggle link above.
