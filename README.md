# The World Wide Web
**Since the WWW went live a lot has changed. The web/internet are being used in ways that would never have been imagined back then. Knowing what we know now, how could it be redesigned  to make use of new technologies, and ideas that have become more important?**

> Disclaimer: This is entirely a thought experiment, there is no 
> code yet. (Hopefully soon). Also, I am in no way an expert on these
> topics - just someone that is interested in working on something
> that is exciting and makes improvements to the things I use. I
> want to hear from anyone that has opinions or expertise on the subjects I mention. 
> If I am wrong/mistaken about something, please let me know! --

## Problems
Here I will identify some of the problems currently. Obviously some would not directly be fixed by re-imagining the web.

* Piracy
* Payment: (paying for things sucks. Whether on mobile, on the browser, or in real life). I think this is related to piracy as well.
* Privacy 
* Owning data
* Decentralization
* Access: Logging in / Signing up / Having multiple accounts on websites = a huge pain
* Portability: HTML/CSS etc vs Flash vs whatever. Will it work on mobile? Does it work on this browser? There has to be a better method for this
* Semantic Web (This is taking way too long)
* Spam
* Communication: (A way for devices to communicate)
* Domains: WWW, HTTP, .COM. Domain squatters, having to actually buy a domain name, we still use www etc. 

There seems to be so many things that could be improved if it were more thought out. I don't know if the answer is to continue building on top of the current implementation of the web or think of an alternative solution. 

In the following sections I will present  some ideas for an alternate WWW that would be fairly well rounded, if possible to implement, in hopes that it addresses and improves upon the issues mentioned above. Of course, I want to hear your ideas as well! 

# Proposal
Alright, lets begin. Here you will find some random thoughts I have been having. 
## Background
**Frustration**

When companies can persuade the 'removal' of websites, when you can not transfer your tweets/friends to another service etc, logging in to websites and creating multiple accounts for services is a pain (this email has already been used), when people are against spending 99 cents on an iPhone app and piracy is rapant, when privacy is not something being considered deeply with many companies, when top search results are dominated by people that have gamed the algorithm and more so when there are 14,900,000  results for the query 'who is the main character in 1984'. 

When all this is true, and much more, I think it is time to re imagine the WWW and how we can use the internet to share and display data, communicate with our friends, conduct transactions, and essentually conduct our lives in a virtual way. Since more and more things are done on the internet  I think it is time to re-imagine how it can be used knowing what we know now after using the internet for so long. 

## Piracy
Although a big part of piracy is that it provides a better service than the alternative, I think another aspect of piracy is that it is not easy to pay online. It is much easier to torrent than to have to type in a bunch of CC information every time you want to purchase something. I think having a currency that encourages spending, is completely digital, and most importantly simple to perform payments, for free, with anyone,  could help some of these problems. This will be discussed next.

