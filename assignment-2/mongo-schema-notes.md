
Collections

# Users
 - _id
 - name
 - password-hash
 - email
 - claims
 - tournaments []
 - updated by
 - created by
 - update on
 - created on

# Tournaments
 - _id
 - name
 - sport
 - teams
 - games []
    - _id
    - home team
    - away team
    - score
        - home team score
        - away team score
 - results
 - updated by
 - created by
 - update on
 - created on

# Tournament Picks
 - _id
 - _user
 - _tournament
 - picks
    - _game
    - home team score
    - away team score