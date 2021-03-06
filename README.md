# The Next World Wide Web
**Since the World Wide web went live a lot has changed. The web/internet are being used in ways that could never have been imagined when it was first designed. Knowing what we know now, how could it be re-designed to make use of new technologies and ideas/values that have become more important?**

> Disclaimer: This is entirely a thought experiment, there is no 
> code yet. (Hopefully soon). Also, I am in no way an expert on these
> topics - just someone that is interested in working on something
> that is exciting and makes improvements to the things I use. I
> want to hear from anyone that has opinions or expertise on the subjects I mention. 
> If I am misguided about something, please let me know! --

---------------------------------------

# Overview / TLDR
There has been some interesting initiatives lately to transform the WWW and how the internet is used. Tent.io wants to allow you to own your own social data instead of having sites like FB own it so that you are free to transfer it, download it, and more. Bitcoin wants to make a currency that does not have a central authority and spending it is as easy as sending an email. Persona wants to make it much easier to sign up/in on websites. I go into others and these in a little more depth below, but I think all of these are interesting projects that would move the web in a better direction. 

However, I wonder if adding these to the current implementation of the World Wide Web is the best thing to do. There are many things that could be improved about the web so even after one is fixed we are still left with other problems that still need to be addressed. What I propose is an alternative to the current WWW. In a few bullet points this is what I see right now (if you are interested read the rest to hopefully get a better understanding!):

* Users would be required to download a new browser (Peer-to-peer, browser). 
    * Bundled in this would be your Tent server that is easily configurable, if a digital currency was used your Bitcoin/whatever wallet, and other things. I'd like to have Tent (or something like it) built into it from the start. 
    * Any sites built on this network would just connect to that (kind of like FB connect but decentralized).
    * I don't know if this would be easier than convincing new websites on the current Web to start using Tent or not, but my hope is that since we could re-design this network we could make it more exciting for developers to develop on than the current implementation. 

* The DOM and use of Javascript/HTML/CSS etc could be analysed. What's a better way? What could be improved? I would like to have a much better way to develop apps that work well cross platform.

* There is data and how that data is viewed. To get the ball rolling on the semantic web the data has to be separate and easily accessible. Right now if you want your restaurant, for example, searchable you need to make an entire website for it. Why can't you just put the data online. 

* Not necessarily run based off domain names. I think it's time we can do away with domain names. But if that proves to be the best way still, then at least make the DNS decentralized when necessary. 

* There are common things most people use, like sending messages, liking thing, saving pages. Why do I have to go to FB to send someone a cool link. Some of these could be built into the browser.

Basically, I'd like to see the entire network re-designed now that we know essentially everything we do goes through the internet and it is being used in ways we could not have for seen. Just like when you join a society there is a money system, you get a passport etc for your identity. Why is the Internet not like that. I understand the web couldn't really break free from the laws of the real world (or could it if decentralized, p2p :p ). But I think it makes sense to include some more basic things into the system for a better experience like the ability to own your data and do with it what you wish, make easy payments, sign up easier, etc. 

So hopefully you find this somewhat interesting. And I hope you share any feedback you have here, on HN or emailing me!
 
---------------------------------------

## Problems
Here I will identify some of the problems/annoyances I currently have with the WWW or how the internet is being used.

1. Piracy
2. Payment
3. Privacy 
4. Owning data
5. Decentralization
6. Access: Logging in / Signing up / Having multiple accounts on websites.
7. Portability: HTML/CSS etc vs Flash vs whatever. Will it work on mobile? Does it work on this browser? There has to be a better method for this
8. Semantic Web
9. Spam
10. Communication: A way for devices to communicate
11. Domains: WWW, HTTP, .COM. Domain squatters, having to actually buy a domain name, we still use www etc. 

There seems to be many things that could be improved, and if the system was designed with these problems in mind, and more thoroughly thought out, I think something revolutionary would come out of it. I don't know if the answer is to continue building on top of the current implementation of the web or think of an alternative solution. 

In the following sections I will present  some ideas for an alternate WWW that would be fairly well rounded, if possible to implement, in hopes that it addresses and improves upon the issues mentioned above. Of course, I want to hear your ideas as well! 

# Details
## Background
When governments/companies can make a website inaccessible or stop payments to organizations they do not agree with, when you can not transfer your data from one service to another, when logging in to websites and creating multiple accounts for services is a pain, when people are against spending 99 cents on an app and piracy is rampant, when privacy is not something being considered deeply with many companies, when top search results are dominated by people that have gamed the algorithm and there are 14,900,000 results for the query 'who is the main character in 1984'. 

