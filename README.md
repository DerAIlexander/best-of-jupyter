<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Jupyter
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome Jupyter projects. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of-badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-290-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-jupyter/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-jupyter?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 290 awesome open-source projects with a total of 300K stars grouped into 13 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-jupyter/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-jupyter/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-jupyter/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Notebook Environments](#notebook-environments) _15 projects_
- [Interactive Widgets & Visualization](#interactive-widgets--visualization) _54 projects_
- [Jupyter Extensions](#jupyter-extensions) _25 projects_
- [Jupyter Magic](#jupyter-magic) _12 projects_
- [Jupyter Kernels](#jupyter-kernels) _38 projects_
- [Notebook Sharing & Conversion](#notebook-sharing--conversion) _24 projects_
- [Notebook Tools](#notebook-tools) _24 projects_
- [JupyterLab Renderer](#jupyterlab-renderer) _8 projects_
- [JupyterLab Themes](#jupyterlab-themes) _9 projects_
- [JupyterLab Extensions](#jupyterlab-extensions) _51 projects_
- [JupyterHub Authenticators](#jupyterhub-authenticators) _15 projects_
- [JupyterHub Spawners](#jupyterhub-spawners) _8 projects_
- [Jupyter Components](#jupyter-components) _3 projects_
- [Others](#others) _3 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## Notebook Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Development environments with support for Jupyter Notebooks._

<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab">JupyterLab</a></b> (🥇44 ·  ⭐ 12K) - JupyterLab computational environment. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab) (👨‍💻 460 · 🔀 2.2K · 📥 23K · 📦 55K · 📋 6.4K - 31% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jupyterlab/jupyterlab
	```
- [PyPi](https://pypi.org/project/jupyterlab) (📥 1.1M / month · 📦 1.8K · ⏱️ 13.01.2022):
	```
	pip install jupyterlab
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab) (📥 5M · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇44 ·  ⭐ 9.6K) - Jupyter Interactive Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/notebook) (👨‍💻 570 · 🔀 3.6K · 📥 4K · 📦 130K · 📋 4.4K - 47% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jupyter/notebook
	```
- [PyPi](https://pypi.org/project/notebook) (📥 13M / month · 📦 8.6K · ⏱️ 12.01.2022):
	```
	pip install notebook
	```
- [Conda](https://anaconda.org/conda-forge/jupyter) (📥 1.7M · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge jupyter
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 26M · ⭐ 890 · ⏱️ 12.01.2022):
	```
	docker pull jupyter/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥈38 ·  ⭐ 6.8K · 📈) - Multi-user server for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyterhub) (👨‍💻 260 · 🔀 1.7K · 📦 1.6K · 📋 2.1K - 9% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jupyterhub/jupyterhub
	```
- [PyPi](https://pypi.org/project/jupyterhub) (📥 160K / month · 📦 360 · ⏱️ 10.01.2022):
	```
	pip install jupyterhub
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 490K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge jupyterhub
	```
- [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 2.5M · ⭐ 300 · ⏱️ 12.01.2022):
	```
	docker pull jupyterhub/jupyterhub
	```
</details>
<details><summary><b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥈31 ·  ⭐ 5.7K) - The interactive computing suite for you!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/nteract) (👨‍💻 180 · 🔀 560 · 📥 1.3M · 📋 1.7K - 9% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/nteract/nteract
	```
- [PyPi](https://pypi.org/project/nteract_on_jupyter) (📥 2.9K / month · 📦 5 · ⏱️ 16.07.2019):
	```
	pip install nteract_on_jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈30 ·  ⭐ 6.8K) - Ready-to-run Docker images containing Jupyter applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/docker-stacks) (👨‍💻 210 · 🔀 2.6K · 📋 710 - 9% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jupyter/docker-stacks
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook) (📥 80M · ⭐ 330 · ⏱️ 12.01.2022):
	```
	docker pull jupyter/scipy-notebook
	```
</details>
<details><summary><b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥈27 ·  ⭐ 970) - Interactive tools and developer experiences for Big Data on Google.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googledatalab/datalab) (👨‍💻 52 · 🔀 260 · 📋 900 - 25% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/googledatalab/datalab
	```
- [PyPi](https://pypi.org/project/datalab) (📥 300K / month · 📦 12 · ⏱️ 25.03.2020):
	```
	pip install datalab
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥉25 ·  ⭐ 2K) - Kaggle Python docker image. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/docker-python) (👨‍💻 140 · 🔀 790 · 📋 290 - 7% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/kaggle/docker-python
	```
- [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 190K · ⭐ 160 · ⏱️ 05.01.2022):
	```
	docker pull kaggle/python
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥉25 ·  ⭐ 510 · 📈) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/vscode-jupyter) (👨‍💻 240 · 🔀 100 · 📋 6.6K - 9% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/microsoft/vscode-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/retrolab">retrolab</a></b> (🥉24 ·  ⭐ 220) - JupyterLab distribution with a retro look and feel. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/retrolab) (👨‍💻 16 · 🔀 37 · 📥 330 · 📦 44 · 📋 130 - 33% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/jupyterlab/retrolab
	```
- [PyPi](https://pypi.org/project/retrolab) (📥 880 / month · 📦 2 · ⏱️ 07.01.2022):
	```
	pip install retrolab
	```
- [Conda](https://anaconda.org/conda-forge/retrolab) (📥 5.7K · ⏱️ 07.01.2022):
	```
	conda install -c conda-forge retrolab
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥉23 ·  ⭐ 210) - SoS workflow system for daily data analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/sos) (👨‍💻 33 · 🔀 28 · 📦 1.6K · 📋 1.4K - 4% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/vatlab/SOS
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉21 ·  ⭐ 2.4K) - All-in-one web-based IDE specialized for machine learning and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-workspace) (👨‍💻 10 · 🔀 320 · 📋 76 - 7% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/ml-tooling/ml-workspace
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-workspace) (📥 500K · ⭐ 20 · ⏱️ 13.07.2021):
	```
	docker pull mltooling/ml-workspace
	```
</details>
<details><summary><b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉20 ·  ⭐ 3.8K) - Run code interactively, inspect data, and plot. All the power of Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nteract/hydrogen) (👨‍💻 88 · 🔀 350 · 📋 1.2K - 12% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/nteract/hydrogen
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉17 ·  ⭐ 210) - Multi-user development platform for machine learning teams. Simple to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-hub) (👨‍💻 7 · 🔀 45 · 📥 1.7K · 📋 26 - 57% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/ml-tooling/ml-hub
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-hub) (📥 44K · ⭐ 5 · ⏱️ 18.02.2020):
	```
	docker pull mltooling/ml-hub
	```
</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉14 ·  ⭐ 290) - Leverage the flexibility of Jupyterlab through the power of your.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iot-salzburg/gpu-jupyter) (👨‍💻 10 · 🔀 110 · 📋 45 - 13% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/iot-salzburg/gpu-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlite">jupyterlite</a></b> (🥉12 ·  ⭐ 53 · 🐣) - Wasm powered Jupyter running in the browser. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlite) (👨‍💻 16 · 🔀 6 · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jtpio/jupyterlite
	```
</details>
<br>

## Interactive Widgets & Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide interactive UI-widgets and visualization tools._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b>  - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇43 ·  ⭐ 16K · 📈) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 590 · 🔀 3.9K · 📦 43K · 📋 6.8K - 10% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 1.9M / month · 📦 3.5K · ⏱️ 06.01.2022):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 6.3M · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇39 ·  ⭐ 2.4K) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipywidgets) (👨‍💻 190 · 🔀 790 · 📦 3K · 📋 1.7K - 33% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jupyter-widgets/ipywidgets
	```
- [PyPi](https://pypi.org/project/ipywidgets) (📥 12M / month · 📦 8.5K · ⏱️ 23.12.2021):
	```
	pip install ipywidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 4.2M · ⏱️ 23.12.2021):
	```
	conda install -c conda-forge ipywidgets
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 95K / month · 📦 77 · ⏱️ 23.12.2021):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/pandas-profiling/pandas-profiling">pandas-profiling</a></b> (🥇36 ·  ⭐ 8.4K) - Create HTML profiling reports from pandas DataFrame objects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pandas-profiling/pandas-profiling) (👨‍💻 83 · 🔀 1.2K · 📦 6.4K · 📋 530 - 18% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 960K / month · 📦 140 · ⏱️ 27.09.2021):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 180K · ⏱️ 28.09.2021):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥇35 ·  ⭐ 1.6K) - A high-level app and dashboarding solution for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/panel) (👨‍💻 82 · 🔀 220 · 📦 2.6K · 📋 1.6K - 31% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/holoviz/panel
	```
- [PyPi](https://pypi.org/project/panel) (📥 300K / month · 📦 84 · ⏱️ 06.01.2022):
	```
	pip install panel
	```
- [Conda](https://anaconda.org/conda-forge/panel) (📥 360K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge panel
	```
</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥇32 ·  ⭐ 1.2K) - Matplotlib Jupyter Integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/matplotlib/ipympl) (👨‍💻 25 · 🔀 170 · 📦 2.4K · 📋 230 - 42% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/matplotlib/ipympl
	```
- [PyPi](https://pypi.org/project/ipympl) (📥 59K / month · 📦 70 · ⏱️ 04.01.2022):
	```
	pip install ipympl
	```
- [npm](https://www.npmjs.com/package/jupyter-matplotlib) (📥 45K / month · ⏱️ 15.12.2021):
	```
	npm install jupyter-matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥇32 ·  ⭐ 1.2K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 73 · 🔀 320 · 📦 1.4K · 📋 470 - 38% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 43K / month · 📦 100 · ⏱️ 06.12.2021):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 790K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge ipyleaflet
	```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 36K / month · 📦 2 · ⏱️ 06.12.2021):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈31 ·  ⭐ 3.2K) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 55 · 🔀 460 · 📦 29 · 📋 580 - 38% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 47K / month · 📦 90 · ⏱️ 07.01.2022):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 910K · ⏱️ 07.01.2022):
	```
	conda install -c conda-forge bqplot
	```
- [npm](https://www.npmjs.com/package/bqplot) (📥 17K / month · 📦 10 · ⏱️ 07.01.2022):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥈29 ·  ⭐ 4.5K) - Parameterize, execute, and analyze notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/papermill) (👨‍💻 96 · 🔀 340 · 📦 1.8K · 📋 330 - 30% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/nteract/papermill
	```
- [PyPi](https://pypi.org/project/papermill) (📥 390K / month · 📦 170 · ⏱️ 09.03.2021):
	```
	pip install papermill
	```
- [Conda](https://anaconda.org/conda-forge/papermill) (📥 220K · ⏱️ 21.10.2021):
	```
	conda install -c conda-forge papermill
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈28 ·  ⭐ 6.8K · 💤) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 28 · 🔀 830 · 📦 95 · 📋 150 - 50% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 100K / month · 📦 4 · ⏱️ 24.07.2019):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipyvolume">ipyvolume</a></b> (🥈28 ·  ⭐ 1.7K) - 3d plotting for Python in the Jupyter notebook based on IPython.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipyvolume) (👨‍💻 39 · 🔀 210 · 📦 660 · 📋 300 - 58% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/maartenbreddels/ipyvolume
	```
- [PyPi](https://pypi.org/project/ipyvolume) (📥 21K / month · 📦 48 · ⏱️ 29.10.2021):
	```
	pip install ipyvolume
	```
- [Conda](https://anaconda.org/conda-forge/ipyvolume) (📥 340K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge ipyvolume
	```
- [npm](https://www.npmjs.com/package/ipyvolume) (📥 2.1K / month · 📦 3 · ⏱️ 29.10.2021):
	```
	npm install ipyvolume
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈26 ·  ⭐ 780) - A Jupyter - Three.js bridge. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 29 · 🔀 160 · 📦 19 · 📋 210 - 31% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs) (📥 28K / month · 📦 34 · ⏱️ 26.02.2021):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 360K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge pythreejs
	```
- [npm](https://www.npmjs.com/package/jupyter-threejs) (📥 4.5K / month · 📦 7 · ⏱️ 26.02.2021):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/lux-org/lux">lux</a></b> (🥈25 ·  ⭐ 3.2K) - Automatically visualize your pandas dataframe via a single print!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lux-org/lux) (👨‍💻 19 · 🔀 260 · 📦 67 · 📋 200 - 30% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/lux-org/lux
	```
- [PyPi](https://pypi.org/project/lux-api) (📥 8.7K / month · ⏱️ 10.09.2021):
	```
	pip install lux-api
	```
- [Conda](https://anaconda.org/conda-forge/lux-api) (📥 3.4K · ⏱️ 11.09.2021):
	```
	conda install -c conda-forge lux-api
	```
- [npm](https://www.npmjs.com/package/luxwidget) (📥 560 / month · ⏱️ 24.10.2021):
	```
	npm install luxwidget
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/ipyregulartable">ipyregulartable</a></b> (🥈25 ·  ⭐ 2.4K) - High performance, editable, stylable datagrids in jupyter.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/ipyregulartable) (👨‍💻 4 · 🔀 790 · 📦 9 · 📋 25 - 40% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/jpmorganchase/ipyregulartable
	```
- [PyPi](https://pypi.org/project/ipyregulartable) (📥 65 / month · ⏱️ 08.01.2021):
	```
	pip install ipyregulartable
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 95K / month · 📦 77 · ⏱️ 23.12.2021):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥈25 ·  ⭐ 2.4K) - ipywidgets library for drawing directed acyclic graphs in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/ipydagred3) (👨‍💻 3 · 🔀 790 · 📦 9 · 📋 19 - 26% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/ipydagred3
	```
- [PyPi](https://pypi.org/project/ipydagred3) (📥 330 / month · 📦 1 · ⏱️ 31.12.2020):
	```
	pip install ipydagred3
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 95K / month · 📦 77 · ⏱️ 23.12.2021):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈25 ·  ⭐ 380) - This project provides responsible AI user interfaces.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 24 · 🔀 91 · 📦 18 · 📋 220 - 21% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/microsoft/responsible-ai-widgets
	```
- [PyPi](https://pypi.org/project/raiwidgets) (📥 3.7K / month · 📦 2 · ⏱️ 05.01.2022):
	```
	pip install raiwidgets
	```
</details>
<details><summary><b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥈25 ·  ⭐ 170) - A Cytoscape Jupyter widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cytoscape/ipycytoscape) (👨‍💻 29 · 🔀 48 · 📥 3 · 📦 55 · 📋 140 - 38% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/cytoscape/ipycytoscape
	```
- [Conda](https://anaconda.org/conda-forge/ipycytoscape) (📥 26K · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge ipycytoscape
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥈24 ·  ⭐ 590 · 💤) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 21 · 🔀 130 · 📦 120 · 📋 100 - 34% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl) (📥 13K / month · 📦 14 · ⏱️ 02.06.2019):
	```
	pip install mapboxgl
	```
</details>
<details><summary><b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥈24 ·  ⭐ 520) - Interactive Canvas in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/martinRenou/ipycanvas) (👨‍💻 14 · 🔀 42 · 📦 340 · 📋 100 - 37% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/martinRenou/ipycanvas
	```
- [PyPi](https://pypi.org/project/ipycanvas) (📥 6.7K / month · 📦 12 · ⏱️ 01.12.2021):
	```
	pip install ipycanvas
	```
- [Conda](https://anaconda.org/conda-forge/ipycanvas) (📥 36K · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge ipycanvas
	```
</details>
<details><summary><b><a href="https://github.com/nglviewer/nglview">nglview</a></b> (🥈24 ·  ⭐ 510) - Jupyter widget to interactively view molecular structures and trajectories. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nglviewer/nglview) (👨‍💻 33 · 🔀 100 · 📥 200 · 📦 2 · 📋 420 - 6% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/nglviewer/nglview
	```
- [PyPi](https://pypi.org/project/nglview) (📥 2.7K / month · 📦 37 · ⏱️ 11.06.2021):
	```
	pip install nglview
	```
- [Conda](https://anaconda.org/conda-forge/nglview) (📥 390K · ⏱️ 11.06.2021):
	```
	conda install -c conda-forge nglview
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥈24 ·  ⭐ 320) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 10 · 🔀 55 · 📋 95 - 14% open · ⏱️ 02.01.2022):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 13K / month · 📦 82 · ⏱️ 03.06.2021):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 470K · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥉23 ·  ⭐ 650 · 💤) - Develop Dash apps in the Jupyter Notebook and JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyter-dash) (👨‍💻 3 · 🔀 170 · 📥 65 · 📦 1.1K · 📋 49 - 69% open · ⏱️ 22.01.2021):

	```
	git clone https://github.com/plotly/jupyter-dash
	```
- [PyPi](https://pypi.org/project/jupyter-dash) (📥 36K / month · 📦 13 · ⏱️ 22.01.2021):
	```
	pip install jupyter-dash
	```
</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥉23 ·  ⭐ 40) - JWST astronomical data analysis tools in the Jupyter platform. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spacetelescope/jdaviz) (👨‍💻 25 · 🔀 26 · 📋 520 - 47% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/spacetelescope/jdaviz
	```
- [PyPi](https://pypi.org/project/jdaviz) (📥 290 / month · ⏱️ 23.12.2021):
	```
	pip install jdaviz
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉22 ·  ⭐ 620) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 120 · 📋 100 - 54% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 6.2K / month · 📦 3 · ⏱️ 12.10.2021):
	```
	pip install witwidget
	```
- [npm](https://www.npmjs.com/package/wit-widget) (📥 3.2K / month · ⏱️ 12.10.2021):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/mariobuikhuizen/ipyvuetify">ipyvuetify</a></b> (🥉22 ·  ⭐ 240) - Jupyter widgets based on vuetify UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mariobuikhuizen/ipyvuetify) (👨‍💻 10 · 🔀 38 · 📦 4 · 📋 160 - 28% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/mariobuikhuizen/ipyvuetify
	```
- [PyPi](https://pypi.org/project/ipyvuetify) (📥 33K / month · 📦 10 · ⏱️ 06.08.2021):
	```
	pip install ipyvuetify
	```
- [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 67K · ⏱️ 06.08.2021):
	```
	conda install -c conda-forge ipyvuetify
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipysheet">ipysheet</a></b> (🥉21 ·  ⭐ 460) - Jupyter handsontable integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipysheet) (👨‍💻 10 · 🔀 58 · 📦 3 · 📋 120 - 51% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/QuantStack/ipysheet
	```
- [PyPi](https://pypi.org/project/ipysheet) (📥 20K / month · 📦 13 · ⏱️ 11.08.2021):
	```
	pip install ipysheet
	```
- [Conda](https://anaconda.org/conda-forge/ipysheet) (📥 41K · ⏱️ 11.08.2021):
	```
	conda install -c conda-forge ipysheet
	```
- [npm](https://www.npmjs.com/package/ipysheet) (📥 2.8K / month · ⏱️ 13.08.2021):
	```
	npm install ipysheet
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥉21 ·  ⭐ 240) - Pandas DataFrames and Series as Interactive DataTables. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/itables) (👨‍💻 3 · 🔀 20 · 📦 86 · 📋 29 - 13% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/mwouts/itables
	```
- [PyPi](https://pypi.org/project/itables) (📥 2.5K / month · 📦 6 · ⏱️ 10.01.2022):
	```
	pip install itables
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥉21 ·  ⭐ 200 · 💤) - WebRTC for Jupyter notebook/lab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipywebrtc) (👨‍💻 9 · 🔀 30 · 📦 410 · 📋 49 - 59% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/maartenbreddels/ipywebrtc
	```
- [PyPi](https://pypi.org/project/ipywebrtc) (📥 22K / month · 📦 11 · ⏱️ 04.07.2019):
	```
	pip install ipywebrtc
	```
- [Conda](https://anaconda.org/conda-forge/ipywebrtc) (📥 230K · ⏱️ 29.03.2021):
	```
	conda install -c conda-forge ipywebrtc
	```
- [npm](https://www.npmjs.com/package/jupyter-webrtc) (📥 390 / month · 📦 1 · ⏱️ 29.03.2021):
	```
	npm install jupyter-webrtc
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/tributary">tributary</a></b> (🥉20 ·  ⭐ 290) - Streaming reactive and dataflow graphs in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/tributary) (👨‍💻 7 · 🔀 25 · 📦 17 · 📋 81 - 13% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/timkpaine/tributary
	```
- [PyPi](https://pypi.org/project/tributary) (📥 76 / month · ⏱️ 25.08.2020):
	```
	pip install tributary
	```
- [Conda](https://anaconda.org/conda-forge/tributary) (📥 15K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge tributary
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉20 ·  ⭐ 49) - Viewer for Altair and Vega-Lite visualizations. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair_viewer) (👨‍💻 3 · 🔀 8 · 📋 7 - 42% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/altair-viz/altair_viewer
	```
- [PyPi](https://pypi.org/project/altair_viewer) (📥 170K / month · 📦 10 · ⏱️ 06.11.2021):
	```
	pip install altair_viewer
	```
</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥉19 ·  ⭐ 2K) - Interactive reports to analyze machine learning models during.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evidentlyai/evidently) (👨‍💻 11 · 🔀 160 · 📋 68 - 57% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/evidentlyai/evidently
	```
</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥉19 ·  ⭐ 410) - Interactive Jupyter widgets to visualize images, point sets, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) (👨‍💻 20 · 🔀 50 · 📥 64 · 📋 170 - 41% open · ⏱️ 17.09.2021):

	```
	git clone https://github.com/InsightSoftwareConsortium/itkwidgets
	```
- [PyPi](https://pypi.org/project/itkwidgets) (📥 4.7K / month · 📦 9 · ⏱️ 14.05.2021):
	```
	pip install itkwidgets
	```
- [npm](https://www.npmjs.com/package/itkwidgets) (📥 1.6K / month · ⏱️ 14.05.2021):
	```
	npm install itkwidgets
	```
</details>
<details><summary><b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉19 ·  ⭐ 390) - Visualize Python code execution (line-by-line) in Jupyter Notebook cells. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lgpage/nbtutor) (👨‍💻 3 · 🔀 36 · 📦 23 · 📋 32 - 59% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/lgpage/nbtutor
	```
- [Conda](https://anaconda.org/conda-forge/nbtutor) (📥 95K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge nbtutor
	```
</details>
<details><summary><b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥉19 ·  ⭐ 28 · 💤) - A set of widgets to help facilitate reuse of large datasets.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vidartf/ipydatawidgets) (👨‍💻 5 · 🔀 7 · 📦 420 · 📋 9 - 33% open · ⏱️ 04.01.2021):

	```
	git clone https://github.com/vidartf/ipydatawidgets
	```
- [PyPi](https://pypi.org/project/ipydatawidgets) (📥 47K / month · 📦 24 · ⏱️ 04.01.2021):
	```
	pip install ipydatawidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipydatawidgets) (📥 120K · ⏱️ 06.01.2021):
	```
	conda install -c conda-forge ipydatawidgets
	```
</details>
<details><summary><b><a href="https://github.com/mariobuikhuizen/ipyvue">ipyvue</a></b> (🥉18 ·  ⭐ 36) - Jupyter widgets base for Vue libraries. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mariobuikhuizen/ipyvue) (👨‍💻 3 · 🔀 10 · 📦 16 · 📋 6 - 33% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/mariobuikhuizen/ipyvue
	```
- [PyPi](https://pypi.org/project/ipyvue) (📥 33K / month · 📦 9 · ⏱️ 28.10.2021):
	```
	pip install ipyvue
	```
- [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 41K · ⏱️ 28.10.2021):
	```
	conda install -c conda-forge ipyvue
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipytree">ipytree</a></b> (🥉17 ·  ⭐ 86) - A Tree Widget using Jupyter-widgets protocol and jsTree. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipytree) (👨‍💻 8 · 🔀 23 · 📋 29 - 55% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/QuantStack/ipytree
	```
- [PyPi](https://pypi.org/project/ipytree) (📥 11K / month · 📦 5 · ⏱️ 03.03.2021):
	```
	pip install ipytree
	```
- [Conda](https://anaconda.org/conda-forge/ipytree) (📥 28K · ⏱️ 03.03.2021):
	```
	conda install -c conda-forge ipytree
	```
</details>
<details><summary><b><a href="https://github.com/igvteam/igv-jupyter">igv.js widget</a></b> (🥉15 ·  ⭐ 140) - Extension for Jupyter Notebook which integrates igv.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/igvteam/igv-jupyter) (👨‍💻 4 · 🔀 14 · 📦 6 · ⏱️ 22.11.2021):

	```
	git clone https://github.com/igvteam/igv-jupyter
	```
- [PyPi](https://pypi.org/project/igv-jupyter) (📥 130 / month · 📦 1 · ⏱️ 22.11.2021):
	```
	pip install igv-jupyter
	```
</details>
<details><summary>Show 17 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈28 ·  ⭐ 2.9K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈25 ·  ⭐ 2.8K · 💀) - An interactive grid for sorting, filtering, and editing DataFrames.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥈24 ·  ⭐ 730 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉22 ·  ⭐ 450 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython Notebook,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/OpenGeoscience/geonotebook">geonotebook</a></b> (🥉16 ·  ⭐ 1K · 💀) - A Jupyter notebook extension for geospatial visualization and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉16 ·  ⭐ 70 · 💀) - Neuroimaging widgets for jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉15 ·  ⭐ 13 · 💤) - A widget library for scales. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉13 ·  ⭐ 75 · 💀) - Jupyter Widgets based on React Material UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/agermanidis/pigeon">pigeon</a></b> (🥉12 ·  ⭐ 390 · 💀) - Quickly annotate data from the comfort of your Jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉12 ·  ⭐ 140 · 💀) - Jupyter Notebook extension leveraging pandas DataFrames.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉12 ·  ⭐ 33 · 💀) - Interactive performance benchmarking in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉11 ·  ⭐ 13 · 💀) - Jupyter widget - ag-grid in the notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉10 ·  ⭐ 30 · 💀) - p5.js Jupyter Widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉9 ·  ⭐ 120 · 💀) - Jupyter Widget for data annotation. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Yomguithereal/ipysigma">ipysigma</a></b> (🥉9 ·  ⭐ 31 · 💀) - A custom Jupyter widget library to display graphs using sigma.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉8 ·  ⭐ 3 · 💤) - Toolbox for easy and effective data exploration in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉7 ·  ⭐ 250 · 💀) - UI visual interface for fastai - now compatible with Google.. <code>❗Unlicensed</code>
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇30 ·  ⭐ 4.8K · 💤) - A collection of various notebook extensions for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 130 · 🔀 750 · 📋 780 - 42% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions
	```
- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 270K / month · 📦 250 · ⏱️ 28.03.2018):
	```
	pip install jupyter_contrib_nbextensions
	```
</details>
<details><summary><b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥇29 ·  ⭐ 8.9K) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyter-themes) (👨‍💻 42 · 🔀 990 · 📋 400 - 50% open · ⏱️ 23.08.2021):

	```
	git clone https://github.com/dunovank/jupyter-themes
	```