## Payments
Paying for things is annoying. Way too much friction. Online and in life. One project that I find interesting that is, I believe, making exchanging money easier is [Bitcoin](http://en.wikipedia.org/wiki/Bitcoin) project. A decentralized, distributed, anonymous, digital currency. 

Few problems I have with Bitcoin:

1. No regard for common users. The client is not friendly to your common user, being able to set up mining is not easy either. Money is awesome, and a crazy motivator. I see everyone getting so into Bitcoin mining, setting up rigs, and wonder what if it was made so it was easy for common users to experience that. Not that it would be easy to get the money, but the process was more inviting. I have some ideas which i'll discuss later, but still not entirely sure if this is feasible. Ultimately, i'd like to see people unafraid to spend this as it is essentially their online currency. ( Maybe even give the coins a half-life to encourage spending :p ) Even the adresses. Is there a way this could be tied to an email? Not everyone would be ultra worried about being anonymous. 
2. It is great that there are no transaction costs. However, once all of the Bitcoins have been distributed it will cost a transaction fee to encourage Miners to validate the transaction. At this point the mining will be very difficult (the difficulty increases), so how much will the fees have to be to make it worthwhile? I am not sure how/if this problem can be solved and still keep the anonymity/decentralization/security of the currency  in place. But I'd like to explore ideas on that because that is something that makes Bitcoin exciting, the ability to send money like you would email!

There are other things that could be improved, but these are the main ones for now.

Canada has also introduced a similar idea called [MintChip](http://en.wikipedia.org/wiki/MintChip). This is the future of money.

## Owning Data
I think there are some interesting initiatives in this area: [Tent.io](http://tent.io/) (open, decentralized social networking) and others.

So much of what we do is social. Tweeting, texting, FBing, whatever is next. 

So essentially, instead of Facebook having all your messages, posts, friends etc you would store this on a 'Tent server' (your own computer, or a hosted one, think email). Now when a new app comes along, say Facebook, and they want your relationships, images, posts, they would essentially access that data via an API to your Tent server. This gives you the ability to transfer your data at will, see what data FB has on you, add data once and have it shown in all the apps that want that data, etc etc.

What I really like about Tents plan:

1. Users take their content/relationships with them. Why can't I instantly transfer all my FB data to another service (Obviously not good for FB, but we'd likely see some more competition).
2. Plan to be secure login replacement. (This address Access above).
3. Extensible data types: After Tweets there may be Beeps. Tent can handle that.
4. You have control of your data and who you want to be able to see that data and what they can do with it. Want historians to be able to analyze your data in the future? Nice! Want FB to only have pictures you think are professional but John to see everything? No problem. 
5. "Imagine if you could only email other customers of your Service Provider". Tent address this. And I think this is important. 

Something like this must happen. Hopefully it is really easy to set up a Tent server. I am sure, however, we will most likely see hosted solutions like email where you have a dashboard to your data and can easily download it.

## Decentralization / Distributed
The web is centralized, but some of the important services run on it are not. For example, DNS and payments. A truly beautiful web would have more aspects decentralized. Another thing, servers can get shut down (Megaupload, etc) and then all the users would lose their content. Or a website owner may take a website down and now all of that is not available. If there was a more simple representation of the data, then it could be backed up more easily, and maybe with a peer-to-peer network.

## Access
I talked about this in Owning Data. But this is something that annoys me on a daily basis. Maybe there is a better way to do things. But having to create new accounts by typing the same information over and over, if I want multiple accounts I get an error saying I have already used this email before so I have to create another gmail account. Unless I forward the emails I have to log out every time to check the emails for different accounts. I can see how a system like Tent could fix this. All sites will use an oath to allow you to log in. Similar to FB login, but would have the benefit of decentralization. Not only that, but you would be able to instantly see all the sites you have signed up for, and what data they have. Also, hopefully provide a solution to CAPTCHA.

## Portability
Worrying if it will work on older browsers, need to throw in some hacks to make it work, will it work on mobile. Im not sure what the answer to this is. Maybe something like Microsoft is doing where the apps all work the same on tablet/PC/phone? But the thing is you don't use your PC the same way as you do your tablet, etc. Another markup language that could make it all more fluent? HTML5? A higher level declarative language. I am not really sure, but I know this is no fun.

## Semantic Web
**This is taking way too long!!!**

Seriously.

I understand this is hard to solve, and likely requires some AI that we are not at the point of yet. There are proposals (RDF etc). But these just make it harder on the developer. Now instead of doing basic HTML everything must be marked up semantically too. Couple ideas:

1. Allow users to markup. Built into the browser? This would make it easier for people to mark things up instead of having to type it in.
2. Forms to fill it. Say you have a restaurant, you can fill out a form with information about your restaurant and it would give you some tags to paste in the HTML.

Current AI is not at a place where it can be done automatically (from my experience) but it could be used to complement these solutions.

Basically, what if certain data was entered via form or some way to get semantics from it. Then the developer accesses that via an APi or something to display it however they wanted on their website. (The data could be entered into their Tent (or whatever) server.

Again, I think something that could help this is a higher level language that could abstract more complexity away. Creating all the HTML to show an item on a menu could be changed with menu_item(:price => $10.00, :name => 'Steak'...). This would output some HTML that you could then change the view of via CSS (or something better than that!) 

## Spam 
So much of the internet is junk. I don't even think it would take that much time to transfer the Web to a better system :p. Search engine results such. I don't think we will really see much improvement until something like the Semantic Web is realized. Google is making attempts. I type in "who wrote 1984" and it tells me, along with a billion other links. YAY! Many of which are identical. Can we apply DRY to the entire WWW? 

## Communication
As more and more things become connected to the internet it needs to be easier for them to communicate with each other in a secure way. Maybe my fridge one day will know what I have left. (and then have that delivered automatically). I don't know if there is a protocol that makes this easy, and also really extensible. I expect eventually we will be able to receive messages from parts of our body. (instantly know of any sickness etc, ohh you just got the perfect amount of sleep let me slowly turn your alarm on). I am really interested in the idea of quantifiable self (tracking data about yourself - sleep, exercise, etc etc) and then being able to visualize that data and extract knowledge from it.

## Domains
A few things annoying in this category.

1. Domain Squattors.
2. DNS not decentralized (NameCoin is an interesting project working on this).
3. Why do we still use http://, www., or even have domain names. (I know why we use them now. But can a better, more clean system be imagined).

Mobile services have solved this with Apps. Anyone can have an app called 'XYZ'. (I think?, unless copyrighted). But the most popular one appears higher in search results, etc. A new one becomes more popular, it naturally becomes the App for that name. However, Apps SUCK at linking. Since there are no URLs how can you link to things, or other apps. So maybe the best solution for that is the current way (hmmm). We are encouraged to hide things like .php, so how about hiding www., http://, etc. Maybe a cleaner implementation wouldn't serve much further benefit. But the only time we enter the full URL is when someone links us. Domain names are getting so weird and there are so many TLD now you can't keep track of them anyways - you just Google. 


## Other interesting things.
### Voting Online
Politics in general is a mess. Maybe making people able to vote online could help? A project that uses Bitcoin to assist with this is at: 
[CommitCoin](http://people.scs.carleton.ca/~clark/projects/commitcoin/)
Ultimately a new country should be made and everything should be re-thought and reimplemented. But that's next.

### Alternatives to Hypertext
I have been reading recently about [Project Xanadu](http://en.wikipedia.org/wiki/Project_Xanadu) by Ted Nelson. His idea before the current one we use is interesting. He says:  "HTML is precisely what we were trying to PREVENT— ever-breaking links, links going outward only, quotes you can't follow to their origins, no version management, no rights management". I am thinking a new language could be designed to keep simplicity and allow it to be easily adapted but provide more powerful features like the ones Xanadu suggested. (ex: transcluded text: when the original source changed, the transcluded text in the other document would also change, etc).

## Altogether Now
So I have outlined some of the annoying things about the Web and provided a few suggestions. Here I want to just write a bit about what I see being the 'future'. 

I have talked a lot about Bitcoin, Tent, peer-to-peer and related technologies. I think going forward these ideas and the others I have talked about will be more important. In order to get to a more semantic web and a more connected world, we need to be able to easily access the data. What I see is a completely new system that's main goal is to take all of these problems (and more) very seriously, and design a system that is easy to use, built to scale and be adaptable to change. 

What I think would be interesting is to combine Bitcoin, Tor network, Tent, BitTorrent and a browser into a sort of bundle. (Forgive me if this is just ridiculous, I have not thought about how it would all work out completely!). So you would have a very user friendly dashboard. Here you could manage your Tent (or however open data is managed). So you could see all your friends, messages, emails, bookmarks, websites you have signed up for. Basically this would be your history of what you have done on the internet. And any site can access certain information if you give them permission. You would also have your Bitcoin wallet and be able to pay anyone anywhere. (Hopefully) instead of a cryptic address we could have a decentralized name server to store a user friendly name for people that wish so you could send money to an email, like paypal. 


This is the next stage in terms of the Web and the internet, it is all a matter of how we get there. And are the current technologies the correct technology to get us there? 

## Conclusion
I know this just looks like a bunch of complaining with no solutions. The Web is awesome, and these are just some things I think would improve it. I'd love to work on something like this. If you are interested, check out the contact section! If this is something worth perusing I would like it to be done well. Experts on any subject or anyone that uses the web, I would like to hear comments. I have no doubt that there are many more ideas that are far more thought out than mine (I just begun thinking this out!). This was longer than I expected, and I did not go into full detail.

## Contact

