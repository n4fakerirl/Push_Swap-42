# push\_swap - 42 | [FRENCH VERSION] _english below_

## 📚 Description

`push_swap` est un projet algorithmique de l'école 42 qui consiste à trier une pile d'entiers avec un ensemble restreint d'opérations sur deux piles (pile A et pile B). Le but est de produire l'algorithme de tri le plus efficace possible en un minimum de coups. Le projet se divise en deux programmes : `push_swap`, qui génère la séquence d'instructions, et la partie bonus `checker`, qui vérifie si push_swap trie bien la pile.

---

## 📦 Objectifs

* Implémenter un ensemble limité d'opérations : `sa`, `sb`, `ss`, `pa`, `pb`, `ra`, `rb`, `rr`, `rra`, `rrb`, `rrr`
* Analyser les différentes approches de tri selon la taille de l'entrée
* Créer un algorithme performant (J'ai utilisé l'algorithme turc pour ce projet)
* Optimiser les mouvements

---

## 🧠 Fonctionnement général

* Le programme `push_swap` prend une liste d'entiers en argument
* Il affiche sur la sortie standard une suite d'opérations
* Ces opérations, appliquées successivement, trient la pile A
* Le programme `checker` vérifie si les instructions fournies trient effectivement la pile

---

## 🔁 Opérations autorisées

| Commande | Description                          |
| -------- | ------------------------------------ |
| `sa`     | swap les deux premiers éléments de A |
| `sb`     | swap les deux premiers éléments de B |
| `ss`     | `sa` et `sb` en même temps           |
| `pa`     | pousse le sommet de B vers A         |
| `pb`     | pousse le sommet de A vers B         |
| `ra`     | fait tourner A vers le haut          |
| `rb`     | fait tourner B vers le haut          |
| `rr`     | `ra` et `rb` en même temps           |
| `rra`    | fait tourner A vers le bas           |
| `rrb`    | fait tourner B vers le bas           |
| `rrr`    | `rra` et `rrb` en même temps         |

---

## 🧪 Exemple

```bash
./push_swap 3 2 1
```

Sortie :

```
ra
sa
```

---

## ⚙️ Compilation

| Commande      | Description                                 |
| ------------- | ------------------------------------------- |
| `make`        | Compile `push_swap`                         |
| `make bonus`  | Compile le bonus `checker`                  |
| `make clean`  | Supprime les fichiers objets (`.o`)         |
| `make fclean` | Supprime les fichiers objets et exécutables |
| `make re`     | Nettoie puis recompile entièrement          |

---

## 🖼️ Note du projet

<p align="center">
  <img width="199" height="169" alt="image" src="https://github.com/user-attachments/assets/0f81d37f-0483-4001-948e-bc940ce6b006" />
</p>

---

## 🫐 Auteur

* Océane (ocviller)
* Piscine de Mars 2025
* Projet réalisé à 42 Paris, 2025

---

# push_swap - 42 | [ENGLISH VERSION]

## 📚 Description

`push_swap` is an algorithmic project from the 42 curriculum that consists of sorting a stack of integers using a limited set of operations on two stacks (Stack A and Stack B). The objective is to produce the most efficient sorting algorithm possible while using the fewest operations. The project is divided into two programs: `push_swap`, which generates the sequence of instructions, and the bonus program `checker`, which verifies that `push_swap` correctly sorts the stack.

---

## 📦 Objectives

* Implement a limited set of operations: `sa`, `sb`, `ss`, `pa`, `pb`, `ra`, `rb`, `rr`, `rra`, `rrb`, `rrr`
* Analyze different sorting strategies depending on the input size
* Develop an efficient sorting algorithm (I used the Turkish Algorithm for this project)
* Optimize the number of operations performed

---

## 🧠 How It Works

* The `push_swap` program takes a list of integers as arguments
* It prints a sequence of operations to the standard output
* When executed in order, these operations sort Stack A
* The `checker` program verifies that the provided instructions correctly sort the stack

---

## 🔁 Allowed Operations

| Command | Description                                  |
| ------- | -------------------------------------------- |
| `sa`    | Swap the first two elements of Stack A       |
| `sb`    | Swap the first two elements of Stack B       |
| `ss`    | Perform `sa` and `sb` simultaneously         |
| `pa`    | Push the top element from Stack B to Stack A |
| `pb`    | Push the top element from Stack A to Stack B |
| `ra`    | Rotate Stack A upwards                       |
| `rb`    | Rotate Stack B upwards                       |
| `rr`    | Perform `ra` and `rb` simultaneously         |
| `rra`   | Reverse rotate Stack A                       |
| `rrb`   | Reverse rotate Stack B                       |
| `rrr`   | Perform `rra` and `rrb` simultaneously       |

---

## 🧪 Example

```bash
./push_swap 3 2 1
```

Output:

```text
ra
sa
```

---

## ⚙️ Compilation

| Command       | Description                          |
| ------------- | ------------------------------------ |
| `make`        | Compiles `push_swap`                 |
| `make bonus`  | Compiles the bonus `checker` program |
| `make clean`  | Removes object files (`.o`)          |
| `make fclean` | Removes object files and executables |
| `make re`     | Cleans and recompiles the project    |

---

## 🖼️ Project Grade

<p align="center">
  <img width="199" height="169" alt="image" src="https://github.com/user-attachments/assets/0f81d37f-0483-4001-948e-bc940ce6b006" />
</p>

---

## 🫐 Author

* Océane (ocviller)
* March 2025 Piscine
* Project completed at 42 Paris in 2025