- [PyPi](https://pypi.org/project/jupyterthemes) (📥 34K / month · 📦 99 · ⏱️ 22.11.2018):
	```
	pip install jupyterthemes
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈27 ·  ⭐ 200) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 60 · 🔀 100 · 📦 1 · 📋 160 - 42% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/jupyterhub/jupyter-server-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 43K / month · 📦 87 · ⏱️ 29.11.2021):
	```
	pip install jupyter-server-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 580K · ⏱️ 30.11.2021):
	```
	conda install -c conda-forge jupyter-server-proxy
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥈25 ·  ⭐ 1.1K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 84 · 🔀 280 · 📋 780 - 26% open · ⏱️ 03.10.2021):

	```
	git clone https://github.com/jupyter/nbgrader
	```
- [PyPi](https://pypi.org/project/nbgrader) (📥 1.9K / month · 📦 16 · ⏱️ 08.05.2021):
	```
	pip install nbgrader
	```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 100K · ⏱️ 25.09.2021):
	```
	conda install -c conda-forge nbgrader
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈25 ·  ⭐ 150) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 23 · 🔀 53 · 📦 420 · 📋 120 - 39% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/jupyterhub/nbgitpuller
	```
- [PyPi](https://pypi.org/project/nbgitpuller) (📥 6.1K / month · 📦 18 · ⏱️ 02.09.2021):
	```
	pip install nbgitpuller
	```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 28K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge nbgitpuller
	```
