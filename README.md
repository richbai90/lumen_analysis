<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center">
	<em>Deciphering mysteries, one sound wave at a time.</em>
</p>
<p align="center">
	<!-- local repository, no metadata badges. --></p>
<p align="center">Built with the tools and technologies:</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=default&logo=Jupyter&logoColor=white" alt="Jupyter">
	<img src="https://img.shields.io/badge/NumPy-013243.svg?style=default&logo=NumPy&logoColor=white" alt="NumPy">
	<img src="https://img.shields.io/badge/SciPy-8CAAE6.svg?style=default&logo=SciPy&logoColor=white" alt="SciPy">
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

Here's a 50-word overview of the project:

Uncover the secrets hidden within Severance's enigmatic audio. This project analyzes the distorted speech at the end of the "Lumen is Listening" TV spot. Using Python and signal processing, it aims to decipher the garbled message, shedding light on the show's mysteries for curious fans and audio enthusiasts.

---

##  Features

|      | Feature         | Summary       |
| :--- | :---:           | :---          |
| ⚙️  | **Architecture**  | <ul><li>Jupyter notebook (`analyze.ipynb`) for exploratory data analysis and visualization</li><li>Python scripts for audio signal analysis (`project_summary.txt`)</li><li>WAV audio file (`lumen_is_listening.wav`) as the primary data source</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Uses popular data science libraries like `numpy`, `scipy`, `matplotlib`</li><li>Modular design with separate files for analysis, data, and dependencies</li></ul> |
| 📄 | **Documentation** | <ul><li>Includes a project summary file (`project_summary.txt`)</li><li>Code comments and Markdown cells in the Jupyter notebook explain the analysis steps</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Utilizes the `soundfile` library for reading the WAV audio file</li><li>Leverages Jupyter notebook for interactive development and analysis</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separates concerns with a dedicated Jupyter notebook for analysis</li><li>Externalizes dependencies in a `requirements.txt` file</li><li>Modular design allows for easy extension and modification</li></ul> |
| 🧪 | **Testing**       | <ul><li>Testing approach not explicitly mentioned in the provided context</li><li>Opportunity to add unit tests for the audio analysis functions</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Utilizes NumPy and SciPy for efficient numerical computations</li><li>Processes a single audio file, performance considerations for larger datasets</li></ul> |
| 🛡️ | **Security**      | <ul><li>No apparent security concerns for the given use case</li><li>Potential considerations for securely handling and storing audio files</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Clearly defined in the `requirements.txt` file</li><li>Uses standard data science libraries: `numpy`, `scipy`, `matplotlib`, `soundfile`</li><li>Relies on `jupyter` for the interactive development environment</li></ul> |
| 🚀 | **Scalability**   | <ul><li>Designed for analyzing a single audio file</li><li>Scalability considerations for processing larger datasets or multiple files</li><li>Potential for parallel processing or distributed computing for scalability</li></ul> |

---

##  Project Structure

```sh
└── /
    ├── analyze.ipynb
    ├── lumen_is_listening.wav
    ├── project_summary.txt
    └── requirements.txt
```


###  Project Index
<details open>
	<summary><b><code>/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='/requirements.txt'>requirements.txt</a></b></td>
				<td>- Specifies the project's Python dependencies, including Jupyter for interactive development, NumPy and SciPy for scientific computing, Matplotlib for data visualization, and SoundFile for audio file I/O<br>- These libraries enable the project to perform computational tasks, analyze data, create visualizations, and process audio files, forming the foundation for the project's functionality.</td>
			</tr>
			<tr>
				<td><b><a href='/lumen_is_listening.wav'>lumen_is_listening.wav</a></b></td>
				<td>- Extracted audio from the Youtube spot 
			</tr>
			<tr>
				<td><b><a href='/analyze.ipynb'>analyze.ipynb</a></b></td>
				<td>- The analyze.ipynb Jupyter notebook performs exploratory data analysis and visualization on the project's dataset<br>- Its purpose is to gain insights, identify patterns, and communicate findings about the data.</td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with , ensure your runtime environment meets the following requirements:

- **Programming Language:** Python >= 3.10
- **Package Manager:** Pip


###  Installation

Install  using one of the following methods:

**Build from source:**

1. Clone the  repository:
```sh
❯ git clone ../
```

2. Navigate to the project directory:
```sh
❯ cd 
```

3. Install the project dependencies:
```sh
❯ pip install -r requirements.txt
```




###  Usage
Run using your preferred jupyter runtime

---

##  License

This project is protected under the MIT License. For more details, refer to the LICENSE file.


---
