-  What is the difference between 301 and 302?

---> 301 is used for permanent redirection from old to new url for example, the new feature added in application and 302 is used for temporary redirection from old to new url for example, maintainance issue in the application.  

- Why is PUT idempotent but POST is not?

---> PUT method updates the existing data hence whenever any modification occurs it always shows the same result. For example, if the user modifies the name as "Karan" multiple times everytime it shows result as "Karan" but in case of POST method every time the data is inserted if the user inserts "Karan" multiple times, it can create an issue of creating duplicate user.

- What is the difference between localStorage and sessionStorage?

---> localStorage is the permanent storage it remains stored even after refresh the tab or restart the browser but sessionStorage is temparory storage which can store the data upto the expiration, both have their own use cases.  

- What triggers a reflow vs a repaint?

---> Reflow represents the layout that is modifying the existing value of layout of the element like width, height, padding, margin, etc. Repaint changes the existing appearance of the element like color, shadow, etc


- What is CORS and why does it exist?

---> CORS stands for cross origin resourse sharing which is used for interacting two origins to connect and produce a desired result for example if frontend is running on 2987 and backend is running on 3847 then they should be interact with each other to secure the application.  