</details>
<details><summary><b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈22 ·  ⭐ 380 · 💤) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oschuett/appmode) (👨‍💻 8 · 🔀 65 · 📦 290 · 📋 52 - 5% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/oschuett/appmode
	```
- [PyPi](https://pypi.org/project/appmode) (📥 2.2K / month · 📦 22 · ⏱️ 09.06.2020):
	```
	pip install appmode
	```
- [Conda](https://anaconda.org/conda-forge/appmode) (📥 150K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge appmode
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈22 ·  ⭐ 290) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 20 · 🔀 67 · 📥 4 · 📋 58 - 53% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyter-server/jupyter-resource-usage
	```
- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 13K / month · 📦 3 · ⏱️ 06.12.2021):
	```
	pip install jupyter-resource-usage
	```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 470K · ⏱️ 23.11.2020):
	```
	conda install -c conda-forge nbresuse
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥈21 ·  ⭐ 86) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 19 · 🔀 66 · 📦 35 · 📋 66 - 36% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyterhub/jupyter-rsession-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 1.2K / month · ⏱️ 01.12.2021):
	```
	pip install jupyter-rsession-proxy
	```
</details>
<details><summary><b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉19 ·  ⭐ 940 · 💤) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/8080labs/pyforest) (👨‍💻 13 · 🔀 170 · 📋 27 - 48% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/8080labs/pyforest
	```
- [PyPi](https://pypi.org/project/pyforest) (📥 7.9K / month · 📦 6 · ⏱️ 14.06.2021):
	```
	pip install pyforest
	```
</details>
<details><summary><b><a href="https://github.com/codota/jupyter-tabnine">jupyter-tabnine</a></b> (🥉19 ·  ⭐ 730) - Autocompletion with Deep Learning on Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/codota/jupyter-tabnine) (👨‍💻 10 · 🔀 100 · 📋 66 - 63% open · ⏱️ 23.08.2021):

	```
	git clone https://github.com/codota/jupyter-tabnine
	```
- [PyPi](https://pypi.org/project/jupyter-tabnine) (📥 9K / month · ⏱️ 23.08.2021):
	```
	pip install jupyter-tabnine
	```
</details>
<details><summary><b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉18 ·  ⭐ 200) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googlecolab/jupyter_http_over_ws) (👨‍💻 3 · 🔀 34 · 📋 26 - 73% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/googlecolab/jupyter_http_over_ws
	```
- [PyPi](https://pypi.org/project/jupyter_http_over_ws) (📥 26K / month · 📦 15 · ⏱️ 12.03.2020):
	```
	pip install jupyter_http_over_ws
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥉18 ·  ⭐ 200) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 24 · 🔀 21 · 📥 2 · 📦 1 · 📋 53 - 30% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/mamba-org/gator
	```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 11K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge mamba_gator
	```
- [npm](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 160 / month · ⏱️ 03.09.2021):
	```
	npm install @mamba-org/gator-lab
	```
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉18 ·  ⭐ 160 · 💤) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 51 · 📥 2.4K · 📋 37 - 81% open · ⏱️ 03.02.2021):

	```
	git clone https://github.com/krishnan-r/sparkmonitor
	```
- [PyPi](https://pypi.org/project/sparkmonitor) (📥 1.3K / month · ⏱️ 22.11.2021):
	```
	pip install sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 900 · ⏱️ 04.10.2019):
	```
	docker pull krishnanr/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉16 ·  ⭐ 51) - A Jupyter/Jupyterlab extension to make, download and extract.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 8 · 🔀 8 · 📥 3.3K · 📋 30 - 3% open · ⏱️ 14.10.2021):

	```
	git clone https://github.com/jupyterlab-contrib/jupyter-archive
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 19K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge jupyter-archive
	```
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉7 ·  ⭐ 380 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 17 · 📋 20 - 40% open · ⏱️ 01.02.2020):

	```
	git clone https://github.com/drillan/jupyter-black
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">dtale</a></b> (🥇28 ·  ⭐ 2.9K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈23 ·  ⭐ 870 · 💀) - A jupyter notebook serverextension providing config.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉18 ·  ⭐ 450 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉17 ·  ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉17 ·  ⭐ 76 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉16 ·  ⭐ 74 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 ·  ⭐ 130 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉14 ·  ⭐ 47 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉12 ·  ⭐ 14) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉3 ·  ⭐ 8 · 💤) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Magic

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide magic commands to access convenient functionality within a notebook._

<details><summary><b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇29 ·  ⭐ 1.5K · 💤) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/catherinedevlin/ipython-sql) (👨‍💻 44 · 🔀 240 · 📦 2.6K · 📋 140 - 73% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/catherinedevlin/ipython-sql
	```
- [PyPi](https://pypi.org/project/ipython-sql) (📥 64K / month · 📦 67 · ⏱️ 02.05.2020):
	```
	pip install ipython-sql
	```
- [Conda](https://anaconda.org/conda-forge/ipython-sql) (📥 130K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge ipython-sql
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇29 ·  ⭐ 1.1K) - Jupyter magics and kernels for working with remote Spark clusters. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-incubator/sparkmagic) (👨‍💻 54 · 🔀 370 · 📦 220 · 📋 390 - 33% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/jupyter-incubator/sparkmagic
	```
- [PyPi](https://pypi.org/project/sparkmagic) (📥 36K / month · 📦 20 · ⏱️ 19.08.2021):
	```
	pip install sparkmagic
	```
- [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 38K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge sparkmagic
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈25 ·  ⭐ 590) - An IPython magic extension for printing date and time stamps, version.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasbt/watermark) (👨‍💻 18 · 🔀 73 · 📦 1.3K · 📋 44 - 38% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/rasbt/watermark
	```
- [PyPi](https://pypi.org/project/watermark) (📥 43K / month · 📦 77 · ⏱️ 04.01.2022):
	```
	pip install watermark
	```
- [Conda](https://anaconda.org/conda-forge/watermark) (📥 190K · ⏱️ 04.01.2022):
	```
	conda install -c conda-forge watermark
	```
</details>
<details><summary><b><a href="https://github.com/rossant/ipycache">ipycache</a></b> (🥈18 ·  ⭐ 120) - Defines a %%cache cell magic in the IPython notebook to cache results.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rossant/ipycache) (👨‍💻 9 · 🔀 22 · 📦 17 · 📋 33 - 51% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/rossant/ipycache
	```
- [PyPi](https://pypi.org/project/ipycache) (📥 120 / month · 📦 6 · ⏱️ 13.10.2013):
	```
	pip install ipycache
	```
- [Conda](https://anaconda.org/conda-forge/ipycache) (📥 67K · ⏱️ 07.07.2020):
	```
	conda install -c conda-forge ipycache
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥉17 ·  ⭐ 280) - IPython magic command to format python code in cell using black. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/blackcellmagic) (👨‍💻 3 · 🔀 9 · 📦 130 · 📋 10 - 50% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/csurfer/blackcellmagic
	```
- [PyPi](https://pypi.org/project/blackcellmagic) (📥 2.9K / month · 📦 3 · ⏱️ 18.09.2021):
	```
	pip install blackcellmagic
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥉16 ·  ⭐ 970 · 📉) - IPython magic command to profile and view your python code as a heat map. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/pyheatmagic) (👨‍💻 3 · 🔀 20 · 📦 24 · 📋 5 - 40% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/csurfer/pyheatmagic
	```
- [PyPi](https://pypi.org/project/py-heat-magic) (📥 1.4K / month · ⏱️ 19.08.2017):
	```
	pip install py-heat-magic
	```
</details>
<details><summary><b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥉16 ·  ⭐ 550 · 💤) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ShopRunner/jupyter-notify) (👨‍💻 11 · 🔀 30 · 📋 22 - 50% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/ShopRunner/jupyter-notify
	```
- [PyPi](https://pypi.org/project/jupyternotify) (📥 1.3K / month · 📦 2 · ⏱️ 08.01.2018):
	```
	pip install jupyternotify
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉11 ·  ⭐ 160) - manim cell magic for IPython/Jupyter to show the output video. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyter-manim) (👨‍💻 5 · 🔀 11 · 📋 24 - 25% open · ⏱️ 02.01.2022):

	```
	git clone https://github.com/krassowski/jupyter-manim
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/nteract/pick">pick</a></b> (🥈21 ·  ⭐ 400 · 💀) - Customize your kernels on Launch!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉15 ·  ⭐ 440 · 💀) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉13 ·  ⭐ 140 · 💀) - SQLCell is a magic function for the Jupyter Notebook that executes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dnanhkhoa/nb_black">nb_black</a></b> (🥉13 ·  ⭐ 62 · 💀) - A simple extension for Jupyter Notebook and Jupyter Lab to beautify.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Kernels

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter kernels that run and introspect the user's code in a given language._

<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇38 ·  ⭐ 450) - IPython Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipykernel) (👨‍💻 150 · 🔀 290 · 📥 130 · 📦 150K · 📋 390 - 52% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/ipython/ipykernel
	```
- [PyPi](https://pypi.org/project/ipykernel) (📥 13M / month · 📦 9.5K · ⏱️ 03.01.2022):
	```
	pip install ipykernel
	```
- [Conda](https://anaconda.org/anaconda/ipykernel) (📥 240K · 📦 28 · ⏱️ 07.10.2021):
	```
	conda install -c anaconda ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥇26 ·  ⭐ 1.7K) - IJavascript is a javascript kernel for the Jupyter notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/n-riesco/ijavascript) (👨‍💻 14 · 🔀 170 · 📦 55 · 📋 240 - 26% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/n-riesco/ijavascript
	```
- [npm](https://www.npmjs.com/package/ijavascript) (📥 3.2K / month · 📦 22 · ⏱️ 15.11.2021):
	```
	npm install ijavascript
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇26 ·  ⭐ 260) - Jupyter/IPython Kernel Tools. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/metakernel) (👨‍💻 29 · 🔀 74 · 📥 12 · 📋 140 - 18% open · ⏱️ 02.12.2021):

	```
	git clone https://github.com/Calysto/metakernel
	```
- [PyPi](https://pypi.org/project/metakernel) (📥 17K / month · 📦 75 · ⏱️ 15.12.2021):
	```
	pip install metakernel
	```
- [Conda](https://anaconda.org/conda-forge/metakernel) (📥 530K · ⏱️ 02.12.2021):
	```
	conda install -c conda-forge metakernel
	```
</details>
<details><summary><b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥇24 ·  ⭐ 1.5K) - R kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IRkernel/IRkernel) (👨‍💻 40 · 🔀 290 · 📋 560 - 9% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/IRkernel/IRkernel
	```
- [Conda](https://anaconda.org/r/r-irkernel) (📥 54K · ⏱️ 10.03.2020):
	```
	conda install -c r r-irkernel
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/r-notebook) (📥 1.2M · ⭐ 42 · ⏱️ 12.01.2022):
	```
	docker pull jupyter/r-notebook
	```
