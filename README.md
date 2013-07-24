Beem
====

Beem is the first DI.FM client for Windows Phone. It allows its users to stream EDM directly from the DI.FM servers.

It supports both standard and premium streams, given that the user has the secret key necessary to unlock the 
premium quality stream.

### I don't want to mess with source code. Can I download your app on my Windows Phone?

Absolutely. Head over to the Windows Phone Store and either download [Beem](http://www.windowsphone.com/en-us/store/app/beem-plus/8433ad41-9a4e-46ff-ba33-340d265f53d5) or [Beem for SKY.FM] (http://www.windowsphone.com/en-us/store/app/beem-for-sky-fm/89012aa1-3606-42fe-b924-48b305f50ebc).

### Can I re-distribute Beem in the Windows Phone Store?
Sure. Under a few conditions, though:
- You will not distribute it under the name of Beem.
- None of the Beem logos are included in your distribution.
- You will include a reference to this project in the "About" page.

### I want to have SkyDrive and Last.fm support in my app, but none work.
The source code that I have provided has all the API keys stripped. You will have to obtain those through the proper developer channels and include them in the app.

### Why none of the station lists load?
Beem relies on Windows Azure Mobile Services, and I cannot give you access to my data. Based on the existing data models, you can create your own data infrastructure.