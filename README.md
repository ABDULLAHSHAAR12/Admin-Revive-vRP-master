Hello,

I made simple code for vrp for admin can revive with [server id]

>how install 
go to vrp/modules/admin.lua 

like this pic

http://prntscr.com/l9ge4w

http://prntscr.com/l9gev4

and make sure to delete cache file after 

you can download admin.lua and replaced if dosent work you can add the code manual

> how to use 
go to Admin then you will see Admin revive just put server id for the player 

not tested in public servers , use as own your risk

you can edit to use user id instead server id

-- Made by Sul6an for vRP freamwork
-- install on vrp/modules/admin.lua 
-- not tested on public servers , use as own your risk

```
-- Made by Sul6an for vRP freamwork
-- install on vrp/modules/admin.lua 
-- not tested on public servers , use as own your risk
-----------------------------------------------------------------------------------------
		 if vRP.hasPermission(user_id,"admin.tickets") then
          menu["Admin Revive"] = {ch_revive_stn}
        end
-----------------------------------------------------------------------------------------
local function ch_revive_stn(player,choice) -- Admin Revive 
  local user_id = vRP.getUserIdentity(user_id)
  if user_id ~= nil then
    vRP.prompt(player,"Revive:","",function(player,user_id) 
	  	vRPclient.varyHealth(user_id, {100})
    end)
  end
end
		
			
```
https://i.gyazo.com/4cdf36f587da940e14d485ad245be003.mp4


if you have any problem 

DM me on discord : Sul6an#2203

sorry for bad lang.