</details>
<details><summary><b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥈23 ·  ⭐ 3.1K) - The Go kernel for Jupyter notebooks and nteract. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gopherdata/gophernotes) (👨‍💻 28 · 🔀 220 · 📥 40 · 📦 7 · 📋 170 - 27% open · ⏱️ 09.01.2022):

	```
	git clone https://github.com/gopherdata/gophernotes
	```
- [Docker Hub](https://hub.docker.com/r/gopherdata/gophernotes) (📥 84K · ⭐ 7 · ⏱️ 22.12.2018):
	```
	docker pull gopherdata/gophernotes
	```
- [Go](https://pkg.go.dev/github.com/gopherdata/gophernotes) (📦 1 · ⏱️ 03.06.2021):
	```
	go install github.com/gopherdata/gophernotes
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈23 ·  ⭐ 690) - Jupyter kernel for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-toree) (👨‍💻 100 · 🔀 210 · ⏱️ 07.09.2021):

	```
	git clone https://github.com/apache/incubator-toree
	```
- [PyPi](https://pypi.org/project/toree) (📥 8.3K / month · 📦 9 · ⏱️ 01.08.2020):
	```
	pip install toree
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/enterprise_gateway">Enterprise Gateway</a></b> (🥈23 ·  ⭐ 480) - A lightweight, multi-tenant, scalable and secure gateway.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/enterprise_gateway) (👨‍💻 86 · 🔀 160 · 📥 12K · 📋 500 - 19% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/jupyter/enterprise_gateway
	```
- [PyPi](https://pypi.org/project/jupyter_enterprise_gateway) (📥 570 / month · 📦 1 · ⏱️ 27.04.2020):
	```
	pip install jupyter_enterprise_gateway
	```
</details>
<details><summary><b><a href="https://github.com/gibiansky/IHaskell">IHaskell</a></b> (🥈22 ·  ⭐ 2.3K) - A Haskell kernel for IPython. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gibiansky/IHaskell) (👨‍💻 100 · 🔀 240 · 📋 720 - 4% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/gibiansky/IHaskell
	```
- [npm](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 16 / month · ⏱️ 01.08.2018):
	```
	npm install ihaskell_jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥈22 ·  ⭐ 380) - An Octave kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/octave_kernel) (👨‍💻 17 · 🔀 57 · 📥 9 · 📋 160 - 14% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/calysto/octave_kernel
	```
- [PyPi](https://pypi.org/project/octave_kernel) (📥 8.1K / month · 📦 5 · ⏱️ 11.06.2018):
	```
	pip install octave_kernel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/kernel_gateway">Kernel Gateway</a></b> (🥈22 ·  ⭐ 380) - Jupyter Kernel Gateway. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/kernel_gateway) (👨‍💻 44 · 🔀 120 · 📥 100 · 📋 180 - 8% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/jupyter/kernel_gateway
	```
- [PyPi](https://pypi.org/project/jupyter-kernel-gateway) (📥 4.3K / month · 📦 6 · ⏱️ 24.08.2021):
	```
	pip install jupyter-kernel-gateway
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-python">xeus-python</a></b> (🥈22 ·  ⭐ 320) - Jupyter kernel for the Python programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-python) (👨‍💻 17 · 🔀 58 · 📋 170 - 29% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/jupyter-xeus/xeus-python
	```
- [PyPi](https://pypi.org/project/xeus-python) (📥 5.5K / month · 📦 3 · ⏱️ 13.01.2022):
	```
	pip install xeus-python
	```
- [Conda](https://anaconda.org/conda-forge/xeus-python) (📥 950K · ⏱️ 13.01.2022):
	```
	conda install -c conda-forge xeus-python
	```
</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥈22 ·  ⭐ 300) - Official mirror of https://gitlab.com/lfortran/lfortran. Please submit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lfortran/lfortran) (👨‍💻 21 · 🔀 15 · ⏱️ 08.01.2022):

	```
	git clone https://github.com/lfortran/lfortran
	```
- [PyPi](https://pypi.org/project/lfortran) (📥 120 / month · ⏱️ 31.07.2020):
	```
	pip install lfortran
	```
- [Conda](https://anaconda.org/conda-forge/lfortran) (📥 31K · ⏱️ 23.09.2021):
	```
	conda install -c conda-forge lfortran
	```
</details>
<details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥈21 ·  ⭐ 1.4K) - A Scala kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/almond-sh/almond) (👨‍💻 35 · 🔀 210 · 📥 1.2K · 📋 300 - 36% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/almond-sh/almond
	```
- [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 13K · ⭐ 6 · ⏱️ 26.08.2021):
	```
	docker pull almondsh/almond
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈20 ·  ⭐ 2.1K) - Jupyter kernel for the C++ programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-cling) (👨‍💻 20 · 🔀 220 · 📋 240 - 52% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/jupyter-xeus/xeus-cling
	```
- [Conda](https://anaconda.org/conda-forge/xeus-cling) (📥 130K · ⏱️ 03.01.2022):
	```
	conda install -c conda-forge xeus-cling
	```
</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥈20 ·  ⭐ 670) - Official gem repository: Ruby kernel for Jupyter/IPython Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SciRuby/iruby) (👨‍💻 44 · 🔀 10 · 📥 15 · 📦 150 · 📋 180 - 24% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/SciRuby/iruby
	```
- [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 1.5K · ⭐ 3 · ⏱️ 28.09.2021):
	```
	docker pull rubydata/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥉19 ·  ⭐ 2.4K) - Julia kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JuliaLang/IJulia.jl) (👨‍💻 100 · 🔀 370 · 📋 780 - 12% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/JuliaLang/IJulia.jl
	```
</details>
<details><summary><b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥉19 ·  ⭐ 210) - An OCaml kernel for Jupyter (IPython) notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akabe/ocaml-jupyter) (👨‍💻 18 · 🔀 30 · 📥 58K · 📋 67 - 4% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/akabe/ocaml-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉18 ·  ⭐ 720) - a Jupyter kernel for Clojure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/clojupyter/clojupyter) (👨‍💻 26 · 🔀 82 · 📋 92 - 17% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/clojupyter/clojupyter
	```
- [Conda](https://anaconda.org/simplect/clojupyter) (📥 2.7K · ⏱️ 02.03.2020):
	```
	conda install -c simplect clojupyter
	```
- [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 350 · ⏱️ 25.04.2019):
	```
	docker pull simplect/clojupyter
	```
</details>
<details><summary><b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉18 ·  ⭐ 480) - Jupyter Notebook Kernel for running Ansible Tasks and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ansible/ansible-jupyter-kernel) (👨‍💻 10 · 🔀 49 · 📦 8 · 📋 42 - 30% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/ansible/ansible-jupyter-kernel
	```
- [PyPi](https://pypi.org/project/ansible-kernel) (📥 98 / month · ⏱️ 12.12.2018):
	```
	pip install ansible-kernel
	```
- [Conda](https://anaconda.org/conda-forge/ansible-kernel) (📥 8.7K · ⏱️ 14.01.2020):
	```
	conda install -c conda-forge ansible-kernel
	```
- [Docker Hub](https://hub.docker.com/r/benthomasson/ansible-jupyter-kernel) (📥 66K · ⭐ 2 · ⏱️ 12.12.2018):
	```
	docker pull benthomasson/ansible-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥉17 ·  ⭐ 180) - A Jupyter kernel for SAS. This opens up all the data manipulation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sassoftware/sas_kernel) (👨‍💻 7 · 🔀 71 · 📋 55 - 5% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/sassoftware/sas_kernel
	```
- [PyPi](https://pypi.org/project/sas_kernel) (📥 530 / month · 📦 2 · ⏱️ 13.09.2017):
	```
	pip install sas_kernel
	```
</details>
<details><summary><b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥉17 ·  ⭐ 180) - Write SciJava scripts in Jupyter notebook!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scijava/scijava-jupyter-kernel) (👨‍💻 9 · 🔀 44 · 📥 76 · 📋 84 - 16% open · ⏱️ 08.11.2021):

	```
	git clone https://github.com/scijava/scijava-jupyter-kernel
	```
- [Conda](https://anaconda.org/conda-forge/scijava-jupyter-kernel) (📥 75K · ⏱️ 03.03.2018):
	```
	conda install -c conda-forge scijava-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉15 ·  ⭐ 660) - Wolfram Language kernel for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WolframResearch/WolframLanguageForJupyter) (👨‍💻 7 · 🔀 83 · 📥 4.8K · 📋 86 - 26% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/WolframResearch/WolframLanguageForJupyter
	```
</details>
<details><summary><b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉15 ·  ⭐ 47) - SSH Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NII-cloud-operation/sshkernel) (👨‍💻 4 · 🔀 10 · 📦 6 · 📋 8 - 25% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/NII-cloud-operation/sshkernel
	```
- [PyPi](https://pypi.org/project/sshkernel) (📥 56 / month · ⏱️ 04.11.2021):
	```
	pip install sshkernel
	```
</details>
<details><summary><b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉14 ·  ⭐ 340 · 💤) - Jupyters kernel for Elixir programming language. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pprzetacznik/IElixir) (👨‍💻 19 · 🔀 39 · 📋 30 - 33% open · ⏱️ 20.03.2021):

	```
	git clone https://github.com/pprzetacznik/IElixir
	```
- [Docker Hub](https://hub.docker.com/r/pprzetacznik/ielixir) (📥 310 · ⭐ 1 · ⏱️ 20.03.2021):
	```
	docker pull pprzetacznik/ielixir
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉11 ·  ⭐ 130) - Jupyter kernel for SQLite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) (👨‍💻 12 · 🔀 22 · 📋 41 - 31% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/jupyter-xeus/xeus-sqlite
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥉19 ·  ⭐ 570 · 💀) - A bash kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/vericast/spylon-kernel">Spylon Kernel</a></b> (🥉19 ·  ⭐ 150 · 💀) - Jupyter kernel for scala and spark. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉18 ·  ⭐ 430 · 💀) - F# for Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda_kernels">nb_conda_kernels</a></b> (🥉18 ·  ⭐ 420 · 💀) - Package for managing conda environment-based kernels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥉17 ·  ⭐ 730 · 💀) - A Jupyter kernel for executing Java code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉17 ·  ⭐ 410 · 💀) - Jupyter Kernel for Matlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉15 ·  ⭐ 140 · 💀) - An Jupyter plugin to enable the automatic detection of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉14 ·  ⭐ 2.2K · 💀) - Interactive Go programming with Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/minrk/allthekernels">allthekernels</a></b> (🥉13 ·  ⭐ 67 · 💀) - A multiplexer kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉11 ·  ⭐ 8 · 💀) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/zabirauf/icsharp">ICSharp</a></b> (🥉10 ·  ⭐ 260 · 💀) - C# kernel for Jupyter. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉4 ·  ⭐ 10 · 💀) - kernel-relay is a GraphQL service for interfacing with.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉4 ·  ⭐ 6 · 💤) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Notebook Sharing & Conversion

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools to share, convert and simplify collaboration (e.g., via git) with notebook files._

