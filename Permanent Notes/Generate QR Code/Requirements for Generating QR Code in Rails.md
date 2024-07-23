#Requirements for Generating QR Code in Rails
Created: 2024-07-04 20:27

##References
1. Install gems/libraries needed for this and for that we have the rqrcode gem nad the mini_magick gem
2. connect the app to the test database
3. create your model
4. create your routes and controller files
5. write your association with the qr code i.e "has_one_attached :qrcode" on the model
6. create a services folder
7. create a fetch_service.rb file that will fetch the agent data from the api and persist it in the db
8. confirm if the data already exists before persisting.
9. write function for generating qr code and appending the id of the agent to it.
10. always generate new qr codes on each instance 
11. we will be using the data from the api to generate the qr codes and not the database.
12. make the qr code mobile responsive.
