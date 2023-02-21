# CSS
## Flexbox 

Site aide : https://css-tricks.com/snippets/css/a-guide-to-flexbox/

La flexbox est un container, elle est donc parent. Pour faire en sorte que le container soit une flexbox, il faut mettre : 
``` css
    display : flex;
```

On peut choisir l'organisation des items, donc des enfants présents dans la flexbox avec le paramètre : 
``` css
    justify-content
```
Elle peut prendre en paramètre : `center`, `space-between`,`space-around`,`space-evenly`,`flex-end`,`flex-start`, `start`,`end`,`right`,`left`,

On peut également mettre donner en paramètres :
``` css
    align-items
```
Elle prends en paramètres : 
`stretch`, `flex-start/start/self-start`, `flex-end/end/self-end`, `center`, `baseline`

On peut donner du style au container mais également aux items à l'intérieur du container.
Par exmeple, on a les paramètres : `flex-shrink` ou `flex-grow` qui influence sur la taille des items les un par rapport aux autres.