<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">TORGRAB</h1>
</p>
<p align="center">
    <em><code>► Darkweb Onion Link Extraction Made Easy.</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/last-commit/DefinitelyNotWilko/TorGrab?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/DefinitelyNotWilko/TorGrab?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/DefinitelyNotWilko/TorGrab?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
</details>
<hr>

##  Overview

<code>► TorGrab is a Python script designed to search the Dark Web for .onion links using the "Ahmia" Dark Web Search engine. It extracts relevant .onion links and stores the results in a CSV file for further analysis or usage.</code>

---

##  Features

<code>► 1. Dark Web Search: Utilizes the Ahmia search engine to perform queries on the Dark Web.
      2. .Onion Link Extraction: Extracts .onion links from search results.
      3. CSV Output: Stores extracted links and relevant metadata in a CSV file.
      4. Configurable Search Parameters: Allows users to customize search queries and parameters.</code>

---

##  Modules

<details open><summary>.</summary>

| File                                                                                           | Summary                         |
| ---                                                                                            | ---                             |
| [torgrab.py](https://github.com/DefinitelyNotWilko/TorGrab/blob/master/torgrab.py)             | The main TorGrab Python Script. |
| [requirements.txt](https://github.com/DefinitelyNotWilko/TorGrab/blob/master/requirements.txt) | Requirements to be installed to make TorGrab function. |

</details>

---

##  Getting Started

**System Requirements:**

* **Python**: `version 3.8`

###  Installation

<h4>From <code>Github</code></h4>

> 1. Clone the TorGrab repository:
>
> ```console
> $ git clone https://github.com/DefinitelyNotWilko/TorGrab.git
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd TorGrab
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

###  Usage

<h4>From <code>source</code></h4>

> Run TorGrab using the command below:
> ```console
> $ python torgrab.py <QUERY> <NUMBER_OF_RESULTS>
> ```

---

##  Project Roadmap

- [X] `► Rework the Script now that im better at Python.`
- [ ] `► Other stuff`
- [ ] `► ...`

---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/DefinitelyNotWilko/TorGrab/issues)**: Submit bugs found or log feature requests for the `TorGrab` project.
- **[Submit Pull Requests](https://github.com/DefinitelyNotWilko/TorGrab/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.


<details open>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/DefinitelyNotWilko/TorGrab
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-torgrab-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature for TorGrab - x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-torgrab-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>


---

[**Return**](#-overview)

---
