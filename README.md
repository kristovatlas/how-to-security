# how-to-security
Basic advice on how to do computer things securely for non-experts

# Table of Contents

1. [How to securely text and call your friends](#how-to-securely-text-and-call-your-friends)
2. [How to securely use free/open Wi-Fi](#how-to-securely-use-freeopen-wi-fi)
3. [How to use Tor](#how-to-use-tor)
4. [How to choose a search engine](#how-to-choose-a-search-engine)
5. [How to save your passwords](#how-to-save-your-passwords)
6. [How to come up with a password](#how-to-come-up-with-a-password)
7. [How to not get your accounts hacked](#how-to-not-get-your-accounts-hacked)
8. [More resources](#more-resources)
9. [Helpful people to follow](#helpful-people-to-follow)

## How to securely text and call your friends

Install Signal. [Download for iOS](https://itunes.apple.com/us/app/signal-private-messenger/id874139669?mt=8) | [Download for Android](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms&hl=en)

Read [this article](https://theintercept.com/2016/07/02/security-tips-every-signal-user-should-know/) by Micah Lee.

## How to securely use free/open Wi-Fi

You need a VPN service. A VPN connection will encrypt the traffic between you and a service that you trust more than the wi-fi router, which could be operated by __anyone__.

You should pay for the service rather than using a free service, so they have some accountability to you as a user.

[Here](https://www.privacytools.io/#vpn)'s  a solid list of respectable VPN services to use.
[Here](https://thatoneprivacysite.net/)'s an even more sophisticated list, with more data and advice.

## How to use Tor

Using Tor **does not make you anonymous**, but it can make specific internet activities more difficult to track and connect to your offline identity. There's a lot to learn about how to use Tor safely and protect your privacy; don't get over-confident as a beginner.

There are two pieces of software to get you on Tor:

* [Tor Browser](https://www.torproject.org/projects/torbrowser.html.en): You can install this on your existing operating system with minimal fuss.
* [Tails](https://tails.boum.org/): A hardened operating system that tunnels all traffic through Tor for all applications, and which stores no data permanently on your hard drive.

As a small number of Tor users have been [legally targeted](http://themerkle.com/fbi-can-obtain-a-warrant-if-you-run-tor-come-december/), consider connecting to a VPN before connecting to Tor so your Tor connection is less obvious to those snooping on the connection between you and your ISP. Keep in mind, however, that any website who knows your offline identity will also have a record of you connecting via Tor.

## How to choose a search engine

Google's search quality is far superior to every other search engine, but searching with them is also a privacy disaster. Consider switching to [another search engine](https://www.privacytools.io/#search), such as DuckDuckGo.

## How to save your passwords

Use a password manager to store your passwords. This will help you establish a random, long, and unique password for every single service and account you use. For beginners, I recommend [LastPass](https://lastpass.com/) -- it's simple, secure, and avaiable on both desktop and mobile devices.

## How to come up with a password

Almost every password you ever set should be randomly generated using a password manager. However, there may be some passwords that you need to generate on your own, such as the one you use to authenticate to your password manager.

You're probably really bad at coming up with good passwords, because you're a human. We have terrible intuition about what constitutes true randomness, and have a strong bias for coming up with strings that are easy to memorize rather than easy to break.

One strong option is to generate a "random passphrase." Choose 6-8 truly random words and memorize them. Although this may seem like a surprisingly small amount of information, there are so many possible words that this actually represents a lot of randomness, and will be very difficult to brute force. [Here is one online passphrase generator](https://www.fourmilab.ch/javascrypt/pass_phrase.html). For bonus points, save that page to your desktop, and open the local copy of the page in your web browser to prevent the owner of the website from snooping on your generated passwords.

## How to not get your accounts hacked

* Use a unique password for every service, generated randomly by a password manager.
* Enable two-factor authentication whenever possible. Avoid services that do not support 2FA. [Google Authenticator](https://en.wikipedia.org/wiki/Google_Authenticator) is probably the best 2FA option in terms of security and privacy.
* Evaluate the recovery process for each service you sign up for; you want to make it very difficult for an attacker to use a "password reset" or "2FA reset" process to hijack your account. If the recovery process relies on answers to recovery questions, choose questions and answers that will be difficult for an attacker to brute force or guess; such questions have many possible answers, and your answer to it will be uncommon. If the recovery process relies on receiving an SMS or email message, make sure those accounts are locked down. Every internet account is only as secure as its recovery process. (See [https://nakedsecurity.sophos.com/2016/06/14/deray-mckessons-twitter-account-hacked-with-just-his-name-and-four-digits/](this) story, for example.)
* Learn how to identify and avoid phishing attempts.

## Requests

Got other questions on security? Pitch your suggestions via Twitter to one of the contributors listed below.

## More resources

* [https://www.privacytools.io/#search](https://www.privacytools.io/#search)
* [Home Security checklist](home-security.md)

## Helpful people to follow

* Micah Lee [personal blog](https://micahflee.com/) | [twitter](https://twitter.com/micahflee)
* Steve Gibson [Security Now podcast](https://twit.tv/shows/security-now) | [twitter](https://twitter.com/SGgrc)
* Jameson Lopp [personal blog](https://www.lopp.net/) | [twitter](https://twitter.com/lopp)

## Contributors

* [@kristovatlas](https://www.twitter.com/kristovatlas)
