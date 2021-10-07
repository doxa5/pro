# pro
let temperatureKelvin = 283;
let celsius;
let fahrenheit;
//kelvin constant
const kelvin = 273;
//convert kelvin to celsius
celsius = temperatureKelvin - kelvin;
//convert celsius to fahrenheit
fahrenheit = celsius * (9/5) + 32;
//convert fahrenheit from decimal to whole number
fahrenheit = Math.floor(fahrenheit);
console.log(`The temperature is ${fahrenheit} degrees Fahrenheit.`);
