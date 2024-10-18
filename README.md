# 🌟 Markdown-ToC-Generator

_A quick and easy tool to generate a **Table of Contents** for your markdown files with minimal effort!_

---

## 📋 Table of Contents

1. [🚀 Installation Guide](#-installation-guide)
   - [✅ Step 1: Download the Executable](#-step-1-download-the-executable)
   - [✅ Step 2: Make it Executable](#-step-2-make-it-executable)
   - [✅ Step 3 (Optional): Global Access](#-step-3-optional-global-access)
   - [🐍 Download Python Script](#-download-python-script)
2. [🛠️ Usage Instructions](#️-usage-instructions)
   - [🖊️ Choosing ToC Location](#️-choosing-toc-location)
   - [⚡ Running the Generator](#-running-the-generator)
3. [🎨 Example](#-example)
4. [🔧 Additional Information](#-additional-information)
5. [✨ Final Words](#-final-words)
---

## 🚀 Installation Guide

The `mdtoc` tool can be installed in two ways: as a **standalone executable** or as a **Python script**.


### 📦 Download Executable

If you want to install the tool globally and easily, this is the best option for you.

#### ✅ Step 1: Download the Executable

Head over to the repository and download the `mdtoc` executable file. 📥

#### ✅ Step 2: Make it Executable

Ensure the file is executable by running the following command in the directory where you've downloaded it:

```bash
chmod +x mdtoc
```


#### 💡 Tip: You can check if the file is executable by running:

```bash
./mdtoc --help
```

#### ✅ Step 3 (Optional): Global Access

To make the tool globally available on Linux, move it to a directory in your PATH (like /usr/bin):

```bash
sudo mv mdtoc /usr/bin
```

*For other operating systems, check specific documentation on making a file executable globally. 🔍*


## 🐍 Download Python Script

If you prefer to use the generator as a Python script, follow these steps:

#### ✅ Step 1: Download the Script

Download the mdtoc file from the repository and rename it to mdtoc.py. 📝

#### ✅ Step 2: Edit the Script

Remove the first line of the file `(#!/usr/bin/env python3)` if it exists, as this is only needed for executables.


# 🛠️ Usage Instructions

Using the tool is incredibly simple! Just follow these two steps to add a **Table of Contents (ToC)** to your markdown file.


#### 🖊️ Choosing ToC Location

In the markdown file where you want to generate the Table of Contents, insert the following placeholder text:

```markdown
**MD-TOC**
```

This is where the generator will place your beautiful ToC. 🌟 Note: If **MD-TOC** appears on the same line as text, the generator will overwrite it!

## ⚡ Running the Generator

Once you've added the ToC placeholder, run the generator using one of these commands:

#### 🌍 If using the executable:

```bash
mdtoc <source_file> <dest_file>
```

#### 🐍 If using the Python script:

```bash
python mdtoc.py <source_file> <dest_file>
```

#### Explanation:

- `source_file` → The markdown file from which the Table of Contents should be generated.

- `dest_file` → The markdown file where the ToC should be inserted.

*💡 Both `source_file` and `dest_file` can be the same if you want to insert the ToC into the same file.*

## 🎨 Example

Let's say you want to generate a ToC for this very README.md file. First, you would mark the location with the **MD-TOC** placeholder like this:

```markdown
# Project Documentation

**MD-TOC**

## Section 1: Introduction
...
```

After running the generator, it would automatically generate the Table of Contents based on your file's headers:

```markdown
# Project Documentation

- [Section 1: Introduction](#section-1-introduction)
- [Section 2: Installation](#section-2-installation)
...

## Section 1: Introduction
...
```

And voilà! 🎉 You now have a neatly organized and clickable ToC!

## 🔧 Additional Information

- **Supported Markdown Headers**: The generator will include headers from # to ###### in the ToC.

- **Customization**: Feel free to modify the code to adjust the ToC style (e.g., nested lists, numbering).

- **Issues & Contributions**: If you encounter any issues or have ideas for improving the tool, please open a GitHub issue or submit a pull request. We welcome contributions! 🙌


## ✨ Final Words

The `Markdown-ToC-Generator` was designed to save you time and effort in organizing your markdown documents. We hope it helps improve your workflow! 🚀

Feel free to share this tool with others and give it a ⭐ on GitHub if you find it useful!

Made with ❤️ for developers by developers.
