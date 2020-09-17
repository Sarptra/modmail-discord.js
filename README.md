# modmail-discord.js

{
  "name": "hmm",
  "permissions": "NONE",
  "restriction": "3",
  "_id": "aNKQx",
  "actions": [
    {
      "title": "Sarptra Bot Help Center",
      "author": "",
      "color": "FF0000",
      "timestamp": "true",
      "url": "",
      "authorIcon": "",
      "imageUrl": "",
      "thumbUrl": "",
      "storage": "1",
      "varName": "em",
      "name": "Create Embed Message"
    },
    {
      "message": "0",
      "varName": "",
      "info": "2",
      "storage": "1",
      "varName2": "txt",
      "name": "Store Message Info"
    },
    {
      "storage": "1",
      "varName": "em",
      "message": "Ticket opened, Your message sent to help center.\n\nYour message: **${tempVars(\"txt\")}**\n\n",
      "name": "Set Embed Description"
    },
    {
      "storage": "1",
      "varName": "em",
      "message": "Sarptra's Stupid Offical bot",
      "footerIcon": "",
      "name": "Set Embed Footer"
    },
    {
      "storage": "1",
      "varName": "em",
      "channel": "0",
      "varName2": "",
      "storage3": "0",
      "varName3": "",
      "iffalse": "0",
      "iffalseVal": "",
      "messageContent": "",
      "name": "Send Embed Message"
    },
    {
      "storage": "0",
      "varName": "",
      "emoji": "4",
      "varName2": "✅",
      "varName3": "",
      "name": "Add Reaction"
    }
  ],
  "comType": "3"
}
-------------------- ayrı bi komut atmanızı öneririm aynı yerde olunca karışıyor 3 ve 5 server id ve channel id kendi id'lerinize göre yazın

{
  "name": "ModMail",
  "permissions": "NONE",
  "restriction": "3",
  "_id": "zcksY",
  "actions": [
    {
      "member": "1",
      "varName": "",
      "info": "1",
      "storage": "1",
      "varName2": "ID",
      "name": "Store Member Info"
    },
    {
      "message": "0",
      "varName": "",
      "info": "2",
      "storage": "1",
      "varName2": "txt",
      "name": "Store Message Info"
    },
    {
      "info": "0",
      "find": "754583927502667846",
      "storage": "1",
      "varName": "server",
      "name": "Find Server"
    },
    {
      "server": "1",
      "varName": "server",
      "name": "Change Server"
    },
    {
      "info": "0",
      "find": "755001067191664650",
      "storage": "1",
      "varName": "channel",
      "name": "Find Channel"
    },
    {
      "title": "New Message",
      "author": "",
      "color": "1dd3f1",
      "url": "",
      "authorIcon": "",
      "authorUrl": "",
      "imageUrl": "",
      "thumbUrl": "",
      "timestamp": "true",
      "debug": "false",
      "text": "",
      "year": "",
      "month": "",
      "day": "",
      "hour": "",
      "minute": "",
      "second": "",
      "storage": "1",
      "varName": "embed",
      "name": "Create Embed Message"
    },
    {
      "storage": "1",
      "varName": "embed",
      "fieldName": "Sender Info:",
      "message": "ID: **${tempVars(\"ID\")}**",
      "inline": "1",
      "name": "Add Embed Field"
    },
    {
      "storage": "1",
      "varName": "embed",
      "fieldName": "Message Content:",
      "message": "${tempVars(\"txt\")}",
      "inline": "1",
      "name": "Add Embed Field"
    },
    {
      "storage": "1",
      "varName": "embed",
      "channel": "5",
      "varName2": "channel",
      "storage3": "0",
      "varName3": "",
      "iffalse": "0",
      "iffalseVal": "",
      "messageContent": "",
      "name": "Send Embed Message"
    }
  ],
  "comType": "3"
}
