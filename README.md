# e-plantShopping — Paradise Nursery E-Commerce Application

Welcome to **e-plantShopping**, a comprehensive responsive e-commerce web application built with React and Redux Toolkit. This project simulates a complete user shopping lifecycle for **Paradise Nursery**, an online botanical store tailored for houseplant enthusiasts looking to bring green serenity into their living spaces.

---

## 🌿 Project Overview

The **e-plantShopping** platform is engineered to deliver an intuitive interface for plant exploration, cart orchestration, and real-time financial subtotals computation. The system features a modular architecture that bridges layout states dynamically across individual product views, inventory collections, and customer carts.

### Key Functionalities Implemented:
* **Dynamic Plant Matrix Grid:** Hosts 5 core botanical categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, and Low Maintenance Plants) featuring distinct thumbnail references, descriptive metadata, and targeted pricing models.
* **Redux Architecture State Engine:** Utilizes `@reduxjs/toolkit` hooks (`useSelector` and `useDispatch`) to decouple state tracking from layout parameters, governing instant updates on element insertions, drops, and bulk unit shifts.
* **Reactive Inventory Buttons:** Modifies product card CTA buttons to a grayed-out disabled state once selected, shifting contextual display text from "Add to Cart" to "Added to Cart" dynamically.
* **Unified Navbar Indicator Counter:** Aggregates a running tally of every atomic plant unit held within the cart slice, displaying the numerical result instantly inside the global menu bar across all app screens.
* **Precise Subtotal & Total Computation:** Strips formatting elements on the fly to process raw mathematical floats, instantly parsing values to recalculate individual item rows and overall cart weights upon quantity shifts.

---

## 🛠️ Tech Stack & Architecture

* **Frontend Library:** React (Functional Components & State Hooks)
* **State Management Container:** Redux Toolkit (Slices, Actions, and Immutable Reducer Mutations)
* **Build Tooling & Server:** Vite (Fast Hot-Module Replacement)
* **Deployment Suite:** GitHub Pages (`gh-pages`)

---

## 🚀 Installation and Local Execution

To run the **e-plantShopping** application architecture inside your local environment, utilize the following instructions:

1. Clone the repository upstream branch:
```bash
   git clone [https://github.com/SOMBUDDHAASH/e-plantShopping.git](https://github.com/SOMBUDDHAASH/e-plantShopping.git)
