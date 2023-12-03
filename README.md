# ArtistConnect Online Art Gallery Documentation 
#### [GitHub Link](https://github.com/Online-Art-Gallery/Documentation)
___


## The problem:

The problem we are aiming to solve with this website is the difficulty for new and experienced artists to gather attention towards their artworks and meet people with a similar or compatible taste in art.

---

## The solution/purpose:

Our idea is for an Online art gallery where artists and art enthusiasts can gather to show off their work, gain some attention towards it, and share their opinions with other like-minded people. This web application will attempt to help talented artists, no matter their circumstances, to get some publicity for their hard work. The site will also serve as a supportive place for new artists to show off their artistic projects and learn, gather inspiration from, and connect with others working in similar mediums. We believe this type of website will also have a number of transferable skills for common web development projects e.g. blogs, portfolio sites, etc.

---

## Functionality/features:

### Artists:

- Can create/delete an account
  - can upload their artworks to be displayed
  - can add a title
  - description/artist-statement
  - genre
  - medium
- Can create/update/delete content related to an artist profile with information about themselves and their practice
- Can view other artists profiles
  - sort by name, categories such as art-genre, medium, etc
- Can view all comments and report inappropriate comments on their own artworks
- Can view/create/update/delete comments they made on others artworks

### Art-lovers:

- Can create/delete an account
- Can view Artwork uploaded by Artists
  - Sort by name, categories such as art-genre, medium, etc
- Can create/update/delete comment on pieces of art
- Can view all comments and report inappropriate comments on pieces of art
- Can view all comments made by themselves

### Admins:

- Can view all login users' artworks or comments
- Can delete artworks not suitable for the website
- Can delete Artist accounts not suitable for the website
- Can delete comments not suitable for the website

---

## Components:

### Onboarding:

- Stylised animation upon opening?
- Sign up
  - Add email account
  - Create username
  - Create password
  - Optional: add profile picture
- Sign in
  - Requires email
  - Requires password
- Select language

### Home page:

- Header
  - Logo
  - Nav link to explore page
  - Link to create account / Profile picture and username link to profile page
- Selection of recommended artworks
  - frequently viewed genres/mediums/artists
- Description/purpose of website
- Footer
  - Mock links to socials

### Explore

- Dropdown selection to refine genre/medium
- Random artworks ^^
  - Artist
    - Genre/medium
  - Comments
    - Button to leave a comment
  - Report button

### Profile page

- Profile picture
- Username
- User bio/description
- User artworks
  - Comments on artworks
  - Artwork activity
  - Gallery
- Settings
  - Update account
  - Delete account

### Components List: 
1. Logo - clickable 
2. Navbar with “explore” button 
3. Button Login
4. Login Form
5. Registration Form to create the account 
6. Carrousel Artworks for home page.
7. Footer with links to social media
8. Upload photo Profile 
9. Setting Account Form
10. Upload Artwork  Button 
11. Upload Artwork Form 
12. Card Artwork uploaded with heart and comments button 
13. Gallery with cards of the artworks 
14. My Artworks button 
15. Favourite Artworks button 
16. Comments component (edit/delete/report  button)
17. Search Bar with dropdown selection of genre/medium

---

## User Persona:

### Experienced Artist

![pic1](./docs/Personas/ExpriencedArtist.png)

### Emerging Artist

![pic1](./docs/Personas/EmergingArtist.png)

### Art Critic

![pic1](./docs/Personas/ArtCritic.png)

### Art Enthusiast

![pic1](./docs/Personas/ArtEnthusiast.png)

### Unintentional Visitor

## ![pic1](./docs/Personas/UnintentionalVisitor.png)

---

## Dataflow Diagram:

## ![dataflow](./docs/Diagrams/DFD.png)

---

## Application Architecture Diagram:

![pic1](./docs/Diagrams/%20ArchitectureDiagram.png)

---

## Wireframes:

### Home Page:
#### Desktop
![homepage](./docs/wireframes/Home%20page%20desktop.png) 
#### Mobile
![homepage](./docs/wireframes/Home%20page%20mobile.png)

### Login Page:
#### Desktop
![loginpage](./docs/wireframes/Login%20page%20desktop.png) 
#### Mobile
![loginpage](./docs/wireframes/Login%20page%20mobile.png)

### Create profile Page:

![createprofilepage](./docs/wireframes/Create%20Profile.png) 

![createprofilepagemobile](./docs/wireframes/Create%20Profile%20mobile.png) 


### Profile Page:

![profilepage](./docs/wireframes/Profile%20Page.png)

### Explore Page:

![explorepage](./docs/wireframes/Explore%20Page.png)

### Setting Page:

![settingpage](./docs/wireframes/Setting%20Page.png)

### Upload Artwork Page:

![uploadartworkpage](./docs/wireframes/Upload%20Artwork%20Page%20.png)

### Artwork Uploaded Page:

![uploadedartworkpage](./docs/wireframes/Artwork%20Uploaded%20Page.png)

### Gallery Page:

![gallerypage](./docs/wireframes/Gallery%20Page.png)

### Comments Page:

![artworkpage](./docs/wireframes/Comments%20Page.png)

### Admin Page:

![adminpage](./docs/wireframes/Admin%20management%20page.png)

### Logo:

![logo](./docs/logo/Logo.png)

### Colour Palette:

![colourPalette](./docs/logo/Colour%20Palette%20.png)

## Tech Stack:

We decided on the MERN tech stack for this project, choosing MongoDB for the database, ExpressJS and NodeJS were selected for the back-end server and the front-end web client is handled by React. The use of MERN stack allows for flexible, non-repetitive and scalable full-stack design.

### Libraries:

- JWT
- Bcrypt
- Dotenv
- Cors

#### Front End:

- HTML
- CSS
- JavaScript
- APIs
- React-router-dom

#### Back End:

- Express
- Mongoose
- MongoDB

---

## Trello Board:

#### [Trello Link](https://trello.com/b/v5aGv47r/online-art-gallery)

![pic1](./docs/trello/Trello%201.png)
![pic1](./docs/trello/inProgress2.png)

![pic1](./docs/trello/inProgress3%20.png)

