## Use with these parameters :

#### Obligatory parameters :


msg.params.service "notify.mobile_app_phone_sam"

msg.params.titre = "Notification Title"

msg.params.message = "Message de la notification"


#### Optional parameters :

msg.params.image = "/api/camera_proxy/camera.camera_garage"

msg.params.action.oui = "Oui"

msg.params.action.non = "Non" (You can personalise and add)


msg.params.timeout = 1800 (default value) (in seconde)

msg.params.ttl = 0 (default value)

msg.params.priority = "high" (default value)


### Output :

If timeout, the output payload is "timeout".

If it's a notification, payload is "done".

Else, it's the choice data.

