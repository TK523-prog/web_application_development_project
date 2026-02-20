# Mediquick project

MediQuick is a modern Django-based healthcare application that allows users to explore medicines based upon what type of medicine they are looking for but also based on their symptoms that they are experiencing.

The core features of the application are search & browse, user management, and the contact system. 

Search & Browse:
- Search by name or symptom (dynamically filters medicines using query
type).
- Alphabetical filter (quick letter-based navigation of medicines).
- Detailed views (medicine pages include usage, ingredients, side effects, availability, symptoms, and price).

User Management:
- Sign up / login / logout (custom registration with health status).
- User profiles (views, edit, and update personal info and health status).
- Password change view (built-in, styled password update page).

Contact system:
- Contact form (submits title, message, and email).
- Email integration (sends submissions to admin email).
- Stored contact submissions (saved to the database for reference).

### Run locally

<pre> python manage.py run </pre>
