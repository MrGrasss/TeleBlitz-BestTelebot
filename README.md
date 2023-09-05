![Screenshot_1](https://github.com/MrGrasss/TeleBlitz-BestTelebot/assets/132838549/5e4eb54f-219c-4e6a-9bc7-95663eb476cb)
Welcome to the only allround telegram bot on the market!
This is a licensed tool and can be purchased by contacting https://t.me/MrGrassss (Free trial is possible).

## Features:

    # Login to your tokens in various ways (TDATA, sessions, manual and accounts.json)
    # Proxy support
    # Restart clients with new proxies when max limit is reached
    # Scrape members from chat messages
    # Add members to group/ channel (private groups supported)
    # Group Joiner (private chats supported)
    # Multi Group Joiner (private chats supported)
    # Load sessions in from TDATA
    # Load TDATA in from sessions
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
    # Custom Message Creator
    # MassDM (Copy Message)
    # Member Banner
    # Mass reporter (Groups / Channels)

## Future:

    # Premium emojis included in custom message creator
    # Group Creator

## Info

    - Note: In every functionality there will be prompts that will ask you if you have already done something needed for
      it to work. This means that you don't necessarily need to use one function first before using the other.

    - Important: If your going to use this tool for any other activity then scraping make sure to select "Y" to scrape
      all users info because you will be needing their usernames.
    
    - Scrapers: Scraped users will always be added ontop of each other in user_info.json and user_ids.txt excluding 
      duplicates. 

    - Proxies: The formats of the proxies are hostname:port@username:password or hostname:port:username:pass.
      Don't use proxies for scraping or changing client info! For Iproyal only SOCKS5 is supported in the hostname:port@
      username:password format. Proxies do not seem to effect telegram at all, hence why I have not expended on it. 
      
    - TDATA: Formats: {name}/tdata/(actual_data), {name}/(actual_data). For best results use bought TDATA. TDATA with 
      multiple accounts logged in are not supported YET. 
      
    - Add members to group: This feature ensures that your clients are joined to the specified group before adding the 
      scraped users. Within the 'adder' folder, you will find a configuration file where you can adjust the program's 
      waiting time and the number of members to be added per client. While private groups are supported, channels are not 
      yet supported.

    - Admin Promoter: This feature needs atleast one of your clients to be admin in the channel and your clients to
      have usernames. You can use the "Username Changer" to guarantee this works. You get to choose if the admin
      appears invisible and the title this admin should have.

    - Normal Scraper: This only works when a channel has their member list on public and only requires one client.
      (scrapes almost instantly)

    - MassDM: The message.txt that is used for this tool is in HTML format, so if you want bold text for example you use
      <b>#text</b> and for an image you can just add an <a href=#Image link>.</a> to display this image and only add a
      dot or anything as text else it won't show up :)
    
    - MassDM (Copy): This is the same as the mass forwarder except instead of forwarding we copy the given message and 
      send it as a dm. There is an option to randomly edit your message on flags, see 'Change message randomly' below.

    - Message Scraper: This function scrapes all messages in the channel and saves the users info of the sender of that
      message, this way you can also scrape channels that have their member list disabled aslong as chatting is allowed.
      Using multiple clients for this would speed it up. 

    - accounts.json: This is just a way to manually login to your clients, just a bit faster than normal.
      If you find it annoying that it keeps asking if you want to use accounts.json you can simply remove the accounts
      from the list and use sessions / tdata instead. This way it won't prompt you anymore :)

    - Bio Changer: Max length of a telegram bio is 70 characters, the same rules apply here.

    - Client Checker: This just gets all data from your client and shows them in a GUI with a search function and remove
      included.

    - Verification Scraper: This feature uses the title of the channel to scrape the members, this would normally not
      work with the channel its @. Make sure that atleast one of your clients is in this channel through manually
      verifying if needed.

    - Group Advertiser: For this feature you will find a full config that you can change to your needs.I recommend to 
      first use 'full_fetch: true' with multiple clients to clean your channels in groups.txt and turn it off after the
      cleaning process. Clients seconds between depends on the quality of your sessions (experiment at your own risk).
      Using multiple accounts will speed this process up x the amount of clients which I do recommend if your using over    
      40 groups to advertise in.
      
    - Group Fetching in advertiser: groupadvertiser/groups.txt supports channelname, @channelname, 
      https://t.me/joinchat/, https://t.me/ and http. (public groups only)

    - Load TDATA in from sessions: This will convert your sessions to usable tdata so that you can login to your clients
      via something like telegram portable.
    
    - +users_info.json: This will contain the succesfully messages users_info so that you could reuse that list in the 
      future.

    - Change message randomly: In MassDM(copy) and Massforwarder you will find an option to change message on flags
      (only appears when using a channel), this adds random characters in between words while keeping emojis, links 
      and markdown characters intact. For this you will need one client that has admin permissions with atleast 
      "Edit Messages of Others" turned on. There is also an option called "changed_message_ratio" which is a percentage
      of how often a random character will be added, the higher the more characters. "change_group_url" will change the
      messageId behind a telegram group link to prevent flags, this is recommended to be used with having your actual 
      promo message in that telegram group that you have used the link of.

## Suggestions / Feedback

I'm open to any suggestions / feedback!

For questions, you can always contact me on telegram: https://t.me/MrGrassss
