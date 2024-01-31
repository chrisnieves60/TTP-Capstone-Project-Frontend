## NOTE: 
This web app relies on backend servers hosted on Supabase. If you encounter any issues with the website, please be aware that it may not work as expected if Supabase servers are paused. 

# GGC (Goat Grade Collectibles)
Goat Grade Collectibles (GGC) is a dynamic web application that offers an exciting alternative to traditional gambling. Built with technologies like PostgreSQL, Express, React, and Node.js, this platform lets users experience the thrill of opening trading card packs without the risks associated with gambling. Whether you're a sports fan or just love collectibles, GGC brings a safe and engaging way to test your luck and collect cards of your favorite players.


## Getting Started
To run the program, download and install a few packages:
```
npm install react-bootstrap bootstrap@5.1.3
npm install -D sass
npm install aos --save
npm install redux react-redux redux-devtools-extension redux-thunk
```

## Live Demo
Experience GGC live at [Goat Grade Collectibles ](ggc-numahn.vercel.app/)

## Project Journey
Developed over a week for a full-stack web development bootcamp, GGC was a collaborative effort between four students, including me. Our goal was to recreate the excitement of in-game gambling experiences found in NBA2K, but in a risk-free environment. We believe this is a crucial step toward addressing the problematic issue of gambling in video games, especially for younger audiences.

Although we have many ideas for this project, this is what we had for the allotted time that was given for us to complete the project. Some other ideas we have are: 
* **Earning Currency:** Introduce ways to earn currency, like daily logins.
* **Team Building:** Allow users to create teams with their collected cards, similar to the myTEAM feature in NBA2K.
* **Expanding Collections:** Add more card packs and expand our database to enhance the collecting experience.

### Challenges and Solutions

#### 1. Associating Cards with User Accounts
**Challenge:** We initially struggled with managing the relationship between trading cards and user accounts, particularly understanding and implementing foreign keys in a PostgreSQL database with a React frontend. 

**Solution:** Our approach was to break this complex problem into smaller, more manageable tasks. Through collaborative debugging sessions and extensive research, we progressively refined our understanding of database associations. This effort culminated in a robust implementation that seamlessly ties users' card collections to their accounts.

#### 2. Implementing Redux for Cross-Page Currency Display
**Challenge:** Managing and displaying the user's currency consistently across different components and pages posed a significant technical hurdle.

**Solution:** To overcome this, we integrated React Redux into our application. It was a journey marked by a steep learning curve, but through progressive learning and application of Redux's state management capabilities, we developed a fluid and responsive currency display system, significantly enhancing user interaction and experience.

## How It Works

We first created the database ourselves for the cards we wanted. Since we did not have a lot of time, we decided to make 30 entries, 10 for each pack. Once the database was running, we created packs and added animations to the card opening to add a gambling feel to it. This would then save the cards you earned.

![Navbar Before](https://raw.githubusercontent.com/nali556/NBAGatchaFrontend/main/images/NavbarBefore.png)
In order to open packs and for them to save, you must first create an account. Before that, the navbar at the top of the site will ask you to either signup or login.

![Navbar After](https://raw.githubusercontent.com/nali556/NBAGatchaFrontend/main/images/NavbarAfter.png)
 Once the website displays your username and currency instead of login, you can open some packs! Simply click on the pack you would like to open, buy the pack, and see the card that you got pop up! When you open a card, you can see the players stats by hovering over the card, and also see all the cards that are in that pack. You can then see the cards you've earned in your collections page, which will have only the cards you have on that specific account. 

 ![Pack Page](https://raw.githubusercontent.com/nali556/NBAGatchaFrontend/main/images/CardPage.png)
 The page before you open cards, displaying the cards that are available

 ![Card Display](https://raw.githubusercontent.com/nali556/NBAGatchaFrontend/main/images/CardDisplay.png)
 The page after buying packs, the front displaying the image, the back displaying the stats of the players

 ![Collections Page](https://raw.githubusercontent.com/nali556/NBAGatchaFrontend/main/images/CollectionPage.png)
 The collections page, which only displays the cards the user that is logged in has. It also displays all the stats of the players, unlike the pack pages, which only display the overall stat of the player.

 Want to try it out? Check out the Netlify link!

## Built Using
* PostgreSQL
* Express
* React
* Node
* and other React Libraries!

