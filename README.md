# BCS Notify
A notification system script for any type of server.

# Preview
![image](https://user-images.githubusercontent.com/116667373/228020974-26af86dd-7cea-4e67-a8b2-87f47c54f69e.png)

# Installation
- [FiveM Forum](https://forum.cfx.re/t/bcs-notify/5058625)
- For any questions or issue join my discord: https://discord.gg/yMV5A9RBcw.

# Other releases
- [BCS HUD](https://forum.cfx.re/t/bcs-hud-simple-hud-for-fivem-rp-servers/5057159)
Installation
You have to change your core Notify function. es_extended (ESX), qb-core, etc…

QB-Core example:
Default (qb-core/server/functions.lua):
image
![image](https://forum-cfx-re.akamaized.net/original/4X/b/6/5/b65eb1a76b81f05d52dd8f56dc4878c5ce37353a.png)

BCS Notify:

![image](https://forum-cfx-re.akamaized.net/original/4X/1/6/e/16eb0e9a33d0ae85d112f8710a213622e1f8b91d.png)

Default (qb-core/client/functions.lua):

![image](https://forum-cfx-re.akamaized.net/original/4X/8/f/7/8f75a96e7e86227c6398e1b44bbb983c7114449d.png)

BCS Notify:

![image](https://forum-cfx-re.akamaized.net/original/4X/f/d/5/fd5602c2a102b4d2ccf9bab9a564cd74afd1d0c3.png)


ESX example:

Default (es_extended/client/functions.lua):
![image](https://forum-cfx-re.akamaized.net/original/4X/6/f/8/6f8ac65b776463ef34bea4dc8b66daecc2fcf91b.png)

BCS Notify:
function ESX.ShowNotification(message, type, length)
    TriggerEvent('bcs-notify', message, type, length)
end