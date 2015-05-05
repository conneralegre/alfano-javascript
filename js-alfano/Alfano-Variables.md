# Alfano variable challenge

#1
    var dog = 'awesome';
    var cat = 'meh';
    var lion = 'scary';

    var sentence = 'dogs are ' + dog + ' cats are just ' + cat + ' lions are ' + lion;

    // what is the output of sentence?

#2

    var a = 7;
    var b = 3;
    var c " is a cool number";
    var d = (a + b) + c;

    // what is the output of d?

#3  

    var age = 26;
    var cent = 100;
    var sentence = 'you are ' + (cent - age) + ' years away from being 100 years old!';

    // what is the output of sentence?

#4

    var mybday = new Date(1989, 03, 06);
    var now = new Date(2015, 04, 5);
    var timeDiff = Math.abs(mybday.getTime() - now.getTime());
    var diffDays = Math.ceil(timeDiff / (1000 * 3600 * 24)); 
    var diffYears = (diffDays / 365);
   // how do you get age to output my age? diffYears == 26.095890410958905
