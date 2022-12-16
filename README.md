hargapack = 12500
namapack = "crackers"
MinItemPack = 50
maxbuy = 3
iditempack = {242, 5402}

targetinfo = 1
TilePNB = 3
InfoLoop = true
TakePickaxe = false

if getPing() < 70 then
	delayht = 75 -- DELAY HARVEST
    delayplant = 50 -- DELAY PLANT
    delaypnb = 165 -- DELAY PNB
    delayplace = 115 -- DELAY PLACE
    delayworld = 3000 -- DELAY MASUK DOOR
    delaydrop = 300 -- JEDA DROP PER ITEM
else
    delayht = 100 -- DELAY HARVEST
    delayplant = 75 -- DELAY PLANT
    delaypnb = 185 -- DELAY PNB
    delayplace = 125 -- DELAY PLACE
    delayworld = 6000 -- DELAY MASUK DOOR
    delaydrop = 1000 -- JEDA DROP PER ITEM
end
