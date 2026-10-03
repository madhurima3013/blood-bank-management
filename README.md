# Blood Bank Management System
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Ravi%20Shyam%20Singh-red)

An end-to-end Django application that helps organisations digitise their blood bank processes. It centralises donor, patient, inventory, and request management so administrators can keep stock levels accurate and respond to demand quickly.

---

## Table of Contents
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available User Roles](#available-user-roles)
- [Screenshots](#screenshots)
- [Feedback](#feedback)

---

## Key Features
- Real-time blood inventory dashboard segmented by blood group.
- Approval workflows for blood donation and request submissions.
- Comprehensive donor and patient profiles with update and archive capabilities.
- Automated stock adjustments after each approved donation or request.
- Historical audit of all requests for compliance and reporting.
- Responsive UI designed for quick navigation across administrator, donor, and patient portals.

## Technology Stack
- Python 3.7+
- Django 3.x
- SQLite (default) or any Django-compatible relational database
- HTML5, CSS3, Bootstrap, and Select2 for rich forms and UI components

---

## Getting Started
1. **Clone the repository**
	```bash
	git clone https://github.com/Ravishyamsingh/Online-blood-donation.git
	cd Online-blood-donation
	```
2. **Create and activate a virtual environment (recommended)**
	```bash
	python -m venv venv
	venv\Scripts\activate
	```
3. **Install dependencies**
	```bash
	python -m pip install --upgrade pip
	python -m pip install -r requirements.txt
	```
4. **Run database migrations**
	```bash
	py manage.py makemigrations
	py manage.py migrate
	```
5. **Create an administrator account**
	```bash
	py manage.py createsuperuser
	```
6. **Start the development server**
	```bash
	py manage.py runserver
	```
7. Visit `http://127.0.0.1:8000/` in your browser to explore the application.

---

## Available User Roles

### Administrator
- Inspect overall inventory, donor count, pending requests, and aggregate stock units via the dashboard.
- Approve or reject donation submissions after reviewing donor health declarations.
- Approve or reject blood requests submitted by donors or patients, with automatic stock updates.
- Edit or archive donor and patient profiles and manage individual blood group stock levels.
- Access a detailed history of all fulfilled and rejected requests for auditing.

### Donor
- Register with essential contact and health information.
- Submit blood donation requests and track approval status (Pending, Approved, Rejected).
- Request blood units when needed and follow the status of each request.
- Monitor dashboard summaries of donations and requests across all statuses.

### Patient
- Self-register and log in without administrator approval.
- Raise blood requests specifying blood group and units required.
- Monitor request status history (Pending, Approved, Rejected) and dashboard metrics.

---

## Screenshots
| Module | Preview |
| --- | --- |
| Homepage | ![Homepage](https://raw.githubusercontent.com/Ravishyamsingh/Online-blood-donation/main/static/screenshot/homepage.png) |
| Admin Dashboard | ![Admin Dashboard](https://raw.githubusercontent.com/Ravishyamsingh/Online-blood-donation/main/static/screenshot/admindashboard.png) |
| Blood Donation Workflow | ![Blood Donation](https://raw.githubusercontent.com/Ravishyamsingh/Online-blood-donation/main/static/screenshot/blooddonation.png) |
| Blood Request Workflow | ![Blood Request](https://raw.githubusercontent.com/Ravishyamsingh/Online-blood-donation/main/static/screenshot/bloodrequest.png) |
| Secure Logout | ![Logout](https://raw.githubusercontent.com/Ravishyamsingh/Online-blood-donation/main/static/screenshot/logout.png) |

---

## Feedback
I am continuously improving this project and would love to hear from you. Feel free to reach out with suggestions, bug reports, or collaboration ideas:

- Email: [rshyamsingh106@gmail.com](mailto:rshyamsingh106@gmail.com)
- LinkedIn: [Ravi Shyam Singh](https://www.linkedin.com/in/ravishyamsingh/)

Thank you for supporting the Blood Bank Management System project.
