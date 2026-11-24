### FizzBuzz Project
Fizzbuzz Project merupakan program untuk menampilkan angka 1 hingga 100 secara berurutan dengna kondisi sebagai berikut :
1. Jika habis dibagi 3 dan 5, ditampilkan "FizzBuzz"
2. Jika habis dibagi 3, ditampilkan "Fizz"
3. Jika habis dibagi 5, ditampilkan "Buzz"
4. Untuk angka lainnya, ditampilkan angka itu sendiri.

Fizzbuzz Project ini menggunakan gabungan perulangan serta kondisi.
Berikut codenya
```
for (let i = 1; i <= 100; i++){
    if(i % 3 === 0 && i % 5 === 0){
        console.log("FizzBuzz");
    }
    else if(i % 3 === 0){
        console.log("Fizz");
    }
    else if(i % 5 === 0){
        console.log('Buzz')
    }
    else{
        console.log(i);
    }
};
```
Code tersebut akan melakukan perulangan sebanyak seratus kali sambil mengecek apakah habis dibagi 3, habis dibagi 5, atau habis dibagi keduanya.
% di dalam if merupakan sisa bagi. Jadi bisa dibilang begini "jika hasil sisa bagi setelah dibagi 3 dari i merupakan 0 maka muncul "Fizz", jika hasil sisa bagi setelah bagi 3 dan 5 merupakan 0 maka muncul FizzBuzz, jika habis bagi setelah bagi 5 merupakan 0 maka muncul Buzz, jika semua kondisi tidak memenuhi maka muncul angka.
