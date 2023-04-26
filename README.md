.booking-form {
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 500px;
  margin: 0 auto;
  padding: 20px;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
}

.booking-form h2 {
  font-size: 24px;
  font-weight: 700;
  margin-bottom: 20px;
}

.booking-form label {
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 5px;
}

.booking-form input[type="text"],
.booking-form input[type="email"],
.booking-form input[type="tel"],
.booking-form input[type="date"],
.booking-form input[type="time"],
.booking-form input[type="number"],
.booking-form textarea {
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
  margin-bottom: 10px;
  font-size: 16px;
  font-family: Arial, sans-serif;
  width: 100%;
}

.booking-form input[type="submit"] {
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  font-size: 18px;
  font-weight: 600;
  cursor: pointer;
}

@media screen and (max-width: 768px) {
  .booking-form {
    max-width: 90%;
  }
}
