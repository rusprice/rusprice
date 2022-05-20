# I am UntrustableRus, but you can call me Rus
Here's some information about me.
## Reverse Engineer
I am a reverse engineer/white-hat hacker. I've reversed engineered quite a few companies:
### Roblox/Trello (Admin Panel Pictures)
#### Roblox is a 3D gaming platform used by millions of players each day.
I was able to exploit a vulnerability with Trello that allowed everyone to see private images in a Trello board. I exploited this vulnerability to find images of Roblox's admin panel that were shared on their internal Trello board that was seemingly used for admin panl suggestions/bugs.
### World2Build (Major Vulnerability)
#### World2Build is a 3D sandbox similar to Roblox, but does not have as many players.
Unfortunately, the vulnerability is classified as it still exists. I'll update this when it's patched.
### HQ Trivia (Admin Panel Experience)
#### HQ Trivia is a live mobile game show app, where every Thursday if you answer 12 questions presented by a live host correctly, you will split the cash prize with the other winners.
I was able to use the source maps of HQ Trivia's admin panel to get one running locally. I was able to see what all of the menus looked like and everything, however, I did not have a user account or anything, so I coudln't exactly see or do anything special, asides from seeing what the admin panel looks like.
### Blooket (Admin Panel Experience)
#### Blooket is a live game played in school for studying, similar to GimKit and Kahoot, among others.
I was able to use the source maps of Blooket's admin panel to get one running locally. I was able to see what all of the menus looked like and everything, however, I did not have a user account or anything, so I coudln't exactly see or do anything special, asides from seeing what the admin panel looks like. *(Yes, this is the same exact thing I did for HQ Trivia)*
### VocabularySpellingCity (XSS)
#### VocabularySpellingCity was a learning website for teachers to assign to students. It allowed students to use the site to play games with the words that the teacher assigns.
They forgot to sanitize inputs, so I was able to create a spelling set on their website will script tags and stuff like that, which would then show up on one of their pages as "recently created"
### Clouthub
#### Clouthub is an alt-right social media platform that promotes free speech, serving as a safe haven from censorship on other social platforms.
I was able to change any and all data about my account, including verified status. I was able to set my account to be verified, set my account as a founder, and more. In addition, I was able to access the personal information of any user on the platform. I could see phone numbers, emails and more. If I was in bad faith, I cou have mined all of this information and old it on the dark web, but of course I did the right thing and reported the vulnerability to the company. There are some more minor vulnerabiities that still exist on the site, but they are so minor I haven't bothered to report them.
