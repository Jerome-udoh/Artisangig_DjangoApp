# ArtisanGig

ArtisanGig is a web application that connects customers with artisans, allowing them to view portfolios, chat with artisans, and place orders for services. The application facilitates secure payments and ensures that artisans receive their payment after completing the gig.

## Features

- **Customer Registration**: Customers can sign up for an account by providing their name, phone number, address, and optional profile picture.
- **Artisan Registration**: Artisans can sign up for an account by providing their name, phone number, address, portfolio, and necessary verification documents (e.g., NIM or Driving License).
- **Portfolio Display**: Artisans can upload their work samples and categorize them based on different categories.
- **Direct Chat**: Customers can initiate a chat with artisans directly through the application using WhatsApp.
- **Secure Payments**: Customers can make payments for their orders, and the funds are held until the gig is completed. The payment is then disbursed to the artisan.
- **Order Management**: Customers can view their order history and track the progress of their ongoing gigs.
- **Authentication and Authorization**: The application provides secure authentication for customers and artisans, ensuring only authorized access to the platform.

## Technologies Used

- Django: Python web framework for backend development
- HTML/CSS: Frontend markup and styling
- JavaScript: Used for frontend interactivity and integration with WhatsApp API
- PostgreSQL: Database management system for storing application data
- Paystack: Payment gateway integration for secure and seamless payments

## Installation

1. Clone the repository:
https://github.com/Jerome-udoh/Artisangig_DjangoApp.git

pip install -r requirements.txt

2. Install the required dependencies:


3. Configure the database settings in `settings.py` to connect to your PostgreSQL database.

4. Run database migrations:
python manage.py migrate

5. Start the development server:

python manage.py runserver

6. Access the application in your web browser at `http://localhost:8000`.

## Contributing

We welcome contributions to the ArtisanGig project. If you find any issues or have suggestions for improvements, please submit a pull request or open an issue on the GitHub repository.

## License

The ArtisanGig project is licensed under the [MIT License](LICENSE).

# AUTHOR Jerome Udoh
# Twitter @UdohJerom
# instagram @jeromeudoh
# linkedin https://www.linkedin.com/in/jerome-udoh-072756125
# facebook https://www.facebook.com/jerome.udoh
# Whatsapp https://wa.me/c/2348088221162

