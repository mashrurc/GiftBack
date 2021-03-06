## GiftBack

**Visit the https://giftback.me/ to get started!**

## Inspiration
It is the holiday season, a time of gift-giving. In the age of COVID-19, much of this is done online. Yet, it is important to remember those less fortunate than we are. We've all personally known those who haven't had the luxury we take for granted of having the means to have a complete Christmas with proper gifts and all. 

However, donating is often inconvenient and burdensome. It is hard to know who to donate to, making sure to consistently give is taxing. There are often subconscious barriers to giving, but automating the process allows you to not second guess your acts of kindness. As a first of its kind, we decided to make a convenient Chrome extension to solve these problems and overcome the subconscious barriers that come coupled with regular donations that so often go overlooked.  **_Give back with GiftBack_**.

## What it does
GiftBack _automatically_ raises the price of items on online retailers by your specified donation rate, and the excess money, which you already believe is gone, is instead donated to a cause of your choice, from our trusted list of vetted and ethical Canadian charities.

The GiftBack Chrome extension relays your current donation balance, your lifetime donations, and gives quick links to monitor your goals and donate with one press. You can also change the donation amount for that particular purchase with one click. Behind the scenes, the extension modifies the price of all items on the retailer so that you make your purchases with the post-donation price in mind. You can always hover over any price to determine how much the original price is, and what amount of it you are giving back to others, with a _custom CSS injected widget_.

Yet, GiftBack is more than just a Chrome extension, it is also a web application where you can monitor your donations through graphs and statistics, maintain a ledger of your donations for tax rebate purposes, and change your default charity and donation rate permanently. Our landing page explains the features and GiftBack's quick 5-minute installation and setup process.

## How we built it
Our front-end landing page was developed in **HTML/CSS** using **Bootstrap** to make an innovative and easy-to-access UI/UX experience. We then moved onto the actual Chrome extension, keeping a steady design process, designed first in **Figma**, and then implementing our design using HTML/CSS/JavaScript and Bootstrap. We used **JavaScript** to track and change prices and injected CSS for the hovering features, and to inform the user of how much they are donating upon purchasing. First, we set up what we wanted to do with one example. We then implemented a user signup/login and created a dashboard to display stats. We then went back to our Chrome extension and generalized it across any unique user. After adding security features, including abilities to reset and change passwords, and the ability to change one's default charity (compiled from a list of trusted Canadian organizations) and the default donation amount (either a percentage or a flat rate), we felt confident that we had a finished product. 

## Challenges we ran into
The main challenge was getting the pop-up system to display correctly on websites such as Amazon where it would interfere with surrounding HTML tags, we got around the problem by _injecting_ our own HTML code and Javascript into the header of the websites we entered in order to make everything fit together correctly. As well, we had trouble integrating aspects of a user's information into the Chrome extension, as we had to update a user's donation balance live as they made purchases. This was all of our first time making a Chrome Extension, something we had all wanted to do at one point, but simply did not have the creativity to do so. We're glad HolidayHacks was the perfect environment to explore the world of Chrome Extensions.

## Accomplishments that we're proud of
We are most proud of the backend changes and style injections we make to websites with our chrome extension in order to provide users with the modified process. We find that it makes the experience of using our extension a lot more pleasing and robust! We are proud of the landing page, which easily teaches users about GiftBack and provides an accessible platform to download the application and complete the onboarding process. Further, seeing as this was a learning experience for us all, we can all happily say we learned some valuable skills, and much of what we did today will be valuable for future projects.

## What we learned
We learned how to fully integrate a custom CSS widget in a professional development manner, and have gained extensive experience in the process of developing a Chrome extension. Moreover, we learned about the importance of UI in creating a seamless experience. But we didn't just take away technical skills - we also learned the importance of patience and perseverance, and how to maintain a team chemistry. By combining our strengths, we were able to accomplish something greater than ourselves. We developed valuable communication and interpersonal skills that will prove useful in any facet of life. 

## What's next for GiftBack
Our request to put GiftBack on the Chrome Web Store is currently pending and is something we highly look forward to. This will allow even more users to give back to their communities. 

Currently, we have support for vetted Canadian charities, many of which are holiday-oriented, but going forward, we plan on adding support for more international charities that have broader goals. As well, we plan to partner with a few select local charities and implement a **Stripe** payment to allow for even more easy giving. Then, once a user securely loads his credit information, his donations will be automatically given to the charity of their choice upon any online purchases. This will take GiftBack to new heights and further streamline the platform to make donations easier than ever before.
