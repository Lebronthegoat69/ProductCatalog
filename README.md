# Product Catalog

## Description
Product Catalog is an ASP.NET Core MVC web application that allows users to view products, see product details, and add new products. It uses JSON file storage to save product information and data annotations to validate user input.

## Features
- Display a list of products.
- View individual product details.
- Add new products through a form.
- Store product data in a JSON file.
- Validate product names and prices.
- Use strongly typed Razor views.
- Navigate between pages using the navigation bar.

## Technologies Used
- C#
- ASP.NET Core MVC
- Razor Views
- HTML and Bootstrap
- JSON file storage
- Data Annotations

## Project Structure
- `Models/Product.cs` — Defines the Product model and validation rules.
- `Controllers/ProductsController.cs` — Handles product listing, details, creation, and JSON persistence.
- `Views/Products/Index.cshtml` — Displays the product list.
- `Views/Products/Details.cshtml` — Displays individual product details.
- `Views/Products/Create.cshtml` — Provides the form for adding products.
- `Views/Shared/_Layout.cshtml` — Contains the navigation bar and shared page layout.
- `data/products.json` — Stores product information.

## Validation
- Product names are required.
- Product prices must be between $0.01 and $1,000.
- Invalid form submissions display validation messages.

## How to Run
1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run the following command:

   ```bash
   dotnet run
   ```

4. Open the local URL displayed in the terminal.
5. Click **Products** in the navigation bar to view and manage products.

 
<img width="975" height="184" alt="image" src="https://github.com/user-attachments/assets/77412f34-1ab4-44f6-bbdb-be346a331c3f" />

 <img width="975" height="466" alt="image" src="https://github.com/user-attachments/assets/af4a87b6-7556-476d-9203-6ea8f6f5232e" />

 <img width="906" height="469" alt="image" src="https://github.com/user-attachments/assets/8ad55a58-7d5c-4100-aab3-201186d3557b" />
 <img width="579" height="315" alt="image" src="https://github.com/user-attachments/assets/3a5ccbf1-444c-4604-a756-130980077134" />


 

## Author
Sam