<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇39 ·  ⭐ 1.2K) - Jupyter Notebook Conversion. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbconvert) (👨‍💻 240 · 🔀 470 · 📦 130K · 📋 970 - 42% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/jupyter/nbconvert
	```
- [PyPi](https://pypi.org/project/nbconvert) (📥 13M / month · 📦 8.2K · ⏱️ 03.01.2022):
	```
	pip install nbconvert
	```
- [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 5.5M · ⏱️ 05.01.2022):
	```
	conda install -c conda-forge nbconvert
	```
</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥇34 ·  ⭐ 3.8K) - Voil turns Jupyter notebooks into standalone web applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/voila-dashboards/voila) (👨‍💻 56 · 🔀 370 · 📥 110 · 📦 5.7K · 📋 580 - 43% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/voila-dashboards/voila
	```
- [PyPi](https://pypi.org/project/voila) (📥 37K / month · 📦 50 · ⏱️ 09.12.2021):
	```
	pip install voila
	```
- [Conda](https://anaconda.org/conda-forge/voila) (📥 160K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge voila
	```
- [npm](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 2.7K / month · ⏱️ 19.05.2020):
	```
	npm install @jupyter-voila/jupyterlab-preview
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇33 ·  ⭐ 5.1K) - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/jupytext) (👨‍💻 67 · 🔀 320 · 📦 2.3K · 📋 490 - 11% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/mwouts/jupytext
	```
- [PyPi](https://pypi.org/project/jupytext) (📥 130K / month · 📦 140 · ⏱️ 11.01.2022):
	```
	pip install jupytext
	```
- [Conda](https://anaconda.org/conda-forge/jupytext) (📥 260K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge jupytext
	```
- [npm](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 10K / month · ⏱️ 04.12.2021):
	```
	npm install jupyterlab-jupytext
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥇33 ·  ⭐ 2.2K) - A static website and blog generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 220 · 🔀 420 · 📦 400 · 📋 2.1K - 1% open · ⏱️ 09.01.2022):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola) (📥 1.8K / month · 📦 140 · ⏱️ 27.12.2021):
	```
	pip install nikola
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/jupyter-book">Jupyter Book</a></b> (🥈30 ·  ⭐ 2.6K) - Create beautiful, publication-quality books and documents from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/jupyter-book) (👨‍💻 99 · 🔀 440 · 📋 980 - 39% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/executablebooks/jupyter-book
	```
- [PyPi](https://pypi.org/project/jupyter-book) (📥 28K / month · 📦 47 · ⏱️ 19.11.2021):
	```
	pip install jupyter-book
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈30 ·  ⭐ 2.1K) - Tools for diffing and merging of Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbdime) (👨‍💻 34 · 🔀 130 · 📦 63 · 📋 280 - 23% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/jupyter/nbdime
	```
- [PyPi](https://pypi.org/project/nbdime) (📥 180K / month · 📦 140 · ⏱️ 25.10.2021):
	```
	pip install nbdime
	```
- [Conda](https://anaconda.org/conda-forge/nbdime) (📥 430K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge nbdime
	```
- [npm](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 56K / month · ⏱️ 25.10.2021):
	```
	npm install nbdime-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈28 ·  ⭐ 3.2K) - RISE: Live Reveal.js Jupyter/IPython Slideshow Extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/damianavila/RISE) (👨‍💻 40 · 🔀 370 · 📦 1.7K · 📋 420 - 32% open · ⏱️ 26.11.2021):

	```
	git clone https://github.com/damianavila/RISE
	```
- [PyPi](https://pypi.org/project/RISE) (📥 12K / month · 📦 160 · ⏱️ 29.10.2020):
	```
	pip install RISE
	```
- [Conda](https://anaconda.org/conda-forge/rise) (📥 190K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge rise
	```
</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥈28 ·  ⭐ 620) - Living documents for reproducible research. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stencila/stencila) (👨‍💻 26 · 🔀 38 · 📥 1K · 📦 16 · 📋 560 - 12% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/stencila/stencila
	```
- [npm](https://www.npmjs.com/package/stencila) (📥 210 / month · 📦 8 · ⏱️ 06.11.2020):
	```
	npm install stencila
	```
- [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 16K · ⏱️ 08.04.2019):
	```
	docker pull stencila/cloud
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥈24 ·  ⭐ 2K) - nbconvert as a web service: Render Jupyter Notebooks as static web pages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbviewer) (👨‍💻 86 · 🔀 480 · 📦 7 · 📋 560 - 28% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/jupyter/nbviewer
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/nbviewer) (📥 2.4M · ⭐ 27 · ⏱️ 02.12.2020):
	```
	docker pull jupyter/nbviewer
	```
