# {{cookiecutter.title}}

{{cookiecutter.description}}

![](thumbnail.png)

- Author: {{cookiecutter.author_name}} ({{cookiecutter.author_affiliation}})
- Author Website: {{cookiecutter.author_website}}
- License: {{cookiecutter.license}}
- [Submission Guidelines]({{cookiecutter.source}})

## Steps to creating your own template!

- [ ] 📑 Replace the `template.tex` with your template content
- [ ] 👯‍♀️ Copy in any other style, definitions or images necessary for the template
- [ ] 👩‍🔬 Add the files necessary into `files` list in the `template.yml`
- [ ] 🧙‍♀️ Start replacing template values with `[-options.my_value-]` and put in `[# if parts.abstract #]` conditions to toggle sections on and off
- [ ] 👩🏿‍💻 Install `jtex` (`npm install -g jtex`) and run `jtex check`
- [ ] 🪄 Continue to improve the options in your template for `parts` and `options`
- [ ] 💾 When ready, save your `template.yml` and run `jtex check --fix`, this will add various packages that are auto detected and fix document options
- [ ] 🧪 Test with real content: `myst build my-document.md --template ../path/to/template`
- [ ] 📸 Create a `thumbnail.png` with an accurate screenshot of the template
- [ ] 🧭 Update this README, and check all values in the `template.yml`
- [ ] 🚀 Push to GitHub, and contribute to the [community templates repository](https://github.com/myst-templates/templates)
