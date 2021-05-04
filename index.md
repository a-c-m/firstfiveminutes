title: [FirstFiveMinutes.club]
description: [give the first 5 minutes back]
show_downloads: ["false"]
google_analytics: [Your Google Analytics tracking ID]
---

![sharescreen](https://user-images.githubusercontent.com/105557/116999002-f3e85300-acd6-11eb-886a-369229f73c57.png)

# FirstFiveMinutes.club

*The idea here is simple, when you start your meeting, give the first 5 minutes back.*

That's it. Join the #FirstFiveMinutes club!

## 4 Simple Steps

1. Schedule your meeting as normal
2. Share your screen, load [this image](https://user-images.githubusercontent.com/105557/116999002-f3e85300-acd6-11eb-886a-369229f73c57.png), then mute yourself
3. Use the 5 minutes you now have to improve your well being
4. Un-mute and have great meeting

## Why
- Back to back meetings happen
- [Meeting fatigue](https://support.microsoft.com/en-gb/office/reduce-meeting-fatigue-f44be8a1-1bb4-4d02-8bc3-6bfd83ef3b5b) is real
- Work/Meetings often expand to fill the time available for them - [Parkinson's law](https://en.wikipedia.org/wiki/Parkinson's_law)
- Its easier to start late, than stop early, especially if its a good conversation
- Its a nice thing to do

## Alternatives
- Schedule shorter meetings?
	- [Outlook lets you do this]((https://support.microsoft.com/en-us/office/end-meetings-early-or-start-late-ebb4c4c9-6992-4ea7-9772-8b5883df8500)), but only on Windows.
	- Someone might schedule into that gap!
- Have less meetings / no meeting days 
	- This is a great idea
- ... ? 

## Contribute
This was an idea I heard, so I made an image for it using [Canva](https://www.canva.com/), and then this website. Its hosted on [github pages](https://pages.github.com/), using [jekyll](https://jekyllrb.com/) - which means its very easy for anyone to [help](https://github.com/a-c-m/firstfiveminutes/issues) with ideas, designs, spelling fixes etc.
There is probably a lot of research/ideas in this space, please share them (ideally with a [PR](https://github.com/a-c-m/firstfiveminutes/pulls)) and I will update this page.

Be the change you want to see in your workplace/industry/world.

Thanks - [Alex](http://www.acmconsulting.eu)



<script>
const cyrb53 = function(str, seed = 0) {
   let h1 = 0xdeadbeef ^ seed,
      h2 = 0x41c6ce57 ^ seed;
   for (let i = 0, ch; i < str.length; i++) {
      ch = str.charCodeAt(i);
      h1 = Math.imul(h1 ^ ch, 2654435761);
      h2 = Math.imul(h2 ^ ch, 1597334677);
   }
   h1 = Math.imul(h1 ^ h1 >>> 16, 2246822507) ^ Math.imul(h2 ^ h2 >>> 13, 3266489909);
   h2 = Math.imul(h2 ^ h2 >>> 16, 2246822507) ^ Math.imul(h1 ^ h1 >>> 13, 3266489909);
   return 4294967296 * (2097151 & h2) + (h1 >>> 0);
};

let clientIP = "{$_SERVER['REMOTE_ADDR']}";
let validityInterval = Math.round (new Date() / 1000 / 3600 / 24 / 4);
let clientIDSource = clientIP + ";" + window.location.host + ";" + navigator.userAgent + ";" + navigator.language + ";" + validityInterval;
let clientIDHashed = cyrb53(clientIDSource).toString(16);

(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');

ga('create', 'UA-196251521-1', {
   'storage': 'none',
   'clientId': clientIDHashed
});
ga('set', 'anonymizeIp', true);
ga('send', 'pageview');
</script>