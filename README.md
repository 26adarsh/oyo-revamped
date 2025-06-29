# 🏨 OYO-REVAMPED Django Project

A feature-rich hotel booking platform inspired by OYO, offering users a seamless and secure experience to discover, book, and manage hotel accommodations. Built using Django, this application integrates modern web technologies and robust backend services to deliver a scalable solution for travelers.

---

## ✨ Key Features

### 🔐 User Authentication  
- Secure user registration and login system  
- OTP-based email verification for enhanced security  
- Session-based authentication with profile management support

### 🏨 Hotel Listings  
- Display a curated list of hotels with complete details:
  - Name, location, images, pricing, room types, and available amenities  
- Filter and search options based on:
  - City, price range, star rating, room type, availability, and more

### 📅 Booking Management  
- Book rooms with flexible date selection  
- View room availability, hotel policies, and room features before confirming  
- View and manage your upcoming and past bookings

### 📩 Confirmation & Notifications  
- Automated booking confirmation via email and/or SMS  
- Notifications for:
  - Booking status updates, cancellations, check-in reminders, and offers

---

## 🖥️ Technology Stack

### Backend  
- Django 4.2.17  
- Python 3.13.1  
- Django REST Framework (DRF)  
- PostgreSQL  
- Redis *(optional for session or caching)*

### Frontend  
- HTML5 / CSS3  
- Bootstrap 5.3.2  

### Infrastructure  
- Docker & Docker Compose *(for isolated deployment)*

---

## 📦 Requirements

All Python dependencies are listed in the `requirements.txt` file. Key packages include:

- `Django`, `django-allauth`, `django-otp`, `django-crispy-forms`  
- `psycopg2-binary`  
- `django-cors-headers`, `python-decouple` , `Pillow`

---



## 💡 Future Enhancements

- 🛠️ **Admin Dashboard** for hotel and room management  
- 🌐 **Third-Party API Integration** (e.g., Expedia, Booking.com) for wider hotel options  
- 📊 **Dynamic Pricing & Availability** based on demand and location  
- 🌟 **User Reviews & Ratings** to build trust and improve hotel listings  
- 🗺️ **Map Integration** using Google Maps or Leaflet for hotel location view  
- 🌎 **Multilingual & Currency Support** for global users  
- 🎟️ **Coupon & Discount System** to attract users with deals  
- 💳 **Advanced Payment Integration** with real gateways (Stripe, Razorpay) and refund handling

## 🤝 Contributing

1. Fork the repository  
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)  
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)  
4. Push to the branch (`git push origin feature/AmazingFeature`)  
5. Open a Pull Request






## 📄 License
This project is licensed under the MIT License - see the license file for details.