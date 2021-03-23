## Capstone Proposal
#### Plant App (still thinking of name)

### Project Overview
Plant App is a social platform for plant collectors to buy, sell, trade, and "purge" plants. The app will feature info on plants and commnuity boards where users can trade or purge plants. Users can also create profiles to post blogs, images and other plant related information. Will primarily use Django and Vue to create this app.

### Functionality
- Provide plant library as user resource.
- Community board to post trades and purges.
- Allow users to sell and purchase.
- Allow user to create personal profiles.

### Data Model
-User
    - Name
    - Profile picture
    - Location
- Blog
  - Date Published
  - Text
  - Image
  - User (ForeignKey to User)
- Community Board 
  - Title
  - Text
  - User (ForeignKey to User)
- For Sale
  - Plant name
  - Price
  - Image
  - Description
  - User (ForeignKey to User)
- Plant Library (Still debating on if I'll add this or not)
  - Plant name
  - Temp requirements
  - Watering
  - Description
  - Humidity
  - Type of Soil
  - Sunlight

### Schedule
#### Week 1
- [ ] Set up Models
  - [ ] User
  - [ ] Blog
  - [ ] Community Board
  - [ ] For Sale
  - [ ] Plant Library
  

#### Week 2
- [ ] Create user signin and login 
- [ ] Get User signup/login functionality working
- [ ] Create blog
- [ ] Create for sale post
- [ ] Create Community Board
- [ ] Create plant library
  - [ ] Plant API properly functioning

#### Week 3
- [ ] Finish styling
- [ ] Make sure everything is functioning properly