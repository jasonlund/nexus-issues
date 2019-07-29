# Nexus

Nexus is a forum software created by NeosteelEnthusiast (Jason Lund) for The Pylon Show Starcraft 2 talk show. It is meant to be a new, modern place for like-minded RTS players to gather and discuss any topic.

If you are reading this you are most likely a beta tester for Nexus. Thank you! Your help is very apperciated.

Please use and test the forum as much as possible. See the "Testing" section below on specifics.

**Your discretion is appreciated**. Please do not discuss or share Nexus with anyone who is not also a beta tester. The app is not ready to be launched to the general public.

## Issues

Here you will find all outstanding, completed or deferred issues for your reference. Please read this before submitting an issue to ensure it hasn't already been addressed.

Please note that an issue only concerns problems with a currently implemented feature. Please see the Roadmap section below for currently implemented features & information on how to request a new feature.

### Outstanding Issues

- [ ] Outstanding issue

### Completed Issues

- [x] Completed issue

## Testing

Again, thank you for helping beta test the forum. If you've never beta tested a web app before, don't worry it's really easy.

Just use the website as you would if it was live. If you run into an issue please create a topic in the "Issues" channel of Nexus . If the issue is making it impossible to create a topic, post a message in the ```#beta-testing``` channel of The Pylon Show's Discord.

Please see the "Roadmap" section below to know exactly what should be tested.

When submitting an issue, please include the following:

- The current URL
- What was done to cause the issue
- What behavior was expected
- What behavior occured
- What user (if any) were you logged into
- The Date and Time (including timezone) this occured

For example:
- https://nexus.thepylonshow.com/users
- Clicked the "Logout" button in navigation
- To be logged out
- An error message displayed stating "An unknown error occured"
- admin (admin@example.com)
- Sun Jul 28 at 5:50 pm EST

### Important Testing Information

Please note the following while testing.

1. There is currently no email verification and you are able to sign up with any validly formatted email. Feel free to make up emails when creating users.
2. When creating users for testing, you may want to assign a certain role to that new user (Admin, Super Moderator, etc.). You may login to the generic admin user to edit the user you've created. Please **DO NOT** modify this generic admin user in any way whatever. The credentials for this user are as follows:
 - email: admin@example.com
 - password: secret
3. The "Forgot Your Password" functionality does not currently send an email. This is expected and will be resolved when we launch.

## Roadmap

### Feature Requests

If you have an idea for the forum and it isn't already outlined below, we'd love to hear it! Please create a topic in the "Feature Requests" Channel. Please note that your request will most likely be filed un the "Post Launch" category. If you feel it's important enough to be included "At Launch" then please make your case as to why.

### At Launch

- [ ] Front end design
  - [ ] Complete new design transition
  - [ ] Breadcrumbs
- [ ] Users
  - [x] Anyone can register accounts
  - [ ] Users must verify their email address when registering an account
  - [x] Users have a role
      - Administrator
      - Super Moderator
      - Moderator
      - Users
  - [x] Users can modify and delete themselves
  - [x] Administrators can modify and delete any Users
  - [x] Administrators and Super Moderators can temporarily or permanently ban users
  - [x] Users can optionally upload an Avatar
  - [x] Users can optionally define a simple signature
  - [x] Currently active (within the last 10 mintes) users are displayed
- [ ] Channels
  - [x] Anyone can view Channels
  - [x] Administrators can create, modify and delete Channels
  - [x] Channels have a simple description
  - [x] Channels can be locked wherein by Administrators.
  - [x] Locked Channels only allow Administrators, Super Moderators or Moderators of that Channel to create Topics
  - [ ] Channels belong to a Channel Category and are grouped as such when listed
  - [ ] Channels can optionally have a featured image which is displayed in that channel's header
- [ ] Topics & Replies
  - [x] Topics belong to a Channel
  - [x] Topics in a Channel are paginated (25 per page)
  - [x] Replies belong to a Topic
  - [x] Replies in a Topic are paginated (25 per page)
  - [x] Anyone can view Topics & Replies
  - [x] Authenticated users can create Topics & Replies
  - [x] Authenticated users can modify or delete Topics & Replies they created
  - [x] Administrators, Super Moderators & Moderators of a particluar Channel can modify and delete Topics & Replies
  - [x] Threads can be locked by Administrators, Super Moderators or Moderators of that Channel
  - [x] Locked Threads and Replies in a locked Thread can only be created, modified or deleted by an Administrator, Super Moderator or Moderator of that Channel
  - [ ] Authenticated users may optionally "Reply with Quote" referencing another Reply within that Thread
  - [ ] Topics & Replies support Rich Text content
    - [x] Bold
    - [x] Italic
    - [x] Strikethrough
    - [x] Underline
    - [x] Ordered List
    - [x] Unordered List
    - [x] Blockquote
    - [x] Images (directly linked & uploaded)
    - [x] Video Embeds (YouTube & Twitch only)
    - [ ] Links
    - [ ] Emotes (see below)
    - [x] Undo
    - [x] Redo
- [ ] Emotes
  - [ ] Administrators & Super Moderators can create, modify and delete Emotes
  - [ ] Authenticated Users can choose to insert Emotes in Threads or Replies
  - [ ] Authenticated Users can react to a particular Thread or Reply with an Emote
  
  
### Post Launch
- [ ] Notifications
  - [ ] Authenticated Users can @ mention other users. The mentioned user will receive a notification via email or in app
  - [ ] Authenticated Users can subscribe to a Thread. A subscribed Thread will notify the user of any new Replies via email or in app
- [ ] Users
  - [ ] Users may optionally define a birthdate and may exlude the year if they do.
  - [ ] Any user whos birthday is "today" will be listed
  - [ ] Users may be "verified" either manually by staff or by linking their Twitch account
- [ ] Calendar
  - [ ] A calendar of Starcraft events
- [ ] Messages
  - [ ] Users may directly send messages to other users
  - [ ] Users may choose to block other users or choose not to accept messages entirely
