# **PROVENANCE NOTICE**

---

**Source Repository and Reference Commit:**  
https://github.com/eric-prog/API-Search/commit/3fbe1900dabb05e9764a4f2073f5c5951c3623e7

**Note:**  
To comply with double-blind review requirements, this fork’s commit history was anonymized. The transformed and instrumented codes included in this repository were produced from this reference commit.

---

## Me.com! https://medotcom.netlify.app/ <br>
Link: https://medotcom.netlify.app/
<br>
### APIs Supported 

✅ StackOverflow API <br>
✅ Giphy API <br>
✅ Wikipedia API <br>

<br>

### Project Overview

<img src="./src/assets/project.png"/> <br>

/assets -> Contains images <br>
/components -> Components that make up the web app <br>
/models -> API models for the API response data <br>
/styles -> css files and styling <br>

Deployed manually on Netlify through Netlify CLI

### UI Design Thought Process

Overall Design Choice 🔮 <br>
I first thought of a theme and chose just a very simple UI which is composed of a search bar with a toggle at the top of the page (to choose which source to search from), and the results as the bulk of the website. Pretty standard and effective. I liked the toggle because it can allow for scaling to more API options and it's more efficient then rendering every possiblity every time.<br>
I think one reason I like Google over Bing.com and other search engines is because their front page.Google.com & You.com is very simple while a search engine like Bing.com have too stuff going on. There are articles, news, and this take a long time to load and are unnessesary. <br>
Made it also response to be viewed on phones and smaller devices. <br>

StackOverflow Search API ⚙️ <br>
<img src="./src/assets/stackoverflow.png"/> <br>
To showcase the StackOverflow search API data I made sure to include the title (with a hyperlink), the number of views, number of answers, and whether or not the question has an accepted answer. <br>
I only included these because I wanted the result data to be minimalistic and only show the attributes that any dev would look for. As a dev myself I would love to know if the stackoverflow question was answered, the number of answers (the more the better), and maybe the number of views (because too few can indicate inactivity). <br>

GIPHY Search API ⚙️ <br>

<img src="./src/assets/giphy.png"/> <br>
I love gifs. So for this API I included the actual GIF and the title (which includes a hyperlink to the source of the gif on giphy.com)

Wikipedia Search API ⚙️ <br>

<img src="./src/assets/wiki.png"/> <br>
Wikipedia API was interesting. A typical search engine would include a short summary and I could of done that with the advanced search API params but decided not to. This is because most people who search for Wikipedia links most likely want a deeper understanding then some 1 or 2-liner that barely communicates anything and regardless still leads the user to click on the Wikipedia link. I decided to just showcase the title (which leads to wikipedia link) of potential options. 


<br>
Built by Eric Sheen
