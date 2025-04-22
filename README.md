# Helix Machine Translation System

## About
Helix is a Machine Translation System developed by Calnic Solutions and incubated by TWFTW International to translate text for low digital resource languages such as English and Manyika, among other languages of India. Its open system can be used to develop other language pairs by incorporating language-specific databases. Tested on the available corpus of the Bible, HELIX can also translate general domain text.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Installation

The language system mentioned below is mainly installed and tested on Ubuntu Operating Systems.

### Install system dependencies one by one.

---

**Step 1: Stanza Installation**

```bash
pip install stanza
```

---

**Step 2: Install Language**

```bash
python3
```

```python
> import stanza  
> stanza.download('en')  
> exit
```

---

**Step 3: Download or Clone the system repository from Git**

Use the command below to clone the system setup from the Git repository:

```bash
git clone https://github.com/calnicsolutions/Helix-Machine-Translation-System.git
```

---

**Step 4: Updating file path**

Navigate to the language folder:

```bash
cd manyika_aibt/bin
```

Edit the path in the shell file:

Open `aibt_mt_manyika.sh` in the VI editor:

```bash
vi aibt_mt_manyika.sh
```



Change `mypath` to the current folder path.  

Example:  

Change  
```bash
export mypath=/home/calnic/PROJECTS/AiBT/AFRICA/MANYIKA/manyika_aibt
```  
to  
```bash
export mypath=/home/calnic/AIBT_Africa/manyika_aibt
```

Save and exit.

## Usage

**Step 5: Follow the step below to run the system**

```bash
sh aibt_mt_manyika.sh input.txt output.txt
```

## Contact

[jossy@calnicsolutions.com](mailto:jossy@calnicsolutions.com)
