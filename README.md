# Hindi Manga Weaver

Clone this GitHub project and make it working here

https://github.com/qcute2038-code/hindi-manga-studio.git

I got the foundation in place, but the app isn't finished yet.

Done so far: database (stories, parts, chapter-chunks with public read/write, no login), your four Paralon keys stored securely, the AI engine (plan → 46+ chapters → parallel writing across all 4 keys → auto top-up until 50,000+ Hindi words), a strict sanitizer that strips numbers, symbols, emoji and English so only casual Devanagari remains, server functions for create/plan/write/finish/edit/delete, the public open endpoints (`/api/public/library`, `/api/public/story/:id`, `/api/public/part/:id?format=txt|json`), the manga design system, and the writer loop hook.

Still remaining: the three pages — home (summary upload + start), `/library` (list, delete, edit, open, next-part), `/story/$storyId` (progress, read, download, "part 2 चाहिए?" flow), plus `/api-docs`, and then a live end-to-end test. Top up credits and tell me to continue, and I'll finish those pages in one go.

Fucking useless ai each story must be written in Devnagari language casual devanagari language 

build an web app for manga story write.

user will upload english summary - our ai analyse complete summary - build an plan to write manga story - write complete story in Hindi by following some rules which are below - save story permanently on server - allow download manga story anyone anytime.- once story writing complete ask user if part 2 needed if needed part 2 then analyse part 1 story and write part 2. After part 2 ask again for part 3 and so on. Make sure user can pick any story from library and ask for its next part any time.

Manage all stories properly in library properly with its part with next part writing option, delete modify option. Make sure add open endpoint to library. Anyone can use complete library in any other project using endpoint.

Make sure complete web app must be public no one need any authentication. Anyone can download any user manga story any time .

Fucking useless ai this web app must follow all these below given rules. Fucking ai never broke these rules.

rules:-

1. manga story must be in hindi(Devnagari lipi). make sure in any condition use only casual hindi language.

2. make sure use only simple words which are getting used in daily life. never use hard spoken words.Keep the language natural, casual, warm, and easy to understand. 

3. user will use this story to convert in speech using Fish Audio or elevenlabs like ai so make sure never use words which sounds annoying in Hindi speech.

4. make sure each manga story length must be atleast 50,000 hindi words. (I am assuming 200000+ characters). no any upper limit 

5. make sure manga story must be engaging as possible as with proper hooks, twist, suspension, emotions ,comedy, humar, drama and everything which is needed to make story more engaging.

6. make sure end every story with open ending.

7. Keep conversations natural and situation-appropriate. also make sure add proper punctuation marks.

8. never add any type of symbols, emoji, number, stars in manga story.

use this https://paraloncloud.com api key for ai:-

make sure paraloncloud api key is with 0 credits so in any condition use only free model Qwen 3.8 27B. make sure use this free model. (free limit 60 request/min). 

api key 1

prlc_9dec184306d8d0dbb7d12c98d6dc22ce35d5ac3feaf2ccb9

Paraloncloud api key 2

prlc_667ae9e467f065c6202fc7e12f07f575a8111b7ad906dd73

Paraloncloud api key 3

prlc_99b14331acd49b119237bef2ecc2e1078ecdd0f3be8a83d7

Paraloncloud api key 4

prlc_a16ea589738ffd489a8c2bb8550facce032e2263922de645

Must use all api keys in parallel to speed up writing process while managing consitancy of story.

Fucking useless ai each story must be written in Devnagari language casual devanagari language

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/6d7cab53-cb3a-4ba0-9bd4-b73d7dd01a90).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
