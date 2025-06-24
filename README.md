# DealSPY

An AI-powered e-commerce product-scraping platform that automatically pulls product details from Amazon, tracks price and sends alert emails to subscribed users.

---

## ⚙️ Tech Stack

- **Frontend**: Next.js, Tailwind CSS, Headless UI  
- **Scraping**: Bright Data (formerly Luminati), Cheerio  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Email**: Nodemailer  
- **Task Scheduling**: Node Cron

---

## 🔋 Features

- **Header with Carousel**  
  Visually appealing hero section showcasing key benefits.  
- **Product Scraping**  
  Users paste an Amazon product URL into a search bar to begin scraping.  
- **Scraped Products Dashboard**  
  Displays a list of all scraped items with thumbnail, title, price, and more.  
- **Product Details View**  
  Detailed view of each item: image, title, current price, description, and metadata.  
- **Track Option**  
  Modal where users enter their email to subscribe to price and stock alerts.  
- **Email Notifications**  
  Automated alerts for back-in-stock or lowest-price triggers.  
- **Automated Cron Jobs**  
  Scheduled scraping tasks to keep product data fresh (e.g. every hour).  
- **Modular Code Architecture**  
  Clean service-controller-router pattern with reusable utilities and middlewares.

---

##  Setting Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

-BRIGHT_DATA_USERNAME=
-BRIGHT_DATA_PASSWORD=
-MONGODB_URI=
-EMAIL_USER=
-EMAIL_PASS=

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these specific websites from BrightData, MongoDB, and Node Mailer
