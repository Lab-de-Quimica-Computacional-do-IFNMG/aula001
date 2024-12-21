# aula001 
# Introdução a rdkit plotando estruturas em 2D.

# Importando as bibliotecas
```python
from rdkit import Chem
from rdkit.Chem import Draw
```

# definir nosso smiles
```python
smiles = ''
```


# atribuir função
```python
mol = Chem.MolFromSmiles(smiles)
```

# gerar desenho em 2D 
```python
img = Draw.MolToImage(mol)
display(img)
```

## Atividade: 
Passar todos para a forma de smiles em seguida gerar todas as estruturas em 2D 
Lista de Compostos Orgânicos para o Exercício:



Metano (CH₄)
Etano (C₂H₆)
Álcool Etílico (Etanol) (C₂H₅OH)
Ácido Acético (C₂H₄O₂)
Acetona (C₃H₆O)
Fenol (C₆H₆OH)
Benceno (C₆H₆)
Tolueno (C₆H₅CH₃)
Ciclohexano (C₆H₁₂)
Butano (C₄H₁₀)
Metil Acetato (Éster Metílico do Ácido Acético) (C₃H₆O₂)
Anilina (C₆H₇N)
Benzeno-1,2-diol (Hidroquinona) (C₆H₆(OH)₂)
Propileno (C₃H₆)
Clorofórmio (CHCl₃)
