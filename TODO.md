### TODO
* [X] Subscribe to an auction (without payement)
  * [X] (app ) create a protected page subscribe.
  * [X] (app ) protecte the route if the user is subscribed.
  * [X] (db ) create a table auction_user.
  * [X] (api) create route /auctions/subscribe.

* [X] Manage Jobs - create auction, init when server (re)start
  * [-] Jobs - when **update** / delete / create new auction

*  [X] (app) Display a message when no auction is available
*  [-] (app+bak) strategy for expired token.
*  [X] (app+api) display expired auctions
*  [-] (app) Profil
*  [*] When an auction room end
    * [-] edit auctions.is_finished
    * [-] [proposal] maybe add the last bider user_id to the auctions
    * [-] Update the jobs.state_id = 4 (off:finished)
*  [-] Phone input mask

* [ ] Catch error authentication
* [ ] Phone mask when register (XX XXX XXX)
* [X] On /auctions/subscribe we have an extra call to the localhost:5000/undefined
* [X] Form submit with key press enter.
* [ ] JWT expires redirections
* [ ] Animation sur le lient Ventes en cours si il y a des ventes en cours :p
* [ ] (api) refactor all queries to better solution
### REFACTORING API AND SWAGGER
1. AUTH
  [X] API
  [X] SWAGGER
  [X] Backend
2. USERS
  [ ] API
  [ ] SWAGGER
  [ ] Backend
3. PRODUCTS
  [ ] API
  [ ] SWAGGER
  [ ] Backend
4. AUCTIONS
  [ ] API
  [ ] SWAGGER
  [ ] Backend
5. Client