</details>
<details><summary><b><a href="https://github.com/greenape/mknotebooks">mknotebooks</a></b> (🥈24 ·  ⭐ 90) - A plugin for mkdocs to help you include Jupyter notebooks in your.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/greenape/mknotebooks) (👨‍💻 13 · 🔀 19 · 📦 140 · 📋 39 - 35% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/greenape/mknotebooks
	```
- [PyPi](https://pypi.org/project/mknotebooks) (📥 13K / month · 📦 19 · ⏱️ 11.01.2022):
	```
	pip install mknotebooks
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥉23 ·  ⭐ 5K) - A next-generation curated knowledge sharing platform for data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/knowledge-repo) (👨‍💻 60 · 🔀 640 · 📋 300 - 43% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/airbnb/knowledge-repo
	```
- [PyPi](https://pypi.org/project/knowledge-repo) (📥 1.9K / month · 📦 1 · ⏱️ 20.01.2021):
	```
	pip install knowledge-repo
	```
</details>
<details><summary><b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉21 ·  ⭐ 5.7K) - Notebook sharing hub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/commuter) (👨‍💻 27 · 🔀 560 · 📦 3 · 📋 91 - 57% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/nteract/commuter
	```
- [npm](https://www.npmjs.com/package/@nteract/commuter) (📥 460 / month · ⏱️ 27.10.2020):
	```
	npm install @nteract/commuter
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉21 ·  ⭐ 2.1K) - Run your code in the cloud, with technology so advanced, it feels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/binderhub) (👨‍💻 82 · 🔀 300 · 📦 6 · 📋 720 - 38% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyterhub/binderhub
	```
</details>
<details><summary><b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉21 ·  ⭐ 230 · 💤) - A library for recording and reading data in notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/scrapbook) (👨‍💻 11 · 🔀 23 · 📦 88 · 📋 49 - 48% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/nteract/scrapbook
	```
- [PyPi](https://pypi.org/project/nteract-scrapbook) (📥 31K / month · 📦 17 · ⏱️ 06.01.2021):
	```
	pip install nteract-scrapbook
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/thebe">ThebeLab</a></b> (🥉19 ·  ⭐ 260) - Turn static HTML pages into live documents with Jupyter kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/thebe) (👨‍💻 26 · 🔀 55 · 📦 5 · 📋 150 - 43% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/executablebooks/thebe
	```
</details>
<details><summary><b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉19 ·  ⭐ 150) - JupyterHub extension for ContainDS Dashboards. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ideonate/cdsdashboards) (👨‍💻 11 · 🔀 25 · 📋 77 - 35% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/ideonate/cdsdashboards
	```
- [PyPi](https://pypi.org/project/cdsdashboards) (📥 350 / month · ⏱️ 28.10.2021):
	```
	pip install cdsdashboards
	```
- [Conda](https://anaconda.org/conda-forge/cdsdashboards) (📥 18K · ⏱️ 28.10.2021):
	```
	conda install -c conda-forge cdsdashboards
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥉19 ·  ⭐ 100) - Use Jupyter Notebook in mkdocs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/mkdocs-jupyter) (👨‍💻 10 · 🔀 13 · 📋 34 - 2% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/danielfrg/mkdocs-jupyter
	```
- [PyPi](https://pypi.org/project/mkdocs-jupyter) (📥 14K / month · 📦 7 · ⏱️ 30.11.2021):
	```
	pip install mkdocs-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉18 ·  ⭐ 210 · 💤) - Create interactive webpages from Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SamLau95/nbinteract) (👨‍💻 8 · 🔀 20 · 📦 1 · 📋 84 - 51% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/SamLau95/nbinteract
	```
- [PyPi](https://pypi.org/project/nbinteract) (📥 760 / month · 📦 37 · ⏱️ 05.01.2021):
	```
	pip install nbinteract
	```
</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉18 ·  ⭐ 140) - Enterprise Jupyter notebook sharing and collaboration app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbgallery/nbgallery) (👨‍💻 18 · 🔀 21 · 📋 350 - 25% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/nbgallery/nbgallery
	```
- [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery) (📥 130K · ⭐ 3 · ⏱️ 12.11.2021):
	```
	docker pull nbgallery/nbgallery
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉14 ·  ⭐ 230) - Build dashboards using Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/jupyter-flex) (👨‍💻 3 · 🔀 39 · 📦 1 · 📋 47 - 10% open · ⏱️ 31.12.2021):

	```
	git clone https://github.com/danielfrg/jupyter-flex
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉20 ·  ⭐ 780 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉20 ·  ⭐ 180 · 💀) - Notebook storage and publishing workflows for the masses. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉12 ·  ⭐ 230 · 💀) - Jupyter Notebooks as plain Python code with embedded Markdown text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉8 ·  ⭐ 94 · 💤) - An awesome viewer to browse and render Jupyter.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Notebook Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries and tools that work with or can be used within notebook files._

<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥇35 ·  ⭐ 250) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_client) (👨‍💻 110 · 🔀 220 · 📥 110 · 📋 300 - 44% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/jupyter/jupyter_client
	```
- [PyPi](https://pypi.org/project/jupyter-client) (📥 13M / month · 📦 2.1K · ⏱️ 15.12.2021):
	```
	pip install jupyter-client
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥇33 ·  ⭐ 2.1K) - IPython Parallel: Interactive Parallel Computing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 100 · 🔀 850 · 📦 1.8K · 📋 320 - 15% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel) (📥 44K / month · 📦 280 · ⏱️ 22.12.2021):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 550K · ⏱️ 23.12.2021):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥇32 ·  ⭐ 160) - Reference implementation of the Jupyter Notebook format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbformat) (👨‍💻 60 · 🔀 120 · 📦 140K · 📋 110 - 40% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/jupyter/nbformat
	```
- [PyPi](https://pypi.org/project/nbformat) (📥 13M / month · 📦 8.5K · ⏱️ 02.04.2021):
	```
	pip install nbformat
	```
- [Conda](https://anaconda.org/conda-forge/nbformat) (📥 6.9M · ⏱️ 02.04.2021):
	```
	conda install -c conda-forge nbformat
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇32 ·  ⭐ 84) - A client library for executing notebooks. Formally nbconverts.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbclient) (👨‍💻 29 · 🔀 39 · 📥 10 · 📦 40K · 📋 86 - 37% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/jupyter/nbclient
	```
- [PyPi](https://pypi.org/project/nbclient) (📥 13M / month · 📦 62 · ⏱️ 19.11.2021):
	```
	pip install nbclient
	```
- [Conda](https://anaconda.org/conda-forge/nbclient) (📥 2.5M · ⏱️ 19.11.2021):
	```
	conda install -c conda-forge nbclient
	```
</details>
<details><summary><b><a href="https://github.com/fastai/nbdev">nbdev</a></b> (🥈30 ·  ⭐ 3.1K) - Create delightful python projects using Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastai/nbdev) (👨‍💻 61 · 🔀 320 · 📋 350 - 22% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/fastai/nbdev
	```
- [PyPi](https://pypi.org/project/nbdev) (📥 42K / month · 📦 58 · ⏱️ 29.10.2021):
	```
	pip install nbdev
	```
</details>
<details><summary><b><a href="https://github.com/twosigma/beakerx">BeakerX</a></b> (🥈29 ·  ⭐ 2.6K · 💤) - Beaker Extensions for Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/twosigma/beakerx) (👨‍💻 81 · 🔀 380 · 📥 31 · 📋 4.5K - 7% open · ⏱️ 21.01.2021):

	```
	git clone https://github.com/twosigma/beakerx
	```
- [PyPi](https://pypi.org/project/beakerx) (📥 6.6K / month · 📦 22 · ⏱️ 16.12.2021):
	```
	pip install beakerx
	```
- [Conda](https://anaconda.org/conda-forge/beakerx) (📥 480K · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge beakerx
	```
- [npm](https://www.npmjs.com/package/beakerx) (📥 680 / month · 📦 1 · ⏱️ 06.04.2019):
	```
	npm install beakerx
	```
- [Docker Hub](https://hub.docker.com/r/beakerx/beakerx) (📥 240K · ⭐ 22 · ⏱️ 02.12.2018):
	```
	docker pull beakerx/beakerx
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥈29 ·  ⭐ 1.3K) - Turn repositories into Jupyter-enabled Docker images. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/repo2docker) (👨‍💻 100 · 🔀 290 · 📦 140 · 📋 480 - 35% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/jupyterhub/repo2docker
	```
- [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 4K / month · 📦 24 · ⏱️ 24.08.2021):
	```
	pip install jupyter-repo2docker
	```
</details>
<details><summary><b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥈27 ·  ⭐ 1K · 💤) - Python Helper library for Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pixiedust/pixiedust) (👨‍💻 33 · 🔀 160 · 📦 230 · 📋 420 - 38% open · ⏱️ 16.02.2021):

	```
	git clone https://github.com/pixiedust/pixiedust
	```
- [PyPi](https://pypi.org/project/pixiedust) (📥 15K / month · 📦 29 · ⏱️ 01.02.2021):
	```
	pip install pixiedust
	```
- [Conda](https://anaconda.org/conda-forge/pixiedust) (📥 35K · ⏱️ 06.02.2021):
	```
	conda install -c conda-forge pixiedust
	```
</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈26 ·  ⭐ 370) - A py.test plugin to validate Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/computationalmodelling/nbval) (👨‍💻 29 · 🔀 42 · 📦 1.3K · 📋 96 - 36% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/computationalmodelling/nbval
	```
- [PyPi](https://pypi.org/project/nbval) (📥 75K / month · 📦 200 · ⏱️ 30.07.2020):
	```
	pip install nbval
	```
- [Conda](https://anaconda.org/conda-forge/nbval) (📥 180K · ⏱️ 31.07.2020):
	```
	conda install -c conda-forge nbval
	```
</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥈23 ·  ⭐ 380) - Run isort, pyupgrade, mypy, pylint, flake8, and more on Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbQA-dev/nbQA) (👨‍💻 23 · 🔀 23 · 📋 240 - 1% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/nbQA-dev/nbQA
	```
- [PyPi](https://pypi.org/project/nbqa) (📥 15K / month · 📦 2 · ⏱️ 11.01.2022):
	```
	pip install nbqa
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉21 ·  ⭐ 150) - Schedule notebooks, run them like APIs, expose securely your assets:.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 13 · 🔀 11 · 📦 3 · 📋 120 - 66% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/jupyter-naas/naas
	```
- [PyPi](https://pypi.org/project/naas) (📥 4.7K / month · ⏱️ 11.01.2022):
	```
	pip install naas
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥉21 ·  ⭐ 140) - Sphinx extension for rendering of Jupyter interactive widgets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-sphinx) (👨‍💻 24 · 🔀 48 · 📋 110 - 32% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/jupyter/jupyter-sphinx
	```
- [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 60K / month · 📦 17 · ⏱️ 06.08.2018):
	```
	pip install jupyter_sphinx
	```
</details>
<details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥉19 ·  ⭐ 180) - Pytest in IPython notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chmp/ipytest) (👨‍💻 4 · 🔀 18 · 📦 140 · 📋 43 - 4% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/chmp/ipytest
	```
- [PyPi](https://pypi.org/project/ipytest) (📥 7.3K / month · 📦 12 · ⏱️ 28.07.2021):
	```
	pip install ipytest
	```
</details>
<details><summary><b><a href="https://github.com/tweag/jupyterWith">JupyterWith</a></b> (🥉16 ·  ⭐ 300) - declarative and reproducible Jupyter environments - powered by Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tweag/jupyterWith) (👨‍💻 24 · 🔀 70 · 📋 88 - 52% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/tweag/jupyterWith
	```
</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉15 ·  ⭐ 140) - jupyter/ipython experiment containers for GPU and general.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stas00/ipyexperiments) (👨‍💻 3 · 🔀 10 · 📦 5 · 📋 6 - 16% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/stas00/ipyexperiments
	```
- [PyPi](https://pypi.org/project/ipyexperiments) (📥 130 / month · 📦 2 · ⏱️ 07.12.2021):
	```
	pip install ipyexperiments
	```
</details>
<details><summary><b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉14 ·  ⭐ 270) - Unit test your Jupyter Notebooks the right way. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/testbook) (👨‍💻 14 · 🔀 26 · 📦 69 · 📋 79 - 43% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/nteract/testbook
	```
</details>
<details><summary><b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉10 ·  ⭐ 150) - GitHub Action for testing notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/treebeardtech/nbmake-action) (👨‍💻 2 · 🔀 6 · ⏱️ 21.09.2021):

	```
	git clone https://github.com/treebeardtech/nbmake-action
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥉18 ·  ⭐ 280 · 💀) - Easy to use test framework for Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉17 ·  ⭐ 73 · 💀) - A Sphinx Extension for Generating Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉16 ·  ⭐ 260 · 💀) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉14 ·  ⭐ 13 · 💀) - Experimental new kernel management framework for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉10 ·  ⭐ 770 · 💀) - Cloud Native Presentation Slides with Jupyter Notebook +.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉9 ·  ⭐ 40) - A collection of helpers for Jupyter/IPython. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉6 ·  ⭐ 38 · 💀) - Run your jupyter notebooks as a REST API endpoint... <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## JupyterLab Renderer

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can render and display files of specific MIME types._

<details><summary><b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥇20 ·  ⭐ 520 · 💤) - A standalone embedding of the FOSS drawio / mxgraph.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/QuantStack/jupyterlab-drawio) (👨‍💻 16 · 🔀 58 · 📦 170 · 📋 64 - 60% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/QuantStack/jupyterlab-drawio
	```
- [npm](https://www.npmjs.com/package/jupyterlab-drawio) (📥 3.5K / month · ⏱️ 29.04.2021):
	```
	npm install jupyterlab-drawio
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥇20 ·  ⭐ 510) - JupyterLab extension for live editing of LaTeX documents. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-latex) (👨‍💻 21 · 🔀 60 · 📦 2 · 📋 100 - 47% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-latex
	```
- [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 1K / month · 📦 1 · ⏱️ 15.09.2021):
	```
	pip install jupyterlab_latex
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/latex) (📥 1.5K / month · ⏱️ 06.07.2021):
	```
	npm install @jupyterlab/latex
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥇20 ·  ⭐ 420) - Renderers and renderer extensions for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyter-renderers) (👨‍💻 23 · 🔀 61 · 📦 1 · 📋 100 - 31% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyter-renderers
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 3.8K / month · ⏱️ 11.03.2021):
	```
	npm install @jupyterlab/geojson-extension
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉16 ·  ⭐ 200 · 💤) - JupyterLab extension for Plotlys react-chart-editor. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/plotly/jupyterlab-chart-editor) (👨‍💻 5 · 🔀 20 · 📦 3 · 📋 31 - 38% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/plotly/jupyterlab-chart-editor
	```
- [npm](https://www.npmjs.com/package/jupyterlab-chart-editor) (📥 1.5K / month · ⏱️ 10.03.2021):
	```
	npm install jupyterlab-chart-editor
	```
</details>
<details><summary><b><a href="https://github.com/jupytercalpoly/jupyterlab-tabular-data-editor">jupyterlab-tabular-data-editor</a></b> (🥉15 ·  ⭐ 120 · 💤) - Manipulate your tabular data responsively and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupytercalpoly/jupyterlab-tabular-data-editor) (👨‍💻 5 · 🔀 18 · 📦 4 · 📋 130 - 23% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/jupytercalpoly/jupyterlab-tabular-data-editor
	```
- [PyPi](https://pypi.org/project/jupyterlab-tabular-data-editor) (📥 590 / month · ⏱️ 24.03.2021):
	```
	pip install jupyterlab-tabular-data-editor
	```
</details>
<details><summary><b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉13 ·  ⭐ 140) - JupyterLab plugin for viewing spreadsheets, such as.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/quigleyj97/jupyterlab-spreadsheet) (👨‍💻 4 · 🔀 9 · 📋 24 - 25% open · ⏱️ 20.11.2021):

	```
	git clone https://github.com/quigleyj97/jupyterlab-spreadsheet
	```
- [npm](https://www.npmjs.com/package/jupyterlab-spreadsheet) (📥 4.3K / month · ⏱️ 17.07.2021):
	```
	npm install jupyterlab-spreadsheet
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥇20 ·  ⭐ 520 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉14 ·  ⭐ 270 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Themes

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can customize the appearance of JupyterLab._

<details><summary><b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇18 ·  ⭐ 120) - A handsome Darcula theme for Jupyterlab. The first jlab theme to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/telamonian/theme-darcula) (👨‍💻 7 · 🔀 24 · 📦 150 · 📋 21 - 23% open · ⏱️ 26.08.2021):

	```
	git clone https://github.com/telamonian/theme-darcula
	```
- [npm](https://www.npmjs.com/package/@telamonian/theme-darcula) (📥 1.6K / month · ⏱️ 26.08.2021):
	```
	npm install @telamonian/theme-darcula
	```
</details>
<details><summary><b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥈13 ·  ⭐ 130) - The Material Darker theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/oriolmirosa/jupyterlab_materialdarker) (👨‍💻 2 · 🔀 14 · 📦 4 · 📋 18 - 22% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/oriolmirosa/jupyterlab_materialdarker
	```
- [npm](https://www.npmjs.com/package/@oriolmirosa/jupyterlab_materialdarker) (📥 540 / month · ⏱️ 31.08.2021):
	```
	npm install @oriolmirosa/jupyterlab_materialdarker
	```
</details>
<details><summary><b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈12 ·  ⭐ 110 · 💤) - A flat, 80s neon inspired theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yeebc/jupyterlab-neon-theme) (👨‍💻 3 · 🔀 5 · 📦 1 · 📋 12 - 16% open · ⏱️ 07.03.2021):

	```
	git clone https://github.com/yeebc/jupyterlab-neon-theme
	```
- [npm](https://www.npmjs.com/package/@yeebc/jupyterlab_neon_theme) (📥 790 / month · ⏱️ 07.03.2021):
	```
	npm install @yeebc/jupyterlab_neon_theme
	```
</details>
<details><summary><b><a href="https://github.com/dunovank/jupyterlab_darkside_ui">jupyterlab_darkside_ui</a></b> (🥈11 ·  ⭐ 71) - Darkside ui and syntax theme for jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyterlab_darkside_ui) (👨‍💻 4 · 🔀 4 · 📋 2 - 50% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/dunovank/jupyterlab_darkside_ui
	```
- [PyPi](https://pypi.org/project/jupyterlab_darkside_ui) (📥 240 / month · ⏱️ 06.01.2022):
	```
	pip install jupyterlab_darkside_ui
	```
</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥈11 ·  ⭐ 51 · 📉) - JupyterLab 2/3 Solarized Dark extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) (👨‍💻 2 · 🔀 6 · 📦 1 · 📋 2 - 50% open · ⏱️ 16.11.2021):

	```
	git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
	```
- [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark) (📥 490 / month · ⏱️ 20.09.2021):
	```
	pip install jupyterlab_theme_solarized_dark
	```
- [npm](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 2.7K / month · ⏱️ 20.09.2021):
	```
	npm install jupyterlab-theme-solarized-dark
	```
</details>
<details><summary><b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥈11 ·  ⭐ 46 · 💤) - VSCode Horizon Theme port for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mohirio/jupyterlab-horizon-theme) (👨‍💻 1 · 🔀 1 · 📋 5 - 20% open · ⏱️ 11.04.2021):

	```
	git clone https://github.com/mohirio/jupyterlab-horizon-theme
	```
- [npm](https://www.npmjs.com/package/@mohirio/jupyterlab-horizon-theme) (📥 1.6K / month · ⏱️ 11.04.2021):
	```
	npm install @mohirio/jupyterlab-horizon-theme
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥈11 ·  ⭐ 40 · 💀) - Gruvbox dark theme for Jupyter Lab. Modeled on classic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉8 ·  ⭐ 23 · 💀) - JupyterLab - Nord Theme. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉8 ·  ⭐ 10 · 💤) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of JupyterLab itself._

<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇32 ·  ⭐ 4.1K) - A data visualization and analytics component, especially well-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 65 · 🔀 430 · 📦 220 · 📋 490 - 14% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 3K / month · 📦 9 · ⏱️ 06.01.2022):
	```
	pip install perspective-python
	```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 1.7K / month · ⏱️ 05.01.2022):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥇29 ·  ⭐ 12K) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-toc) (👨‍💻 14 · 🔀 2.2K · 📦 160 · 📋 120 - 55% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-toc
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/toc) (📥 91K / month · 📦 6 · ⏱️ 12.01.2022):
	```
	npm install @jupyterlab/toc
	```
</details>
<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇29 ·  ⭐ 1.2K) - Elyra extends JupyterLab Notebooks with an AI centric approach. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elyra-ai/elyra) (👨‍💻 38 · 🔀 200 · 📦 28 · 📋 1.3K - 18% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/elyra-ai/elyra
	```
- [PyPi](https://pypi.org/project/elyra) (📥 1.7K / month · 📦 3 · ⏱️ 08.01.2022):
	```
	pip install elyra
	```
- [Conda](https://anaconda.org/conda-forge/elyra) (📥 9.1K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge elyra
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇29 ·  ⭐ 1K) - A Git extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-git) (👨‍💻 69 · 🔀 220 · 📦 14 · 📋 500 - 17% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/jupyterlab/jupyterlab-git
	```
- [PyPi](https://pypi.org/project/jupyterlab-git) (📥 91K / month · 📦 20 · ⏱️ 10.01.2022):
	```
	pip install jupyterlab-git
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 120K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge jupyterlab-git
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇28 ·  ⭐ 12K · 💤) - A visual debugger for Jupyter notebooks, consoles,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/debugger) (👨‍💻 11 · 🔀 2.2K · 📋 280 - 10% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/jupyterlab/debugger
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/debugger) (📥 73K / month · 📦 2 · ⏱️ 12.01.2022):
	```
	npm install @jupyterlab/debugger
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-lsp/jupyterlab-lsp">JupyterLab LSP</a></b> (🥇28 ·  ⭐ 1.1K) - Coding assistance for JupyterLab (code navigation + hover.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-lsp/jupyterlab-lsp) (👨‍💻 38 · 🔀 89 · 📦 100 · 📋 380 - 32% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/krassowski/jupyterlab-lsp
	```
- [npm](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 7.8K / month · 📦 2 · ⏱️ 01.01.2022):
	```
	npm install @krassowski/jupyterlab-lsp
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥈22 ·  ⭐ 310) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-github) (👨‍💻 15 · 🔀 84 · 📦 2 · 📋 60 - 40% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-github
	```
- [PyPi](https://pypi.org/project/jupyterlab-github) (📥 650 / month · 📦 2 · ⏱️ 27.11.2021):
	```
	pip install jupyterlab-github
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/github) (📥 1.3K / month · ⏱️ 27.11.2021):
	```
	npm install @jupyterlab/github
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥈22 ·  ⭐ 240) - JupyterLab extension for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-labextension) (👨‍💻 18 · 🔀 44 · 📋 120 - 27% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/dask/dask-labextension
	```
- [PyPi](https://pypi.org/project/dask-labextension) (📥 3.8K / month · 📦 3 · ⏱️ 08.01.2022):
	```
	pip install dask-labextension
	```
- [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 490K · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge dask-labextension
	```
- [npm](https://www.npmjs.com/package/dask-labextension) (📥 2.7K / month · ⏱️ 08.01.2022):
	```
	npm install dask-labextension
	```
</details>
<details><summary><b><a href="https://github.com/ryantam626/jupyterlab_code_formatter">Code Formatter</a></b> (🥈20 ·  ⭐ 500 · 💤) - A universal code formatter for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryantam626/jupyterlab_code_formatter) (👨‍💻 30 · 🔀 40 · 📋 140 - 16% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/ryantam626/jupyterlab_code_formatter
	```
- [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 14K / month · 📦 3 · ⏱️ 02.04.2021):
	```
	pip install jupyterlab_code_formatter
	```
- [npm](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 4.6K / month · ⏱️ 02.04.2021):
	```
	npm install @ryantam626/jupyterlab_code_formatter
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyterlab_templates">JupyterLab Templates</a></b> (🥈20 ·  ⭐ 280) - Support for jupyter notebook templates in jupyterlab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyterlab_templates) (👨‍💻 14 · 🔀 49 · 📦 4 · 📋 78 - 10% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/jpmorganchase/jupyterlab_templates
	```
- [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 3.4K / month · ⏱️ 30.06.2019):
	```
	pip install jupyterlab_templates
	```
- [npm](https://www.npmjs.com/package/jupyterlab_templates) (📥 2.8K / month · ⏱️ 28.03.2021):
	```
	npm install jupyterlab_templates
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥈20 ·  ⭐ 190) - An extension for rendering Bokeh content in JupyterLab notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/jupyter_bokeh) (👨‍💻 16 · 🔀 37 · 📋 79 - 11% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/bokeh/jupyter_bokeh
	```
- [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 4.6K / month · 📦 5 · ⏱️ 30.09.2021):
	```
	pip install jupyter-bokeh
	```
- [npm](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 16K / month · ⏱️ 30.09.2021):
	```
	npm install @bokeh/jupyter_bokeh
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥈20 ·  ⭐ 77) - View html as an embedded iframe in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_iframe) (👨‍💻 5 · 🔀 15 · 📦 3 · 📋 66 - 12% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_iframe
	```
- [PyPi](https://pypi.org/project/jupyterlab_iframe) (📥 450 / month · 📦 8 · ⏱️ 29.06.2019):
	```
	pip install jupyterlab_iframe
	```
- [npm](https://www.npmjs.com/package/jupyterlab_iframe) (📥 800 / month · ⏱️ 30.11.2021):
	```
	npm install jupyterlab_iframe
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈19 ·  ⭐ 350) - Cloud storage for JupyterLab using Google Drive. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-google-drive) (👨‍💻 15 · 🔀 71 · 📦 2 · 📋 100 - 38% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-google-drive
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/google-drive) (📥 2.1K / month · ⏱️ 27.05.2020):
	```
	npm install @jupyterlab/google-drive
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥈19 ·  ⭐ 220) - JupyterLab extension to display system metrics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-system-monitor) (👨‍💻 6 · 🔀 26 · 📦 27 · 📋 36 - 47% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-system-monitor
	```
