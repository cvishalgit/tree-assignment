# Assignment

## Display a Hierarchical Tree Structure in Angular

### 🎯 Objective  
Build an Angular component that takes a tree-like data structure (`key → children array`) and displays it as a properly **indented hierarchy** using nested `<ul>` and `<li>` lists.

---

### 📋 Input Data  
The component should work with the following tree object:

```typescript
const tree = {
  "a": ["b", "c"],
  "b": ["d", "e"],
  "c": ["f", "g"],
  "e": ["h", "i"],
  "f": ["j", "k"]
};
📌 Expected Output

The tree should be rendered as:
a
- b
    - d
    - e
        - h
        - i
- c
    - f
        - j
        - k
    - g
🚀 How to Run

Clone this repository:

git clone https://github.com/cvishalgit/tree-assignment.git


Navigate into the project:

cd tree-assignment


Install dependencies:

npm install


Run the Angular development server:

ng serve


Open your browser and go to:

http://localhost:4200

📂 Project Structure
tree-assignment/
│-- src/
│   ├── app/
│   │   ├── app.component.ts
│   │   ├── app.component.html
│   │   ├── app.component.css
│   │   └── ...
│   ├── index.html
│   └── styles.css
├── angular.json
├── package.json
├── tsconfig.json
└── README.md
