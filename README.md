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
- flex-grow : peut être utilisé pour que l'item prenne toute la place 
```css
    .items {
        flex-grow : 1;
    }
```

# Déploiement du site internet 
## GitHub Pages
Pour déployer son site avec GitHub Pages, il faut aller dans son répertoire Github puis aller dans `paramètres`.
Ensuite on va dans l'onglet `Pages` et on choisit de `déployer depuis la branche` ensuite on choisi la branche l'on veut déployer et voilà !

Lien du site : https://kazeynma.github.io/Kazeynma-Ecommerce/


## Vercel 
Il suffit d'aller sur le site internet de Vercel : https://vercel.com/

Ensuite on se connecte avec son compte Github.
- Lorsque nous sommes connectés, Vercel nous propose d'installer Vercel sur son Github.
- Ensuite on choisi le répertoire que l'on veut déployer, on le configure un peu et voilà !

Lien du site : https://lorant.vercel.app/