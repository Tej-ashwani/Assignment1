# 🧩 Design System Assignment

A scalable, reusable design system using **React**, **TypeScript**, **TailwindCSS**, and **Storybook**. Includes components for Typography, Data Entry, and Feedback — built for enterprise-grade accessibility, theming, and responsiveness.

## 📦 Live Demo: https://silver-sprite-888a97.netlify.app/

---

## 📦 Sample
![Screenshot (253)](https://github.com/user-attachments/assets/2c3a7a51-c85d-4b5c-b270-c9a283267450)

 ![Screenshot (252)](https://github.com/user-attachments/assets/6db609dc-79a7-4e0d-9f90-690e9e2c26ea)

![Screenshot (250)](https://github.com/user-attachments/assets/4c1eda4e-88da-4fa1-82eb-d779fad58369)

![Screenshot (251)](https://github.com/user-attachments/assets/93391a1c-050b-46c3-ba64-d80ef8934905)

![Screenshot (249)](https://github.com/user-attachments/assets/ab96d333-909d-48c4-ae1b-d7174c1766bd)

---

## 📦 Tech Stack

- ⚛️ React
- 🟦 TypeScript
- 🎨 TailwindCSS (or styled-components)
- 📚 Storybook

---

## 📁 Folder Structure

src/
├── components/ │
├── Typography/ │
├── TextInput/ │
├── ToggleSwitch/ │
├── Toast/ │
└── Modal/ ├
── themes/ 
│ └── index.ts ├
── stories/ │
└── *.stories.tsx ├
── utils/ │
└── accessibility.ts
└── App.tsx


---

## ✅ Components

### 1️⃣ Typography

- Headings (H1 – H6)
- Paragraphs
- Labels, Captions, Helper Text

### 2️⃣ Data Entry (You can choose 1–2)

- Text Input
- Dropdown / Select
- Checkbox
- Radio Button
- Toggle Switch
- Date Picker
- File Upload

**Implemented:**
- ✅ `TextInput`
- ✅ `ToggleSwitch`

### 3️⃣ Feedback Components (You can choose 1–2)

- Toast / Snackbar
- Popover
- Alert Banner
- Modal Dialog

**Implemented:**
- ✅ `Toast`
- ✅ `Modal`

---

## 📚 Storybook Documentation Checklist

Each component includes:

- ✅ Component name + description
- ✅ Props / API with TypeScript interfaces
- ✅ Use cases
- ✅ Anatomy / Structure
- ✅ States & variants
- ✅ Interaction behavior
- ✅ Accessibility notes (ARIA roles, focus)
- ✅ Theming / responsiveness
- ✅ Do’s and Don’ts / Best Practices

---

## 🎨 Theming + Accessibility

- 🌙 Light/Dark mode
- 🎨 Brand tokens using Tailwind config
- ♿ Accessible contrast ratios
- 📏 Responsive font sizes and layouts
- ⌨️ Keyboard navigation
- 🔊 ARIA roles and screen reader support

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/Tej-ashwani/Assignment.git
cd Assignment

# 2. Install dependencies
npm install

# 3. Start Storybook
npm run storybook

# 4. Start the app (optional)
npm run dev
