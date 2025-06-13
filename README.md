# Habbo Classic Posters Integration Guide

---

## 🎨 Overview
This project brings back the charm of approximately **98 unique poster images** extracted from the legacy `posters.swf` Flash file. With Adobe Flash now retired, these nostalgic posters have been converted into modern `.nitro` files for seamless integration into your catalog system. This guide walks you through the extraction details and integration steps to revive these classics.

---

## 🛠️ Extraction Details
- **Source File**: `posters.swf`
- **Extracted Content**: ~98 unique poster images
- **Output Format**: `.nitro` files, optimized for modern compatibility

---

## 🚀 Integration Instructions
Follow these steps to integrate the posters into your catalog system:

### 1. Update the `catalog_items` SQL
- **Action**: Modify the `catalog_items` table in your database.
- **Steps**:
  - Replace `page_id_here` with the desired catalog page ID where posters will appear.

### 2. Update the `furnidata` File
- **Action**: Add poster entries to the **bottom half** of your `furnidata` file.
- **Details**:
  - The **top half** is reserved for floor furniture; the **bottom half** is for wall furniture like posters.

---

## 📝 Notes
- **Testing**: After integration, test the catalog to confirm posters display correctly and are selectable.

---

**Bring your catalog to life with these iconic Habbo posters!** 🎉
