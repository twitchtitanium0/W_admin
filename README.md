# W_admin
W_amdin menu admin creer par Wuram Discord : Wuram-Mickael#4443


IMPORTANT !!!!!!!

mettre ceci coté client dans funtions.lua de votre es_exdented :

ESX.DrawMissionText = function(msg, time)
    ClearPrints()
    BeginTextCommandPrint('STRING')
    AddTextComponentSubstringPlayerName(msg)
    EndTextCommandPrint(time, true)
end
