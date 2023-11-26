# Astrological Sign Determination

This JavaScript code determines the astrological sign based on the current system date. The collection of signs is represented as a list of objects, each containing the sign's name, start date, and end date. The retorna_signo function iterates through this collection and checks if the current date falls within the range of any sign. 
If a corresponding sign is found, its name is returned; otherwise, the message "Sign not found" is returned.

### Usage

1 -Ensure you have Node.js installed.

2 - Clone this repository.

3 - Run the script using the command:

```bash
node astrological_sign.js
```
The function will return the zodiac sign for the current date.

For example, the following code will print the zodiac sign for the current day:

```bash
const signs = [
{
name: "Aquarius",
start: "01-20",
end: "02-18",
},
{
name: "Pisces",
start: "02-19",
end: "03-20",
},
// ...
];

const currentDate = new Date();
const zodiacSign = getSign(signs);

console.log(zodiacSign);
```

5 - Example Output

The output of the code above will vary depending on the current date. For example, if the current date is February 2, 2023, the output will be "Pisces".

### Contribution

Feel free to customize the colecao_signos array with your preferred astrological sign data.

Note: The code automatically retrieves the current system date.

### License

This code is licensed under the MIT License.
