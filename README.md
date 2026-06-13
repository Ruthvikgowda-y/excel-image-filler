# 🖼️ Excel Image Auto-Filler

Automatically fills an Excel column with images searched from Bing Images — runs 100% online via Google Colab, no installation needed.

---

## 👤 For Employees — How to Use

1. Click this link to open the tool:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/blob/main/excel_image_filler.ipynb)

2. Sign in with your **Google account** if asked

3. Click **Runtime → Run All** in the top menu

4. Scroll down to **Step 3**, click **Choose Files** and upload your `.xlsx` file

5. Wait for it to finish (you'll see progress in the output)

6. Click the **Download** button that appears at the bottom

✅ Your file with images will be saved as `yourfilename_with_images.xlsx`

---

## ⚙️ Settings (inside the notebook)

| Setting | Default | What it does |
|---|---|---|
| `col_read` | `A` | Column that has your search text |
| `col_write` | `B` | Column where images will be placed |
| `start_row` | `1` | First row of data (use `2` if row 1 is a header) |

---

## 📋 Requirements

- A Google account (to use Google Colab — it's free)
- Your Excel file must be `.xlsx` format (not `.csv`)
- Each cell in column A should have the topic to search for

---

## 🔧 For the Owner — Setup Instructions

### First time setup:

1. Create a free GitHub account at [github.com](https://github.com)
2. Create a new repository (click the **+** button → **New repository**)
3. Name it anything e.g. `excel-image-filler`
4. Upload `excel_image_filler.ipynb` to the repository
5. Replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO_NAME` in this README with your actual values
6. Share the Colab badge link above with your employees

That's it — employees just click the link and use it!
