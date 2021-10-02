Structure

/api/users
/api/login - return token - will be stored in frontend through state
/api/vlog
/api/vlog&tag=<tag name>

Routes 

get user - /api/users/:userId/profile 
get account - /api/users/:userId/account - GET
download - /api/users/:userId/account - POST
get all vlog - /api/users/:userId/vog - GET
get single vlog - /api/users/:userId/vlog/:vlogId - GET
create a vlog - /api/users/:userID/vlog - POST
