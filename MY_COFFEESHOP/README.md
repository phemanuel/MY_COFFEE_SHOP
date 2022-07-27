# Created dummy accouts on auth0 with each of the token to expire within 7 days

--User1(coffeshop_manager@gmail.com)-manager
Password : coffmang@2022
# Token( Manager Role)
eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6ImRZWFZ4NW9OTDVyc1lzMFpDRElTbiJ9.eyJpc3MiOiJodHRwczovL2Rldi13M2ZmZXJ2di51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NjJkYjZlOTBhNTU5Zjg2ZTM2NzczMTYwIiwiYXVkIjoiY29mZmVlc2hvcCIsImlhdCI6MTY1ODc3NjY1NSwiZXhwIjoxNjU4NzgzODU1LCJhenAiOiJ1S2pJbHpEZ05EQTNVN2FlQUgwN2VNNkljaXRTTkx4diIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZGVsZXRlOmRyaW5rcyIsImdldDpkcmlua3MiLCJnZXQ6ZHJpbmtzLWRldGFpbCIsInBhdGNoOmRyaW5rcyIsInBvc3Q6ZHJpbmtzIl19.s-OWwOeGGDej8bx21MYFqhJalKYhOq4dSTeQXwl4rXS4exaVSm7TXeUnMUfD8W8GB6_FP-woOn8AE3ILtuSsRsp54tQE59jV-Q3Hv31zxFWG7E7uzjsOve8nCgRrjCr-ShuGNaJeoO3K1BaxFa4Kc7-QgcyLiXGea9lTM1vgFvvybMm4r5sQObc0UyiOqLwnO6Eko6HjLWbqMY8uB1e6fuuvi74TouQ_26JWzXDAjYnnvOsqsMjoVlblKHDBkUYH9_dy9b0F2pZBMMgT7VtPJSHLcCvgbYis5Xb-LNFApVfwjKSBTBpAN2CvICl2UuaHQ5zMaChyRtGGC3lXbNZHUw


---User2(coffeshop_barista@gmail.com)- barista
Password : coffbarr@2022
# Token( Barista Role)
eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6ImRZWFZ4NW9OTDVyc1lzMFpDRElTbiJ9.eyJpc3MiOiJodHRwczovL2Rldi13M2ZmZXJ2di51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NjJkYjZmNDZhNTU5Zjg2ZTM2NzczMTZiIiwiYXVkIjoiY29mZmVlc2hvcCIsImlhdCI6MTY1ODc3NzI0MiwiZXhwIjoxNjU4Nzg0NDQyLCJhenAiOiJ1S2pJbHpEZ05EQTNVN2FlQUgwN2VNNkljaXRTTkx4diIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZ2V0OmRyaW5rcyIsImdldDpkcmlua3MtZGV0YWlsIl19.WYS35L-GGfWV58DiCJ0aKPVQSDLIhTZDTEzy1EBK6SsSVV5ZahJa5411w5ss5RJgD3R9NqsfhRBLX_avHgMK5CA8jzzOwrk_EMEWvCPcnGvX9NSsRBwxG8U8D10wNlbZkCNJBdrJ7P57aYNGCVXGM5D1a2LVojneJ6H-MQwfzYzW0sgu1I-ypwQFJDDPBruJyeRVJ0hBHaDyZ8YzsDnbEdFAiRrcBcruR5X9Ed2tyjRUfiUPonQDuzgiM1JjriP0lgOhhSHWYPl9C0gBjvK4QdD3BOI9hfBpoHLxZttZrXFHFbfYFU0SIn_pbosr_GSJO7h9cIgxiV_3_h5CoRTxIg
# --------------------------------------------------------------------------------------------------------

# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.

You have been called on to demonstrate your newly learned skills to create a full stack drink menu application. The application must:

1. Display graphics representing the ratios of ingredients in each drink.
2. Allow public users to view drink names and graphics.
3. Allow the shop baristas to see the recipe information.
4. Allow the shop managers to create new drinks and edit existing drinks.

## Tasks

There are `@TODO` comments throughout the project. We recommend tackling the sections in order. Start by reading the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

We started the full stack application for you. It is designed with some key functional areas:

### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app.

[View the README.md within ./frontend for more details.](./frontend/README.md)
