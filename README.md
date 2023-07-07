# Warbler

## A social media app for birds to chirp their thoughts.

### Technologies Used

- Python
- Flask
- Jinja
- PostgreSQL
- SQLAlchemy
- WTForms
- Bcrypt
- Bootstrap
- HTML
- CSS

### Features

- Users can create an account and log in
- Users can edit their profile (including changing their profile picture)
- Users can write posts (called "warbles")
- Users can like warbles
- Users can follow other users
- Users can see the warbles of users they follow (called "following")
- Users can see who is following them
- Users can see their own warbles and their following warbles on their homepage
- Users can delete their own warbles
- Users can like and unlike warbles
- Users can see a list of all warblers
- Users can see a list of warbles that they have liked
- Users can see a list of warbles that they have posted

### Getting Started

1. Clone this repository (only this branch)

   ```bash
   git clone
   ```

2. Create a virtual environment

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies

   ```bash
    pip install -r requirements.txt
   ```

4. Create database

   ```bash
    createdb warbler
   ```

5. Seed database

   ```bash
    python seed.py
   ```

6. Run the app

   ```bash
    flask run
   ```

7. Go to localhost:5000 to view the app