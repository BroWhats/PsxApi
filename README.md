# Initialization
**! Forgeting this step will result in your script not working !**
```
-- At the top of your script, add this
local CelestialScript = loadstring(game:HttpGet("https://raw.githubusercontent.com/MrGalaxy10/Psx/main/Api.lua",true))()
```

## Documentation

**Teleport functions**
```
-- Teleports user to bank
CelestialScript.TpToBank()
-- Teleports use to mailbox
CelestialScript.TpToMailbox()
```
**General/Main functions**
```
-- Returns the amount of diamonds the user has
CelestialScript.GetDiamonds()
-- Returns the pets the player has (table)
CelestialScript.GetPets()
-- Unlocks all of the user's pets
CelestialScript.UnlockAll()
-- Locks all of the user's pets
CelestialScript.LockAll()
-- Unlocks a specific pet
CelestialScript.UnlockPet(<PetId>)
-- Locks a specific pet
CelestialScript.LockPet(<PetId>)
```
**Bank functions**
```
-- Returns the banks the user is in
CelestialScript.GetMyBanks()
-- Returns the bank data of a specific bank
CelestialScript.GetBank(<BankId>)
-- Kicks a member from a bank
CelestialScript.KickMember(<BankId>, <PlayerId>)
-- Invites a member to a bank
CelestialScript.InviteToBank(<BankId>, <PlayerId>)
-- Cancels all outgoing invites
CelestialScript.CancelOutgoing()
-- Deposits pets to a bank
CelestialScript.DepositPets(<BankId>, <PetId List>, <Diamond Amount>)
-- Withdraws pets from a bank
CelestialScript.WithdrawPets(<BankId>, <PetId List>, <Diamond Amount>)
```
**Mailbox functions**
```
-- Sends mail to a user
CelestialScript.SendMail(<Receiver>, <Diamond Amount>, <PetId>, <Message>)
```
