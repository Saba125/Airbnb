🏡 Airbnb Clone
A full-stack Airbnb clone built using Next.js, Prisma, and MongoDB, providing a full-featured property booking platform.

🚀 Tech Stack
Next.js: Server-side rendering and static site generation.
Prisma ORM: For database management with MongoDB.
MongoDB: Database solution for storing all user, property, and reservation data.
Various libraries to enhance user experience.
✨ Features
User Authentication: Secure login and signup.
Property Listings: Browse, search, and filter properties.
Create Reservations: Book a property for specified dates.
Update Reservations: Modify booking details.
Cancel Reservations: Easily cancel bookings.
Property Management: Hosts can create, update, and delete their listings.
User Reviews: Users can leave reviews after a stay.
Responsive Design: Fully optimized for desktop and mobile devices.
⚙️ Installation
Clone the repository:
git clone https://github.com/yourusername/airbnb-clone.git
Navigate to the project directory:

cd airbnb-clone
Install dependencies:
npm install
Set up the .env file for environment variables, including the Prisma and MongoDB configurations.

Migrate the Prisma schema:


npx prisma migrate dev
Run the development server:

npm run dev
The app should now be running at http://localhost:3000.

🛠️ Usage
Users can sign up or log in to browse available properties.
Hosts can create, edit, and delete their property listings.
Guests can make, update, or cancel reservations, as well as leave reviews after their stay.
🤝 Contributing
Feel free to submit pull requests or open issues for any suggestions or improvements!

