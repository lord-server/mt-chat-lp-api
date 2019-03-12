# LongPoll APi mod for minetest

#### Add this mods to the trusted_mods:
- Open : minetest.confg
- Add : secure.http_mods = lp_api

#### Edit parameters if needed in to minetest.confg
- lp_api.url (LongPoll server url)
- lp_api.channel_id (Channel ID in Discord)
- lp_api.timeout (Timeout connection)
- lp_api.header (Header if needed)
- lp_api.subscriber.timeout (Timeout for subscribe)
- lp_api.router.cmd (Support commands or not)