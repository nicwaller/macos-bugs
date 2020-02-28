# macos-bugs
Bugs I've stumbled across in macOS

## Disappearing desktop icons

https://youtu.be/wFjkBJEOVkk 

## Mail modal lockout

- Click a "send email" link in some third party application (I'm using OmniFocus -> Help -> Contact Omni, but other apps might work for you)
- Mail.app opens a new email draft screen
- Write your email and click send
- Get an error because you haven't configured any email accounts yet

    This message could not be sent. It will remain in your Outbox until it can be sent. This message could not be sent because your account does not have a preferred outgoing mail server. Select an outgoing mail server from the list below.

- Your message disappears, then you're presented with a modal to add an account
- You cannot access your Drafts or Outbox until after adding an account
