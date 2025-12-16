Create new workspace and edit its name
![1st step](image-5.png)

adding webhook node, acting as a trigger
![2nd step](image-9.png)

adding http request node, the node issues an external API, which doesnt work. As my colleague told me, there was an error in the link, which i now fixed, so everything works fine.
![3rd step](image-10.png)

adding response to webhook node, it transforms the JSON data returned by previous step into HTTP response to the original webhook
![4th step](image-11.png)

**after minor fix now it works fine**