
---

## Tasks Overview

### **Task 0 — API Request Automation**
Fetches data for a single Pokémon (Pikachu) from the Pokémon API and saves it to `data.json`.  
Logs errors to `errors.txt` if the request fails.

### **Task 1 — Extract Pokémon Data**
Parses the `data.json` file to extract Pikachu’s name, type, weight, and height using `jq`, `awk`, and `sed`.

### **Task 2 — Batch Pokémon Data Retrieval**
Retrieves data for multiple Pokémon and saves each to a separate JSON file in the `pokemon_data` directory.  
Handles API rate limits by adding delays between requests.

### **Task 3 — Summarize Pokémon Data**
Generates a CSV report containing the name, height, and weight of all Pokémon fetched in Task 2.  
Calculates average height and weight using `awk`.

### **Task 4 — Error Handling and Retry Logic**
Enhances batch retrieval with retry logic (up to 3 attempts per Pokémon) and error logging.

### **Task 5 — Parallel Data Fetching**
Fetches Pokémon data in parallel using background processes and `jobs`.  
Ensures proper process handling and waits for completion before continuing.

---

## 🛠 Requirements
- Bash (v4+ recommended)
- `curl`
- `jq`
- `awk`
- `sed`

---

## 📦 Installation
Clone the repository:
```bash
git clone https://github.com/<your-username>/ALXprodev-Devops.git
cd ALXprodev-Devops

