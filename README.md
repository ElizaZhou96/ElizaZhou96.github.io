<h1 align="center">
👨🏻‍🎓Academic Homepage of Yutong👩🏻‍🎓(ෆ`꒳´ෆ)~ 
</h1>

⭐ The source code of this homepage is based on [**AcadHomepage**](https://github.com/RayeRen/acad-homepage.github.io). If you want to reuse their source code, please credit them appropriately.

### ✒ Quick Start
> For more details, please refer to [**AcadHomepage**](https://github.com/RayeRen/acad-homepage.github.io).
1. Generate icon using [**favicon-generator**](https://redketchup.io/favicon-generator) and upload all files to `images` folder.
2. Update `_config.yml` for **basic settings** (Name, Email...).
3. Uptade contents in `_pages/about.md` for **main contents** (Education, Publications...).
4. Update `_data/navigation.yml` for **links** of header.
5. Update `_includes/head/custom.html` to change the **icon of head**.
6. Add [**ClustrMaps**](https://clustrmaps.com/) to `_layouts/default.html`.

### :house: Run Workflow
> For more details, please refer to [**AcadHomepage**](https://github.com/RayeRen/acad-homepage.github.io).
1. **Clone** REPO to local using `git clone https://github.com/xxx/xxx.github.io.git`.
2. Install Jekyll **building environment**, including `Ruby`, `RubyGems`, `GCC` and `Make` following the [installation guide](https://jekyllrb.com/docs/installation/#requirements).
3. Run bash `run_server.sh` to start **Jekyll** livereload server.
4. Open [http://127.0.0.1:4000](http://127.0.0.1:4000) in your browser and do changes.
5. When you finish the modification of your homepage, `commit` your changings and `push` to your remote REPO using `git` command.

### 💫 Git
1. Setup user email and user name
```
git config --global user.email "xxx"
git config --global user.name "xxx"
```
2. Setup SSH

  * Refer to [Connecting to GitHub with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).

3. Add & Status
```
git add .
git status
```
4. Commit & Status
```
git commit -m "xxx"
git status
```
5. Pull & Push
```
git pull
git push origin <branch name>
```
