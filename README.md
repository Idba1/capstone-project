## **Digital Money Management System (DMMS)**

https://1drv.ms/p/s!AhWf8FcUSoTEgRic7mGGeOyQzZEr?e=8VOqb2

![Digital money managemant system](https://i.ibb.co.com/gjGfmPH/napkin-selection.png)


## **Description**  
The **Digital Money Management System (DMMS)** is a secure and efficient platform designed to streamline personal financial management. Built with the lightweight **C programming language**, it offers:  
- Robust tools for users to track expenses, manage accounts, and generate reports.  
- Administrative features for user account oversight and monitoring.  

---

## **Features**

![Feature](https://i.ibb.co.com/Mk93jcw/napkin-selection-2.png)


### **User Features**  
- **Financial Tracking**:  
  - Monthly and yearly reports.  
  - Track expenses across categories: **Food**, **Housing**, **Children**, **Health**, and **Others**.  
  - View detailed transaction history.  

- **Account Operations**:  
  - Deposit and withdraw money.  
  - **Category-based withdrawals** (e.g., Food, Housing).  
  - Update account details:  
    - Name.  
    - Account Number.  
    - Password.  

- **Account Management**:  
  - Request account deletion (requires admin approval).  

---

### **Admin Features**  
- **User Management**:  
  - View a complete list of all user accounts.  
  - Search and manage specific user accounts.  
  - Approve or decline account deletion requests.  

- **Reporting and Monitoring**:  
  - View all accounts on a single page.  
  - Generate detailed financial activity reports.  
  - Monitor system health and ensure compliance.  

- **Security**:  
  - Validate transactions.  
  - Secure data encryption and storage.  

---

## **Technical Details**

![Technical Details](https://i.ibb.co.com/tp6SM79/napkin-selection-3.png)

### **Programming Language**  
- C Programming Language  

### **Libraries Used**  
- `<stdio.h>`  
- `<string.h>`  
- `<stdlib.h>`  
- `<conio.h>`  
- `<time.h>`  

### **Key Modules and Functions**

#### **User Modules**  
- `void deposit_money()`  
- `void withdraw_money()`  
- `void account_report()`  
- `void update_account_details()`  

#### **Admin Modules**  
- `void view_support_requests()`  
- `void approve_deletion_requests()`  
- `void search_account()`  

#### **Utility Functions**  
- `void record_transaction()`  
- `void save_user_data()`  
- `void load_user_data()`  

---

### **File Handling**  
![Technical Details](https://i.ibb.co.com/HtcF9qZ/napkin-selection-4.png)

- User data is stored and retrieved via files for data persistence.  

### **Compilation**  
Use **GCC Compiler** for compiling and running the program:  
```bash
gcc -o digital_money_manager main.c
./digital_money_manager
```

---

## **How to Use**
![Technical Details](https://i.ibb.co.com/TkWCHFs/napkin-selection-5.png)

1. **Installation**:  
   - Clone the repository or download the source files.  
   - Compile the program:  
     ```bash
     gcc -o digital_money_manager main.c
     ```  
   - Run the program:  
     ```bash
     ./digital_money_manager
     ```  

2. **Main Menu Options**:  
   - **1. Login to Account**  
   - **2. Register Account**  
   - **3. Admin Login**  
   - **4. User Support**  
   - **5. Exit**  

3. **User Operations**:  
   - Deposit/withdraw money.  
   - View transaction history or account reports.  
   - Update personal details or request account deletion.  

4. **Admin Operations**:  
   - Monitor user activities and transactions.  
   - Approve or decline deletion requests.  

---

## **Future Enhancements**  
- **Graphical User Interface (GUI)** for better usability.  
- Support for multiple users in a single application instance.  
- Advanced data export options (e.g., CSV).  
- **AI-powered financial insights** based on user spending habits.  

---

## **Contributors**  
![Technical Details](https://i.ibb.co.com/8XB9WPN/napkin-selection-6.png)
- **Monira Islam**  
- **Md Jakaria Nur**  
- **Sami Ansari**  

---

## **Contact Information**  
For support or inquiries:  
- **Email**: [moniraislam793@gmail.com](mailto:moniraislam793@gmail.com)  
- **Phone**: +8801618360986  


