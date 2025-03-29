# **AIRBNB - Data Engineering Project**

## **Setup Instructions for DBT with Snowflake**

Follow these steps to set up your DBT project:

### **1. Create and Activate a Virtual Environment**
```sh
python -m venv venv  # Create a virtual environment  
venv\Scripts\activate  # Activate the virtual environment (Windows)  
# For macOS/Linux: source venv/bin/activate  
```

### **2. Install Dependencies**
```sh
pip install --upgrade pip  # Upgrade pip  
pip install dbt-snowflake==1.9.0  # Install DBT for Snowflake  
```

### **3. Initialize DBT Project**
```sh
dbt init dbtlearn  # Initialize a new DBT project  
```

### **4. Configure Snowflake Credentials**
- Add Snowflake credentials in the `profiles.yml` file.  
- Ensure correct **account, user, password, role, database, warehouse, and schema** details.  

### **5. Navigate to the Project Directory**
```sh
cd dbtlearn  
```

### **6. Test Snowflake Connection**
```sh
dbt debug  # Verify DBT connection to Snowflake  
```

---

This version keeps it clean, precise, and professional. Let me know if you'd like any other refinements! 🚀

