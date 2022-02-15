# Chat-Tagger

Update tags for chats handled via agent workspace

## Description
This is a sample application run from the ticket sidebar location. When a ticket is opened by an agent the app checks to see if the ticket is a chat. If it is, it will add tags onto the ticket via a api request.

For production use, you may want to:

- Check createdAt timestamp  to make sure that this is an active ticket
- Checking presence of tags to prevent sending extraneuous requests.
