Project: Create an open but secure private forum with nearly no moderation necessary/present.
Platforms: Web browser access by a PC. No expressed Mobile Phone comptability at this time.*
python version(s) = 2.7.3 or 3.5.2
flask version(s) = 8.1.1 / 8.1.2
Source-Openness: Open and on github.

Before reading this document be aware of a few things. 
'-' denotes a section.
'?' are put in places where a string is yet to be determined.
'*' will have one placed to the right of unsure/unset item of the project.

-The Home Page

The site/forum's name is Georgioland.

Georgioland is powered by heroku.
heroku is a cloud hosting solution.
Project will be written primarily with python & flask.

The site will have standard EULA stuff about how we don't guarantee anything (as in the acceptability of sueing us if we fail to provide you what you expected in some way).

We should display relevant constitutional-laws for a few noteable countries as it relates their rights. But we will stress we are not saying our interpretation carries weight of that of a public defender.*

We should display links to various OTR. OTR is tech for doing off the record messaging.

Finally we give our breakdown of the site's purpose and rules during registration and make a copy of those details easily available somewhere else. Possibly for download? We ideally do a breakdown of how the tech and moderators will control content and/or accounts. Such as the fact that staff will *not* help a user recover an account.


-If your posts contain any of the below formatted information, then they won't make it through the site filter.

Phone Numbers
Emails
Links to all social media sites. twitter, facebook. 
Home Addresses
GPS coordinates
IP numbers
MAC addresses
All streaming sites
Spammer (as in advertisement shit)
Spammer (merely posting too much in a short period)
Embedding of custom scripts
Images
High-res ascii art
Streaming site links (you may be able to link to sites that have links to streaming sites)
Note: No media is expected to make it through. 
But in some cases if a user does a highly sophisticated bypass to share text or a link, it doesn't bother us too much.*


-The following things are accepted and will make it through.
Tox IDs
Possibly a couple other secure OTR user IDs.
News sites*
Tech news sites*
Game news sites*
Conspiracy sites*
IRC urls.
IRC chatroom. (however users cannot expect same level of tolerance in this room.) 

-No posted forum/thread content contains:
Timezone or Time information of when it was made. This goes for PMs as well.


-The features afforded to every user:
quotation
content rating (think codex smilies at present)
ignore
signature
profile posts*
no profile may ever be set to private.
user being logged in or not is never shown.
number of users online, topics, posts, forums is publically displayed.
Users are allowed to edit thread titles a couple of times only.

-Features afforded for both moderator and user:
Appropriateness Ratings

Moderators can flag a post as having a certain level of appropriateness. Users by default get
a "you're a baby option". They are told this means they are only shown the least offensive material. They are told they must switch to a higher level to see more fucked up shit. Important: Only moderators may flag. 

The point of appropriateness rating is to hide the stuff a filter could not catch or is too taboo to just be out in the open (atleast by default)

Posts are promised never to be deleted. Not moderators, but only an admin are the exception and can do deletions in dire circumstances (probably sick perverts finding how to circumventing filter )


-To solve impersonation problems:
Each user's key is converted to ascii art shown to all forum users. 

With the help of the server as additional provider of a random offset to these. Which is to make a unique ascii art which identifies a user but not their key exactly. 

More User Stuff:
Additionally a user may append/redact any key of their signature or profile details. But not to affect the existing data associated with the already made posts or PMs.

A user when registering has a non-mandatory email recovery option. As hinted before: a username is actually ascii art. To generate it you simply input a key (if it's not taken), then you're profile graphic is generated. Another key for authentication password is used. NO d.o.b/age/sex bullshit.


-Donations:
Until the founders can afford off-shore bank accounts (that are neutral to INTERPOL and so forth) we should accept donations in the form of some cryptocurrency.

At somepoint use of Patreon to pay site monthly fees*

-Copyright and Piracy claims policy:
Users should be warned and expect what they post will never be deleted even if they think they own the rights. No matter how much they regret it. Fact of the EULA.


-Connection encryption policy:
HTTPS

-Message encryption policy:
For local storage of PMs, RSA is enabled. But *no* encryption of any forum messages. It would defeat the purpose of an open forum if it was all secured behind encryption.

Credit:
2238C0BA6B4A199E7CBF11B41AC38C5842D8387FBF04E2ABB7BEB7005101D231 (tox) (tox-name: jcd)
7445A650FC0110214A5E25882BE872A8ADAA6061A8BBDF0B5AFFC0185D9EE7142C1EB0F30E58 (tox) (tox-name: n/a)



