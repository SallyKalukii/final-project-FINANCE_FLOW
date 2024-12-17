# FinanceFlow - Interactive Financial Education Platform

FinanceFlow is a comprehensive financial education platform designed to help users develop healthy financial habits through real-world data analysis, interactive simulations, and personalized learning paths.

## Features

### 1. Investment Simulator
- Real-time investment scenario simulation
- Risk tolerance assessment
- Multiple asset class options (Stocks, Bonds, Mutual Funds, Crypto)
- Visual representation of projected returns
- Historical simulation data storage

### 2. Goal Tracking
- Create and manage financial goals
- Track progress with visual indicators
- Categorize goals (Savings, Investment, Debt Repayment, Emergency Fund)
- Achievement system for completed goals
- Real-time progress updates

### 3. Learning Center
- Interactive financial education modules
- Progress tracking for each module
- Content sanitization for security
- Completion achievements
- Mobile-responsive design

### 4. User Management System
- Role-based access control (Super Admin, Admin, User)
- Profile management with image upload
- Secure authentication system
- Email verification
- Password encryption

### 5. Profile Management
- Profile picture upload
- Personal information management
- Secure data handling
- Responsive design
- Input validation

## Technical Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5.3.0
- Font Awesome 6.0.0
- Chart.js (for data visualization)

### Backend
- PHP
- MySQL
- Session Management
- PDO/MySQLi for database operations

### Security Features
- Password hashing
- Input sanitization
- DOMPurify for XSS prevention
- CSRF protection
- Secure file upload handling

## Installation

1. Clone the repository

2. Configure database
- Create a MySQL database
- Import the provided SQL schema
- Update `db/config.php` with your database credentials

3. Set up web server
- Configure Apache/Nginx to serve the application
- Ensure PHP 7.4+ is installed
- Enable required PHP extensions (mysqli, gd)

4. Configure file permissions
chmod 755 -R /path/to/financeflow
chmod 777 -R /path/to/financeflow/uploads


## Usage

1. Access the application through your web browser
2. Register a new account or login
3. Navigate through the services menu to access features
4. Start with the Learning Center to understand financial concepts
5. Use the Investment Simulator to practice strategies
6. Set up and track financial goals

## Security Considerations

- Implement HTTPS
- Regular security updates
- Backup database regularly
- Monitor error logs
- Update dependencies

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

For support or queries, contact:
- Email: sallymutemwa@gmail.com 

## Acknowledgments

- Bootstrap team for the UI framework
- Chart.js for visualization capabilities
- Font Awesome for icons
- Contributors and testers

