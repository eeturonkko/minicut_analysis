# Fall Mini Cut: Workout Analysis Project

---

## Features

### 1. **Exercise Progress Tracking**

- Extracts and analyzes specific exercises:
  - **Leg Extension**
  - **V-Triceps Extension**
  - **Seated Hamstring Curl**
  - **Bayesian Curl**
- Visualizes:
  - **Weight Progress** over time
  - **Repetition Progress** over time

### 2. **Training Frequency**

- Calculates and visualizes:
  - **Sessions per Week**

---

## Data Structure

### Expected Input Format:

The notebook uses a CSV file containing workout data with the following columns:

| Column          | Description                       |
| --------------- | --------------------------------- |
| `date`          | Date of the workout (YYYY-MM-DD)  |
| `weight`        | Weight used for the exercise (kg) |
| `reps`          | Number of repetitions performed   |
| `exercise_name` | Name of the exercise              |

### Example Data:

| date       | weight | reps | exercise_name         |
| ---------- | ------ | ---- | --------------------- |
| 2024-10-03 | 54.5   | 7    | Seated Hamstring Curl |
| 2024-10-03 | 65.7   | 9    | Leg Extension         |

---

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fall-mini-cut-analysis.git
   cd fall-mini-cut-analysis
   ```
