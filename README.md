![Screenshot_2](https://github.com/MrGrasss/TeleBlitz/assets/132838549/9f3fbfcf-f818-4510-98f9-efb21d9b0a43)

Welcome to the only allround telegram bot on the market!
This is a licensed tool and can be purchased by contacting https://t.me/MrGrassss (Free trial is possible).

## Features:

    # Login to your tokens in various ways (TDATA, sessions, manual and accounts.json)
    # Proxy support 
    # Restart clients with new proxies when max limit is reached
    # Scrape members from chat messages
    # Add members to group/ channel
    # Group Joiner (private chats supported)
    # Load sessions in from TDATA
    # Name Changer
    # Avatar Changer
    # MassDM 
    # Mass Forwarder (private chats supported)
    # Channel Leaver
    # Normal Scraper
    # Group Advertiser (private chats supported)
    # BIO Changer
    # Username changer 
    # Admin Promoter (private chats supported)
    # Client Checker (GUI)
    # Verification Scraper

## Future:
 
    # Rework Client Checker GUI 
    # Account Generator 

## Info

    - Note: In every functionality there will be prompts that will ask you if you have already done something needed for 
      it to work. This means that you don't necessarily need to use one function first before using the other.

    - Important: If your going to use this tool for any other activity then scraping make sure to select "Y" to scrape
      all users info because you will be needing their usernames.

    - Proxies: The formats of the proxies are hostname:port@username:password or hostname:port:username:pass. 
      I suggest using proxies for most functions 
      except for scraping / changing info :)  Using 0 proxies on everything should not be too bad, just make sure to use 
      multiple accounts if you do.
    
    - Add members to group: This will always first join your clients to the destined group before adding your scraped 
      users. In the adder folder you will find a config file to adjust at which added amount per client the program 
      should wait and what the wait time should be. We need these waits else the members will look like their being 
      added when they actually are not.

    - Admin Promoter: This feature needs atleast one of your clients to be admin in the channel and your clients to 
      have usernames. You can use the "Username Changer" to guarantee this works. 

    - Normal Scraper: This only works when a channel has their member list on public and only requires one client. 
      (scrapes almost instantly)

    - MassDM: The message.txt that is used for this tool is in HTML format, so if you want bold text for example you use
      <b>#text</b> and for an image you can just add an <a href=#Image link>.</a> to display this image and only add a 
      dot or anything as text else it won't show up :)

    - Mass Forwarder: Like MassDM but uses a forwarder message instead. After 3 flags in a row the message that your 
      using is 99% flagged so change it, flagged tokens can still be used in other functions and will be saved in 
      massforwarder/flagged-clients folder

    - Messages: In forwarding and mass messaging your message could get flagged if enough users report this message. 
      If you start to see "[ERROR] {phone} got flagged." prompt when trying to send this message it 99% means that this 
      message is flagged and that you should change it ASAP! (The bot stops when it detects this behaviour and prompts 
      the user)
      
    - Message Scraper: This function scrapes all messages in the channel and saves the users info of the sender of that 
      message, this way you can also scrape channels that have their member list disabled aslong as chatting is allowed. 

    - accounts.json: This is just a way to manually login to your clients, just a bit faster than normal. 
      If you find it annoying that it keeps asking if you want to use accounts.json you can simply remove the accounts 
      from the list and use sessions / tdata instead. This way it won't prompt you anymore :)

    - Bio Changer: Max length of a telegram bio is 70 characters, the same rules apply here.

    - Admin Promoter: Promotes your clients to admin in your group and option to choose their admin title / if they will
      appear as  invisible or not.
    
    - Verification Scraper: This feature uses the title of the channel to scrape the members, this would normally not 
      work with the channel its @. Make sure that atleast one of your clients is in this channel through manually 
      verifying if needed.

    - Group Advertiser: For this feature I recommend using atleast 10 minute delay between groups for safety of your 
      account. This works with multiple accounts too but if you have a HQ account using one should be fine and would 
      also be the fastest way.

## Suggestions / Feedback

I'm open to any suggestions / feedback!

For questions, you can always contact me on telegram: https://t.me/MrGrassss
