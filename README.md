A movie booking app that allow users to book for movie tickets. updates on the db the number of tickets sold and capacity remaining.

Install JSON server:
npm instal -g json-server

Start server:
json-server --watch db.json

GET /films → Fetch movies
PATCH /films/:id → Update tickets
DELETE /films/:id → Remove movie once sold out.

