# Presentation about Harbor project

* Presentation git repository: [https://github.com/ruzickap/k8s-harbor-presentation](https://github.com/ruzickap/k8s-harbor-presentation)
* Presentation URL: [https://ruzickap.github.io/k8s-harbor-presentation](https://ruzickap.github.io/k8s-harbor-presentation)
* Demo Git repository: [https://github.com/ruzickap/k8s-harbor](https://github.com/ruzickap/k8s-harbor)
* Demo web pages: [https://ruzickap.github.io/k8s-harbor/](https://ruzickap.github.io/k8s-harbor/)

---

## Notes

Few commands how to initialize this git repository.

### Initial setup

Create GitHub repository by selecting proper `.gitignore` and license.

```bash
git clone git@github.com:ruzickap/k8s-harbor-presentation.git
cd k8s-harbor-presentation
git submodule add https://github.com/hakimel/reveal.js.git revealjs
cp revealjs/demo.html index.html
cp revealjs/{package*,gruntfile.js} .
```

### Development

```bash
npm install
npm start
```
