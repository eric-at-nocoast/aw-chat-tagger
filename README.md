# Chat-Tagger

Update tags for chats handled via agent workspace

## Description
This is a sample application run from the ticket sidebar location. When a ticket is opened by an agent the app checks to see if the ticket is a chat. If it is, it will make a post request to a third party service.

For production use, you may want to:

- Check createdAt timestamp  to make sure that this is an active ticket
- Add a tag and then check for presence of aforementioned tags to prevent sending extraneuous requests.
- Add secure parameters to add api keys

