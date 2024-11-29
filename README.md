# SmartTaxHub - GST Billing System in Django

SmartTaxHub is a simple yet powerful GST billing system developed using Django. It helps businesses and service providers generate GST-compliant invoices with ease, manage inventory, track balances, and keep accurate books. This project allows automatic GST and tax calculations, making billing faster and more efficient.

## Features:
- **Create GST Invoices**: Easily generate GST-compliant invoices for goods and services.
- **Inventory Management**: Maintain an inventory of products with quantities and prices.
- **Track Balances**: Keep track of payments, balances, and outstanding amounts for clients.
- **Print Bills**: Print bills or invoices for clients directly from the system.
- **Automatic Tax Calculation**: The system automatically calculates CGST, SGST, or IGST based on the type of transaction.
- **Automatic GST Calculation**: GST is automatically calculated and displayed on the invoice, reducing manual errors.

## Technology Stack:
- **Backend**: Python, Django
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (or any other database you prefer)
  
## Installation:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MTank76/SmartTaxHub.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd SmartTaxHub
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

6. Visit `http://127.0.0.1:8000` in your web browser to access the application.


## Contributing:
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are welcome, and we appreciate any improvements or bug fixes!

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
