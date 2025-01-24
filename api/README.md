# selfdriven.social API
API to verify a user using BlueSky / AT Protocol.

### Status:
- Proof of Concept code
- Powering *.selfdriven.social
  
### Usage in the Pilot phase using BlueSky App
- BlueSky > Settings > Account > Handle > I have my own domain > No DNS Panel
- Copy the text starting with "did:plc"
- Send this text with your details to octo@selfdriven.foundation or do a pull request.
- Include your existing bsky.social handle with the request.
- It will then be validated and if OK, added to profiles.json.
- You can then complete the set up in BlueSky
- URL example: <code>https://octo.selfdriven.social/.well-known/atproto-did</code>

