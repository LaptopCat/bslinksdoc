# Brawl Stars links documentation (unofficial)
# Domains used for links

- ## link.brawlstars.com (Normal game)
- ## link-staging.brawlstars.com (Staging)
- ## link-cn.brawlstars.com (Chinese BS version)

# Protocols

- ## brawlstars:// (Normal game)
- ## brawlstars-inbox:// (Normal game) 50/50
- ## brawlstars-cn:// (Chinese BS) UNKNOWN
- ## kakaogame241121:// (Normal game) UNKNOWN
- ## kakaod509a010c29a8768bcc216071a43fa9b:// (Normal game) UNKNOWN
- ## selfweb:// (Normal game) UNKNOWN

## (*) - Required argument
# brawlstars://
## If you know any points that are not mentioned here, please make a pull request and add them.
## Any invalid point just opens the game.
- ## brawlstars://
Opens the game. Thats all.
<a href="brawlstars://"><button>Try it</button></a>

- ## addFriend
Adds a friend to your friend list.
### Arguments:
- ### tag (*)
Player tag.
- ### token (*)
Friend invite token. (Only valid for 3 days)

### Example URL: 
### ```brawlstars://addFriend?tag=SomeTagHere&token=SomeTokenHere```

- ## supportcreator
Supports a creator in the shop. (Expires after 7 days)
### Arguments:
- ### code (*)
Content creator code.

### Example URL: 
### ```brawlstars://supportcreator?code=OJ```
<a href="brawlstars://supportcreator?code=OJ"><button>Try it</button></a>

- ## joinBand
Joins a club.
### Arguments:
- ### tag (*)
Club tag.
- ### token (*)
Club invite token. (Only valid for 3 days)

### Example URL: 
### ```brawlstars://joinBand?tag=SomeTagHere&token=SomeTokenHere```

- ## joinRoom
Joins a gameroom.
### Arguments:
- ### tag (*)
Gameroom tag. Only valid while there are people in the room.

### Example URL: 
### ```brawlstars://joinRoom?tag=SomeTagHere```

- ## supercell_id
Views a Supercell ID profile. If UUID not provided, opens the supercell id tab.
### Arguments:
- ### p
Supercell ID account UUID.

### Example URL: 
### ```brawlstars://supercell_id&p=S0M3-UU1D-1S-H3R3```

- ## extlink
Opens Brawl Stars and then it opens your browser with a provided url. (it's used in the brawl stars inbox)
### Arguments:
- ### page (*)
Page URL to open.

### Example URL: 
### ```brawlstars://extlink?page=brwl.cf```
<a href="brawlstars://extlink?page=brwl.cf"><button>Try it</button></a>

- ## webview
Opens Brawl Stars and shows your page and title. (if no title provided, it is blank)
### Arguments:
- ### page (*)
Page URL to open.
- ### popup_title 
Popup title. (Literally)
### Example URL: 
### ```brawlstars://webview?page=brwl.cf;popup_title=BRWL```
<a href="brawlstars://webview?page=brwl.cf;popup_title=BRWL"><button>Try it</button></a>

# brawlstars-inbox://
## The protocol only works in the news tab of BS
## If you know any points that are not mentioned here, please make a pull request and add them.
- ## brawlstars-inbox://
Unknown
- ## getParams
Unknown
- ## shop
Opens the shop.

# brawlstars-cn://
## Probably the same as brawlstars://
## If you have the chinese version, you can try the normal game ones, please make a pull request and copy it if its correct

# kakaogame241121://
## If you know any points that are not mentioned here, please make a pull request and add them.
- ## kakaogame241121://
Opens the game. Thats all.
<a href="kakaogame241121://"><button>Try it</button></a>

# kakaod509a010c29a8768bcc216071a43fa9b://
## If you know any points that are not mentioned here, please make a pull request and add them.
- ## kakaod509a010c29a8768bcc216071a43fa9b://
Opens the game. Thats all.
<a href="kakaod509a010c29a8768bcc216071a43fa9b://"><button>Try it</button></a>

- ## kakaolink
Unknown
### Arguments:
Unknown

- ## kakaostory
Unknown
### Arguments:
Unknown

# selfweb://
## The protocol only works in the Help & Support tab of BS
## If you know any points that are not mentioned here, please make a pull request and add them.
- ## selfweb://
Unknown
- ## getParams
Used to get Tag & name of current user
- ## openWeb
Opens a page on the web
### Arguments:
- ### url (*)
Page to open
