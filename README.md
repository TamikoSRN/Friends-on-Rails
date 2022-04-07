# README: PLEASE, READ THIS BEFORE TRYING TO RUN THE APP!

# Installation instructions: (otherwise it won't run!) (please, make sure your Ruby version it's the 3.0.3)

Once you have the repository cloned in your PC, please, open your terminal inside the repository folder and run the following command:
## bundle install
to make sure all Gems will be in order.

-----

Once the bundle is installed, please run in your terminal the following command:
## bin/rails db:migrate RAILS_ENV=test
this will migrate the app's Database and will avoid an error at the moment of trying to run the app!

-----

As a final step, inside the repository folder (Friends-on-Rails), create ANOTHER folder called
## Friends
and move *ALL* the archives inside it.
It should end like this: 
### Friends-on-Rails/Friends/{all the folders/archives goes here}


I truly apologize for that last folder step, I was having tons of troubles with Github if I uploaded this repository inside the Friends folder and I couldn't find a better solution than doing it manually after realizing it was breaking it all due to the way the routes were created.
Thank you a lot for reading, I hope you enjoy my app!
