
# R Take-Home Assignments (PhD Course)

This repository contains the complete set of **R take-home assignments** and **answers** for the PhD course *R Programming for Data Analysis*.

All materials are organised in two top-level folders:

- **Exercises/** – student versions of all assignments (with hints in code blocks)  
- **Answers/** – corresponding instructor/solution versions (same text, filled-in code)

Each folder contains:
- Individual `.Rmd` files (to open and edit in RStudio)
- Pre-rendered PDFs (`all_exercises.pdf` / `all_answers.pdf`)
- A front page explaining how to use the materials

---

## 🚀 How to use

You can work with these assignments in two ways:

1. **Using Git** — clone the repository:

   ```bash
   git clone https://github.com/<your-org>/<repo-name>.git
   ```

2. **Without Git** — download the latest ZIP bundles from the  
   [**Releases page**](../../releases) and unzip them locally.

Then open any `.Rmd` file in **RStudio**, fill in the missing code where the comments indicate tasks, and click **Knit** to create your own PDF or HTML output.

---

## 🧩 What you will learn

Across six assignments, you will:

1. **Introduction & patient data** – reading, wrangling, plotting  
2. **Penguins** – exploratory data analysis and visualisation  
3. **COVID** – loops, conditionals, moving averages, flags  
4. **World development** – exploring GDP, life expectancy, and CO₂ emissions  
5. **Statistics with penguins** – *intro to t-tests, ANOVA, effect sizes, diagnostics*  
6. **Modeling life expectancy** – simple → multiple regression models, diagnostics, reflection

Assignment 5 is intentionally a bit more in-depth to provide a gentle introduction to statistics in R.

---

## 🧾 Building the combined PDFs

To recreate the concatenated PDFs yourself, knit the corresponding `.Rmd` files:

```r
rmarkdown::render("Exercises/combined_assignments.Rmd")  # All exercises
rmarkdown::render("Answers/combined_answers.Rmd")        # All answers
```

Each combined file includes a front page with usage instructions and a short RMarkdown primer.

---

## 🧠 Tips for students

- Use the `.Rmd` versions for hands-on work.  
- The PDFs are great as quick references.  
- The **answers** are for review only — try the exercises first!  
- For help in R, use:
  ```r
  ?drop_na
  ??"linear model"
  example(lm)
  ```

---

## 📜 License

These materials are shared under the [MIT License](LICENSE) and may be reused for teaching and research with attribution.

---

## ✉️ Contact

Questions or feedback: **Bauke van der Velde** — please open an issue or contact directly.
