# Beautiful_github_profile


# 1 importing image

List of similar badges in the [link](https://github.com/MikeCodesDotNET/ColoredBadges#)

| **badge and code** |
| --------------- | 
| <img src='https://github.com/MikeCodesDotNET/ColoredBadges/blob/master/svg/dev/services/google_cloud_platform.svg' >| 
`<img src='https://github.com/MikeCodesDotNET/ColoredBadges/blob/master/svg/dev/services/google_cloud_platform.svg'>` |

------------------------

## 2 Predefined IMG sheilds

Cimpletet list of similar badges can be found in the following links: [link1](https://github.com/alexandresanlim/Badges4-README.md-Profile), [link2](https://github.com/Ileriayo/markdown-badges)

| **badge and code** |
| --------------- | 
|![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)| 
`![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)` |
|![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)| 
`![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)` |     


const gradientBadge = require('gradient-badge');
exports.endpoint = function (req, resp) {
    resp.setHeader('Content-Type', 'image/svg+xml');
    resp.end(gradientBadge({
        subject: 'Sarvandani',
        status: 'badges',
        gradient: ['b65cff', '11cbfa', '9000ff', '40ff00', 'dd00ff', '00ff84', 'b700ff', '0800ff', '00ffa2', 'd000ff', 'ffcc00', '00ff33', '00ff0d', 'ff8000']
    }));
}
