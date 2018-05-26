# egs-ids

## for translating new style slugs urls into old style ID based urls

The 3 txt files contain python dicts (will also work in JS) for converting the url slugs on the egs comic site. into their respective comic ID

pages that come after the 22nd of may 2018 do not have valid ids and so cannot be converted

'EGS back to IDs.user.js' is a user script that will attempt to convert all links in the new style into the old style if they have a valid id to link to. As with all userscripts, please verify what it does before running it, so you can see it is not malicious