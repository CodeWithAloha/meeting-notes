# Code for Hawaii 12/12/2022

### Level of effort required for the following features

- Logging in with email
- Tying to location. Ideally would like to track responses to location. Map the variants in vision and values in census by location. Nice to drill down to the census tracked level.
    - We don't want to store an address, but would like to sum up responses by census track otherwise by zip code.
- A tie in to a demographic questionnaire. To speak to the representation
- Ability to customize the out of box database. A way to build out and customize a database.
    
    

### Spam Risk

- Issue is polis is accessible by anybody
- Mitigate by in person workshops. Access polis that way
- Requires email address to get into the polis.

### Timeline

Hoping to reach that go/no go decision point.

Want something to have a way for people to engage in March.



### Updates

 - We spec'ed out what we would need to do to correlate data we collect vs. data that pol.is collects through an xid (ref: https://github.com/compdemocracy/polis-embed-examples/tree/main#polis-xid-system)
 - pol.is doesn’t seem to have any authentication on it’s API routes (example: https://pol.is/api/v3/conversations?conversation_id=5a6mr8dh2r&cacheBust=872539947), so we should be able to query any data we need
 - Created this GitHub repository here: https://github.com/CodeforHawaii/HIERR to start holding some information related to this project



### Follow up questions

How do they want to store demographics information?
How do they want to view the reports on the data they've collected?

We need a centralized database for the information that is collected

Where are we going to host the data for the database?