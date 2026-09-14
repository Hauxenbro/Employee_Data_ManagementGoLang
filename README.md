# Gestion des Employés en Go (`data_management.go`)

Ce projet propose une implémentation simple en **Go** pour la gestion d'une liste d'employés via une structure `Manager`.

## 📋 Description

Le fichier `data_management.go` définit les structures de données pour représenter un employé (`Employee`) et un gestionnaire (`Manager`). Il fournit des méthodes clés pour manipuler et analyser les données des employés.

## 🚀 Fonctionnalités

- **Ajout d'employé (`AddEmployee`)** : Ajoute un nouvel employé à la liste gérée par le `Manager`.
- **Suppression d'employé (`RemoveEmployee`)** : Supprime un employé de la liste à partir de son identifiant unique (`ID`).
- **Calcul du salaire moyen (`GetAverageSalary`)** : Calcule et retourne le salaire moyen de l'ensemble des employés enregistrés (retourne `0` si la liste est vide).
- **Recherche par ID (`FindEmployeeByID`)** : Recherche et renvoie un pointeur vers l'employé correspondant à l'ID fourni (ou `nil` si non trouvé).

## 🛠️ Data Structures

```go
type Employee struct {
	ID     int
	Name   string
	Age    int
	Salary float64
}
type Manager struct {
	Employees []Employee
}
```

### 1.Copier le programme
`git clone`
### 2. Executer
` go run data_management.go `
### 3. Example:
```
$ go run data_management.go
Average Salary: 65000.000000
Employee found: {ID:2 Name:Bob Age:25 Salary:65000}
```
