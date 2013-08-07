# Security Affair

> **A note from the editors:** In each installment, a new author from the W3C 
will keep you informed on what we're up to—and how you can be a part of it. This 
month's column is from Virginie Galindo, Chair, W3C Web Cryptography Working 
Group.

Apps are shifting more logic to the client, which is changing the security 
landscape. These are exciting times for the web.

The company I work for, [Gemalto][1], provides digital security solutions to 
banks, mobile network operators, governments, and corporations, all of whom are 
flocking to the web. In 2012 Gemalto became a W3C Member to help make the web a 
more secure place, stone by stone. My story, one year later, is a bit about my 
experience entering the W3C community, and also a bit about web security.

## The first date

Much W3C business is conducted online, but from time to time W3C groups meet in 
person. In October 2011, I traveled from France to Santa Clara, California, to 
attend my first Technical Plenary/Advisory Committee (TPAC) meeting, the annual 
cross-pollination of W3C groups.

It was a bit overwhelming seeing so many W3C members in person, but their 
humanity and variety of personalities put me at ease and piqued my curiosity. 
That week I met many new people, including a Viking who speaks five languages, a 
werewolf wearing a medieval costume, a friendly lawyer (yes, it happens), an 
expert on French cocktails, and a genius who speaks very rapidly. Together we 
discussed web business models, how to be friends with browser makers, keys to 
various patent wars, and more.

Around 500 people attended TPAC that year. Meeting rooms were fully packed, with
people spilling out the open doors. Any person wearing the magic W3C member
badge could freely enter, raise their hand, make a comment, and be listened to.
On my first date I fell for this smart collective of open-minded people building
an Open Web Platform.

I started thinking about the second date soon after the first. That would soon
come, and would involve more than a petite Francaise sharing her views about
security, identity, and authentication on behalf of customers and her industry.

## The heavy date

Several weeks later W3C management contacted me about chairing a Working Group
on cryptography, one of the essential pieces of web application security. Oh Mon
Dieu! (Not my true utterance. I have softened it so that young people may take
inspiration from this piece.) Chair of a W3C Working Group! After thinking about
it half a nano-second, I jumped.

Thus began a long but exciting journey into the W3C world, learning the ins and
outs of the process, meeting new colleagues, working with new collaboration
tools. And today I am chair of the Web Cryptography Working Group, with more
than 60 registered participants.

For the past year, 15–20 of us have held a teleconference every other week. I
chair the call, which takes place in the evening in France, from my quiet living
room. While children sleep nearby, the group discusses security models and APIs.
And we make progress. We don’t always agree, but we make progress, as we pledged
to do.

Our goal is for people be able to create secure web apps, and for web users to
trust apps they discover on the web. A challenge is to devise technology that
enables developers to meet very specific security needs, while at the same time
making the solution flexible and interoperable enough for the entire world.

The first piece of this puzzle is the Web Cryptography API (edited by colleagues
from Mozilla and Google). With that API, developers can perform basic
cryptographic operations within a web app such as hashing, signature generation
and verification, and encryption and decryption. Developers can also generate,
derive, or import cryptographic keying material.

The ability to generate a key suggests apps also need access to previously
generated keys. That is the purpose of our second specification, Web Crypto Key
Discovery API, edited by a Netflix colleague.

Why did we choose to represent the “generation” and “discovery” capabilities in
two specifications rather than one? Diverging interests within the group. As
Chair it is my job to avoid stalling. We found a way forward with two
specifications.

Our most recent draft of Web Crypto API was published in late June 2013. We plan
to “go to Last Call” in the last quarter of this year. Last Call means we think
we will have satisfied our technical requirements, and we will turn our
attention to implementation. But, as is often the case, implementation has begun
even at this draft stage. BBN Technologies, Netflix, and Inventive Designers
have all announced prototypes, and Google has started to implement.

## Passion and pain

When the Working Group published its first draft, we didn’t expect flowers or
chocolates, but we did anticipate some appreciation for making the web a better
place. While some in the community recognized this step forward, others were not
as enthusiastic. Some security experts showered us with criticism. Of course,
that’s less fun than a love fest, but it might be more useful.

One criticism we heard is that the solution won’t work for social reasons. (The
web is all about the intersection of technology and society, another good take-
away from the W3C community.) The API, we were told, would require web
developers to have a deep understanding of crypto in order to meet their
security needs. This would be complex and even hazardous, like a dangerous
weapon in the wrong hands.

The Working Group agreed there was some merit to the concern. As a solution, the
group suggested that developers should be able to choose between the API
initially envisioned and available, and a simpler but less powerful API — under
construction at the moment. By 2014 I expect to see drafts of this high-level
API that will act as a sort of “one-click button” to perform basic security
operations.

And so, the love affair is transforming into something more predictable. We are
making future plans together.

## Seeing other people

Fortunately, the Web Crypto Working Group is not the only W3C forum that is
discussing web security.

* The Web Application Security Working Group seeks to bind and adapt the web 
security model to today’s requirements: more control on resources (Content 
Security Policy), more controlled openness to allow mashups (Cross-Origin 
Resource Sharing — CORS, replacing the Single Origin Policy), and more trust in 
user interfaces (User Interface Safety Directives).
* The Systems Applications Working Group is investigating how the security model 
changes when you move from the browser to the web-as-platform. For instance, 
they are looking at how to give packaged web apps access to the more sensitive 
APIs that one can use within an application running in a traditional operating 
system. One example is an API that provides access to a smart card or any 
similarly secure chip located on the device. This is an area of strong interest 
to Gemalto — we want to be able to trust web apps with access to this 
information.
* If you are interested in discussions about web security but not in developing 
a specific technology, you can join the Web Security Interest Group, a mailing 
list open to all and frequented by web security experts.

The many conversations and the rapidly changing security landscape give me hope 
that the web will soon be a safer place to surf and use apps. All these groups 
have different areas of focus and recognize that what we come up with has to 
play nice together. Get involved now and tell us your security stories at TPAC 
2013.

[1]: https://www.gemalto.com/