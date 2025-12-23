# Libft - Projet 42

## 📚 Description

**Libft** est l’un des premiers projets du cursus 42. Il consiste à recréer une bibliothèque standard en C regroupant des fonctions utilitaires courantes (gestion de chaînes, mémoire, conversions, listes chaînées, etc.) afin de renforcer la compréhension du langage C et des bases de la programmation.

Vous implémentez vos propres versions de fonctions telles que `memset`, `strcpy`, `atoi`, `split`, ainsi qu’une liste chaînée générique.

---

## 🛠️ Fonctionnalités

- Fonctions de manipulation de mémoire (`memset`, `memcpy`, etc.)
- Fonctions sur les chaînes de caractères (`strlen`, `strchr`, etc.)
- Fonctions de conversion (`atoi`, `itoa`, etc.)
- Fonctions d’affichage (`putchar`, `putstr`, etc.)
- Gestion de listes chaînées (`lstnew`, `lstadd_front`, `lstsize`, etc.)
- Respect des normes et des conventions de l’école 42

---

## 📂 Structure du projet

- `libft.h` : Fichier d’en-tête regroupant les prototypes
- `*.c` : Fichiers source pour chaque fonction
- `Makefile` : Compilation de la bibliothèque

---

## 🚀 Utilisation

### 1. Compilation

```bash
make
```

La commande produit un fichier `libft.a` (archive statique).

### 2. Intégration dans vos projets

Incluez le header dans votre code :

```c
#include "libft.h"
```

Et lors de la compilation, liez la bibliothèque :

```bash
gcc votre_code.c -L. -lft
```

---

## 📝 Contraintes

- Respect des prototypes et des comportements de la libc
- Gestion correcte des erreurs (NULL, allocations, etc.)
- Interdiction d’utiliser la plupart des fonctions de la libc (sauf celles autorisées par le sujet)

---

## 💡 Conseils

- Testez chaque fonction séparément
- Utilisez `valgrind` pour vérifier les fuites de mémoire
- Respectez la norme de codage 42 (Norminette)

---

## 👤 Auteur

Projet réalisé par [asmati](https://github.com/karten1080) dans le cadre du cursus 42.
