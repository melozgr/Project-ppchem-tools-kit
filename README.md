# 🧰 Tools Kit
![logo](https://github.com/sgrunber/Project-ppchem-tools-kit/assets/160881864/2e4590b3-7015-4f69-9746-d950e87a7f8f)

## 📖 Description
The **Tools Kit** package allows chemistry students to find basic information on molecules and provides easy access to some graphs and calculations required in experimental laboratories.

## 📚 Table of Contents
- [Installation](#-installation)
- [Usage](#-usage)
- [Features](#-features)
- [Contributing](#-contributing)
- [License](#-license)
- [Screenshots](#-screenshots)
## How to use the Tools Kit package

### 1. Forking the repository
To begin, fork the repository to your own GitHub account. In order to do so, navigate to the repository page and press the *"Fork"* button. The repository will then be copied to your account and you will be able to access it.

### 2. Cloning of the repository
With the code `git clone https://github.com/*username*/Project-ppchem-tools-kit.git` and replacing *username* by your github username, a local copy is created.

### 3. Using the Tools Kit
Line 24: replace the line ASSETS_PATH = OUTPUT_PATH / Path(r"**path to your folder**"), with the pathname of your forked repository. Run the code in order for the interface to appear.

### 4. Navigating the interface
**i.** *Molecule Name*
Upon entering the molecule's raw formula, the Tools Kit will output the SMILEs of that molecule.

**ii.** *Molecular Weight*
Input of the molecule's SMILEs gives the corresponding molar mass, in g/mol.

**iii.** *Linear Regression*
By inputting an excel document, found by pressing the *browse* key and importing the file, the Tools Kit will output the linear regression graph, with the corresponding R<sup>2</sup> value.

**iv.** *Excel Graph*
By inputting an excel document with only x and y values arranged in two columns, the Tools Kit will print out the corresponding graph, plotting all the values. The graphs in part iii. and iv. can also take input Title, and X, Y axis labels.

**v.** *Error Calculation*

**vi.** *Show Molecule*
Input : SMILE Output : Molecular structure

### Installation

You can install **Tools Kit** using pip:

```bash
pip install Project_ppchem-tools-kit
