 loops
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

console.log("Javascript VAriables let ,const and var");
        //var
       let a = 45;
        let b = 10;
         let c = null;

         objects:    

         
       const name = "Hafsa kanwal";
         {
         let b = "hafsa";
          console.log(b);
         }
        console.log(name);

      //primitive data types  nn bb ss u
      
         let a = null;
        let b = 35;
       let c = true;
         let d = BigInt("567") + BigInt("5");
      let e = "Hafsa";

        let g = undefined;
       console.log(a, b, c, d, e, g);
        console.log(typeof d);

      //   //non-premitive   objects

        const items = {
           hafsa: true,
          " kanwal": false,
          "roll-no": 11,
        class: undefined,
       };
       console.log(items["roll-no"]);

       Practice Questions:
        // 1 -Create a variable of type string and add  a number into it.

      let a = "hafsa";
      let b = 6;
      console.log(a + b);

      // use a type operator to find the datatype of first string
      console.log(typeof (a + b));

      //create a constant object in js.
      const student = {
        name: "hafsa",
        roll_no: 11,
        section: "A",
        IsPrinciple: false,
      };

      // ADD NEW KEY TO CONST
      student["friend"] = "kanwal";
      console.log(student);

      // js programe to create word meaning dictionery of 5 words
      const dictionery = {
        appreciate: "admire",
        respect: "a feeling of deep admiration for someone",
        ballad: "a slow sentimental or romantic song",
        democracy:
          "a system of government by the whole population or all the eligible members of a state",
        eligible: "having the right to do or obtain something",
      };
      console.log(dictionery.respect);
 VAriables
