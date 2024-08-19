# CAPSTONE-PROJECT 🏖️
 This repo contains Front-end (zip) & Back-end (zip) of my final project for the EPICODE school.
 
 Hello everyone, my final project is a website that allows the reservation of the limited number beaches of Sardinia (Italy). 
 This is a full-stack project developed all by myself! In the next paragraph I leave you some information how to start my project from your pc👩🏻‍💻
 
 
# Front-end
• Repository = https://github.com/chiarafais/capstoneFE

• To start the front-end, clone the repository and open with VScode (or another editor)

and in the terminal write the command --> npm i

after end install --> npm run dev

and press --> o + enter 

# Back-end 
• Repository = https://github.com/chiarafais/capstoneBE

• For the back-end, clone repository and open with intelliJ (or another editor suitable for back-end)

• Create new file env.properties with environment variables :

 SERVER_PORT
 
 PG_USERNAME
 
 PG_PASSWORD
 
 PG_URL es.jdbc:postgresql://localhost:5432/gestionalespiagge
 
 JWT_SECRET

• Make sure there is this line in the application.properties file --> spring.config.import=file:env.properties

• After doing these steps, you are ready to start CapstoneBeApplication ▶️

# Database 💾
• In this repository there is a CSV file, it contains the list of beaches with their data.
I recommend using PostgreSQL (among other things) makes csv import easy.
After you start back-end :
gestionalespiagge › Schemas › public › Tables › spiagge
on "spiagge" import/export data---> inside the folder "configuration PostgreSQL CSV" you will find screens on how to set up the import.


# Contact 📨
 For any information about the project, curiosity, or to report a bug 🐞 contact me at this email: chiara0915@gmail.com
