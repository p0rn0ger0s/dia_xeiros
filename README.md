# Dia Xeiros — τοπικά αρχεία για επεξεργασία σε VS Code

Εξαγωγή της σελίδας σου από το landingsite.ai, καθαρισμένη ώστε να την επεξεργάζεσαι τοπικά.

## Δομή

    index.html          ← Η σελίδα σου. ΕΔΩ επεξεργάζεσαι κείμενα & δομή (61 KB)
    css/
      site.css          ← Χρώματα, γραμματοσειρές, animations — ΕΔΩ αλλάζεις theme
      tailwind.css      ← Utility classes (μην το πειράζεις)
      fonts.css         ← Source Sans Pro + Merriweather Sans
      fontawesome.css   ← Εικονίδια
    images/             ← Οι 8 εικόνες, βγαλμένες από το base64

## Πώς το ανοίγεις
Διπλό κλικ στο `index.html` → ανοίγει στον browser, ίδιο με το online.
Ή στο VS Code: εγκατέστησε την επέκταση **Live Server**, δεξί κλικ στο
`index.html` → "Open with Live Server".

## Πώς αλλάζεις πράγματα
- **Κείμενα**: βρες τη λέξη μέσα στο `index.html` και άλλαξέ την.
- **Χρώματα**: `css/site.css`, πάνω-πάνω τα `--accent-color`, `--primary-color` κ.λπ.
- **Στυλ (μέγεθος, χρώμα, spacing)**: αλλάζεις τις Tailwind classes μέσα στο
  HTML, π.χ. `text-4xl` → `text-5xl`, `bg-white` → `bg-gray-100`.
- **Εικόνες**: αντικατάστησε τα αρχεία στο `images/` (κράτα το ίδιο όνομα) ή
  άλλαξε το `src=` στο HTML.

## Προσοχή
Αυτό είναι στατικό αντίγραφο. Δεν έχει την React interactivity του builder
(forms που στέλνουν email, δυναμικά μενού κ.λπ.). Για απλή landing page όμως,
ό,τι βλέπεις δουλεύει. Τα εικονίδια/γραμματοσειρές είναι ενσωματωμένα, οπότε
λειτουργεί και χωρίς internet.
