# Automated Seating Plan Generator for Exams

This Python script generates a seating plan for students based on clustering. The seating plan assigns students to exam rooms and allocates faculty members to each room. 

## Usage

1. **Input Data:**
   - The script expects two CSV files:
     - `studentdata.csv`: Contains student data including names, domains, and batch information.
     - `facultydata.csv`: Contains faculty data including login numbers, names, and domains.

2. **Data Generation (Optional):**
   - If you need to generate sample student data, use the `studentdatagen.ipynb` notebook. 
   - After generating the data, it will be saved to `studentdata.csv`.

3. **Running the Script:**
   - Execute the main Python script `main.ipynb`.
   - Ensure that the required CSV files (`studentdata.csv` and `facultydata.csv`) are in the same directory.

4. **Output:**
   - The script will generate a seating plan in the file named `seating_plan.csv`.
   - The seating plan includes room numbers, student names, roll numbers, domains, and assigned faculty members.

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib

Install dependencies using:
```bash
pip install -r requirements.txt

Authors
Muhammad Saif
