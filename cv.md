# Alexei Berillo

## Contacts

* Discord: zzzap67
* Email: [zzzap67@gmail.com](mailto:zzzap67@gmail.com)

## Education

2006 Master of Science (Mathematics and Computer Science)
*Belarusian State University, Minsk, Belarus*

2012 Master of Economic (Foreign Economic Activity)
*Belarusian State Economic University, Minsk, Belarus*

## Skils

MS SQL / HTML / CSS / JavaScript / PHP / VueJS / Git / C / Delphi / 1C

## Code Example

Here is my solution for [Who likes it?](https://www.codewars.com/kata/5266876b8f4bf2da9b000362) task on CodeWars:

```javascript
function likes(names) {
  switch (names.length) {
    case 0:
      return "no one likes this";
    case 1:
      return `${names[0]} likes this`;
    case 2:
      return `${names[0]} and ${names[1]} like this`;
    case 3:
      return `${names[0]}, ${names[1]} and ${names[2]} like this`;
    default:
      return `${names[0]}, ${names[1]} and ${names.length-2} others like this`;
  }
}
```