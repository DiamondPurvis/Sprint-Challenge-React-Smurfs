1.  Explain the differences between `client-side routing` and `server-side routing`.
    -- server-side routing
        - when a user clicks a link and it creates a new page from the server. It causes the whole page to refresh and give a new document to the user with a GET request deleting the old page
        - only requests whats needed
        - seo friendly
        - unncessary data is requested and duplicated like headers
        - takes time for the site to render
    -- client-side routing
        - when a users clicks a link, the url changes but the request to the servicer doesnt happen. The link click renders a new component showing a different view of the page but it doesnt create a new document and it doesnt refresh the whole page.
        - less data is passed through
        - animations are easier to add
        - loads slow at first
        - requires a library sometimes
        - not seo friendly
1.  What does HTTP stand for?
    -- It stands for HyperText Transfer Protocol. It defines how messages go through the web and what web servers should do for certain actions.
1.  What does CRUD stand for?
    -- It means create, read, update, and delete.
1.  Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.
    -- HTTP Post = create
    -- HTTP Get = read
    -- HTTP Put = update
    -- HTTP Delete = delete
1.  Mention three tools we can use to make AJAX requests
    -- fetch
    -- axios
    -- request