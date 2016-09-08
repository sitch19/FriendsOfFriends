# FriendsOfFriends
Discovers all friends on "Find my Friends" for any iCloud account. Bypasses Apple's restriction that prevents you from viewing any account other than yours.

Find My Friends is an iOS application that allows iCloud users to share their location with people of their choosing. Apple's implementation of FMF on iOS allows for you to find your friends only if you have your physical phone. You cannot log into somebody else's phone to Find your Friends, the application does not allow you to log out. 

If you have multiple phones / lost your phone / your phone was stolen and you need to find someone, this becomes a problem. 

FriendsOfFriends takes care of this issue. Not only does it not need your iPhone, it doesn't need any iPhone. It also does not need full iCloud credentials if you do not have access to them. It works with a DSID/MMeAuthToken (MobileMeAuthToken) pair as well. The added benefit of using an MMeAuthToken is that it can bypass Apple's 2SV/2FA.

It is built in pure python, so no dependencies are required.

---

***Example Usage***: python FriendsOfFriends.py

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Input: username/DSID

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Input: password/MMeAuthToken

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output: bobloblaw@icloud.com

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output: 123 Mill Road

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output: Bobville, ME, US

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output: Thursday, September 08 at 01:18:44 (0m 10s ago)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output: Found [1] friends for bobloblaw@icloud.com!

---

***Future Features***

- [ ] Look up phone number / email with iCloud's CardDav server to pull coresponding contact information.
