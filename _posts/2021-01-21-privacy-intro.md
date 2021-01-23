---
title: 'Reset Your Privacy Settings'
date: 2020-01-21 00:00:10
description: Going to do a series of articles on internet privacy...starting here 
featured_image: '/images/chicago640.png' 
categories: privacy layout: post
---

Over the last few years, I have allowed more and more technology companies into my day-to-day life. Initially, it was
Google for mail and search, then it was social media, then it was IoT gadgets (
such as alexa or internet connected light bulbs or security cameras). Whereas 15 years ago, I maybe had two or three
devices hooked up to my router, now I have over 20. This trend doesn't seem to be slowing down, and I recently heard the
term "Everything as a Service" for the new business model going forward.

With every new service or device I brought into my life, I abdicated some portion of my privacy to these companies. Many
of these companies use this data to drive advertising revenue (I spent 8 years working as a technologist at an ad-tech
company, so I know how the sausage is made). I've been spending quite a bit of time over the last few months trying to
wrangle back some semblance of privacy and control over the data that is my own.

I'm going to write a series of articles going over specific services and how and why you should disconnect from them (or
at least use them smartly as to protect your privacy).

## Principles for Internet Privacy

My guiding principles for internet privacy are:

1. The aphorism "**If you don't pay for the product, you are the product**" is my touchstone. Generally you should be
   cognizant of how technology companies make money before you use their services.
2. For communication, **use encrypted services**, and assume any other form of communication is public.
3. **Assume all internet-connected devices with a microphone or camera can listen in on you**.
4. **Assume all internet-connected devices with a GPS can track your location and transmit to 3rd party.**
5. **Own your own data**. This isn't really a privacy issue exclusively, but sits at the nexus between privacy and
   security and business sense.

## A Brief Overview of How We Got Here

In the wild-west days of the internet, there were two major ways that you were tracked by advertisers and other data
gatherers: third-party cookies and beacons. Cookies are pieces of information that are set by a website on your browser.
First-party cookies are cookies that are set and used by the same website. They are generally needed to make most
websites function. Third-party cookies are set by advertisers and other vendors when you visit a website. Third-party
cookies allow advertisers to track you as you go to other websites that also have their code embedded on their websites.
So an advertiser could know that you went to Gap, Zappos, Nordstrom. They could know that you looked at shoes, and added
them to your cart. They could then use that information to target you for advertisements about shoes.

Most modern web browsers either no longer support First Party cookies (such as Firefox, Brave, or Safari) or are
beginning to phase out this ability (such as Chrome). So this way of tracking you is on the outs.

Whereas cookies are used to track behavior in web browsers, "pixel beacons" are predominantly used to track behavior in
emails. How does it work? A company wants to know if you read their email. So they send you an HTML email with a link to
an image that is hosted by the advertiser. Sometimes this image is invisible and sometime it is just part of the email.
This image is given a unique identifier so that identifies that image to the specific email sent to you. When you open
the email, it downloads the image, and the advertiser knows you opened the email.

Most email clients have the ability to "Turn Off Remote Content". Sometimes this makes the emails look a little rough
but it gives you a lot more privacy (and allows you to see how often publishers engage in this activity - if they really
just wanted to use images, they could embed them in the message so that they would not need to be remotely downloaded).
When given a choice, I always opt for text-based emails vs. HTML emails.

## Modern Tracking

Since most of the old ways of tracking you are being phased out, how are companies tracking your behavior in the modern
world?

### Social Media Walled Garden

A "walled garden" is a place where all information is self-contained. The biggest of example of a walled garden is
Facebook. To participate with Facebook you have to be a member. Facebook makes most of its money from ad revenue, and
they have amazingly relevant ads. The reason their ads are so relevant is that they know an amazing amount of
information about you. Without considering other sources, consider what they know just from within their walled garden:

* Basic personal information (email, location, who you're married to, what you look like, etc)
* Who your friends are
* Your political affiliation
* What articles you liked
* What groups you're in
* What restaurant pages you've viewed
* When events you're attending
* Who you've muted
* What ads you've clicked on
* All your pictures
* Who you talk to on their messenger

### First Party Data

If I run a marketing department at a Movieflix, and I want to target my customer on Facebook/Instagram/etc. with ads how
do I do that? The key currency here is you're email. Since an email is a somewhat private thing, Movieflix will "
anonymize" your email by applying a hash function, so `joebob@movieflix.com` will
become `012345678901234567890123456789`. They will include that user with the rest of the users they want to target, and
upload those to Facebook. Facebook also knows about a user with the hash  `012345678901234567890123456789` and it will
show them the Movieflix ad on their wall.

In reality, it's much more complicated than that. But the key thing to note here is that this can't really be stopped by
clearing your browser cookies or preventive measures in your email client. This is a website you interact with sharing
your data (something you probably agreed to when you signed up for that website). The only way to stop it, is to stop
using either the website or Facebook.

One way you can minimize first-party data sharing is by having separate emails for each service (or at least Facebook,
Instagram, Twitter, Snapchat, etc), but that can be tedious.

There are a whole bunch of sites that leverage first party data in this way:
* Media Streaming companies
* Video game companies
* Shopping Sites
* IoT companies
* Basically any company that has data about you, something to sell, and identifying information about you.

## Third Party Ad Networks

There is an entire market out their for people selling ID that are associated with market segments.  Nasty Nasty Stuff.

