// innitialization , condition , body execution
      // program to add first 10 natural numbers
      let sum = 0;
      let n = prompt("Enter value of n");
      n = Number.parseInt(n);
      for (let i = 0; i < n; i++) {
        sum += i + 1;
      }
     
      console.log("sum of first  " + n + "natural numbers is " + sum);
      // program to display the sum of n natural numbers
      let sum = 0;
      const n = 100;

       //looping from i = n to 1
      // in each iteration, i is decreased by 1
      for (let i = n; i >= 1; i--) {
        // adding i to sum in each iteration
        sum += i; // sum = sum + i
      }

      console.log("sum:", sum);

      //for in loop

      let obj = {
        hafsa: 90,
        fizza: 80,
        iqra: 70,
        Anisa: 56,
        alia: 23,
      };
      for (let a in obj) {
        console.log("marks of " + a + " are  " + obj[a]);
      }

      //for of loop
      for (let b of "fizza") {
        console.log(b);
      }
