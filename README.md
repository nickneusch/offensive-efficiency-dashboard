# offensive-efficiency-dashboard

I developed an interactive dashboard for the Duquesne University Basketball coaching staff to analyze their offensive possessions. Analytics are focused on paint touches, post touches, and shooting efficiency on different spots of the court.

<img width="1004" alt="Screenshot 2025-02-20 at 4 49 19 PM" src="https://github.com/user-attachments/assets/8a64b9fd-d2d8-4526-9923-55ade4b7f037" />

(View interactive dashboard attached below)

## Motivation

My friend, Taylor, owns a sports cards business. Within his business, he submits cards for grading to PSA (Professional Sports Authenticator). Each card is graded on a scale from 1-10, depending on the quality of four main categories: centering, corners, edges, and surface condition. A higher numerical grade indicates a more prestine card. Thus, cards that receive higher grades are worth exponentially more than their raw (ungraded) value, however, cards that receive a low grade can decrease the value of the card. Additionally, there is a ~$20 fee to grade each card. Therefore, it is important to be selective when deciding which cards to submit. I created this dashboard to help Taylor use analytics to help guide his decision-making.

## Workflow
1. Download the data for each submission from PSA. A submission is a group of cards submitted in the same order.
2. Clean the data with a python script. Taylor allows other people to submit their cards in his orders. Therefore, the data was only used from his cards.
3. Process the data with a python script. The data downloaded from PSA lists the card description, but does not distinguish its qualities seperately (ex. 2020 PANINI SELECT 61 JUSTIN JEFFERSON DIE-CUT PURPLE PRIZM). The description was parsed to extract the year, brand, card number, variation/parallel, and player name.
4. Import the data into Tableau to create an interactive dashboard. Analytics were focused on the "gem rate" (percentage of cards that graded as a "gem") because these are the most profitable cards. Data was analyzed by gem rate vs. order number, brands, parallels, sports, and players. Filters were added to introduce new perspectives of the data. Filters include order number, brand, year, parallel, and player name.

##

### View on Tableau Public

View the dashboard on Tableau Public (For Desktop-view only):
https://public.tableau.com/app/profile/nicholas.neuschwander/viz/Tay_CollectsPSADashboard/Dashboard3

##

Created in July 2024
