<h1>Stop Breathe Think + Amazon Echo?</h1>

Inspiration: stopthinkbreathe.org is an excellent app and website for guided meditations. Wouldn't it be awesome if you could start them up 
with your Amazon Echo?

Purpose: To test out the alexa developer story, not for a fully functioning skill.
This project is a sketch of the initial skills component: connecting Alexa responses to some light python responses.

<h2>Issues</h2>
1. the invocation phrase 'echo <start | ask | play | use > < skill name >' is very awkward and doesn't lend itself easily to this purpose
e.g., 'echo start stop breathe think.... echo ask stop breathe think.... echo play stop breathe think'

2. stopthinkbreathe.org doesn't hav any public API or endpoint for authentication --> alt: do a web request with their 'just browsing' feature

3. streaming the meditation audio from stopthinkbreathe.org may be technically and legally challening.
TODO: Reaching out to stopthinkbreathe.org or Tools For Peace (TFP) for permission. :)

