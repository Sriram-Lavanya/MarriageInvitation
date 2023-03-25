<p align="center"><a href="https://kalaivani-mohan-marriageinvitation.netlify.app/"><img src="https://github.com/Kalaivani-Mohan/MarriageInvitation/raw/demoBranch/assets/wedding.gif" width="150px" height="150px"/></a></p>
<h1 align="center"><a href="https://kalaivani-mohan-marriageinvitation.netlify.app/">Wedding Invitation</a> :ring: <br> <br> SAVE THE DATE: APR 26, 2023 <br> <a href="https://kalaivani-mohan-marriageinvitation.netlify.app/">kalaivani-mohan-marriageinvitation.netlify.app</a></h1>

[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Kalaivani-Mohan/MarriageInvitation?logo=github?logo=github)](https://kalaivani-mohan-marriageinvitation.app/) [![Netlify Status](https://api.netlify.com/api/v1/badges//cf488868-3636-4d6f-ae16-0579ada47339/deploy-status)](https://app.netlify.com/sites/kalaivani-mohan-marriageinvitation/deploys) (https://github.com/Kalaivani-Mohan/MarriageInvitation)





## Wedding Invitation :ring:

<details>
  <summary><strong>View Invitation</strong></summary>
  <a href="https://kalaivani-mohan-marriageinvitation.netlify.app/"><img src="https://github.com/Kalaivani-Mohan/MarriageInvitation/blob/demoBranch/assets/img/Invitation.jpg" /></a>
</details>

With the divine grace of the almighty,
inviting you and your family to younger sister's wedding to be held on **26th April at [Kumaran Mahal](https://goo.gl/maps/5z5xX2hTYzU8VGEJ9), Chennai, Tamilnadu from 7:00 PM** onwards.

- [Download](https://github.com/Kalaivani-Mohan/MarriageInvitation/raw/demoBranch/assets/inviatation.pdf) the Invitation card

- Find [venue](https://maps.app.goo.gl/dHz3rJmWcUbFWEbv8) on Google map

- Visit the [website](https://kalaivani-mohan-marriageinvitation.netlify.app/) for more details

const newCouple = 'Kalaivani & Mohan';

// Nov 29, 2020
const weddingDate = new Date(2023, 04, 26);

// Wedding venue: https://maps.app.goo.gl/dHz3rJmWcUbFWEbv8
const weddingVenue = new Location('Medavakkam, Chennai');

(function() {
    newCouple.willTieKnot(weddingDate);

    // your presence is requested
    (new Wedding()).acceptInvitation(
        window.open('https://kalaivani-mohan-marriageinvitation.netlify.app/')
    );
})();

