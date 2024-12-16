# aula001
Introdução a dkit
#código
from rdkit import Chem
from rdkit.Chem import Draw
from rdkit.Chem import Descriptors, Crippen, Lipinski  

#definir nosso smiles
smiles = ''


#import da biblioteca
mol = Chem.MolFromSmiles(smiles)

#pedir o desenho 
img = Draw.MolToImage(mol)

display(img)

Lista de Compostos Orgânicos para o Exercício:
passar todos para a forma de smiles em seguida gerar todas as estruturas em 2D  

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
