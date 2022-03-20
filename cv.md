# Nikita Virachev

## Contacts

* **Location:** Yaroslavl, Russia
* **E-mail:** iitikbo0216nikitavirachev@gmail.com
* **Discord:** Nikivils#8409
* **GitHub:** [NikitaVirachev](https://github.com/NikitaVirachev)

## About me

I'm 23 years old and I'm finishing my studies at the university. But I don't stop there and I want to study front-end development.

My forte is the thirst for knowledge.

## Skills

* HTML, CSS
* JavaScript (Basic)
* C++, Qt C++
* Git, GitHub
* VS Code, Visual Studio, Qt Creator

## Code examples

**Cata from CodeWars:** *Complete the solution so that it splits the string into pairs of two characters. If the string contains an odd number of characters then it should replace the missing second character of the final pair with an underscore ('_').*

```
function solution(str){
    if (str.length % 2 != 0) str += '_';

    let result = [];

    for (let i = 0; i < str.length; i = i + 2) {
        result.push( str.slice( i, i + 2 ) );
    }

    return result;
}
```