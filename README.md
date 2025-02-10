# Gram-Schmidt Orthogonalization

## Descriere
Această aplicație implementează procesul de ortogonalizare Gram-Schmidt pentru un set de trei vectori 3D. Algoritmul transformă un set de vectori liniar independenți într-un set ortogonal, iar apoi îi normalizează pentru a obține un set ortonormal.

## Funcționalități
- **Introducerea vectorilor de bază**: Utilizatorul introduce trei vectori 3D.
- **Calculul bazei ortogonale** (`B'`) utilizând Gram-Schmidt.
- **Calculul bazei ortonormale** (`B''`) prin normalizarea vectorilor ortogonali.
- **Afișarea rezultatelor**:
  - Baza ortogonală (`u1, u2, u3`).
  - Baza ortonormală (`e1, e2, e3`).

## Structura Codului
- **Inițializarea vectorilor**: Se citesc trei vectori 3D de la utilizator.
- **Calculul proiecțiilor**: Se determină componentele ortogonale folosind formulele Gram-Schmidt.
- **Normalizarea vectorilor**: Se calculează vectorii unitari împărțind la norma lor.
- **Afișarea rezultatului**: Se afișează bazele ortogonale și ortonormale.

## Compilare și Rulare
1. **Executarea scriptului**  
   Rularea programului se face cu:
   ```sh
   python3 gram_schmidt.py
   ```
2. **Introducerea vectorilor**  
   Utilizatorul introduce valorile pentru cei trei vectori.

## Exemplu de Output
```
B' = { u1=(x1, y1, z1) , u2=(x2, y2, z2) , u3=(x3, y3, z3) }
B'' = { e1=(x1', y1', z1') , e2=(x2', y2', z2') , e3=(x3', y3', z3') }
```

