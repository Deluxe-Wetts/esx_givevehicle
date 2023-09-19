# esx_givevehicle

# Requirements:
es_extended
esx_vehicleshop

# Installation
Put in the server.cfg 
ensure esx_givevehicle and ready

# Commands:
In game: (give permission in config)

Give a car to the target player: /givecar [playerID] [vehicle] <plate>
Give a plane to the target player: /giveplane [playerID] [vehicle] <plate>
Give a boat to the target player: /giveboat [playerID] [vehicle] <plate>
Give a helicopter to the target player: /giveheli [playerID] [vehicle] <plate>
Note: If plate is none will randomly generate a new plate

Delete a owned car by plate: /delcarplate [plate]

On console: (prefix need change to "_")

_givecar [playerID] [car] <plate>
_giveplane [playerID] [car] <plate>
_giveboat [playerID] [car] <plate>
_giveheli [playerID] [car] <plate>
_delcarplate [plate]

# Config:

Config = {}
Config.Locale = 'en'

Config.ReceiveMsg = true

-- Allow below identifier player to execute commands
Config.AuthorizedRanks = {
  'superadmin',
--  'admin'
}
