# TXT Number Sorter – Raw Python

A simple Python script to organize numeric lists stored in a TXT file. Perfect when you have a messy list of numbers and just want them sorted without any extra fluff.

## How it works

The script:
- Reads the `ordenar.txt` file
- Converts each line to an integer
- Sorts all numbers
- Saves the result into `ordenados.txt`

## Requirements

- Python 3 installed

## How to use

1. Create a file named `ordenar.txt` in the same directory as the script.
2. Add your numbers, one per line.
3. Run the script:

```bash
python ordenar.py
```

4. The script will generate `ordenados.txt` with all numbers sorted.

## Example code

```python
with open("ordenar.txt", "r") as f:
    ids = [int(line.strip()) for line in f if line.strip()]

ids.sort()

with open("ordenados.txt", "w") as f:
    for i in ids:
        f.write(str(i) + "\n")

print("IDs sorted successfully!")
```

---

# Ordenador de Numerações TXT – Python Bruto

Um script simples em Python para organizar listas numéricas salvas em um arquivo TXT. Ideal quando tu tem um monte de número bagunçado e só quer tudo arrumado sem frescura.

## Como funciona

O script:
- Lê o arquivo `ordenar.txt`
- Converte cada linha para inteiro
- Ordena os números
- Salva tudo em `ordenados.txt`

## Requisitos

- Python 3 instalado

## Como usar

1. Crie um arquivo chamado `ordenar.txt` no mesmo diretório do script.
2. Adicione seus números, um por linha.
3. Execute:

```bash
python ordenar.py
```

4. O arquivo `ordenados.txt` será gerado com tudo ordenado.

## Exemplo de código

```python
with open("ordenar.txt", "r") as f:
    ids = [int(line.strip()) for line in f if line.strip()]

ids.sort()

with open("ordenados.txt", "w") as f:
    for i in ids:
        f.write(str(i) + "\n")

print("IDs ordenados com sucesso!")
```

---

# Trieur de Numéros TXT – Python Brut

Un script Python simple pour trier une liste de numéros stockés dans un fichier TXT. Parfait quand tu as une liste désordonnée et que tu veux juste tout remettre en ordre sans complications.

## Comment ça marche

Le script :
- Lit le fichier `ordenar.txt`
- Convertit chaque ligne en entier
- Trie tous les numéros
- Sauvegarde le résultat dans `ordenados.txt`

## Pré-requis

- Python 3 installé

## Comment utiliser

1. Crée un fichier nommé `ordenar.txt` dans le même dossier que le script.
2. Ajoute tes numéros, un par ligne.
3. Exécute :

```bash
python ordenar.py
```

4. Le fichier `ordenados.txt` sera généré avec tous les numéros triés.

## Exemple de code

```python
with open("ordenar.txt", "r") as f:
    ids = [int(line.strip()) for line in f if line.strip()]

ids.sort()

with open("ordenados.txt", "w") as f:
    for i in ids:
        f.write(str(i) + "\n")

print("IDs triés avec succès !")
```