- [npm](https://www.npmjs.com/package/jupyterlab-system-monitor) (📥 8K / month · ⏱️ 23.11.2020):
	```
	npm install jupyterlab-system-monitor
	```
</details>
<details><summary><b><a href="https://github.com/lckr/jupyterlab-variableInspector">Variable Inspector</a></b> (🥈18 ·  ⭐ 870) - Variable Inspector extension for Jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lckr/jupyterlab-variableInspector) (👨‍💻 17 · 🔀 77 · 📦 3 · 📋 150 - 25% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/lckr/jupyterlab-variableInspector
	```
- [npm](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 7.3K / month · ⏱️ 10.04.2021):
	```
	npm install @lckr/jupyterlab_variableinspector
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈18 ·  ⭐ 440) - A JupyterLab extension for displaying dashboards of GPU usage. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) (👨‍💻 15 · 🔀 52 · 📋 52 - 46% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/rapidsai/jupyterlab-nvdashboard
	```
- [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 8.1K / month · ⏱️ 12.10.2021):
	```
	pip install jupyterlab-nvdashboard
	```
- [npm](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 4K / month · ⏱️ 27.04.2021):
	```
	npm install jupyterlab-nvdashboard
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥈17 ·  ⭐ 300) - Data exploration glue. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/lantern) (👨‍💻 2 · 🔀 20 · 📦 14 · 📋 200 - 5% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/lantern
	```
- [PyPi](https://pypi.org/project/pylantern) (📥 85 / month · 📦 1 · ⏱️ 02.02.2020):
	```
	pip install pylantern
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥈17 ·  ⭐ 190) - A sidecar output widget for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) (👨‍💻 13 · 🔀 34 · 📦 3 · 📋 30 - 66% open · ⏱️ 04.07.2021):

	```
	git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
	```
- [PyPi](https://pypi.org/project/sidecar) (📥 1.9K / month · 📦 6 · ⏱️ 15.01.2021):
	```
	pip install sidecar
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 460 / month · ⏱️ 05.07.2021):
	```
	npm install @jupyter-widgets/jupyterlab-sidecar
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥈17 ·  ⭐ 90) - Control JupyterLab from Python Notebooks with Jupyter Widgets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipylab) (👨‍💻 5 · 🔀 4 · 📥 21 · 📋 26 - 34% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/jtpio/ipylab
	```
- [PyPi](https://pypi.org/project/ipylab) (📥 1.4K / month · 📦 2 · ⏱️ 13.11.2021):
	```
	pip install ipylab
	```
- [Conda](https://anaconda.org/conda-forge/ipylab) (📥 8.3K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge ipylab
	```
</details>
<details><summary><b><a href="https://github.com/chaoleili/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥉16 ·  ⭐ 280 · 💤) - Tensorboard extension for jupyterlab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chaoleili/jupyterlab_tensorboard) (👨‍💻 6 · 🔀 30 · 📦 2 · 📋 26 - 61% open · ⏱️ 24.02.2021):

	```
	git clone https://github.com/chaoleili/jupyterlab_tensorboard
	```
- [npm](https://www.npmjs.com/package/jupyterlab_tensorboard) (📥 5.5K / month · ⏱️ 27.06.2020):
	```
	npm install jupyterlab_tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥉16 ·  ⭐ 190) - Execute Time Plugin for Jupyter Lab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deshaw/jupyterlab-execute-time) (👨‍💻 10 · 🔀 24 · 📋 28 - 7% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/deshaw/jupyterlab-execute-time
	```
- [npm](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 2.8K / month · ⏱️ 18.01.2021):
	```
	npm install jupyterlab-execute-time
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥉16 ·  ⭐ 140) - Spellchecker for JupyterLab notebook markdown cells.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/spellchecker) (👨‍💻 6 · 🔀 16 · 📦 1 · 📋 43 - 23% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/jupyterlab-contrib/spellchecker
	```
- [PyPi](https://pypi.org/project/jupyterlab-spellchecker) (📥 1.1K / month · ⏱️ 08.10.2021):
	```
	pip install jupyterlab-spellchecker
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-spellchecker) (📥 17K · ⏱️ 08.10.2021):
	```
	conda install -c conda-forge jupyterlab-spellchecker
	```
- [npm](https://www.npmjs.com/package/@ijmbarr/jupyterlab_spellchecker) (📥 1.9K / month · ⏱️ 08.10.2021):
	```
	npm install @ijmbarr/jupyterlab_spellchecker
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥉16 ·  ⭐ 100) - A filesystem-like contents manager for multiple backends in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyter-fs) (👨‍💻 8 · 🔀 22 · 📋 49 - 26% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/jpmorganchase/jupyter-fs
	```
- [PyPi](https://pypi.org/project/jupyter-fs) (📥 180 / month · ⏱️ 04.06.2021):
	```
	pip install jupyter-fs
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉16 ·  ⭐ 59) - Cell-by-cell testing for production Jupyter notebooks in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/nbcelltests) (👨‍💻 7 · 🔀 16 · 📋 110 - 27% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/jpmorganchase/nbcelltests
	```
- [PyPi](https://pypi.org/project/nbcelltests) (📥 37 / month · ⏱️ 05.10.2020):
	```
	pip install nbcelltests
	```
- [npm](https://www.npmjs.com/package/jupyterlab_celltests) (📥 140 / month · ⏱️ 05.10.2020):
	```
	npm install jupyterlab_celltests
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉16 ·  ⭐ 54) - Automatically version jupyter notebooks in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) (👨‍💻 4 · 🔀 6 · 📋 29 - 17% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_autoversion
	```
- [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 120 / month · ⏱️ 29.06.2019):
	```
	pip install jupyterlab_autoversion
	```
- [npm](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 49 / month · ⏱️ 01.01.2021):
	```
	npm install jupyterlab_autoversion
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥉15 ·  ⭐ 210) - Navigate to variables definition with a click in.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyterlab-go-to-definition) (👨‍💻 2 · 🔀 9 · 📦 11 · 📋 23 - 43% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/krassowski/jupyterlab-go-to-definition
	```
- [npm](https://www.npmjs.com/package/@krassowski/jupyterlab_go_to_definition) (📥 2.5K / month · 📦 3 · ⏱️ 14.03.2020):
	```
	npm install @krassowski/jupyterlab_go_to_definition
	```
</details>
<details><summary><b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉15 ·  ⭐ 160 · 💤) - Implements Collapsible Headers for Jupyter Lab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/aquirdTurtle/Collapsible_Headings) (👨‍💻 6 · 🔀 7 · 📋 30 - 26% open · ⏱️ 22.05.2021):

	```
	git clone https://github.com/aquirdTurtle/Collapsible_Headings
	```
- [npm](https://www.npmjs.com/package/@aquirdturtle/collapsible_headings) (📥 2.1K / month · ⏱️ 11.01.2021):
	```
	npm install @aquirdturtle/collapsible_headings
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉15 ·  ⭐ 95) - JupyterLab Top Bar extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-topbar) (👨‍💻 4 · 🔀 10 · ⏱️ 07.12.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-topbar
	```
- [npm](https://www.npmjs.com/package/jupyterlab-topbar-extension) (📥 8.3K / month · ⏱️ 30.10.2020):
	```
	npm install jupyterlab-topbar-extension
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥉15 ·  ⭐ 82) - Open and explore HDF5 files in JupyterLab. Can handle very.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-hdf5) (👨‍💻 6 · 🔀 17 · 📋 42 - 21% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-hdf5
	```
- [PyPi](https://pypi.org/project/jupyterlab_hdf) (📥 460 / month · 📦 1 · ⏱️ 22.10.2021):
	```
	pip install jupyterlab_hdf
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/hdf5) (📥 370 / month · ⏱️ 22.10.2021):
	```
	npm install @jupyterlab/hdf5
	```
</details>
<details><summary><b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉15 ·  ⭐ 69) - JupyterLab extension that enables monitoring launched.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/itsjafer/jupyterlab-sparkmonitor) (👨‍💻 9 · 🔀 15 · 📋 15 - 46% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/itsjafer/jupyterlab-sparkmonitor
	```
- [PyPi](https://pypi.org/project/jupyterlab-sparkmonitor) (📥 250 / month · ⏱️ 04.08.2021):
	```
	pip install jupyterlab-sparkmonitor
	```
- [npm](https://www.npmjs.com/package/jupyterlab_sparkmonitor) (📥 93 / month · ⏱️ 29.07.2020):
	```
	npm install jupyterlab_sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/itsjafer/sparkmonitor) (📥 240 · ⏱️ 02.06.2021):
	```
	docker pull itsjafer/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥉15 ·  ⭐ 48) - Jupyterlab extension for SoS Polyglot Notebook and Workflow.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/jupyterlab-sos) (👨‍💻 4 · 🔀 3 · 📦 5 · 📋 58 - 17% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/vatlab/jupyterlab-sos
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 13K · ⏱️ 16.04.2021):
	```
	conda install -c conda-forge jupyterlab-sos
	```
- [npm](https://www.npmjs.com/package/jupyterlab-sos) (📥 180 / month · ⏱️ 14.01.2021):
	```
	npm install jupyterlab-sos
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉14 ·  ⭐ 36) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_commands) (👨‍💻 1 · 🔀 6 · 📦 3 · 📋 23 - 4% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_commands
	```
</details>
<details><summary><b><a href="https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor">jupyterlab-interactive-dashboard-editor</a></b> (🥉13 ·  ⭐ 190 · 💤) - A drag-and-drop dashboard editor for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor) (👨‍💻 10 · 🔀 25 · 📋 44 - 72% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor
	```
- [PyPi](https://pypi.org/project/jupyterlab-interactive-dashboard-editor) (📥 77 / month · ⏱️ 01.04.2021):
	```
	pip install jupyterlab-interactive-dashboard-editor
	```
</details>
<details><summary><b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉13 ·  ⭐ 100) - Jupyterlab python linter for notebooks and text files using.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mlshapiro/jupyterlab-flake8) (👨‍💻 5 · 🔀 9 · 📋 38 - 13% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/mlshapiro/jupyterlab-flake8
	```
- [npm](https://www.npmjs.com/package/jupyterlab-flake8) (📥 260 / month · ⏱️ 31.03.2020):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉13 ·  ⭐ 63) - A Jupyter Lab extension for inspecting messages to/from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) (👨‍💻 4 · 🔀 8 · 📦 3 · 📋 13 - 15% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
	```
- [npm](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 120 / month · ⏱️ 02.09.2021):
	```
	npm install jupyterlab-kernelspy
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/knowledgelab">KnowledgeLab</a></b> (🥉13 ·  ⭐ 43) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/knowledgelab) (👨‍💻 3 · 🔀 6 · 📦 2 · 📋 29 - 17% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/knowledgelab
	```
- [PyPi](https://pypi.org/project/knowledgelab) (📥 7 / month · ⏱️ 19.10.2017):
	```
	pip install knowledgelab
	```
- [npm](https://www.npmjs.com/package/knowledgelab) (📥 17 / month · ⏱️ 16.10.2018):
	```
	npm install knowledgelab
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉12 ·  ⭐ 100) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 1 · 🔀 9 · 📋 36 - 16% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [npm](https://www.npmjs.com/package/jupyterlab-flake8) (📥 260 / month · ⏱️ 31.03.2020):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/parente/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉12 ·  ⭐ 70 · 📉) - Quickly open a file in JupyterLab by typing part of.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/parente/jupyterlab-quickopen) (👨‍💻 5 · 🔀 6 · ⏱️ 12.12.2021):

	```
	git clone https://github.com/parente/jupyterlab-quickopen
	```
- [PyPi](https://pypi.org/project/jupyterlab-quickopen) (📥 350 / month · 📦 1 · ⏱️ 12.12.2021):
	```
	pip install jupyterlab-quickopen
	```
- [npm](https://www.npmjs.com/package/@parente/jupyterlab-quickopen) (📥 37 / month · ⏱️ 20.03.2020):
	```
	npm install @parente/jupyterlab-quickopen
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉12 ·  ⭐ 49) - JupyterLab extension to create Python files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-python-file) (👨‍💻 4 · 🔀 8 · 📥 76 · 📋 11 - 27% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-python-file
	```
- [npm](https://www.npmjs.com/package/jupyterlab-python-file) (📥 1.2K / month · ⏱️ 23.06.2021):
	```
	npm install jupyterlab-python-file
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉11 ·  ⭐ 50) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 1 · 🔀 2 · 📋 36 - 16% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab_email) (📥 120 / month · ⏱️ 30.06.2019):
	```
	pip install jupyterlab_email
	```
