# AI Maverick Fraud Detection System

A comprehensive fraud detection system with a modern web interface, real-time monitoring, and interactive analytics dashboard.

## Features

- *Web-based Interface*: Modern Flask application with secure authentication
- *Real-time Fraud Detection*: Instant analysis of transactions using advanced algorithms
- *Interactive Analytics Dashboard*: Visual insights into fraud patterns and trends
- *Risk Assessment*: Multi-level risk scoring (High, Medium, Low)
- *Transaction Management*: Upload, view, and manage transactions
- *Admin Panel*: Secure administrative interface for system management
- *API Endpoints*: RESTful API for integration with other systems
- *Data Visualization*: Interactive charts and graphs using Chart.js
- *Secure Authentication*: Role-based access control with admin privileges
- *File Processing*: Support for CSV file uploads and processing

## Technologies Used

- Flask (Web Framework)
- Pandas (Data Processing)
- SQLAlchemy (Database ORM)
- Flask-Login (Authentication)
- Chart.js (Data Visualization)
- NumPy (Numerical Computations)
- Python logging (System Monitoring)
- RESTful API architecture
- JWT (Authentication)
- CSV/JSON (Data Formats)

## Installation

1. Clone the repository:
bash
git clone <repository-url>
cd ai-maverick-fraud-detection


2. Create and activate a virtual environment:
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3. Install dependencies:
bash
pip install -r requirements.txt


4. Set up environment variables:
bash
cp .env.example .env
# Edit .env with your configuration


## Usage

1. Start the Flask application:
bash
python app.py


2. Access the web interface:
   - Open your browser and navigate to http://localhost:5000
   - Default admin credentials:
     - Username: admin
     - Password: admin@123

3. Upload Transaction Data:
   - Prepare your CSV file with required columns:
     - TransactionID
     - TransactionDate
     - TransactionAmount
     - AccountID
     - DeviceID
     - Location

4. View Analytics:
   - Access the dashboard for real-time insights
   - View risk distributions and trends
   - Analyze transaction patterns

## System Components

### 1. Web Interface
- Secure login system
- Interactive dashboard
- Transaction management
- File upload functionality
- Real-time analytics

### 2. Fraud Detection
- Risk scoring system
- Anomaly detection
- Pattern recognition
- Real-time analysis

### 3. Analytics Dashboard
- Risk distribution charts
- Fraud trend analysis
- Transaction monitoring
- Risk factor analysis

### 4. Admin Features
- User management
- System configuration
- Data management
- Analytics access

## API Endpoints

### Authentication
- POST /login - User login
- GET /logout - User logout

### Transaction Management
- POST /api/upload - Upload transaction data
- POST /api/transaction/new - Add new transaction
- GET /api/transaction/<id> - Get transaction details

### Analytics
- GET /api/dashboard-stats - Dashboard statistics
- GET /api/risk-distribution - Risk distribution data
- GET /api/fraud-trends - Fraud trend analysis
- GET /api/risk-factors - Risk factor analysis

### Admin
- GET /api/admin/transactions - List all transactions
- POST /api/admin/update-label - Update transaction labels

## Security Features

- Secure authentication system
- Role-based access control
- Input validation
- Error handling
- Secure file processing
- Session management

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
