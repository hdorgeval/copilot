# Copilot

![copilot](./snapshots/copilot-01.png)
[With GitHub Copilot, get suggestions for whole lines or entire functions right inside your editor.](https://copilot.github.com/)

## Some feedbacks on copilot usage


---

### 100% match

![match01](./snapshots/screenshot-01.png)

---

### 90% match but 100% in the intent

Here I just started to write the function signature, and copilot inferred all the code that should be in that function.
Copilot did infer correctly that the code inside the function is about to change a markdown file, but he proposed to modify the `README.md` which is not the right one.

![Match02](./snapshots/screenshot-02.png)

Final version:

![match02](./snapshots/screenshot-02-final.png)

---

### 0% match — complete failure

Here I just started to write the function signature, and copilot could not infer something useful from the function signature.

The idea of that function is, given the start date of a project and given the percentage of the `done` as of today, estimate the end date of the project.

![Match03](./snapshots/screenshot-03.png)

---
