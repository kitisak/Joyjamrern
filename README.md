# Joyjamrern
(The Librarian)

Bot ID: @330uulth

QR Code:
<img width="200" alt="QR Code of @330uulth" src="/images/avatar/330uulth.png">

This side project was developed to solve friend's (P'Aoy) purchasing duplicate books.

## Features
* Verify similarity new book's cover against the existing ones in the library.
* Add new book to your personal library.

## Screenshots
<table width="100%">
	<tr>
	  <td><img src="/images/screenshots/screenshot1.jpg" width="100%"></td>
	  <td><img src="/images/screenshots/screenshot1.gif" width="100%"></td>
	</tr>
</table>

## TODO
* [ ] Let user add more info about books.
* [ ] Let user access to their personal library.

## Overview of Technology and APIs
![Technolofy and API Services](/images/others/tech.jpg)

## Set environment configuration
As The Firebase SDK for Cloud Functions offers built-in environment. I use the `firebase functions:config:set` command in the Firebase CLI to set project configurations.

This is a command I run:
```
firebase functions:config:set line.channel_access_token=CHANNEL_ACCESS_TOKEN line.channel_secret=CHANNEL_SECRET aiforthai.apikey=APIKEY dialogflow.code=CODE
```
ps. Don't forget to replace `CHANNEL_ACCESS_TOKEN`, `CHANNEL_SECRET`, `APIKEY`, `CODE` with your data.

## Attributions
* Icons made by [photo3idea_studio](https://www.flaticon.com/authors/photo3idea-studio) from [www.flaticon.com](https://www.flaticon.com/)
* Food vector created by *lunnadesign* [freepik.com](https://www.freepik.com/vectors/food)


## License
* [MIT](http://opensource.org/licenses/MIT)