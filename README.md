<!---
{
  "id": "2ba87074-5f0a-4949-a25c-a34ab7fcce1e",
  "depends_on": ["boolean_algebra_intro"],
  "author": "Stephan Bökelmann",
  "first_used": "2025-03-27",
  "keywords": ["boolean logic", "logic simulator", "CircuitVerse", "simulation", "digital logic"]
}
--->

# Simulating Boolean Logic with CircuitVerse

## 1) Introduction
Now that you understand the basics of Boolean algebra — with operators like `AND`, `OR`, and `NOT` — it’s time to put this knowledge into practice.

In this exercise, you will **build and simulate digital circuits** using an online logic simulator called **[CircuitVerse](https://circuitverse.org)**.

CircuitVerse lets you visually place switches, gates, and LEDs to construct logic circuits — a perfect playground for experimenting with Boolean expressions.

---

## 2) Tool Instructions

1. Visit [https://circuitverse.org](https://circuitverse.org)
2. Click on **"Launch Simulator"** (you don’t need an account).
3. Use the toolbox to add components:
   - **Inputs** (switches)
   - **Outputs** (bulbs/LEDs)
   - **Logic Gates** (AND, OR, NOT, etc.)
4. Connect components with wires
5. Toggle inputs and observe the outputs

Tip: Right-click on wires or components to delete or configure them.

---

## 3) Tasks

### Task 1: Simple OR Logic
- Create a circuit with two inputs (A and B)
- Connect them to an **OR gate**, and then to an LED
- Test all input combinations and verify the output

Boolean expression:
```
f(A, B) = A OR B
```

### Task 2: Conditional Light
- Use two inputs: A and B
- Create a circuit that turns the light on only if A is ON and B is OFF
- Use **AND** and **NOT** gates as needed

Boolean expression:
```
f(A, B) = A AND (NOT B)
```

### Task 3: Majority Gate (Three Inputs)
- Use **three inputs**: A, B, and C
- Build a circuit that turns on the LED if **at least two** inputs are ON
- You may need multiple **AND**, **OR**, and possibly **NOT** gates

Boolean expression (one possible way):
```
f(A, B, C) = (A AND B) OR (A AND C) OR (B AND C)
```

---

## 4) Questions
1. Did your simulated output match the truth table?
2. Were there any surprising behaviors when toggling inputs?
3. How would you build a function that turns on the output **only if all three inputs are equal**?
4. What’s the difference between building logic in CircuitVerse vs. writing truth tables?

---

## 5) Final Advice
Simulators like CircuitVerse bridge the gap between **abstract logic** and **real circuits**. By building your own logic functions, you’ll gain a deeper understanding of how computers "think" in terms of binary decisions.

> Don’t just build — test! Try every input combination, and verify that your logic circuit behaves as expected.

Next up: try implementing a **half adder** or **multiplexer** with just logic gates. You're already halfway there!

