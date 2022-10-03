# MyST Template (jtex) - Cookiecutter

Create a LaTeX template that works with MyST Markdown, [👉 full tutorial is here 👈](https://js.myst.tools/jtex/create-a-latex-template).
This [cookiecutter](https://github.com/cookiecutter/cookiecutter) repository helps you get setup with creating a `jtex` template for working with MyST Markdown.

```bash
pip install cookiecutter
cookiecutter gh:myst-templates/jtex-template
```

You can also choose to fork this repository, and replace the templated values in all files!

## Steps to creating your own template!

- [ ] 🆕 `cookiecutter gh:myst-templates/jtex-template` (or fork this repository, and update the template values)
- [ ] 📑 Replace the `template.tex` with your existing LaTeX template/article
- [ ] 👯‍♀️ Copy in any other style, definitions or images necessary for the template
- [ ] 👩‍🔬 Add the files necessary into `files` list in the `template.yml` ([documentation](https://js.myst.tools/jtex/template-yml))
- [ ] 🧙‍♀️ Start replacing template values with `[-options.my_value-]` and put in `[# if parts.abstract #]` conditions to toggle sections on and off ([documentation](https://js.myst.tools/jtex/template-rules))
- [ ] 👩🏿‍💻 Install [jtex](https://js.myst.tools/jtex) (`npm install -g jtex`) and run `jtex check` ([documentation](https://js.myst.tools/jtex/command-line))
- [ ] 🪄 Continue to improve the options in your template for `parts` and `options` ([documentation](https://js.myst.tools/jtex/document))
- [ ] 💾 When ready, save your `template.yml` and run `jtex check --fix`, this will add various packages that are auto detected and fix document options ([documentation](https://js.myst.tools/jtex/command-line))
- [ ] 🧪 Test with real content: `myst build my-document.md --template ../path/to/template` ([documentation](https://js.myst.tools/guide/creating-pdf-documents))
- [ ] 📸 Create a `thumbnail.png` with an accurate screenshot of the template
- [ ] 🧭 Update this README, and check all values in the `template.yml`
- [ ] 🚀 Push to GitHub, and contribute to the [community templates repository](https://github.com/myst-templates/templates)
