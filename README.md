local keychecked = false
local hwid = nil
local hwidplr = game:GetService("RbxAnalyticsService"):GetClientId()

if _G.Key == "IHEREMAX" then
    hwid = "EA8541F3-417E-4103-AB61-35059D723515"
    keychecked = true
end

if keychecked == true then
    if hwidplr == hwid then
        print("Script")
    else
        print("incorrect hwid")
    end
else
    print("incorrect")
end
