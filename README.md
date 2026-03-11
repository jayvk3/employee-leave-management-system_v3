# Employee Leave Management System (ELMS) - V3

A simple, interactive web application for managing employee leave requests. Built with vanilla HTML, CSS, and JavaScript with a hardcoded database for easy demonstration.

## Features

- ✅ **Two User Roles**: Employee and Manager
- ✅ **30-Day Leave Quota**: 15 Vacation + 10 Sick + 5 Casual
- ✅ **Employee Dashboard**: View leave balance, submit requests, cancel pending requests
- ✅ **Manager Dashboard**: View team requests, approve/reject with reasons
- ✅ **Hardcoded Database**: No server or database required
- ✅ **Responsive Design**: Works on desktop and mobile devices
- ✅ **Interactive UI**: Modern, clean, and user-friendly interface

## Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Architecture**: Single Page Application (SPA)
- **Data Server**: In-memory JavaScript objects (no persistence)
- **Dependencies**: None (zero external libraries)

## Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)

### Installation & Run

1. **Option 1: Open Directly**
   ```bash
   # Clone the repository
   git clone https://github.com/jayvk3/employee-leave-management-system_v3.git
   
   # Navigate to the directory
   cd employee-leave-management-system_v3
   
   # Open index.html in your browser (double-click or open with browser)
   ```

2. **Option 2: Use Local Server (Recommended)**
   ```bash
   # Using Python
   python3 -m http.server 8080
   
   # OR using Node.js
   npx http-server -p 8080
   
   # Then open in browser: http://localhost:8080
   ```

## Demo Credentials

### Managers

| Username | Password | Department |
|------------|----------|-------------|
| alice.manager | pass123 | Engineering |
| bob.manager | pass123 | Marketing |

### Employees

| Username | Password | Department |
|------------|----------|-------------|
| john.doe | pass123 | Engineering |
| jane.smith | pass123 | Engineering |
| mike.johnson | pass123 | Marketing |
| sarah.taylor | pass123 | Marketing |

## User Roles & Functionality

### Employee Features

- **View Dashboard**: See total, used, and available leaves
- **Request Leave**: Submit new leave requests with: 
  - Leave type (Vacation, Sick, Casual)
  - Start and end dates
  - Reason for leave
- **View Request Status**: Track pending, approved, rejected, and cancelled requests
- **Cancel Requests**: Cancel pending leave requests
- **View Rejection Reasons**: See why a leave was rejected

### Manager Features

- **View Dashboard**: See summary of pending, approved, and rejected requests
- **View Team Requests**: See all leave requests from their department
- **Approve Leaves**: Approve pending leave requests
- **Reject Leaves**: Reject requests with a reason (required)
- **Department Filtering**: Only see requests from their own department

## Leave Policy

### Leave Types & Quotas

| Leave Type | Max Days per Year | Description |
|-------------|--------------------|---------------------------------------|
| Vacation | 15 | Planned holidays, family trips |
| Sick | 10 | Illness, medical appointments |
| Casual | 5 | Unexpected events, emergencies |
| **Total** | **10** | |

### Leave Statuses

- **Pending**: Request submitted, awaiting manager approval
- **Approved**: Manager approved the request
- **Rejected**: Manager rejected the request (leave balance restored)
- **Cancelled**: Employee cancelled the request (leave balance restored)

## Project Structure

```text
employee-leave-management-system_v3/
├── index.html               # Main application file (HTML + CSS + JS)
├── README.md                 # Project documentation
└── LICENSE                   # MIT License (optional)
```

## Browser Compatibility

| Browser | Minimum Version | Supported |
|-----------|-----------------|-----------|
| Chrome | 60+ | ✅ |
| Firefox | 55+ | ✅ |
| Safari | 11+ | ✅ |
| Edge | 79+ | ✅ |
| Opera | 50+ | ✅ |

## Known Limitations

- **No Persistence**: Data resets on page refresh
- **No Authentication**: Simple username/password check (no tokens)
- **No Server**: Entirely client-side application
- **Hardcoded Data**: Users and data are pre-defined in code
- **No Email Notifications**: No actual emails/alerts sent
- **No File Uploads**: Cannot attach documents to leave requests

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open-source and available under the MIT License.

## Contact

- **GitHub**: [https://github.com/jayvk3/employee-leave-management-system_v3](https://github.com/jayvk3/employee-leave-management-system_v3)
- **Issues**: [https://github.com/jayvk3/employee-leave-management-system_v3/issues](https://github.com/jayvk3/employee-leave-management-system_v3/issues)

## Acknowledgments

- Built as a demonstration project for Employee Leave Management System (ELMS)
- Requirements defined in Confluence space: ELMS
- Technical design based on specified requirements
- Jira tracking: EPMCDMETST

---

**Note**: This is a demonstration project for educational/portfolio purposes. Not intended for production use without proper backend, security, and database implementation.

Made with ❤️ by [jayvk3](https://github.com/jayvk3)