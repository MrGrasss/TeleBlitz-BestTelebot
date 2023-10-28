![Screenshot_1](https://github.com/MrGrasss/TeleBlitz-BestTelebot/assets/132838549/678f693d-0f13-428e-924e-a392244636e6)]

Welcome to the only allround telegram bot on the market!
This is a licensed tool and can be purchased by contacting https://t.me/MrGrassss (Free trial is possible).
I also sell my own telegram account generator if your in need of cheap private accounts.

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
    # Mass Reporter (Groups / Channels)
    # Forum Advertiser
    # Group-List Joiner
    # Group-List Leaver

## Future:

    # Premium emojis included in custom message creator
    # Group List Creator 

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
      waiting time and the number of members to be added per client. There is also an option 'additional_joined_check'
      that only counts adds after checking if their actually in (this might cause more privacy errors) While private 
      groups are supported, channels are not. Make sure that the clients are admin in the group.
    
    - MassDM (Copy): This is the same as the mass forwarder except instead of forwarding we copy the given message and 
      send it as a dm. There is an option to randomly edit your message on flags, see 'Change message randomly' below.

    - Prevent MASSDM flags: In MassDM(copy) and Massforwarder you will find an option to change message on flags
      (only appears when using a channel), this adds random characters in between words while keeping emojis, links 
      and markdown characters intact. For this you will need one client that has admin permissions with atleast 
      "Edit Messages of Others" turned on. There is also an option called "changed_message_ratio" which is a percentage
      of how often a random character will be added, the higher the more characters. "change_group_url" will change the
      messageId behind a telegram group link to prevent flags, this is recommended to be used with having your actual 
      promo message in that telegram group that you have used the link of.

    - Admin Promoter: This feature needs atleast one of your clients to be admin in the channel and your clients to
      have usernames. You can use the "Username Changer" to guarantee this works. You get to choose if the admin
      appears invisible and the title this admin should have.

    - Normal Scraper: This only works when a channel has their member list on public and only requires one client.
      (scrapes almost instantly)

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

    - Forum Advertiser: This feature is essentially the same as the Group Advertiser but uses 'forumgroups.txt' found
      in the groupadvertiser folder instead. The groups should have this format: https://t.me/forumtester/2 or 
      t.me/forumtester/2. It uses the same config found in the groupadvertiser folder except "seconds_between_fetch" and
      "full_fetch" don't do anything here. Please know that slow mode counts for the entire group and not just for 1 
      topic, meaning if you try to use 1 client for multiple topics and the first topic will have slow the others will 
      always be skipped. 
    
    - Group-List Joiner: This uses 'https://t.me/addlist/6wxnTZgrHSU2ZmM6' to add up to 100 groups at once and join them
      instantly with no limitations. These links need to be put in 'groupadvertiser/grouplist.txt' in the format I 
      showed above or the last part of the link so in this case '6wxnTZgrHSU2ZmM6'. Joined groups get exported into
      'exported_groupslist.txt' to be used in groups.txt for the normal advertiser.  (Groups should have usernames)
      
    - Group Fetching in advertiser: groupadvertiser/groups.txt supports channelname, @channelname, 
      https://t.me/joinchat/, https://t.me/, http and t.me/. (public groups only)

    - Load TDATA in from sessions: This will convert your sessions to usable tdata so that you can login to your clients
      via something like telegram portable.
    
    - +users_info.json: This will contain the succesfully messages users_info so that you could reuse that list in the 
      future.

## Suggestions / Feedback

I'm open to any suggestions / feedback!

For questions, you can always contact me on telegram: https://t.me/MrGrassss
