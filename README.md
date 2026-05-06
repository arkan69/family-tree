# 🌳 Silsilah Keluarga Bani Sumandar

A simple interactive family tree web application built to visualize and document the lineage of Bani Sumandar.

## 🧠 About

This project was created to help family members explore and understand their family relationships through an interactive tree interface.

Built as a static web app using Astro, with a focus on simplicity, readability, and usability.

## ✨ Features

* Recursive family tree rendering
* Expand / collapse family branches
* Search and highlight family members
* Auto-expand when searching
* Horizontal scroll support for large trees
* Mobile-friendly layout

## 🧱 Tech Stack

* Astro
* Tailwind CSS
* JSON (static data)

## 📂 Project Structure

```txt
src/
  components/
    TreeNode.astro
  data/
    family.json
  pages/
    index.astro
```

## 🧾 Data Source

Family data is manually structured from internal family records.

## 🚀 Getting Started

Clone this repository:

```bash
git clone https://github.com/arkan69/family-tree.git
cd family-tree
npm install
npm run dev
```

Open in browser:

```txt
http://localhost:4321
```

## 🔄 Updating Family Data

All family data is stored in:

```txt
src/data/family.json
```

After updating the file:

```bash
git add .
git commit -m "update family data"
git push
```

The deployed site will automatically update via Vercel.

## 🌍 Deployment

This project is deployed using Vercel with automatic deployment on every push to the main branch.

## 👤 Author

Arkansyah Putra Wibowo

---

Built with purpose for family, and as a meaningful personal project.
