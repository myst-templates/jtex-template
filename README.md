# MyST Template (jtex) - Cookiecutter

Create a LaTeX template that works with MyST Markdown, [๐ full tutorial is here ๐](https://js.myst.tools/jtex/create-a-latex-template).
This [cookiecutter](https://github.com/cookiecutter/cookiecutter) repository helps you get setup with creating a `jtex` template for working with MyST Markdown.

```bash
pip install cookiecutter
cookiecutter gh:myst-templates/jtex-template
```

You can also choose to fork this repository, and replace the templated values in all files!

## Steps to creating your own template!

- [ ] ๐ `cookiecutter gh:myst-templates/jtex-template` (or fork this repository, and update the template values)
- [ ] ๐ Replace the `template.tex` with your existing LaTeX template/article
- [ ] ๐ฏโโ๏ธ Copy in any other style, definitions or images necessary for the template
- [ ] ๐ฉโ๐ฌ Add the files necessary into `files` list in the `template.yml` ([documentation](https://js.myst.tools/jtex/template-yml))
- [ ] ๐งโโ๏ธ Start replacing template values with `[-options.my_value-]` and put in `[# if parts.abstract #]` conditions to toggle sections on and off ([documentation](https://js.myst.tools/jtex/template-rules))
- [ ] ๐ฉ๐ฟโ๐ป Install [jtex](https://js.myst.tools/jtex) (`npm install -g jtex`) and run `jtex check` ([documentation](https://js.myst.tools/jtex/command-line))
- [ ] ๐ช Continue to improve the options in your template for `parts` and `options` ([documentation](https://js.myst.tools/jtex/document))
- [ ] ๐พ When ready, save your `template.yml` and run `jtex check --fix`, this will add various packages that are auto detected and fix document options ([documentation](https://js.myst.tools/jtex/command-line))
- [ ] ๐งช Test with real content: `myst build my-document.md --template ../path/to/template` ([documentation](https://js.myst.tools/guide/creating-pdf-documents))
- [ ] ๐ธ Create a `thumbnail.png` with an accurate screenshot of the template
- [ ] ๐งญ Update this README, and check all values in the `template.yml`
- [ ] ๐ Push to GitHub, and contribute to the [community templates repository](https://github.com/myst-templates/templates)