- [npm](https://www.npmjs.com/package/jupyterlab_email) (📥 110 / month · ⏱️ 25.06.2020):
	```
	npm install jupyterlab_email
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉10 ·  ⭐ 89) - JupyterLab extension to create GitHub commits & pull.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/ReviewNB/jupyterlab-gitplus) (👨‍💻 2 · 🔀 8 · 📋 16 - 50% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/ReviewNB/jupyterlab-gitplus
	```
- [PyPi](https://pypi.org/project/jupyterlab_gitplus) (📥 100 / month · ⏱️ 11.07.2021):
	```
	pip install jupyterlab_gitplus
	```
- [npm](https://www.npmjs.com/package/@reviewnb/jupyterlab_gitplus) (📥 66 / month · ⏱️ 22.06.2021):
	```
	npm install @reviewnb/jupyterlab_gitplus
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥈19 ·  ⭐ 160 · 💀) - First class datasets in JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥈17 ·  ⭐ 900 · 💀) - Vim notebook cell bindings for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉15 ·  ⭐ 360 · 💀) - SQL GUI for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉14 ·  ⭐ 420 · 💀) - Spit shine for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉14 ·  ⭐ 110 · 💀) - A JupyterLab extension for notebook cell tags. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉14 ·  ⭐ 86 · 💀) - Commenting and annotation for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉13 ·  ⭐ 55 · 💀) - A JupyterLab extension for managing keyboard shortcuts. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉10 ·  ⭐ 57 · 💀) - JupyterLab extension to explore CPython Bytecode. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉9 ·  ⭐ 7) - Spark Application UI extension for JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉8 ·  ⭐ 4 · 💤) - JupyterLab extension to execute the scripts from the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterHub Authenticators

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Authentication modules that manage and control how users can access the JupyterHub deployment._

<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇28 ·  ⭐ 330) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/oauthenticator) (👨‍💻 100 · 🔀 300 · 📦 240 · 📋 210 - 13% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jupyterhub/oauthenticator
	```
- [PyPi](https://pypi.org/project/oauthenticator) (📥 34K / month · 📦 41 · ⏱️ 10.08.2021):
	```
	pip install oauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 19K · ⏱️ 19.07.2021):
	```
	conda install -c conda-forge oauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥇23 ·  ⭐ 47) - JupyterHub-native User Authenticator https://native-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nativeauthenticator) (👨‍💻 21 · 🔀 49 · 📦 33 · 📋 89 - 23% open · ⏱️ 30.12.2021):

	```
	git clone https://github.com/jupyterhub/nativeauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 4.6K / month · ⏱️ 19.10.2021):
	```
	pip install jupyterhub-nativeauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥈22 ·  ⭐ 170 · 💤) - LDAP Authenticator Plugin for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ldapauthenticator) (👨‍💻 30 · 🔀 150 · 📦 85 · 📋 140 - 42% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/jupyterhub/ldapauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ldapauthenticator) (📥 5.8K / month · 📦 7 · ⏱️ 28.08.2020):
	```
	pip install jupyterhub-ldapauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-ldapauthenticator) (📥 23K · ⏱️ 28.08.2020):
	```
	conda install -c conda-forge jupyterhub-ldapauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈22 ·  ⭐ 48) - A JupyterHub authenticator for LTI. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ltiauthenticator) (👨‍💻 12 · 🔀 39 · 📦 70 · 📋 31 - 16% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/jupyterhub/ltiauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 2.4K / month · 📦 9 · ⏱️ 15.11.2021):
	```
	pip install jupyterhub-ltiauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈19 ·  ⭐ 38) - JupyterHub Authenticator that lets users set.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/firstuseauthenticator) (👨‍💻 12 · 🔀 21 · 📦 56 · 📋 22 - 22% open · ⏱️ 28.10.2021):

	```
	git clone https://github.com/jupyterhub/firstuseauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-firstuseauthenticator) (📥 3.7K / month · 📦 3 · ⏱️ 28.10.2021):
	```
	pip install jupyterhub-firstuseauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥈13 ·  ⭐ 30) - jupyterhub-samlauthenticator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HewlettPackard/jupyterhub-samlauthenticator) (👨‍💻 6 · 🔀 16 · 📥 13 · 📋 30 - 53% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/HewlettPackard/jupyterhub-samlauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-samlauthenticator) (📥 400 / month · ⏱️ 13.07.2020):
	```
	pip install jupyterhub-samlauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥈13 ·  ⭐ 28 · 💤) - A Dummy JupyterHub Authenticator to make testing easy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dummyauthenticator) (👨‍💻 1 · 🔀 14 · 📦 92 · 📋 8 - 75% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/jupyterhub/dummyauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-dummyauthenticator) (📥 1.8K / month · 📦 17 · ⏱️ 29.04.2017):
	```
	pip install jupyterhub-dummyauthenticator
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥈13 ·  ⭐ 38 · 💀) - A Token Authenticator for JupyterHub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥈13 ·  ⭐ 32 · 💀) - REMOTE_USER authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥈13 ·  ⭐ 7 · 💤) - Null Authenticator for JupyterHub instances that should.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉10 ·  ⭐ 16 · 💀) - CAS authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉10 ·  ⭐ 4 · 💤) - Authenticate users with passwords generated from their.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉8 ·  ⭐ 9 · 💀) - A JupyterHub authenticator using Kerberos. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉8 ·  ⭐ 1) - A collection of JupyterHub Authenticators, including.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/andreas-h/sshauthenticator">SSH Authenticator</a></b> (🥉4 ·  ⭐ 5 · 💀) - A simple SSH authenticator for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterHub Spawners

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Spawner modules that start, monitor, and stop single-user notebook servers._

<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥇30 ·  ⭐ 390) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kubespawner) (👨‍💻 66 · 🔀 240 · 📦 100 · 📋 280 - 21% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/jupyterhub/kubespawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 96K / month · 📦 14 · ⏱️ 28.11.2021):
	```
	pip install jupyterhub-kubespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥈26 ·  ⭐ 410) - Spawns JupyterHub single user servers in Docker containers. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dockerspawner) (👨‍💻 62 · 🔀 280 · 📦 110 · 📋 250 - 6% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/jupyterhub/dockerspawner
	```
- [PyPi](https://pypi.org/project/dockerspawner) (📥 5.6K / month · 📦 26 · ⏱️ 22.07.2021):
	```
	pip install dockerspawner
	```
- [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 10K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge dockerspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥈18 ·  ⭐ 130 · 💤) - Custom Spawner for Jupyterhub to start servers in batch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/batchspawner) (👨‍💻 38 · 🔀 94 · 📦 11 · 📋 110 - 37% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/jupyterhub/batchspawner
	```
- [PyPi](https://pypi.org/project/batchspawner) (📥 500 / month · 📦 2 · ⏱️ 07.04.2021):
	```
	pip install batchspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥈18 ·  ⭐ 74) - Spawn JupyterHub single-user notebook servers with systemd. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/systemdspawner) (👨‍💻 17 · 🔀 37 · 📦 19 · 📋 59 - 50% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/jupyterhub/systemdspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 1.4K / month · 📦 1 · ⏱️ 07.12.2020):
	```
	pip install jupyterhub-systemdspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉15 ·  ⭐ 41) - Spawn JupyterHub single-user servers with sudo. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/sudospawner) (👨‍💻 14 · 🔀 36 · 📦 36 · 📋 37 - 45% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/jupyterhub/sudospawner
	```
- [PyPi](https://pypi.org/project/sudospawner) (📥 780 / month · 📦 3 · ⏱️ 19.06.2018):
	```
	pip install sudospawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉12 ·  ⭐ 48) - Mechanism for runtime configuration of spawners for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/wrapspawner) (👨‍💻 16 · 🔀 44 · 📦 5 · 📋 31 - 58% open · ⏱️ 07.07.2021):

	```
	git clone https://github.com/jupyterhub/wrapspawner
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉11 ·  ⭐ 30 · 💀) - Spawns JupyterHub single user servers in Docker containers.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉11 ·  ⭐ 19 · 💀) - Spawn JupyterHub single user notebook servers in Hadoop/YARN.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Jupyter Components

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Core components of the Jupyter architecture._

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇46 ·  ⭐ 15K · 📈) - Official repository for IPython itself. Other repos in the IPython.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipython) (👨‍💻 850 · 🔀 4.3K · 📥 320K · 📦 240K · 📋 6.9K - 22% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/ipython/ipython
	```
- [PyPi](https://pypi.org/project/ipython) (📥 17M / month · 📦 35K · ⏱️ 12.01.2022):
	```
	pip install ipython
	```
- [Conda](https://anaconda.org/conda-forge/ipython) (📥 9.3M · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge ipython
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉30 ·  ⭐ 280 · 📈) - The backendi.e. core services, APIs, and REST endpointsto.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter_server) (👨‍💻 450 · 🔀 150 · 📥 200 · 📋 240 - 33% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/jupyter-server/jupyter_server
	```
- [PyPi](https://pypi.org/project/jupyter_server) (📥 970K / month · ⏱️ 31.07.2018):
	```
	pip install jupyter_server
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 1.1M · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge jupyter_server
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉24 ·  ⭐ 43) - Tools to help build and install Jupyter Python packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-packaging) (👨‍💻 22 · 🔀 40 · 📋 32 - 31% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/jupyter/jupyter-packaging
	```
- [PyPi](https://pypi.org/project/jupyter-packaging) (📥 190K / month · 📦 38 · ⏱️ 15.11.2021):
	```
	pip install jupyter-packaging
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-packaging) (📥 200K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge jupyter-packaging
	```
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jupyter/qtconsole">qtconsole</a></b> (🥇37 ·  ⭐ 290) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/qtconsole) (👨‍💻 110 · 🔀 170 · 📦 91K · 📋 300 - 34% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/jupyter/qtconsole
	```
- [PyPi](https://pypi.org/project/qtconsole) (📥 7.7M / month · 📦 6.3K · ⏱️ 13.12.2021):
	```
	pip install qtconsole
	```
- [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 2.2M · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge qtconsole
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥉27 ·  ⭐ 190) - Jupyter Terminal Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_console) (👨‍💻 57 · 🔀 120 · 📋 140 - 41% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/jupyter/jupyter_console
	```
- [PyPi](https://pypi.org/project/jupyter-console) (📥 7.8M / month · 📦 62 · ⏱️ 15.12.2021):
	```
	pip install jupyter-console
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉22 ·  ⭐ 1.7K · 💤) - Run VSCode (codeserver) on Google Colab or Kaggle Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/colabcode) (👨‍💻 8 · 🔀 220 · 📦 50 · 📋 72 - 58% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/abhishekkrthakur/colabcode
	```
- [PyPi](https://pypi.org/project/colabcode) (📥 9.7K / month · ⏱️ 11.06.2021):
	```
	pip install colabcode
	```
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
- [**best-of-ml-python**](https://github.com/ml-tooling/best-of-ml-python): A ranked list of awesome machine learning python libraries.
- [**awesome-jupyter**](https://github.com/markusschanta/awesome-jupyter): A curated list of awesome Jupyter projects, libraries and resources.
- [**awesome-jupyterlab**](https://github.com/mauhai/awesome-jupyterlab): A curated list of awesome JupyterLab extensions and resources.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-jupyter/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-jupyter/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-jupyter/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-jupyter/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-jupyter/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
