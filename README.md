# Kelvin-Fahrenheit-Celsius-Converter
JS file to find temperature.

const kelvin = 293;
//setting a constant kelvin
const celsius = kelvin - 273;
//constant set 
let fahrenheit = celsius * (9/5) + 32;
//constant fahrenheit set 
fahrenheit = Math.floor(fahrenheit);
console.log(`The temperature is ${fahrenheit} degree Fahrenheit`);

