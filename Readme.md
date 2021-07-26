<h1 align="center">   &nbsp; GITHUB REPO SEARCH  </h1>


> Built with MERN stack ( html, Css, JavaScript, JQuery).

## 📜 &nbsp; Features
-Github contains millions of repos ans searching specific organization's repo is sometimes too difficult . That web app makes that simple .  

#### Project methodology

-It takes 3 inputs (org_name),(how many top repos's of that org you want to see ) and (how many top contributors of that each repo you want to see)
everything is shown in a readable format with all the links and avatars embedded. The first loading might take 5-10 sec as i am using free version of Api and dont have a fast server but i've taken care that the site never crash and give the output as quick as possible. For making calls less and fast i have used pagination technique. Ajax calls are used so that page dosent have to reload again and again which makes it scalable and ready for production.


## &nbsp; API used
- https://api.github.com/orgs/${org_name}
- https://api.github.com/orgs/${org_name}/repos?per_page=100&page=${page_no}
- https://api.github.com/repos/${org_name}/${repo_name}/stats/contributors


## 💹 &nbsp; Special-features:
- when requested repos are large in number then the site dosent crash as pagination concept is used.
- All the calls are Async.
- Site can handle any amount of data and ready to go for production.
- Per page 10 async repo calls are made.
- Avatar's and profile urls are displayed.
- Ajax (XHR) requests are used so that the page dont reload.
- Client side renderring is done.


## 💻 &nbsp; Setup

To run this project, install it locally using npm:

```
$ download the code.
$ open it in vs code.
$ right click on index.html file.
$ Click on open with live server.
$ Make sure u have active internet connection.

    