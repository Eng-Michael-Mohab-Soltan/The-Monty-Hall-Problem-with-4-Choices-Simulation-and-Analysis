# 🎲 The Monty Hall Problem with 4 Choices — Simulation and Analysis

## 📖 Overview
I once heard a story about a probability puzzle:  
If you have 4 doors and pick one, then the host removes one door that is **neither your choice nor the correct one**, 
switching your choice supposedly increases your chance of winning by 33%.

It sounded unbelievable — so I decided to **simulate it in Python** and find out whether this claim is true or not.

---

## 🧠 The Idea
This project extends the classic **Monty Hall problem** to **4 doors instead of 3**.

- There is **1 correct door** with a prize behind it.  
- You make an initial choice.  
- The host then **removes one door** that is not your choice and not the prize door.  
- You can **either stay** with your first choice or **switch** to one of the remaining unopened doors.

We simulate both strategies one million times to compare the results.

---

## 🚀 Results (based on simulation)
| Strategy | Winning Chance |
|-----------|----------------|
| Stay      | ~25%           |
| Switch    | ~37.5%         |

✅ **Switching really does improve your chances**, even though it feels counterintuitive.

---

## 📂 Files
- `monty_hall_4doors.ipynb` — the full Colab notebook with explanation and code.  
- `README.md` — project overview and theoretical explanation.

---

## 🧩 Conclusion
This project shows how probability often defies human intuition.  
Even with 4 choices, switching after one wrong option is revealed **really increases your chance of winning**.  
Simulations like this help visualize and confirm mathematical reasoning in a hands-on way.

---

## 🧠 Author
Created by **Michael Mohab Soltan Nashed** — a simple experiment proving that math doesn’t lie 😄  

Feel free to fork, modify, or extend it to 5 or more doors to see how switching becomes even more powerful!
