# message-notif-for-fivem
message notif for fivem


es_extended/client/functions.lua

function ESX.ShowNotification(msg, couleurProgress)
    exports.kosmos_notif:Send(msg, couleurProgress)
end

function ESX.ShowAdvancedNotification(title, subject, msg, couleurProgress, banner, timeout, icon)
    exports.kosmos_notif:SendAdvanced(msg, subject, title, couleurProgress, banner, nil, nil, true, nil, icon)
end