When all this is true, and I am sure you can think of more, I think it is time to re-imagine the WWW and how we can use the internet to share and display data, communicate with our friends, conduct transactions, and essentially orchestrate our entire lives in a virtual way. Since more and more things are done on the internet - and this will only increase - I think it is becoming more important to make sure we have a medium that will allow quick growth and adaptability, and be able to support and sustain the values we have. Knowing what we know now about the potential of the internet now, how we redesign it to make it more improved as we go forward into the future?

## Piracy
Although a big part of piracy is that it provides a better service than the alternative, I think another aspect of piracy is that it is not easy to pay online. It is much easier to torrent than to have to type in a bunch of Credit Card information every time you want to purchase something. I think having a currency that encourages spending, is completely digital, and most importantly very easy to perform payments, for free, with anyone, and of any amount of money, could help some of these problems. This will be discussed next.

## Payments
Paying for things is annoying. Way too much friction. Online and in life. One project that I find interesting that is, I believe, making exchanging money easier is [Bitcoin](http://en.wikipedia.org/wiki/Bitcoin). A decentralized, distributed, anonymous, digital currency. 

Few problems I have with Bitcoin:

1. There is not much regard for common users. The client is not very user friendly, being able to set up mining is not easy either. The excitement within people setting up rigs to mine for Bitcoins was fascinating and I wonder what it would be like if it was made so it was easy for everyday users to experience that same rush of being able to mine for currency. Not that it would be easy to get the money, but the process was more inviting. I have some ideas which i'll discuss later, but still not entirely sure if this is feasible. It would be interesting to see if a different mindset could be created with a new currency - one of spending. ( Maybe even give the coins a half-life to encourage spending :p ) Even the addresses - Is there a way this could be tied to an email? Not everyone has the same priorities on remaining anonymous at all times. However, in Bitcoin if you do not create a new address every time then someone could see all the transactions you have made. I am not sure if you could have both. 
2. It is great that there are no transaction costs. However, once all of the Bitcoins have been distributed it will cost a transaction fee to encourage Miners to validate the transaction. At this point the mining will be very difficult (the difficulty increases), so how much will the fees have to be to make it worthwhile? I am not sure how/if this problem can be solved and still keep the anonymity/decentralization/security of the currency in place. But I'd like to explore ideas on that because that is something that makes Bitcoin exciting, the ability to send money like you would an email!

Canada has also introduced a similar idea called [MintChip](http://en.wikipedia.org/wiki/MintChip). They have an improvement that transactions are instant, but they have other issues, such as that the security of the system depends on the security of the hardware. 

## Owning Data
I think there are some interesting initiatives in this area: [Tent.io](http://tent.io/) (open, decentralized social networking), [App.net](http://app.net) (open, centralized service) and [OStatus](http://ostatus.org/) (Similar to Tent) and [Diaspora](https://joindiaspora.com/), [Ampify](http://ampify.it/planfile.html) (Just found out about this but seems interesting).

So much of what we do is social I think it's important to start thinking how our data is used and who has control of it. Are we really ok with not being able to transfer our data - messages, pictures, friends - to another social network if the other one loses our trust or shuts down? How about if we could not take our money from a bank and move it to another? Not as extreme, but as more and more things are done online, and the things we share will essentially exist forever, I would like to have some control on how that is used and who can use/see it.

An interesting point from the OStatus project: "On the Internet, it is THEM who maintain databases with our data, and it is THEM who force us to click on "I agree" buttons with complicated legal texts, before we can do anything useful. **Why shouldn't it be the other way round? Why shouldn't it be US who make companies agree to the terms of service that WE define**, and why shouldn't it be US who have a database where we manage these relationships?"

The idea is simple: essentially, instead of Facebook having all your messages, posts, friends etc you would store this on a 'Tent server' (or whatever project is used. And on your own computer, or a hosted one, think email). Now when a new app comes along, say Facebook, and they want your relationships, images and posts they would essentially access that data via an API to your data server. This gives you the ability to transfer your data at will and chose what data sites can access, see what data certain websites have on you, add data once to the data server and have it shown in all the apps that want that data, etc etc.

What I really like about Tents plan (I have no connection to Tent - just really impressed with what they are doing and they are relatively new).

1. Users take their content/relationships with them. Why can't I instantly transfer all my FB data to another service (Obviously not good for FB, but we'd likely see some more competition).
2. Plan to be a secure login replacement. (This addresses my annoyance I talk about in "Access").
3. Extensible data types: After Tweets there may be Beeps. Tent can handle that. Anyone can create a new data type to store in the server.
4. You have control of your data and who you want to be able to see that data and what they can do with it. Want historians to be able to analyze your data in the future? Nice! Want FB to only have pictures you think are professional but John to see everything? No problem. Had enough FB and want to move to Google+? Easy, disallow FB from accessing your data and give G+ permission.
5. "Imagine if you could only email other customers of your Service Provider". Tent address this. And I think this is important.  

I am sure we will see mostly hosted solutions for this (like email) but it would be nice if there was a way for everyday users to easily set this up. This will be discussed a bit in "Altogether Now".

## Decentralization / Distributed
The web is decentralized, but some of the important services run on it are not. For example, DNS and payments. A truly beautiful web would have more aspects decentralized. Another thing, servers can get shut down (Megaupload, etc) and then all the users could lose their content. Or a website owner may take a website down and now all of that information is not available. If there was a more simple representation of the data, then it could be backed up more easily, and maybe with a peer-to-peer network the storage of it could be distributed - impossible to remove. Something similar to Tor where the DNS (to my knowledge) is distributed among the network.

## Access
Having to create new accounts by typing the same information over and over. Oh and if I want multiple accounts for some service I get an error saying I have already used this email before so I have to create another gmail account. Unless I forward the emails I have to log out every time to check the emails for different accounts. I can see how a system like Tent could fix this (And maybe even the Bitcoin protocol? instead of it being like Persona where it uses your email, it uses the Bitcoin protocol). All sites will use an oath to allow you to log in. Similar to FB login, but would have the benefit of not being owned by a company. Not only that, but you would be able to instantly see all the sites you have signed up for, and what data they have. Also, the ideal system would put an end to CAPTCHA.

Something interesting that just popped up is [Persona](http://identity.mozilla.com/post/32395255498/announcing-the-first-beta-release-of-persona). 

## Portability
Will this website work on older browsers? Need to throw in some hacks to make it work. Will it work on mobile? These are all really annoying questions and make it harder for developers to make amazing things. Im not sure what the answer to this is (but even something that made it a little bit easier would be awesome). Maybe the future is something like Microsoft is doing where the apps all work the same on tablet/PC/phone? But the thing is you don't use your PC the same way as you do your tablet, etc. Another markup language that could make it all more fluent? HTML5? A higher level language that can be more expressive that is designed with different display types in mind? I am not really sure, but I know this is no fun.

## Semantic Web
**This is taking a long time!!!**

Seriously. (And this would enable something so much more exciting than the web already is - so many possibilities).

I understand this is hard to solve, and requires some AI that we are not at the point of yet. There are proposals (RDF etc). But these just make it harder on the developer. Now instead of doing basic HTML everything must be marked up semantically too (Here I would like to explore a new language that is higher up that would provide the ability to markup and semantically tag things very intuitively). Couple ideas:

1. Allow users to markup pages. Built into the browser? This would make it easier for people to mark things up instead of having to type it in.
2. Forms to fill in. Say you have a restaurant, you can fill out a form with information about your restaurant and it would give you some tags to paste in the HTML or if you were not making a website would just distribute the data so that it is able to be searched and then others could present it how they want. 

We could identify a list of the most common things on the web: Store, Restaurant, School site, Blog, App, Paper, Photo, etc and have a set of default questions to answer for this.

Current AI is not at a place where it can be done automatically (from my experience) but it could be used to complement these solutions. (It could see general patterns for certain types and recognize them on new websites, so even if the website changes it can still understand the semantics behind it).

Basically, what if certain data was entered via form or some way to get semantics from it. Then the developer accesses that via an API to display it however they wanted on their website. (The data could be entered into their Tent (or whatever) server. So basically there would be text in a semantic form (JSON or something), and then it could be displayed however. Different websites could take the same data and just display it differently.

Again, I think something that could help this is a higher level language that could abstract more complexity away. Creating all the HTML to show an item on a menu could be changed with menu_item(:price => $10.00, :name => 'Steak'...). This would output some HTML that you could then change the view of via CSS (or something better than that too!).

I want to be able to type in "Schools in Canada that offer a dual degree in Computer Science and Biology" or some other gibberish and see answers that match that query. Think WolframAlpha but more useful for everyday use.

Some interesting discussions/articles on this topic:

* [Why I hate search](http://news.ycombinator.com/item?id=3801956).
* [Ask HN: do you feel Google search result quality has gone down?](http://news.ycombinator.com/item?id=902999).
* [What I Want in My New Google](http://techcrunch.com/2011/02/19/what-i-want-in-my-new-google/).
* [Things Not Strings -- Google Launches Knowledge Graph](http://news.ycombinator.com/item?id=3982887)

## Spam 
So much of the internet is junk. I don't even think it would take that much time to transfer the Web to a better system, we'd need maybe 20 websites :p. Search engine results are only decent. I don't think we will really see much improvement until something like the Semantic Web is realized. Google is making attempts. I type in "who wrote 1984" and it tells me the answer, along with a billion other links. YAY! Many of which are identical. Can we apply DRY to the entire WWW? Furthermore, how many people have "Wedding Crashers" saved on their computer. Is there a streaming P2P system? That is the exciting thing about the cloud. As long as streaming is fast, and always connected to the internet (basically here) you don't have to download anything!

## Communication
As more and more things become connected to the internet it needs to be easier for them to communicate with each other in a secure way. Maybe my fridge one day will know what I have left (and then have that delivered automatically). I don't know if there is a protocol that makes this easy, and is also really extensible. I expect eventually we will be able to receive messages from parts of our body. (instantly know of any sickness, ohh you just got the perfect amount of sleep let me slowly turn your alarm on, etc). I am really interested in the idea of quantifiable self (tracking data about yourself - sleep, exercise, etc etc) and then being able to visualize that data and extract knowledge from it. 

## Domains
A few things annoying in this category.

1. Domain Squatters.
2. DNS not decentralized (NameCoin is an interesting project working on this).
3. Why do we still use http://, www., or even have domain names. (I know why we use them now. But can a better, more clean system be imagined).

Mobile services have solved this with Apps. Anyone can have an app called 'XYZ'. (I think?, unless copyrighted). But the most popular one appears higher in search results, etc. A new one becomes more popular, it naturally becomes the App for that name. However, Apps suck at linking. Since there are no URLs how can you link to things, or other apps. So maybe the best solution for that is the current way, or can we have both. We are encouraged to hide things like .php, so how about hiding www., http://, etc. Maybe a cleaner implementation wouldn't serve much further benefit. But the only time we enter the full URL is when someone sends a link to us. Domain names are getting so weird and there are so many TLD now you can't keep track of them anyways - you just Google. 

One alternative to that is a Content-centric network. "Its founding principle is that a communication network should allow a user to focus on the data he or she needs, rather than having to reference a specific, physical location where that data is to be retrieved from.": [Content-centric networking](http://en.wikipedia.org/wiki/Content-centric_networking). So something like this could perhaps be used for a new way instead of having to use HTTP://, www etc.

* [Content addressable network](http://en.wikipedia.org/wiki/Content_addressable_network).
* [Distributed Hash Table](http://en.wikipedia.org/wiki/Distributed_hash_table).

## Other interesting things.
### Voting Online
Politics in general is a mess. Maybe allowing people to be able to vote online could help? A project that uses the Bitcoin protocol to assist with this is at: 
[CommitCoin](http://people.scs.carleton.ca/~clark/projects/commitcoin/)
Ultimately a new country should be started and everything should be re-thought and reimplemented from the ground up. But that's next.

### Alternatives to Hypertext
I have been reading recently about [Project Xanadu](http://en.wikipedia.org/wiki/Project_Xanadu) by Ted Nelson. His idea before the current WWW we use are interesting. He says: "HTML is precisely what we were trying to PREVENT— ever-breaking links, links going outward only, quotes you can't follow to their origins, no version management, no rights management". I am thinking a new language could be designed to keep simplicity and allow it to be easily adapted but provide more powerful features like the ones Xanadu suggested. (ex: transcluded text: when the original source changed, the transcluded text in the other document would also change, etc).

## Altogether Now
So I have outlined some of the annoying things about the Web and provided a few suggestions here and there. In this section I want to just write a bit about what I see being the 'future' and how in a nutshell these things could be brought together for a all around solution. 

I have talked a lot about Bitcoin, Tent, peer-to-peer and related technologies. I think going forward these ideas and the others I have talked about will be more important. In order to get to a more semantic web and a more connected world, we need to be able to easily access the data. What I see is a completely new system that's main goal is to take all of these problems (and more) very seriously, and design a system that is easy to use (both for user and developer), built to scale and be adaptable to change. 

What I think would be interesting is to combine Bitcoin (or whatever digital currency is used), Tor network (or similar), Tent (or something else), BitTorrent and a browser into a sort of bundle. Once installed you would have a user friendly dashboard to manage everything. For example, you would manage your open data server here so you could see all your friends, messages, emails, bookmarks, websites you have signed up for, classes you have completed, anything. Basically this would be your history of what you have done on the internet (maybe not only things on the web). And any site can access certain information if you give them permission. You would also have your Bitcoin wallet and be able to pay anyone anywhere. (Hopefully) instead of a cryptic address we could have a decentralized name server to store a user friendly name for people that wish so you could send money to an email, like paypal. So when you installed this you would not need to set up a 'Tent' server as it would already be built in. (I am not sure how Tent handles it when the users Tent server is off? - Would there be a way to essentially distribute it throughout the P2P network and still keep it secure if it needs to be used when a users computer is off? Probably not, but maybe that's not necessary). Of course having back ups is important, so things like gmail could be in place to store your data (which would solve the previous problem).

What I would like to see from a digital currency is the opportunity for more people to be able to earn currency off of it (Not just technical people). Bitcoin already distributes the money to people that help out the network because the miners verify transactions. Perhaps a system could be in place that gave currency to people that did this but also contributed to keeping our system anonymous like Tor, donated bandwidth or hard drive space or CPU time to help out important projects. Of course all these seem to give favour to people with lots of processing power. Giving everyday users the opportunity to be as excited as the people mining for Bitcoins could be interesting. And then if people were able to actually buy things with that online! Or, why base the currency on a pretend limited resource - we already had that, it was gold. Instead can we use something more enlightened. People who are helpful to the system, people who donate time to beneficial projects, people who educate themselves and complete a course on Coursera get money :p I admit do not know much about Economy and all it entails, but I like the idea that in order to get money you have to benefit your community/system or yourself (in turn benefiting the community) and not some random rock that we agreed was valuable or like the currency system now that is based off of debt/trust in the government. (Now we no longer have the gold standard, the value is more so trust in the government, etc). Also, instead of having the currency stop being distributed would it be possible to somehow monitor the activity of the currency and how it is being used and distribute according to that? I'm not exactly sure how this could be implemented, but having all the systems integrated would be the first approach to be able to achieve this if it were possible. I know that is one complaint of Bitcoin that it can't adjust to inflation etc, but the Bitcoin network knows every transaction, so it could react to that and distribute coins following some mathematical guide.

So all of this would be hosted and running instantly (ideally) when the software is installed. Apps could be added to this. Maybe an easy way to set up a website, a browser to access the old, crappy WWW, etc. I think combining all these together makes sense because then the entire experience of the web would fit together as these are things more and more people are using - a more seamless experience. I also think incorporating AI into the browser to make them more helpful could be interesting. Browsers really suck - from bookmarks, finding things you earlier looked at. If AI could be implemented in the browser some interesting things could be done with that.

I think integrating into the software that is used to browse the new web things like sharing, commenting, bookmarking/saving (but one that does not suck), annotating for semantics, donating, and other things that are basically a given or may with time become useful. So instead of seeing "LIKE THIS" or "TWEET THIS", on every page we can have that on the browser when you need it. And when you see something you like you could instantly share it with people instead of opening up FB to share it with Bob then opening up email to share it with your mom. Since the browser would know your friends contact information (Through the open data server. Also people could specify that they prefer to receive things via FB, email in their data server dashboard), all you would have to do is click "Share with Bob" and it would go to whatever service he would like it to go to that.! 

Perhaps another room for improvement is that many programming languages were not developed with the Web in mind and browsers were not designed to understand any language besides JS.

Obviously this is not fully thought out yet, and there are many ways to take it and one must go into more depth on each of these and get more technical, but I thought maybe some would think this is interesting with all the recent discussions on Tent, App.net, OStatus, Twitter changing policies, FB being Fb, and earlier discussions about Google sucking.

This is the next stage in terms of the Web and the internet (likely not exactly as described, but the overall ideas), it is all a matter of how we get there. And are the current technologies the correct technology to get us there? 

## Conclusion
I know this just looks like a bunch of complaining with no solutions. The Web is awesome, and these are just some things I think would improve it. I'd love to work on something like this. Obviously this is a huge project if it were all undertaken and not something I could ever do alone. If you are interested, check out the contact section! If this is something worth perusing I would like it to be done well. Experts on any subject or anyone that uses the web, I would like to hear comments and things they would like to see. I have no doubt that there are many more ideas that are far more thought out than mine (I just began thinking this out!). 

Hope you enjoyed reading it!

## What Next?
I would really like to explore this further. I am currently in school, but done in December. After that I am looking to start working on interesting things and learning more everyday. I hope with this I can meet some interesting people that are doing fascinating things. I think this would be an interesting project to work on, but it is not something I am able to do alone with my current expertise. So if you are interested please message me, and we can talk further, and if it gets to the point where it is better thought out and a plan is ready, it could be a neat project to put on Kickstarter, or Selfstarter!

---------------------------------------

## CONTACT
You can email me at: me@jonovono.com or send me a tweet at [@Jonovono](https://twitter.com/Jonovono).

If you are interested in talking about this further, have ideas/questions/extra information, please contact me!

---------------------------------------

# Interesting Projects / Related Projects / etc
Here is just a list of some of the stuff I have talked about and other projects that are doing a lot. Just a nice reference that I will keep updated.

* [WWW Source Code](http://browsers.evolt.org/?dir=archive/worldwideweb/NeXT).
* [Naming Things With Hashes](http://news.ycombinator.com/item?id=4632045)
* [git-annex](http://git-annex.branchable.com/): git-annex allows managing files with git, without checking the file contents into git. Git for large files!

## Content Centric Network
* [CCNx](http://www.ccnx.org/). "Project CCNx® exists to develop, promote, and evaluate a new approach to communication architecture we call content-centric networking.  We seek to carry out this mission by creating and publishing open protocol specifications and an open source software reference implementation of those protocols.  We provide support for a community of people interested in experimentation, research, and building applications with this technology, all contributing to its evolution."
* [CCNx Haskell](https://github.com/tomahawkins/ccnx): A Haskell platform for experimenting with content centric networking.

## Distributed
* [Freenet](https://freenetproject.org/)
* [Why is p2p web hosting not widely used?](http://stackoverflow.com/questions/737560/why-is-p2p-web-hosting-not-widely-used)
* [Google Chrome Web server](https://github.com/GoogleChrome/chrome-app-samples/tree/master/webserver) Have a web server in your browser. Something like this could be useful. 
* [Browserver](http://news.ycombinator.com/item?id=4366555): A Nodejs HTTP server in your browser.
* [Distributed Social Network](https://github.com/gelnior/newebe).
* [Boinc](http://boinc.berkeley.edu/): Use the idle time on your computer to cure diseases, study global warming, discover pulsars, and do many other types of scientific research. It's safe, secure, and easy:
* [Telehash](http://www.telehash.org/): A new wire protocol enabling applications to connect directly in a real-time and fully distributed manner, freeing them from relying on centralized datacenters
* [MediaGoblin](http://mediagoblin.org/): MediaGoblin is a free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc
* [Pastry](http://news.ycombinator.com/item?id=4676505): A distributed hash table in Go
* [CloudHaskell](https://github.com/jepst/CloudHaskell): A distributed computing framework for Haskell
* [Anynet](https://github.com/ssiloti/Anynet): Content Centric P2P network

## Social
* [Tent.io](http://tent.io/) 
* [Project comparison of some social projects](http://gitorious.org/social/pages/ProjectComparison)

## Bitcoin / Digital Currency
There may be some that do not have a limit on the amount of coins that will be generated.

* [Bitcoin](http://bitcoin.org/)
* [GeistGeld](http://www.geistgeld.org/): 15 Second blocks
* [SolidCoins](http://solidcoin.info/): 2 minute blocks, there isn't a limit on how many coins will be generated, CPU friendly, difficulty is adjusted more often, close-source. 
* [LiteCoin](http://litecoin.org/): their blocks are generated every 2.5 minutes, and their hashing algorithms are more CPU-friendly (mining with graphic cards doesn't work well with those).
* [NameCoin](http://dot-bit.org/Main_Page): coinage used as a distributed naiming system blockchain. Their most notable feature is that they can be merged mined with Bitcoins.
* [TimeKoin](http://www.timekoin.org): Controlled by time.
* [TimeCoin](http://www.timecoin.net/)
* [Is it possible for a decentralized currency to have untraceable transactions?](http://bitcoin.stackexchange.com/questions/5088/is-it-possible-for-a-decentralized-currency-to-have-untraceable-transactions)

* [Another list of currencies, financial crypto](http://disattention.com/78/digital-currencies-crypto-finance-and-open-source/)
