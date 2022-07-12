# CatsOfNet
To celebrate International Cat Day on August 8th, I thought I would create CatsOf.NET to allow people to share their cats with the rest of the community.

# Contributing
We want everyone in the tech community to share pictures of their cats.

To add your cat, add an entry to the `/assets/cat-data.js` in the following format

```
{
    "catName": "Stormtrooper",
    "personName": "Lee Englestone",
    "img": "cats/le-stormtrooper.jpg",
    "description": "'Stormy' is a cool cat, never phased by anything. Perhaps a little too laid back. Brother of Molly",
    "github": "https://github.com/leeenglestone",
    "instagram": "https://www.instagram.com/leeenglestone/",
    "twitter": "https://twitter.com/leeenglestone",
    "linkedIn": "https://www.linkedin.com/in/leeenglestone/"
},
```

## Fork the Project
1. Create your Feature Branch (git checkout -b feature/AmazingFeature)
2. Commit your Changes (git commit -m 'Add some AmazingFeature')
3. Push to the Branch (git push origin feature/AmazingFeature)
4. Open a Pull Request

## Notes
- Please place cat image in `docs/cats`
- Cat image path MUST be relative to this site (not absolute to another site)
- Cat image must be .jpg format
- Cat image should be a square and no larger than 500px x 500px
- Descriptions should be no longer than 180 characters