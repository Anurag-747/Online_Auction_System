
# Online Auction System

The Online Auction System is a comprehensive web application designed to facilitate online auctions. This system modernizes the traditional auction process by providing a user-friendly, accessible platform for buying and selling products. It removes geographical, location, and time constraints, enabling users to participate in auctions from anywhere, at any time.


## Features


- **User Registration and Authentication:** Secure registration and login for buyers, sellers, and administrators.
- **Auction Management:** Sellers can list products with detailed descriptions, images, starting prices, and end dates. Buyers can place bids and track auction progress.
- **Administrator Dashboard:** Admins can manage user registrations, monitor auctions, and approve or reject user-submitted auctions.
- **Responsive Design:** Built with HTML, CSS, and Bootstrap to ensure a seamless user experience across devices.
- **Real-Time Updates:** Users can see real-time updates on auction status and bids.




## Technologies Used

- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Backend:** Python, Django
- **Database:** SQLite



## Prerequisites

- Python (version 3.x)
- Django
- SQLite (included with Django)


## Installation

Clone the repository:

```bash
  git clone https://github.com/Anurag-747/Online_Auction_System.git
  ```
Move to the folder:
```bash
 cd Online_Auction_System
```
Create and activate the environment:
```bash
 python -m venv env_name # same for Windows, Mac & Linux

 env_name\Scripts\activate  # For Windows
 source env_name/bin/activate # For Mac/Linux
```
Install the requirements:
```bash
 pip install -r requirements.txt
```
Apply Migrations:
```bash
 python manage.py makemigrations
 python manage.py migrate
```
Create a Superuser:
```bash
 python manage.py createsuperuser #To access the Django admin interface

```
Run the Development Server:
```bash
 python manage.py runserver
```

Access the Application:
  - Open your web browser and go to:
```bash
  http://127.0.0.1:8000/ 
```
- To Access the admin panel:
```bash
  http://127.0.0.1:8000/admin/
```





## Authors

- **[@Anurag Kumar](https://github.com/Anurag-747)**
- **[@Om Chavan](https://github.com/omchavan01/)**
- **[@Atharva Mishra](https://github.com/atharvamishra07)**




## License

[MIT](https://choosealicense.com/licenses/mit/)

