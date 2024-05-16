## What is TypeScript?

The short version would be that typescript is Javascript but on some steroids called- more types.
However, the W3 schools would like to define it as 
```The superset of Javascript``` because it is javascripts with the ability of having more types. Read more here: ```https://www.w3schools.com/typescript/typescript_intro.php.```

## How do I use TypeScript?

It might interest you to know that there is a typescript compiler. Technically, it does trnaspile Typescript into Javascript. 
```Remember that its just Javascript but with additional types```
It is not surpsiing that it would need to be tanspiled back to javascript.

## Installing the Compiler
Well, now you might benefit from installing the compiler.
```Step 1: npm install typescript --save-dev```
```run it with this command -[npx tsc]```
You may wanna read more on how to configure the tsconfig.json file. Here is the link ```https://www.w3schools.com/typescript/typescript_getstarted.php```

## TypeScript Simple Types

We can all agree that we have almost found the following types in almost all languages. ```boolean, number, string ```
They would rightly be considered the ```primitive types```.

But there are more which are not soooo primitive. But they have been added in Javascript and thus Typescript too.
```bignit and symbol``` 

#### Bignit Type
This one is concerned with whole numbers and also floating ones. That would mean that they are concerned with numbers that are with and without decimals [whole and floating number.]

#### Symbol Type
Well, this is the holy grail. Used to create a globally unique idenified. 

## Type Assignment
Well, before we can use the types, we gotta learn how declare or assign them. Yeah?
To declare them, then one can either have an ```Explicit type``` or ```implicit type```

#### Explicit Type
This is the one that tells the world what your variable is. 
eg. ```let firstName: string = "Dylan";

The example above tells that; 
```1. There have been a variable declared and its called - firstName```
```2. That variable is and can only be of the type string.```
```3. And its first given the name Dylan as its placeholder.```

#### Implicit Type
This one now lets us just guess what your variable is. Like that guy that toys with your feelings and never gives what you are a title ```(Darkhumor i guess)```

Here goes an example beyond that sad example of a relationship.
```let firstName = "Dylan"```

From the example above, we know that;
```1. The variable is called firstName```
```2. We dont know the hell your variable type is hence it can be anything.```
```3. But we at least know that its value is the name Dylan```

```simply depressing!```

Anyways, if you want some stability in your code, unlike in your relationship, then you can just disable the choice to have implicit types in your code by having that change in your ```tsconfig.json``` file.

#### step 1
Just go to your ```tsconfig.json``` file

#### step 2
Then disable the implicit option by enabling the ```noImplicitAny``` command. 

```Of course this is dependent in your taste of code just as you have in a spouse. Heehehe!```

For you that likes uncertainty, lets talk about ```Type: any```

#### Type: any
This is the type that is used to tell the compiler that you dont know what the hell you are doing. Therefore, like the same way you dont wanna know what you are doing with that partner of yours, ```type any``` tells the compiler not to bother knowing the type of variable. 

It seemly doesn't check and it allows it to be as everything and anything at the same time. 

Its advantage is that you can use ```type any``` to escape errors because there is no commitment dictated on the variables ```just like you and your spouse```