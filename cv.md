# Daniil Rai
# My contacts
* Email: testnet02@mail.ru
* Phone: +375257773483
* [DaniilRai13](https://github.com/DaniilRai13)
# About Me
*I am 21 years old and was born in Pinsk. I want to become a good front-end developer and further study technologies for back-end development. I am active, purposeful and always ready to learn something new.*
# Skills
> Tools, languages, and other things that I like to work with.
<table>
  <tr>
    <td align="center" width="76">
      <a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" />
      </a>
      <br>Jsonnet
    </td>
    <td align="center" width="76">
      <a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="36" height="36" alt="CSS3" />
      </a>
      <br>CSS3
    </td>
    <td align="center" width="76">
      <a href="https://sass-lang.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/sass-colored.svg" width="36" height="36" alt="Sass" />
      </a>
      <br>SASS
    </td>
    <td align="center" width="76">
      <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" />
      </a>
      <br>JS
    </td>
    <td align="center" width="76">
      <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="36" height="36" alt="TypeScript" />
      </a>
      <br>TS
    </td>
    <td align="center" width="76"> 
      <a href="https://reactjs.org/" target="_blank" rel="noreferrer" >
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" />
      </a>
      <br>React
    </td>
    <td align="center"  width="76">
      <a href="https://redux.js.org/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/redux-colored.svg" width="36" height="36" alt="Redux" />
      </a>
      <br>Redux
    </td>
    <td align="center" width="76">
      <a href="https://nextjs.org/docs" target="_blank" rel="noreferrer" >
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nextjs-colored.svg" width="36" height="36" alt="NextJs" />
      </a>
      <br>Next.js
    </td>
    <td align="center" width="76">
      <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tailwindcss-colored.svg" width="36" height="36" alt="TailwindCSS" />
      </a>
      <br>Tailwind
    </td>
    <td align="center" width="76">
      <a href="https://mui.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/materialui-colored.svg" width="36" height="36" alt="Material UI" />
      </a>
      <br>Material UI
    </td>
    <td align="center" width="76">
      <a href="https://vitejs.dev/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/vite-colored.svg" width="36" height="36" alt="Vite" />
      </a>
      <br>Material UI
    </td>
    <td align="center" width="76">
      <a href="https://webpack.js.org/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/webpack-colored.svg" width="36" height="36" alt="Webpack" />
      </a>
      <br>Material UI
    </td>
  </tr>
</table>
# Code Example
Pete likes to bake some cakes. He has some recipes and ingredients. Unfortunately he is not good in maths. Can you help him to find out, how many cakes he could bake considering his recipes?

Write a function cakes(), which takes the recipe (object) and the available ingredients (also an object) and returns the maximum number of cakes Pete can bake (integer). For simplicity there are no units for the amounts (e.g. 1 lb of flour or 200 g of sugar are simply 1 or 200). Ingredients that are not present in the objects, can be considered as 0.
```
function cakes(recipe, available) {
    let temp
    for(let ingridient in recipe){
        if(ingridient in available){
            let possibleCackes = Math.floor(available[ingridient]/recipe[ingridient])
            if( possibleCackes < temp || !temp ){
                if(!temp) return 0
                temp = possibleCackes
            } 
        }else{
            return 0
        }
    }
    return temp
}
```

# Education
* Belarusian National Technical University(in processing...)
	+ Automated information processing systems
* RS School(in process...)
# Languages 
* English: Intermediate( test by [skyeng](https://magazine.skyeng.ru/check-your-english-level/))
