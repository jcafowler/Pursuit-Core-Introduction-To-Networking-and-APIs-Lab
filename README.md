# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
catfact.ninja/

https://catfact.ninja/fact?max_length=140

{
    "fact": "Cats have 30 vertebrae (humans have 33 vertebrae during early development; 26 after the sacral and coccygeal regions fuse)",
    "length": 122
}
1. A list of 150 random users in English.
https://randomuser.me/api/?results=150

{
    "results": [
        {
            "gender": "male",
            "name": {
                "title": "Mr",
                "first": "Leroy",
                "last": "Burton"
            }]
        }
1. All the repos on Github with Pursuit their name
https://api.github.com/users/joinpursuit/repos

[
  {
    "id": 213441105,
    "node_id": "MDEwOlJlcG9zaXRvcnkyMTM0NDExMDU=",
    "name": "21-web-game",
    "full_name": "joinpursuit/21-web-game",
    "private": false,
    "owner": {
      "login": "joinpursuit",
      "id": 5825944,
      "node_id": "MDEyOk9yZ2FuaXphdGlvbjU4MjU5NDQ=",
      "avatar_url": "https://avatars2.githubusercontent.com/u/5825944?v=4",
      "gravatar_id": "",
      "url": "https://api.github.com/users/joinpursuit",
      "html_url": "https://github.com/joinpursuit",
      "followers_url": "https://api.github.com/users/joinpursuit/followers",
      "following_url": "https://api.github.com/users/joinpursuit/following{/other_user}",
      "gists_url": "https://api.github.com/users/joinpursuit/gists{/gist_id}",
      "starred_url": "https://api.github.com/users/joinpursuit/starred{/owner}{/repo}",
      "subscriptions_url": "https://api.github.com/users/joinpursuit/subscriptions",
      "organizations_url": "https://api.github.com/users/joinpursuit/orgs",
      "repos_url": "https://api.github.com/users/joinpursuit/repos",
      "events_url": "https://api.github.com/users/joinpursuit/events{/privacy}",
      "received_events_url": "https://api.github.com/users/joinpursuit/received_events",
      "type": "Organization",
      "site_admin": false
    },
1. All the JavaScript repos on Github with Pursuit in their name
  https://api.github.com/search/repositories?q=pursuit-core+language:javascript&sort=stars&order=desc

    "total_count": 22,
  "incomplete_results": false,
  "items": [
    {
      "id": 149148208,
      "node_id": "MDEwOlJlcG9zaXRvcnkxNDkxNDgyMDg=",
      "name": "Pursuit-Core-Web",
      "full_name": "joinpursuit/Pursuit-Core-Web",
      "private": false,
1. All the Swift repos on Github with Pursuit in their name
  https://api.github.com/search/repositories?q=pursuit-core+language:swift&sort=stars&order=desc

     "total_count": 130,
  "incomplete_results": false,
  "items": [
    {
      "id": 99703757,
      "node_id": "MDEwOlJlcG9zaXRvcnk5OTcwMzc1Nw==",
      "name": "Pursuit-Core-iOS",
      "full_name": "joinpursuit/Pursuit-Core-iOS",
      "private": false,
      "owner": {
1. A list of all Pokemon
https://pogoapi.net/api/v1/pokemon_names.json
{
    "1": {
        "id": 1,
        "name": "Bulbasaur"
    },
    "2": {
        "id": 2,
        "name": "Ivysaur"
    },
1. A list of all items in Fortnite
  https://www.fortnitehut.com/free-api?rarity=epic

    "results": [
    {
      "rarityid": {
        "name": "epic",
        "date": "November 26th 2019"
      }
    }
  ],
  "items": [
    {
      "name": "Pink Flamingo",
      "ourid": "uQsDME1"

1. A list of all Game of Thrones Episodes.
  https://api.got.show/api/map/episodes
      "message": "Success",
  "data": [
    {
      "characters": [
        "Viserys Targaryen",
        "Catelyn Stark",
        "Cersei Lannister",
        "Jaime Lannister",
        "Eddard Stark",
        "Robert Baratheon",
        "Jorah Mormont",
        "Daenerys Targaryen",
        "Jon Snow",
        "Petyr Baelish",
        "Arya Stark",
        "Sansa Stark",
        "Bran Stark",
        "Robb Stark",
        "Joffrey Baratheon",
        "Tyrion Lannister",
        "Jeor Mormont",
        "Alliser Thorne",
        "Jory Cassel",
        "Barristan Selmy",
        "Rodrik Cassel",
        "Benjen Stark",
        "Yoren",
        "Renly Baratheon",
        "Maester Aemon",
        "Syrio Forel",
        "Grenn",
        "Irri",
        "Pypar",
        "Rakharo",
        "Lancel Lannister"
      ],
      "_id": "5cc0743604e71a0010b85729",
      "director": "Tim Van Patten",
      "airDate": "2011-04-24T04:00:00.000Z",
      "totalNr": 2,
      "season": 1,
      "nr": 2,
      "name": "The Kingsroad",
      "predecessor": "Winter Is Coming",
      "successor": "Lord Snow",
      "createdAt": "2019-04-24T14:35:34.594Z",
      "updatedAt": "2019-04-24T14:35:34.594Z",
      "__v": 0
    },
1. A list of all songs with "Love" in the title.
  http://itunes.apple.com/search?term=love

  {
 "resultCount":50,
 "results": [
{"wrapperType":"track", "kind":"song", "artistId":42616562, "collectionId":715579496, "trackId":715581836, "artistName":"Nat \"King\" Cole", "collectionName":"Nat King Cole",
1. All information about Petyr Baelish from the Game of Thrones books
  https://www.anapioficeandfire.com/api/characters/823

  {
  "url": "https://www.anapioficeandfire.com/api/characters/823",
  "name": "Petyr Baelish",
  "gender": "Male",
  "culture": "Valemen",

1. All the movies Leonardo Dicaprio has acted in
  http://itunes.apple.com/search?term=leonardo+dicaprio

  {
 "resultCount":41,
 "results": [
{"wrapperType":"track", "kind":"feature-movie", "trackId":1473165316, "artistName":"Quentin Tarantino", "trackName":"Once Upon a Time...in Hollywood", "trackCensoredName":"Once Upon a Time...in Hollywood", "trackViewUrl":"https://itunes.apple.com/us/movie/once-upon-a-time-in-hollywood/id1473165316?uo=4",

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
https://github.com/jcafowler
The website loaded without incident.

1. 301
1. 400
1. 401
1. 403

1. 404
https://github.com/jflkm;lkfmkl;M;DSm
The error means there is nothing found at that particular url on the website.
1. 418
1. 500


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat



