# Fediwork Design Considerations

Fediwork is supposed to be a fairly benign change to core mastodon which enables such (FediWork-)Instances to store, send and receive additional information, securely.

This means that the core user profile and such should stay the same and only fields (some of which are encrypted). Later, there should also be logic to display trust (is this company or worker trustworthy?) and enable suggestions from one person or company to the next while actively countering monopolization.

## The User Profile

currently (2025-11-29) there are the following fields visible:

- banner
- profile picture
- nickname
- profile name
- title (eg. (server) owner, bot, etc.)
- Personal note (which the viewer can ascribe)
- Selfdescription
- date joined
- free field 1-4
- amount of posts, following, followers
- featured, posts, posts and replies, media

a fediwork user profile should only add to the current user profile, not change anything that is already in there. also in the hopes of maybe getting it upstreamed someday to enable jobsearch in mastodon and making corporate job platforms unnecessary.

proposed fields (2025-11-29):

- current employment status: select one (happy, open to requests, actively seeking) - either private, findable or public
- current job title
- highest education
- clear name (encrypted)
- work history (dates, names and city are encrypted)
- school history (dates, names and city are encrypted)
- Skills (findable or public)
- Salary (private or public)
