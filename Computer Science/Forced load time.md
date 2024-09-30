```
private static void loadingTime(String baseMessage, int timeMS) throws InterruptedException{

        `String[] dots = {"", ".", "..", "..."};`

        `int index = 0;`

        `int direction = 1;`

        `int begin = 0;`

  

        `timeMS /= 250;`

  

        `while (begin <= timeMS) {`

            `String output = baseMessage + dots[index];`

  

            `System.out.print("\r" + output + " \u001B[?25l");`

            `System.out.flush();`

  

            `Thread.sleep(250);`

  

            `index += direction;`

            `if (index == dots.length - 1 || index == 0) {`

                `direction *= -1;`

            `}`

            `begin++;`

        `}`

    `}`
```