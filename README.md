# Myst Template (jtex) - Cookiecutter

This [cookiecutter](https://github.com/cookiecutter/cookiecutter) repository helps you get setup with creating a `jtex` template for working with MyST Markdown.

```bash
pip install cookiecutter
cookiecutter gh:myst-templates/jtex-template
```

You can also choose to fork this repository, and replace the templated values in all files!

## Steps to creating your own template!

- [ ] 🆕 `cookiecutter gh:myst-templates/jtex-template` (or fork this repository, and update the template values)
- [ ] 📑 Replace the `template.tex` with your template content
- [ ] 👯‍♀️ Copy in any other style, definitions or images necessary for the template
- [ ] 👩‍🔬 Add the files n ecessary into `files` list in the `template.yml`
- [ ] 🧙‍♀️ Start replacing template values with `[-options.my_value-]` and put in `[# if parts.abstract #]` conditions to toggle sections on and off
- [ ] 👩🏿‍💻 Install `jtex` (`npm install -g jtex`) and run `jtex check`
- [ ] 🪄 Continue to improve the options in your template for `parts` and `options`
- [ ] 💾 When ready, save your `template.yml` and run `jtex check --fix`, this will add various packages that are auto detected and fix document options
- [ ] 🧪 Test with real content: `myst build my-document.md --template ../path/to/template`
- [ ] 📸 Create a `thumbnail.png` with an accurate screenshot of the template
- [ ] 🧭 Update this README, and check all values in the `template.yml`
- [ ] 🚀 Push to GitHub, and contribute to the [community templates repository](https://github.com/myst-templates/templates)
