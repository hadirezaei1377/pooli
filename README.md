# pooli

**Pooli** is a shared expense management application that makes it easy to split costs among groups. Whether you're traveling, dining out, or organizing a party, Pooli ensures that everyone knows their share and payments are transparent.  

---

## Features  

### Group Management  
- Add members to a group.  
- Edit or delete group members.  

### Expense Tracking  
- Record expenses with detailed descriptions (e.g., "Lunch at the Cafe").  
- Associate each expense with one or more group members.  

### Debt & Credit Calculation  
- Automatic calculations for each group member.  
- Display of individual balances to show who owes whom and by how much.  

### Final Reports  
- Generate a final summary for settlements.  
- Export the report for offline use or sharing.  

---

### Steps  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/hadirezaei1377/pooli.git 
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd pooli  
   ```  
3. Build the application:  
   ```bash  
   go build  
   ```  
4. Run the application:  
   ```bash  
   ./pooli  
   ```  

---

## Usage  

1. **Start the Application:**  
   Launch Pooli in your terminal.  

2. **Add Group Members:**  
   Use the provided commands to add members:  
   ```bash  
   add-member "name"  
  
   ```  

3. **Record Expenses:**  
   Add expenses with descriptions and allocate them to group members:  
   ```bash  
   add-expense "name1" 50 "name2,name3" 
   ```  

4. **View Balances:**  
   Display the current balances:  
   ```bash  
   view-balances  
   ```  

5. **Generate Reports:**  
   Create a final report for settlements:  
   ```bash  
   generate-report  
   ```  


---

## Contribution  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch for your feature or bug fix.  
3. Submit a pull request.  

---

## License  

This project is licensed under the MIT License. See the `LICENSE` file for details.  
