# Daniil Rai
# My contacts
* Email: testnet02@mail.ru
* Phone: +375444635883
* [DaniilRai13](https://github.com/DaniilRai13)
# About Me
*I am 20 years old and was born in Pinsk. I want to become a good front-end developer and further study technologies for back-end development. I am active, purposeful and always ready to learn something new.*
# Skills
1. HTML
2. CSS, SCSS, Bootstrap
3. JavaScript (Fundamentals, DOM, Async JavaScript and other)
4. Photoshop
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
                if(temp == 0) return 0
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
* Belarusian National Technical University
	+ Automated information processing systems
* RS School(in process...)
# Languages 
* English: Intermediate( test by [skyeng](https://magazine.skyeng.ru/check-your-english-level/))