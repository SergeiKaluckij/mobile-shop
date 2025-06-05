[Русский](/README.ru_RU.md)

## 📱 Mobile Shop

**Mobile Shop** is a mini React Native application for placing orders from a large product list. It was developed as a test assignment to demonstrate proficiency in TypeScript and MobX.

### 🔑 Features

- 📦 Add and remove products from the cart (up to 1000 items)
- ⚙️ Select order options (leave at the door, call upon delivery, etc.)
- 📊 Send analytics events to the backend on any change in the cart or options (with simulated errors and result logging)
- 🧾 Order confirmation screen showing selected items, options, and total amount
- ✅ Minimum order amount validation (1000 ₽)
- 🚫 Handle possible backend errors when placing an order (e.g., item out of stock, service unavailable, order below minimum)

### 🧰 Technologies

- **React Native** (without Expo)
- **TypeScript** — strict typing and data model definitions
- **MobX** — state management and reactivity
- Optional use of third-party UI libraries — clean and user-friendly design is encouraged

### 📝 Note

A real backend is not required. All backend responses and errors are simulated in the code for testing purposes.

---

## 🧑‍💻 Git Commit Workflow

This project uses [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) to maintain consistent commit messages.

### 🔧 Commit types

- `feat`: A new feature  
  _Example_: `feat: add cart`
- `fix`: A bug fix  
  _Example_: `fix: handle out-of-stock error`
- `docs`: Documentation changes only  
  _Example_: `docs: update README with commit workflow`
- `chore`: Routine tasks, tooling, configs (no user-facing change)  
  _Example_: `chore: update dependencies`
- `refactor`: Code refactoring that doesn't add features or fix bugs  
  _Example_: `refactor: simplify MobX logic`

### 📝 Example full commit
