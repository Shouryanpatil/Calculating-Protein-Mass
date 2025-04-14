# Calculating Protein Mass

This project provides a Python script that calculates the **total monoisotopic mass** of a given protein string using the standard 20-symbol amino acid alphabet.

## 🧠 Problem Explanation
Each amino acid is represented by a letter and has a known weight (monoisotopic mass). To find the total weight of a protein string, we simply:

1. Look up the weight for each letter in the string.
2. Add them all together.

### 🧬 Example
Given the protein string:
```
SKADYEK
```
The output will be:
```
821.392
```

## 📥 Input
Set the protein string directly in the Python file:
```python
protein = "SKADYEK"
```

## 📤 Output
The script prints the total mass of the protein string, rounded to 3 decimal places.

## 🧪 How to Run
1. Make sure you have Python installed.
2. Download or clone this repository.
3. Open the Python file and set your desired protein string.
4. Run the script:
```bash
python protein_mass.py
```

## 📂 Files
- `protein_mass.py`: Main script that calculates protein mass.

## 🧾 Amino Acid Mass Table
The script uses the monoisotopic mass table for the standard 20 amino acids.

## 📌 Constraints
- Protein string length: maximum of 1000 characters.
- Only uppercase letters from the standard amino acid alphabet are allowed.

