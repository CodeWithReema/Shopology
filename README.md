# Shopology

Shopology is an online marketplace and eCommerce platform similar to Amazon or eBay. Users can create a free account, build a personal dashboard, list items for sale, purchase goods, and interact with other users in a social and commercial environment.

## Features
- User registration and authentication
- Personalized user dashboard
- Item listing and browsing
- Secure buying and selling
- User-to-user messaging
- Search and filtering options

## Getting Started
Follow these steps to get Shopology running locally on your machine.

### Prerequisites
- Python 3.8+
- Git (optional, for cloning the repo)

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/shopology.git
   cd shopology
   ```

2. **Create and activate a virtual environment**
   - **Mac/Linux:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   - **Windows:**
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server**
   ```bash
   python manage.py runserver
   ```

6. **Open in browser**
   Visit `http://127.0.0.1:8000/` in your web browser.

## Contributing
Feel free to fork the repository and submit pull requests. Issues and feature requests are welcome!

## License
This project is licensed under the MIT License.

